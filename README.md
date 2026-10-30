# Strike & Shield: Map Battle prototype

A clickable prototype of the student game for the Strike & Shield redesign. You answer questions in a cockpit, and after every 3 questions everyone gets a turn: shield yourself, or strike an area of the map with a laser. The more of the 3 you got right, the stronger the strike (−100, −300 or −500 to each player hit); none right means Shield only. Your land is a circle on the map; right answers grow it and strikes shrink it. The biggest land wins.

## Open it

The page loads sounds and images, so it needs a local web server; opening the file directly will not work. From this folder:

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765/ in Chrome. Design and test at **1366×657** (a Chromebook screen) first.

Card art, Qbit avatars and fonts load from the internet (cf.quizizz.com, wayground.com, Google Fonts), so stay online.

## Try it

- The first game opens with a 13-second intro on the map (tap to go on, or Skip intro). `__intro(false)` in the console turns it off for the next game.
- Questions come in sets of 3. The meter top left is your strike power: a rising wedge in three steps that light up yellow, orange, then red with each right answer, ending in a lightning bolt that lights up when it's full (no numbers or label). Every set ends in a turn: you fly out of the cockpit at warp speed to the battlefield, then choose Shield or Strike. After your turn the cockpit closes back round you and the next question rises. 1 right = −100 to each player hit, 2 = −300, 3 = −500 (max); 0 = Shield only. The blast area is the same at every power. The power shows as coloured bolts on the Strike card ("MAX" at 3 of 3). The last set's turn is a final strike (none right: no final strike).
- While you answer, stars stream past and the planets fly by the window, so the ship is always moving forward.
- Music: Loop WIP 1 (`assets/music/loop-wip1.ogg`, the default) or Without Fear (`assets/music/without-fear.ogg`); switch or turn it off in Prototype controls → Music.
- Your shield shows as a glowing ring and shield badge on your ship (top left), and pops when it ends; there is no shield text.
- **Strike** brings the cockpit back round the battlefield and takes you off the map; two lasers fire from under the dashboard. **Shield** zooms in on your land and the dome closes round it.
- When someone strikes you, their face, name and the number show by your ship (top left). Your points sit beside your rank (top right).
- Each turn opens with the warp, then the radar scan finds every ship. On the battlefield ships stand still in the top corner of their land.
- **Teacher view:** Prototype controls → Teacher view, or open `index.html#teacher`. Two tabs. **Battlefield**: every ship with its points, rank and name, and a soft glow where strikes land most; **Shuffle** gives everyone a new spot (on the students' map too). **Leaderboard**: a podium for the top 3, then everyone in rank order with strikes landed and times struck. The class keeps playing while it's open.
- **Prototype controls → Turn every** switches between sets of 3 and 2 questions (remembered in this browser).
- **Prototype controls** (bottom right) set up any situation without playing to it: incoming strikes and shields, the strike and shield types on offer, the blast size, territory style, music, reduced motion, a slow-device mode, and jumping to the end.
- In the browser console: `answer(curQ().c)` answers right, and `strikeMe({ from: 'Leo', variant: 'standard' })` has a classmate strike you.

## What's settled, and why

`decision-log.md` records every change with the reason behind it; the `mapbattle-station` entries are this prototype, newest last. Reading the last five or six entries first is the quickest way in. The main decisions:

- **Territory is the core idea.** Each player's land is a calm cyan circle; its size follows points and a strike shrinks it. Answer right to grow your land; the biggest land wins. The opening and the key say this in one line, and there are no numbers on the map.
- **Top right is the radar and your place in land.** Your land is the cyan disc in the radar's centre, inside a gold ring the size of the biggest land; classmates are the dots. A digital board hanging beside it shows your rank ("RANK 8"; gold with a crown at 1). Your shield is the ring round your arrow on the radar, and the dome on your circle when the map is open. Your circle is on the map with a white edge and your "You" tag.
- **Your turn looks out through the glass.** The grid is projected over open space, not drawn on a screen.
- Things the person who commissioned this asked to keep: the windscreen crack when you're struck, and the asteroids drifting past the cockpit.

Constraints: Chromebook first, no scrolling, no drag-only actions, little text, the words "Strike" and "Shield", a laser rather than bombs, and the question card on top with 4 answers below.

## Rule changes this prototype proposes

The live game's rules are M1–M18 in `fe-join/apps/join/docs/SNS_SKY_STATION.md`. This prototype changes some of them on purpose:

- A turn after every set of 3 questions for everyone; right answers in the set set the strike's power (−100 / −300 / −500 per player hit, same blast area), and none right gives Shield only. The last set ends in a final strike (Strike only). Classmates' strikes lean towards bigger land. Live (M1, M2): 2 right for the first turn, then 3, and no turn after the last question.
- One strike hits an area, so it can hit several players. Live: exactly one target.
- Everyone's land shows on the map while you choose a target. Live: the picker shows only avatar and name (M9).
- Shields other than Classic aren't modelled for area strikes yet.

## How the file is built

Everything is in `index.html`. It grew by layering: each change is a `<style>` or `<script>` block added just before `</body>`, so **later blocks override earlier ones**. To change something, search for the newest block that touches it (blocks open with a comment saying what they do), or add your own block at the end. The map logic lives in `window.MAPB`.
