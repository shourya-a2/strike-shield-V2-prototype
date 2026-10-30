# What you have told me — strike-and-shield-game-feel

- Started: `2026-10-14T07:33:52.473Z`

The run's memory, from the first conversation to the final scorecard. Add to it the moment they say something, never as a write-up afterwards.

*Check: every entry names the thing they were reacting to and the date they said it. An entry a later step cannot act on comes out.*

## What you liked

-

## What you rejected

-

## Off the table for good

Directions not to bring back, even in a later round.

-

## What matters most, in order

- Must have:
- Important:
- Nice to have:

## The one thing that matters most

-

## When the objective changed

Date, what changed, and what it replaced.

-
- Q1 (You said): Students are trying to review a topic. Strike and Shield works as an energizer in class.
- Q1a (You said): Worst results, both: a quiet student gets struck over and over, ends up feeling picked on and stops trying; or the strike moment becomes the whole game and nobody is actually reviewing the topic anymore.
- Q1b (You said): Can it be put right? With effort.
- Q2 (You said): The change covers the strike-or-shield moment and also what a student experiences when they get struck. Today, when struck, they are usually mid-question and a message comes to them. "Ideally I'd like to make them feel like they are still in part of the game."
- Their own idea (verbatim, kept out of exploration, re-enters as its own card at directions): "Maybe a widget or anything else can help" — something persistent while answering that keeps them in the game.
- Q3 (You said): Most often played live in class — whole class at once, teacher at the front.
- Q3a (You said): Must also not break on phones, with sound off, in large classes (30+), and on slow devices or wifi.
- Q2a (You said, accepting the drafted example): They know whether their strike landed or their shield held, and they're keen to answer the next three questions — no lingering confusion or sulking.
- Q4 (You said, accepting the drafted example): Attack or play safe; who to target (the leader, a friend, whoever struck them); whether they are about to be targeted themselves.
- Steering: they want fewer questions; draft answers for them to confirm rather than asking cold.
- Scope (You said): all four in scope — choosing strike or shield; picking who to strike (and seeing it land or bounce); getting struck mid-question (and shield holding); staying in the game during the three questions between moments.
- Solution shape (We guessed, unchallenged): change to an existing flow; mechanic, rules and points unchanged.
- Evidence: code reading saved to evidence/code-reading-strike-and-shield.md. Awaiting user screenshots of the four student moments.
- Write-up edits (You said): deleted the 'how many questions until my next choice' need. Bars fill per correct answer and trigger the choice. Struck students see a message naming who struck them while answering. Other strike/shield kinds are NOT live for students.
- Consent (You said): walkthroughs run from screenshots + code (catalog-only), findings on motion/timing marked weaker.
- Live play done (evidence/live-play-observations.md). Key: shield did not block the strike (or expired at next choice) with no explanation; summary has no strike/shield story.
- Scope narrowed (You said, after exploration started): 'I think you are expanding the scope'. Keep: the choice moment, aiming and the hit, being struck or saved. DROP: standings and rivals during questions (score, rank, who is near you). Off the table for this run.
- Steering (You said): 'is this moving in a game like direction' — round 2 directions read as clarity fixes, not game feel. Re-explore with game feel (build-up, aiming, impact, avatar) as the target; clarity fixes stay as required fixes. Round 2 kept in exploration/round2.
- Directions chosen (You said): Avatar in the corner (direction 1, = their widget idea) and Arena face-off (direction 2). Cards rejected for now. Earlier clarity-only directions archived in exploration/round2.
- Feedback (You said): likes Arena face-off. Wants storytelling rather than just avatars, because avatars cannot be rigged (static images only).
- Storytelling direction (You said): Pirate Kings style — strike the classmate's castle, not the avatar. Decisions: castles in the neon arena; damage repairs itself after a few seconds; all castles the same size (no score shown).
- Feedback on castle-siege (You said): 'Not bad' but too cluttered; question-card-over-battlefield can't accommodate other question types. Proposed (not yet approved): full-size question screen + corner castle badge, battlefield takes over only when cannon is full, fewer castles visible at once. User is reviewing the prototype before deciding.
- Approved changes (You said): one ammo counter (header slots become cannonballs), bigger living widget BUT must not reduce the QnA screen, lighter single-row picker, Fire on your cannon. Strip dropped in favour of widget.
- Feedback (You said): middle school edtech, so no cannons and no hitting/damage. Widget at the bottom isn't working; align it at the top. Art style should match the Classic Strike / Classic Shield cards (shared image of the decision screen). Plan: lightning bolt strike + crystal shield from card art; charge = header lightning bars; no damage to castles, points float away as sparkles; widget in top bar.
- New idea (You said): spaceships flying, doing strike and shield. Building as separate prototype sky-fleet.html alongside castle-siege. Guardrails: formation ordered by name not score, no explosions/damage, bolt drains points as sparkles, crystal bubble shield, animate only near ships.
- Chosen for sky-fleet (You said): battery + question zone; face-off on strike (striker only); steering both no-stakes and full versions (build as a switch). Flight placed once per round (after strike/shield, before the next question zone), not after every question, to protect review pace.
- Flow rethink (You said): 'I should steer in the sky and see my opponents'; current flow feels staggered. Decisions: continuous sky world; full-size question container rises over the live sky (sky visible around it), ship on autopilot while answering; battery full -> container slides down, steer among opponents; strike by steering to lock on with tap-a-ship/name backup; shield in place; ~8 s in sky then gentle nudge, battery stays charged if no choice. Remove zone, fly-out, separate flight segment and scene cuts.
- Storyline (You said): core order is choose Strike/Shield first, then (if Strike) pick opponent. Storm pilot story. Choice integrated as two sky gates (lightning gate = Strike -> Hunt mode; crystal gate = Shield) after a few seconds of free flight; tap gate as backup; gates fade if neither -> battery stays charged. Likes Hunt mode. Tone: playful ('Zapped! -500', 'Bonk! Dev's shield held'), never at struck student's expense.
- Feedback (You said): let me fly a bit to reach the strike/shield zone; flying ahead of them and seeing players around is disorienting; must be able to make the choice and not be sent back to questions because the charge ran out. Plan: zone ahead to fly toward, no classmates during approach (appear in Hunt), remove gate and hunt timeouts (hint only).
- Decisions (You said): Hunt = pick from radar then chase; strike = charge and release; skill style only. Spec drafted in sky-fleet-mechanic.md, NOT final: 'let's iterate through prototypes then we'll finalise'.
- Direction (You said, 2026-10-16, on castle-siege): 'make this game very strategy oriented. it should be extremely fun and exciting for middle schooler'. Today the only decision is strike-or-shield, with flat 500 points and every target equal. Strategy mechanics drafted for them to pick.
- Correction (You said, 2026-10-16): 'i dont want to change the mechanic but instead make strike and shield more playable instead of just button click'. Rules and points stay unchanged; overcharge/bounty/mirror/fog are off the table. Goal: replace button clicks with hands-on interactions for strike and shield, where skill changes the style only (same as sky-fleet).
- Chosen (You said, 2026-10-16): Strike = slingshot (pull back, aim dotted arc, release; arc snaps to nearest castle so it never misses; good aim = PERFECT + bigger flash). Shield = catch the crystals (5 shards fall for ~3 s, tap to snap into the dome; missed shards auto-fill; all 5 = FLAWLESS). Points and outcome are unchanged by skill.
- Direction (You said): fun, simple, addictive. 'Steer to choose, hold to zap': gates by steering (liked), radar picker and chase dropped; after Strike gate a wave of classmates' ships flies toward you in lanes, steer into one, hold-release to zap. Approved to build.
- Approved to build (You said): the orb — one charge, two uses (throw = strike, pull in = shield), spend it now, 6 s nudge, 15 s shield default. Building as new file sky-orb.html from sky-fleet.html.
- Damage (You said): yes, visible damage as motivation; only you see your own. Power-down not destruction, 3 levels, correct answers repair. World: must not feel babyish for middle schoolers; asked which is most enticing.
- World (You said yes): sky pilots with grown-up art — sleek racing jets, crackling orb, power-down damage (sparks, flicker, stutter), short confident words, world name like Storm League. Next step after orb build: restyle ships + add own-only power-down damage with repair by correct answers.
- New direction (You said): learn from boss's hill game without copying. Slingshot strike (Angry Birds), shields are building blocks for your own fort on a floating island, same height for all (no ranking). Agreed: toppling blocks OK (objects not people), gentle aim assist (skill = style), everyone sees built blocks, toppled blocks drift back, forts on floating islands with ship docked. Iterate on feel first; no end-to-end yet. Step 1: sling-forts.html (slingshot + forts physics).
- (You said) Angry Birds-like is the target; boss's game = castles on hill, avoid kingdoms-on-land. Dislikes neon look; art later — crack mechanic and fun first. Next: sling-v2.html greybox: map pick -> camera sweep -> side-view sling at one unique tower (blocks + shield blocks + core); Shield = place earned block on own tower.
- (You said yes): next pass on sling-forts: Robo Fight art style (evidence/art-ref-robofight.webp), Qbit alive on tower, personal records (only you), correct answers bank blocks dropped via crane taps at the charge moment, only active shield block stops a strike, others see towers same size.
- (You said): overcomplicated, can't understand. Back to basic mechanics; art = cyberpunk neon vibe. Dropped: crane building, banked blocks, records, living Qbit extras.
- Build (You said, 2026-10-19, on sky-orb): make strike and shield part of the game, not just clicking; fix "struck kid mid-question doesn't know what's happening". Built on sky-orb.html (previous saved as sky-orb-v2.html): lock-on + aim line; hold and let go in the gold sweep for PERFECT (same 500); shield = catch 5 crystals, FLAWLESS if all caught; incoming warning (~1.5 s edge glow, target ring, "Kabir is aiming at you!") then named bolt, -500 off your widget, line stays until you answer; "Zapped you" tag in the arena behind a prototype toggle.
- Question (You asked, 2026-10-19): what if there are 20 kids to choose from. Proposed (not built): all 20 on one screen on laptop, swipe ship wheel on phone, "Zapped you" shortcut chips, order stays A to Z.
- Approved and built (You said yep, 2026-10-19): end-of-game story screen, only you see it: questions first, pilot title by play style (never rank), moves in order, three counts, best moment, calm line about being zapped.
- Direction (You said, 2026-10-19): "It'll be easier if we come up with some form of storytelling". Chosen: Storm Chasers. The class is a squad flying into a storm that grows over the game; the storm is the real opponent, classmates are friendly rivals. Three acts (Q1-3 takeoff, Q4-7 into the storm, Q8-10 eye of the storm), storm clears at the end into your flight log. Story guide: storm-chasers-story.md.
- Feedback (You said, 2026-10-21, on sky-orb.html): catching crystals "just feel like more clicking"; wants kids to have more fun without clicking and clicking. Didn't see the difference the crystals make.
- Direction (You said, 2026-10-21): judge the game by its high moments for kids, in a class context (creators, class bonding). Choosing is a great act. The strike screen lays the jets out like typical UI; it should feel like open sky with jets scattered, seen through a telescope/scope: eye your opponent, zoom in, select the suspect, then it becomes a face-off between you and them. Three things to build: (1) exaggerate the selection, (2) the strike/shield face-off, (3) what you feel when it happens to you while answering. Earlier: crystal catch felt like more clicking.
- Built (2026-10-21, sky-orb.html; previous saved as sky-orb-v4.html): scope selection (jets scattered in open sky, drag to sweep, names and shield only inside the lens, jet in the centre is in sight, Lock on); lock-on zoom then face-off (MAYA VS DEV with avatars, both jets big, honest shield line, hold and let go in the gold, result in the VS card, Back to scope); mini face-off under the widget for the zapped kid while answering (their jet, orb charging, you with target ring, then -500 or Blocked!, then the line that stays until you answer, desktop only, phone keeps the text line); shield back to one tap (crystal catch removed).
- Tone (You said, 2026-10-21): zapping may feel intense for middle schoolers, but keep the names Strike and Shield and keep the lightning. Not babyish (balloons rejected). Show getting hit, never hurt: things can break a little, nobody is hurt or dies.
- Direction (You said yes, 2026-10-21): storm stations. Each pilot has a floating island with a lightning tower; strikes break pieces (glass panels shatter, rock chunks fall), 3 levels, never destroyed; shield = crystal dome over the station; correct answers rebuild. Start with the face-off only, as a separate file sky-station.html. "If this doesn't work, we go back to the previous version" (sky-orb.html stays as the liked version).
- Approved (You said yes, 2026-10-21): the station face-off works. Next: scope becomes a sky of floating stations, then your small station in the top bar while answering.
- Built (2026-10-21, sky-station.html; step 1 saved as sky-station-v1.html): scope is a sky of floating stations (names and shield only inside the lens, damage hidden by default behind a 'Scope shows damage' switch); your own station beside the question and in the top bar replaces your jet; a strike that lands breaks a piece of your station (glass, then rock), correct answers float pieces back ('Station rebuilt.'); the small face-off shows the striker's jet against your station; your jet no longer powers down.
- Feedback (You said, 2026-10-21, on sky-station.html): the top is cluttered while answering ("Kabir zapped you" UI and placement). Fixed (previous saved as sky-station-v2.html): one slim line in one spot: warning row (their jet, charging bolt, your station, 'Kabir is aiming at your station'), then one line 'Kabir struck your station. -500' until you answer; no avatar, no tip line, no edge name label, no extra target ring on the top-bar station; the shield tip moved to the strike screen; the act line waits for the spot to be free.
- Approved (You said yes, 2026-10-21): two equal choices with your station at the bottom (Shield my station / Strike), plus the full cleanup list, built in a new copy sky-choice.html (sky-station.html stays).
- Built (2026-10-21, sky-choice.html from sky-station.html): your station with the orb at the bottom; two equal buttons 'Shield my station / Blocks the next strike' (blue) and 'Strike Kabir / Lock on, then hold' (red, follows the scope); shield dome blooms on your station; face-off is your station vs theirs. Cleanup: no 'Battery low' text, struck line cleared before the strike screen, one-line banner 'Strike a station, or shield your own.' (no chips), no crosshair, only the station in sight shows name and tags, no 'No shield' tag, search only for classes over 12, no 'Tap to shield' chip, face-off line only when it matters.
- Feedback (You said, 2026-10-21): work on sky-station.html; don't make a new prototype for every feature. sky-station.html now carries the two-button choice (from sky-choice.html). Question raised: you can't find Kabir in the scope; how are opponents laid out and how does the drag work in Chrome.
- Built (2026-10-21, in sky-station.html, which now also carries the two-button choice): stations laid out A to Z left to right (down each column of 3, then the next), names on every station (dim outside the scope, full on the one in sight), edge arrows 'Kabir · struck you' for out-of-view stations that struck you (tap to fly there; name only on phones), mouse wheel and trackpad sweep the sky (plain wheel sweeps sideways), a quick flick keeps gliding, search always shown, hint 'Drag or scroll to look around'.
- Request (You said, 2026-10-21): make all animation and transitions smooth; the prototype is for peers and manager to play, so it must be spick and span. Review as a high-end product designer and clean up.
- Polished (2026-10-21, sky-station.html): staged entrance to the strike screen (fade, scope scales in, stations fade in, your station rises, buttons slide up); strike screen fades out before the next question rises; back to scope fades the sky back and glides your station back; answers ease in on each new question; scope stations rest their small animations so the sweep stays smooth; prototype controls moved bottom right above the buttons ('Controls' on phones); all player-facing words say strike and station. Full scripted game and reduced motion run with no errors.
- Art brief (You said, 2026-10-21): not extremely dark; a restricted colour palette, not everything together; not cute or babyish (middle school); exciting, fun, playful and energetic. Robo Fight was a reference for energy, not colour (the earlier Robo Fight build was clunky and too colourful). Will share a moodboard; wants to know which styles an AI can pull off well. Asked for a separate prototype to test different UI styles: style-lab.html.
- Built (2026-10-21): style-lab.html, a separate UI test prototype (user asked for it): the same three moments (answering, choosing, face-off) in four restricted-palette styles: A Daylight storm, B Dusk arcade, C Comic bolt, D Crystal facets; switch style and moment, play a strike, step damage 0-3, shield on/off, phone frame. Waiting for the user's moodboard.
- Moodboard (You shared, 2026-10-21, Figma board 7F5WbI2HRvPl29p8Iu5EQR node 40:57, 21 refs). Families: flat toon (OK KO brawler, schoolyard Episode 2, DEFEAT court, Steven Universe x2), bold-outline cartoon (gummy wrestling, forest platformer, Bad Piggies, Battletoads), hand-painted HD (Monster Boy, Wonder Boy, Rayman, Mickey, card game, Skullgirls, painted top-down, Cult of the Lamb), pixel art (Alex Kidd, isometric town). Sticky notes: blurred background, palette coordination, easter eggs, glow depth, details of background, dark BG supporting UI, surrounding elements with stroke, Qbits in different worlds, gradients, lighting effects. My recommendation: flat toon + lighting tricks; proposed adding Style E (two palettes) to style-lab.html.
- Built (2026-10-21, style-lab.html): Style E · Flat toon in two palettes from the moodboard: E1 Schoolyard (teal, coral, lemon, cream, ink) and E2 Crystal violet (lilac, deep violet, magenta, cyan, lemon). Blurred far layer (skyline / crystal spires) plus sharp mid layer, Qbit easter egg peeking in the sky, ink strokes with hard offset shadow, glow only on lightning and crystals, dark top and bottom bars holding the UI, Lilita One slanted type (banner, VS, STRIKE!).
- Chosen (You said, 2026-10-21): apply E1 Flat toon: Schoolyard to sky-station.html.
- E1 was applied to sky-station.html (2026-10-21) before the user said: test more styles first, then go forward with one (pre-reskin copy kept in scratchpad). Added Style F · Flat geometric to style-lab.html from the user's new reference (flat blocks with lighter top faces, no outlines, warm sand and terracotta, deep teal frames, chunky round badges, light beam, Luckiest Guy type).
- Feedback (You said, 2026-10-21): dislikes all lab styles A-F: extremely flat, sloppy, palettes all over the place. Asked to try the Heroes Strike look.
- Built (2026-10-21, style-lab.html): G · Heroes Strike (3D), from screenshots of Heroes Strike by Wolffun. Real 3D stations via Three.js (low-poly islands, owner-colour ring, crystal tower with gold core, chunks, faceted shield dome, fog, far islands, bloom), HTML UI in the Heroes Strike language: glossy split-tone buttons, blue ribbon banner with gold edge, gold hexagon badges, metallic gold italic VS and STRIKE!, dark glass panels with cyan rims, Barlow Condensed italic. Palette: navy, royal blue, violet, cyan, gold, red-orange.
- Feedback (You said, 2026-10-21): remove Daylight storm, Comic bolt, Crystal facets, Flat toon Schoolyard, Flat geometric (all too flat, no depth, look bad). Keep: the original look, Dusk arcade, Flat toon Crystal violet, Heroes Strike. Add more styles with depth that look premium and exciting. Plan: Original (2D) + Storm night (3D) + Golden hour (3D).
- Built (2026-10-21, style-lab.html): lab now has six styles: Original (the first Storm Chasers look), Dusk arcade, Crystal violet, Heroes Strike · 3D, and two new 3D styles with depth: Storm night · 3D (original night mood with magenta and blue rim light, strong glow) and Golden hour · 3D (warm sunset, sandstone and moss, low side sun). The 3D engine now takes a theme per style. Removed: Daylight storm, Comic bolt, Crystal facets, Flat toon Schoolyard, Flat geometric.
- Request (You said, 2026-10-21): try an art style like Enyo (Arnold Rauers): Greek black-figure pottery look, black silhouettes, parchment, terracotta, bronze, brush texture.

- Feedback (You said, 2026-10-21): the Enyo theme feels too dark; removed it (lab back to the six styles).
- Request (You said, 2026-10-21): try the PixelJunk Shooter Ultimate art style. Plan: bright lavender/ice cave variant (avoid dark), pebble-textured rock, layered depth, glowing liquids, slanted HUD.
- Built (2026-10-21, style-lab.html): PixelJunk cave style (bright lavender/ice cave in layers, pebble-textured rock and stations, glowing lava fall, drifting motes, slanted translucent HUD, Exo 2 italic). Lab now: Original, Dusk arcade, Crystal violet, Heroes Strike 3D, Storm night 3D, Golden hour 3D, PixelJunk cave.

## Pikmin 4 direction: Garden guard · 3D (style lab)
- User asked to try Pikmin 4's identity: the kid is an alien-like guard protecting their island, messages come in, and the Strike or Shield message arrives before the choice.
- Built as one more style in style-lab.html (no new file): the kid is "Guard Maya"; Captain Pip, an alien commander, radios each moment in. On Choosing, the message lands first and the two buttons pop in about a second later. Face-off and Answering use the same radio box instead of the subtitle and the alert.
- World: bright daylight, soil and grass islands with flowers, three small alien guards in the owner's colour on each island (they hop when a strike lands), tilt-shift blur at the top and bottom, big blurred leaves in the corners. HUD: teal glass panels, round type (M PLUS Rounded 1c), Pikmin red, yellow, blue and purple.
- sky-station.html is unchanged; it still has E1 Flat toon until the user picks a style.

## Starlight (flat, painterly night) in the style lab
- The user shared four references (Pocket Camp night, flat waterfall, flat submarine, a monochrome forest). They want flat art with depth: one colour family, gradients and a painterly grain. They want the night and space feeling of Storm night and the original. They want recognisable characters for the islands, the craft and the strike, built from real examples and curated in a moodboard, not just a recolour.
- Built: a moodboard panel in style-lab.html (shown with the Starlight style). It holds the user's four images plus public-domain prints in prototypes/moodboard/: Grandville's Laputa, the 1783 Montgolfier balloon, and Kuniyoshi's Raijū.
- Free asset packs checked: Kenney Tappy Plane (CC0) and itch.io floating islands. They didn't fit the palette, so the art is drawn fresh from the references.
- Islands: Laputa-shaped, each with its own landmark (lighthouse, observatory, windmill, camp, treehouse, clock tower). Each kid flies a Montgolfier balloon in their own colour with their avatar on it. The strike is a Raijū (thunder beast) that leaps along the bolt. The shield is a dome of stars.

## Game style read, and Garden guard · Clash UI
- The user asked what kind of game this is before any more UI. My read: a quiz game with a light "take that" layer, not real strategy. Closest matches are Coin Master (base, attack, shield), Clash of Clans (base and shield after a raid) and Blooket Gold Quest (classroom steal loop). Highs: choosing the target, the strike landing, a shield bouncing a strike, revenge, comebacks. Lows: getting hit while answering, ganging up, the weak-student spiral, losing earned points.
- The user likes the Garden guard world and its 3D, but the alien guards don't work and the UI is cluttered. They agreed to try a Clash of Clans-inspired UI in the lab.
- Built "Garden guard · Clash UI" alongside Garden guard · 3D: same 3D world, no alien guards, HUD in the corners (your plate top-left; charge and shield status top-right), both choices in the bottom corners, chunky outlined panels, glossy buttons, white outlined type (Lilita One). Captain Pip is a parchment pop-up that slides away on Choosing but stays when you've been hit. No Supercell font or art copied.
- Next agreed step after this: write the garden story beats and a decluttered screen plan for review before changing sky-station.html.

## Sketchbook · paper (collage and pencil) in the style lab
- User asked for a storytelling layer: a full collage and pencil style, as if someone drew the game, with each island as a ship made of paper.
- Built "Sketchbook · paper": ruled notebook page with a red margin, paper grain, pencil doodles (sun, paper plane, stars), torn tissue-paper clouds and tape. Each kid's ship is an origami boat with its sail cut from a notebook page and its hull in the kid's colour, floating on a pencil cloud, with the kid's photo taped to the sail. The charge is a highlighter scribble with a bolt drawn in it. The strike is a bolt drawn in pencil over highlighter that tears a corner off the ship. The shield is tracing paper taped over the ship. Messages arrive as sticky notes before the choice. Type is Permanent Marker and Patrick Hand; buttons and cards are construction paper with hand-drawn borders.
- Copy follows the story: "Your pencil is charged", "Kabir tore a corner off your ship… keep answering to tape it back".
- Note for checking: the in-app Browser pane freezes CSS animations at time 0, so entrance animations look missing in its screenshots. This is not a page bug; finishing the animations shows everything correctly.

## sky-station.html back to the original style
- User asked to keep the prototype in the original style for now. Restored sky-station.html from the backup taken just before the E1 Flat toon reskin; the only differences were the toon layer. The toon version is saved in the scratchpad as sky-station-with-toon.html.
- Next: look at the fonts, with a "mechanical" type in mind. The original uses Chakra Petch for display and Quicksand for body text.

## Mechanics: choice first, cockpit view, simple rules
- Problem: with Strike and Shield on one screen and the target already showing, kids rarely pick Shield.
- User's direction: the choice comes first, from inside the craft (first-person cockpit). A joystick selects the Shield or Strike switch on the dashboard, and what happens plays out from the cockpit. Strike then shows the opponents.
- "Who's aiming at you": parked; the user will check with their developer (it needs live targeting state).
- Rules kept simple: a strike costs 500 points and one health bar. Shield blocks the next strike and repairs one bar. Health shows as 3 bars matching the station's damage looks. No special rule at zero health; the user wants to avoid edge cases and overcomplicating the game.
- Open: is the cockpit the control room of the kid's station, or do kids fly a craft again?

## Clarity of the choice, and a lanes prototype (sky-lanes.html)
- User's concern: choosing Strike or Shield must never depend on skill with the keys or joystick. A kid who wants Strike must never end up with Shield by accident, or the other way round. The choice has to be a clear, deliberate tap.
- User asked for a separate prototype (explicitly a new file) to test another way of picking who to strike: three lanes like a racing game, opponents' stations coming down the lanes, dodge the ones you don't want and hit the one you do.
- Built sky-lanes.html as a copy of sky-station.html:
  - When charged you see only your station, Shield my station and Strike. Opponents appear only after Strike.
  - Strike opens a three-lane run toward a gold line. Stations fly down the lanes in waves of one or two, so there's always a free lane. You steer with the arrow keys, a swipe or a tap on a lane. Whatever crosses the gold line in your lane is struck: your orb fires, the station breaks (or bonks off a shield), −500, then the next question.
  - A Back button or Escape returns to the choice. After about 32 seconds with no hit, the game returns to the choice.
- sky-station.html is unchanged.

## Choice first, in the cockpit (sky-station.html)
- Decisions: (1) two buttons on a cockpit dashboard, not flying through zones; (2) Shield means what it says: it saves you from the next strike, with no repair (right answers still rebuild your station, as before); (3) the word is "Strike" everywhere, never "zap".
- Built in sky-station.html:
  - When charged, a first-person cockpit opens: canopy frame, a HUD showing your station's state, and a dashboard with two equal buttons, Shield (S) and Strike (L). The arrow keys only move between the buttons; a tap or Enter decides.
  - Strike: the cockpit rushes forward into the scope, which has only a Strike button plus Back to the cockpit. Escape also goes back. Lock-on and the face-off work as before.
  - Shield: a crystal dome sweeps over the glass, then the station shield plays.
  - Every player-facing "zap" now says "strike"; the flight log says "You struck N times."
- storm-chasers-story.md updated to the station world, the cockpit beat and the word "Strike".
- Still there from before: after about 15 seconds without a choice, the charge becomes a shield on its own.

## Fortress Wars, built on sky-lanes.html
- User asked to evolve sky-lanes.html into Fortress Wars: each student owns a fortress that grows with correct answers (Outpost, Fort, Stronghold, Citadel). Strike and Shield should feel native, with no structural damage, existing mechanics kept, and a persistent bar showing your fortress, progress, charges, shield, score and rank, plus a class overview.
- What the inspection found: answer() handles questions and charges (S.bars, need() = 2 for the first unlock, then 3); laneHit() resolves your strike through resolveZap(); strikeMe() handles incoming strikes and the shield; there was no score or leaderboard state (558 054 in the header is the game code).
- Built, in place:
  - Progress is the count of correct answers, read from the answer log, and never goes down. Stages at 0, 2, 5 and 8 correct.
  - One renderer: stationHTML now draws a fortress at the owner's stage, so the lanes, the choice screen, the header widget and your big fortress beside the question all became fortresses.
  - A fortress bar under the header: your fortress, its name and stage, progress to the next stage, Charge, Shield, points and rank, and the class list sorted by score (mini fortresses, shield domes, your card highlighted). On phones the class list opens from a Class button.
  - Minimal score state: you +600 per correct answer and −500 when struck. Classmates have mock progress and scores and keep answering at their own pace. Your strike takes 500 off their score, and the caption and the class list show it.
  - Strikes no longer break anything: the station-damage calls were removed from the incoming strike and from your strike.
  - A blocked strike deflects off your barrier in the bar ("Blocked!"); a landed strike costs 500 there.
  - Copy now says fortress instead of station, and the logo reads Fortress Wars.
- Tested with headless Chrome at 1366×768 and 390×844: all seven deliverables, with no console errors.

## Fortress Wars art direction (fortress-wars-art-direction.html)
- User gave a full art brief: stylised 2D/2.5D fantasy strategy, three-quarter isometric, chunky silhouettes, painted surfaces, soft light from the upper left; navy UI, cyan shields, gold progress, coral attacks, green terrain; nothing childish, gritty or glossy 3D.
- Built an art direction board as a new page (prototypes/fortress-wars-art-direction.html). All art is drawn in code from one isometric kit so it can go into the prototype. It covers:
  - a hero scene, five rules and the palette;
  - the four stages (Outpost, Fort, Stronghold, Citadel) on floating islands, with class-list sizes and a silhouette check;
  - six team colours (roofs, banners and flags only), and the five rendering passes;
  - effects: shield up, strike blocked, strike lands, stage up;
  - an interface kit (fortress bar, buttons, chips, type: Rowdies and Nunito), a Chromebook in-context screen, and do/avoid lists.
- Not yet applied to sky-lanes.html, which still uses the earlier flat fortress art.

## Art direction applied to sky-lanes.html
- The user asked to apply fortress-wars-art-direction.html to sky-lanes.html.
- Done:
  - The isometric kit is now one self-contained module (KIT), and every fortress in the game draws from it. Your own fortress gets the painted grain. Earlier stages sit smaller in their box, so growth shows.
  - Shields are a cyan dome inside each fortress drawing.
  - Team colours: you are violet and classmates get deep heraldic tones (these replaced the neon banner colours).
  - A clear day sky with soft clouds; the night tiles, storm weather and night rocks are hidden.
  - Navy interface surfaces; type is Rowdies and Nunito.
  - Navy answer tiles, with green for a correct answer; a green Submit; blue Shield and coral Strike buttons.
  - Fortress bar per the kit: gold progress and charge pips, a blue chip when your shield is up, cyan rings on shielded classmates, a gold ring on you, and a coral ring on a struck classmate (the list scrolls to them).
  - Lanes: navy road, white lines, coral strike line.
  - Effects: strike bolts are coral with a fireball head, deflections are cyan, and the charge bolt stays gold.
- Left as is: the act lines still use storm wording ("Into the storm") even though the weather is now off.
- Tested with headless Chrome at 1366×768 and 390×844, with no errors.

## Crystal shield in sky-station.html
- The user liked Garden guard's crystal dome shield (style lab) and asked for it in sky station. Taken to mean sky-station.html.
- Replaced the flat hexagon shield with a geodesic crystal dome drawn in 2D. It uses the same 80-facet icosphere as the 3D version: faceted cyan glass lit from the upper left, bright facet edges, faint back facets and three twinkling glints (off for reduced motion).
- Every shield in the file uses the one shared symbol, so it updated everywhere: stations, the header widget, the "aiming at you" card and the cockpit's shield sweep. Existing in, fade and block animations still run.
- sky-lanes.html (Fortress Wars) still uses its own art-direction cyan dome.

## Less repetition when you are struck (sky-station.html)
- User: when someone strikes me there is a lot of repeated info.
- Before, it showed:
  - three warnings: an edge glow, a target ring, and a caption with a mini replay of the strike;
  - two bolts, one to the big station and one to the header widget;
  - −500 up to four times: a pop on the station, a stamp on the replay card, then a caption.
- Now it's one of each:
  - one target: your big station if it's on screen, otherwise the small one in your header widget;
  - one target ring, one bolt and one impact;
  - one caption under the widget that changes in place: "Kabir is aiming at your station" becomes "Kabir struck your station. −500" or "Blocked! Kabir's strike bounced off your shield."
- No pop words at the impact and no edge glow; the widget updates its state quietly when the big station takes the hit.

## Station levels and defence towers (option C, sky-station.html)
- The user's idea: a real reason to choose a target. Objective: the strongest station at the end of the round. The user chose option C (a permanent level plus defences that strikes knock off). No crown for the leader, since the end leaderboard already shows who's ahead. Built in sky-station.html in its night style.
- Built:
  - Level from correct answers, never lost: Outpost (start), Tower (2 correct), Spire (5), Citadel (8). Each level makes the crystal tower taller; Spire adds two side spires, and Citadel makes them taller and adds a gold deck trim.
  - Three small crystal defence towers on every island. A strike knocks one off (it falls); a correct answer rebuilds one. They fall front-right, then front-left, then left.
  - The level number is on every name plate.
  - In the target scope, every station shows its real level and towers, and higher levels draw a little larger.
  - The face-off says "Hiro's station: Level 2, 2 of 3 towers, no shield"; the result says "Hiro lost 500 and a tower. 1 of 3 left."
  - Your header chip shows "Lv 2" and three tower icons. Being struck says "−500 and a tower"; rebuilding says "Tower rebuilt. 2 of 3 standing."
  - Level-ups show "Level 2: Tower. Your station grew." If the same answer fills your charge, the message waits until you're back at the questions.
  - Classmates have mock levels spread across 1 to 4 and keep answering between your questions, so they grow and rebuild too.
- My own calls: the level names and thresholds; no protection after being struck (kept simple); the end-of-round story doesn't show final levels yet.

## Free assets for stations: Kenney Space Kit mock-up
- The user found the drawn defence towers unclear and asked to look for free assets on the net first, telling them before building. First round (Kenney Tower Defense, Quaternius Fantasy RTS, KayKit Hexagon): user asked for a different pack. Second round: user picked the Kenney Space Kit (CC0, 6.7 MB).
- Built a mock-up only (prototypes/station-levels-mockup.html); the game is unchanged.
  - Stations rendered with three.js in sky-station's night light (prototypes/_scrap/space-render.html, models in _scrap/kenney-space with the CC0 licence). Kit colours remapped: orange accents become the kid's colour, ground becomes night rock, crystals become cyan.
  - Four levels, each adding a taller landmark: Outpost (small hangar and dish), Base (glass dome and 2-section comms tower), Station (big hangar and 3-section tower), Spaceport (adds a rocket).
  - Three turret defences that become rubble when lost.
  - A scope scene with classmates at different levels and states: the crystal shield dome, Struck you tag and lens on a target.
- Renders are in prototypes/assets/stations/.

## Kenney Space Kit stations in sky-station.html
- User approved swapping the mock-up stations into the game for every kid, keeping the crystal shield and night style.
- Built:
  - Each station is now an image rendered live in the browser by a three.js module from the Kenney Space Kit (prototypes/assets/kenney-space, CC0 licence included), in the night light.
  - Images are cached per level, turrets left and kid colour; any key not yet cached is rendered on demand.
  - stationHTML draws that image and keeps the glow, the kid's docked jet (now hovering at the island's upper left), the name plate with the level badge, and the crystal dome.
  - Strikes and repairs swap the art: a turret becomes rubble, and debris flies from that turret's spot (projected from the 3D scene).
  - The old drawn crystal tower and its turret art are gone.
- Not changed: the classmates drifting beside the question are still jets, as before. three.js loads from jsdelivr, so it needs internet, like the style lab.
- Tested a full round with headless Chrome at 1366×768 and 390×844, with no errors.
- Follow-up: the classmates drifting beside the question are now small Kenney stations too (level, turrets, shield dome, name plate with level), at about 86% of your own station's size. Their art and dome update when their shield is used up.

## Brighter sky, no purple; CraftPix towers mock-up
- User: not heavily dark, no drift to purple; wants sky battle with floating ships but energetic and fun. Brainstorm first, no game change.
- User asked for a mock-up with CraftPix "Free Fantasy Guard & Magic Towers" (free licence: commercial use OK, no redistribution of source files). The real download needs a CraftPix account (I can't sign in), so the 16 tower sprites were cut from the pack's public preview image for the mock-up only (prototypes/assets/craftpix-towers/).
- Built prototypes/sky-towers-mockup.html: daytime sky, cartoon floating islands, four levels = the four built stages of a tower family, four families (brick, wood, green crystal, violet crystal), three pennants in the kid's colour as defences, a bright scope scene with the crystal dome. Game unchanged.

## New prototype: sky-towers.html (stormy daytime + CraftPix towers)
- User chose the stormy daytime direction and asked for a separate prototype with the CraftPix towers to compare against sky-station.html. Kids don't pick a tower: we set the ladder and tell them their level.
- sky-towers.html is a copy of sky-station.html (cockpit choice, scope, face-off, levels, defences, crystal shield all kept). Changes:
  - Tower ladder, the same for everyone: Wooden Lookout (start), Wooden Fort (2 correct), Stone Keep (5), Crystal Spire (8), on cartoon floating islands.
  - Defences are three flags in the kid's colour; a strike knocks one onto the grass.
  - The header chip shows "Lv 2 Wooden Fort" plus flag icons. Level-ups say "You built a Stone Keep! Level 3 of 4. Next: Crystal Spire at 8 correct answers."
  - Bright blue sky with sunlit clouds; storm acts turn it grey-teal with rain (never night); deep teal panels; no purple.
  - Lilita One for names and buttons.
- The Kenney renderer is not used here. Tower images are cut from the CraftPix public preview; the real files need a free CraftPix account.

## Power and live rank (sky-station.html)
- User feedback: you can't tell if you're winning or better, points are unclear, and it feels like a quiz. Decisions: one number, Power (option A: Strike and Shield turns come on a rhythm, shown as a ring, not a battery). Show a live rank: top 3 plus the player above, you and the player below. Streaks and "you passed" moments: undecided, not built.
- Built:
  - Power replaces the battery in the header: a number with a ring that fills toward your next Strike or Shield turn. +600 for a correct answer; −500 when you're struck; your strike takes 500 from the target.
  - A live rank panel at the top right while answering (wide screens), with your row highlighted and flashing green or red when you move. Narrower screens show "#10" on your chip instead.
  - Classmates' mock power grows as they answer.
  - Copy updated: "Your turn: shield or strike?", "−500 power", and so on.
- Note: classmates start with a head start, so you begin at #21 of 21 and climb.
- Follow-up: every classmate now starts at 0 power, level 1, all towers up; the race starts level. Before anyone scores, the panel says "Race starts". Equal power shares a rank, and you're listed first among ties.

## Simplify: no building, sniper scope, rank on your turn, split screen (sky-station.html)
- User feedback: remove the header badge (level and tower shells); simplify and keep the spaceship-and-island idea but drop building (levels and defences); no cards for choosing, use the sniper/scope to zoom in on one; no live rank on the question screen; add part of the gameplay to the question screen as a split screen. Shared a low-poly floating island (trees, rock spires, waterfall) as the island reference. Answers: keep the night sky; the split panel is a live sky view; the rank appears on your turn.
- Built:
  - Header badge removed. Power with its ring is the only header element, plus a small shield badge when your shield is up.
  - No levels and no defence towers anywhere (copy, face-off and scope now talk about power and rank).
  - Every station is now a low-poly floating island like the reference (grass top, faceted earth cliffs, trees, rock spires, pool and waterfall, a rim in the kid's colour) with the kid's Kenney spaceship docked on it.
  - Sniper scope: a crosshair in the lens; the station under it swells up to about 1.85×; a readout gives name, rank, power, shield and "struck you".
  - Live rank: hidden on the question screen; shown on the cockpit and in the scope. Tapping a name swings the scope to that classmate.
  - Split screen on wide screens (≥1000px): a "Your sky" panel on the left holds your island and up to two classmates drifting; strikes land there; the questions sit on the right. Phones keep the full-width question (no split).

## Split removed, bigger ships, rank-ordered sky, unified style mock-up
- User: the art isn't cohesive; remove the split screen; the ships are too small; 30 classmates is still a hunt. Agreed: make a unified-style mock-up first; build the rank-ordered sky plus radar blips.
- sky-station.html:
  - Split screen removed; ships about 80% bigger on their islands.
  - The scope's sky is in rank order: more power floats higher, a few stations per altitude band. It opens centred on your own altitude, with a dashed "You #12" marker in the lens. Every station shows its rank.
  - Radar blips on the scope edge point to the leader, the player just above you and anyone who struck you; tap one to swing there.
- unified-style-mockup.html (mock-up only, for review): one low-poly world (islands, ships, faceted charge gem, low-poly clouds, crystal dome), a deep blue night (no purple, no neon), Fredoka with one solid blue panel style, colour roles (gold power/rank, coral strike, cyan shield, teal you), faceted answer tiles in the same palette. Two screens: answering, and choosing a target in the rank sky with an altitude strip, blips, a live rank and a sniper lens with ticks.
- Applied the unified style to sky-station.html: deep blue night with low-poly clouds (the purple glows, neon rocks and soft clouds are gone); Fredoka everywhere; one solid blue panel with a light border for the header, question card, captions, banners, rank, readout and blips; faceted answer tiles in coral, amber, teal and blue; coral Strike, blue Shield, coral Submit; the glowing orb replaced by a faceted gold gem; strikes in coral; name plates as pills in the kid's colour; cockpit dashboard in the same blues. Tested a full round on laptop and phone with no errors.

## Copy cut, UX chart, fonts, real-code edge cases
- Cut repetitive text in sky-station.html: the cockpit (stale "Storm Chasers", lamp label, second power readout), the scope ("Pick a target.", no button subtitle), the face-off line (#rank · power), the strike result ("X now has N power." instead of a three-way repeat), the blocked and shield-up lines.
- prototypes/ux-flow.html: a flow chart of one round. prototypes/font-options.html: seven fonts; recommended Rubik (Sora as the tech alternative).
- Audited ~/code/fe-gameplay (teacher settings, dashboard, shared types, one student e2e test). Student screens and the game rules are not in it: they live in the join app and play-api.
  - Shared types: 4 strike types and 4 shield types; outcomes rebounded, brokeTargetShield, struckTarget, deflected, absorbed; shields carry expiresAt.
  - The dashboard applies score deltas with no floor, so scores can go negative.
  - Live-only; off for Reading quizzes and Serious theme; turning it on turns Mastery Mode off.
  - The excessive-strikes penalty, timeouts, disconnect handling and targeting rules are not in this repo.

## Building in the real codebase (fe-join)
- User asked to start building on the real code so it can become a PR, locally in this session.
- The student Strike and Shield screens are in quizizz/fe-join (cloned to ~/code/fe-join), not fe-gameplay. Branch: shourya/sns-sky-station (nothing committed or pushed).
- The repo pins Node 20.19.3; it was downloaded to ~/code/.node20 and used for pnpm install, tests and type-check.
- Built, behind the `sns_sky_station` feature flag (or localStorage 'sns_sky_station'='1'):
  - useSnSSkyStation composable;
  - SnSPowerRing (Power plus the ring, replacing SnSProgress in AppHeader);
  - SnSCockpitChoice (replacing the two cards in ActionScreen, showing the offered variant, with a 15 s auto-shield);
  - specs for both, and docs/SNS_SKY_STATION.md mapping every prototype moment to components.
- Tests pass, type-check is clean, and there are no new lint warnings.

## Answers to the four open questions (2026-10-22)
- Picker for 30+ students: the ranked list sits alongside the free-drag scope. Tapping a row swings the scope there, and dragging still works.
- Filters: keep all four (Near me, Leader, Struck me, No shield).
- Font: Rubik replaces Fredoka.
- Design states for every missing outcome: deflected, rebounded and absorbed; Stealth strikes (striker hidden); negative scores; and the excessive-strikes penalty (placeholder threshold, since the real one lives in play-api).

## The mechanic matches the real code (2026-10-22)
- The user's rule: the designer builds on top of the existing game. The mechanic must not change, every edge case in the real code must be covered, and the prototype and fe-join code must match each other so the work hands off cleanly to a developer.
- The 15 s auto-shield was removed from both the code and the plan, because the real game has no timeout on the choice.
- Targeting matches the real game: random order, with no score, rank or shield shown while picking. This replaces the rank-ordered sky.
- The list for 30+ students has a name search and a Struck me filter only. This replaces Near me, Leader and No shield, which would reveal hidden information.
- The scope keeps only the "Struck you" pointer, which is not shown for Stealth strikes. The leader and just-above pointers and the rank panel are removed from the scope. Your own rank stays in the header pill, as it does today.

## Chromebook is the main target (2026-10-22)
- The user said Chromebooks are the main audience and asked to optimise for that screen: 1366×768, or about 1366×657 inside Chrome with its tabs and address bar.
- Dragging the scope was dropped as the way to pick a target, because trackpad dragging is hard and finding 1 of 30 meant sweeping the sky. Picking is now a grid of every player on one screen, in this turn's random order, showing station, avatar and name. It has a name search, a Struck me filter, arrow keys and type-to-search. Up to 40 players fit at 1366×657 with no scrolling. One click flies the scope to that station, locks on, and opens the face-off. Back from the face-off returns to the grid.
- The prototype's Screen control defaults to "Chromebook, in Chrome (1366×657)", with options for full screen (1366×768), fit window and phone.
- Big animated blur layers and backdrop blurs were removed for the low-end graphics chips in Chromebooks.

## Grid rejected; sniper sky built (2026-10-22)
- The user tried the grid and said it "does not look good at all" and asked for something more exciting. Shown three directions (sniper sky, radar, orbit ring). The user noted the sniper sky is close to the earlier scope, and asked to try it, with one firm condition: peers said the old scope did not look easier to pick, and picking must be easier.
- Built: the whole sky fits one screen, with every station's name always showing, in random order. The scope snaps to the station nearest the pointer (magnetic aim) and shows "Strike Name" under the lens; one click anywhere strikes. Search and Struck me dim everyone else and snap to the first match. Arrow keys hop between stations and Enter strikes. A short "Locked on" moment follows, then the face-off; Back returns to the sky with the same player aimed. There's no dragging.
- Radar and orbit ring are kept as alternatives if the sniper sky still doesn't feel exciting enough.

## Font (2026-10-22)
- The user asked for Oxanium across the whole game. It replaces Rubik in the prototype, everywhere: questions, answers, cockpit, sky, face-off and captions.

## Name search removed; screens trimmed to the essentials (2026-10-22)
- The user asked to remove search by name and any unnecessary text. Struck me stays.
- Cuts:
  - The cockpit line is "Your turn".
  - The picker shows only the rebound note, without "Pick a target".
  - The "Hold Space" badge is gone.
  - The face-off shows only the strike's name, and the duplicate name tags under the stations are gone.
  - Results are one short line under the big word, e.g. "Lily −500" or "Lily's shield held".
  - Struck-while-answering captions are one line, e.g. "Strike blocked!" or "Absorbed! +500".
  - The shield-on toast is just the shield's name.
  - The act title banners are off until the story is decided; the weather still changes.
- The screen reader still announces the full sentences.

## Story and fun (2026-10-22)
- Premise: **Into the storm**. The class flies through a storm that builds with each question and clears at the end. It's visual and story only; no rule depends on it.
- Fun moments to prototype, all four:
  - a loot drop that reveals this turn's strike and shield;
  - Payback, when you strike someone who struck you;
  - shield reveals, with Saved! when your shield protects you mid-question;
  - a flight log at the end, built only from real events.
- Sketch the class sky on the teacher's projector in the prototype now. It's a concept for the teacher app; no real code yet.
- Off the table because they would change the game: levels, ranks while picking, revealing who's shielded, and naming Stealth strikers.

## Simplify like Blooket; Space Strike prototype (2026-10-23)
- The user wants proven, simple mechanics that are fun even without art, and referenced Blooket Gold Quest (surprises plus choosing who to act on), Match-3 and similar games. The story should be simple: everyone is a spaceship. No islands or crystals.
- The words stay **Strike** and **Shield**, because teachers already know them ("Zap" was rejected).
- The user asked for a separate prototype, so this is a new file on request: `prototypes/space-strike.html`. `sky-station.html` stays as the richer version.
  - Two taps per turn: two cards flip to show the offered Shield and Strike, then you tap a ship.
  - There's no cockpit, scope, face-off, hold or storm.
- Mapping to existing code: the server's per-turn `decisionOptions` (one strike type and one shield type) is the Blooket-style surprise, and picking the target is the Blooket-style choice. Swap, Precision, Absorb, Deflect and Rebound are already Blooket-like outcomes. The missing piece is a real steal.
- Comeback ideas are allowed as clearly marked proposals; the team will add whichever fits. The prototype has toggles for:
  - Steal: the striker keeps what they take.
  - Underdog luck: the bottom half gets Swap and Precision more often.
  - Show points when picking.
  - Leader handicap: the top 3 get only the basic Shield.

## Ships only in Sky Station; the two prototypes play the same (2026-10-23)
- The user said the green islands felt off once everyone is a spaceship. In `sky-station.html`, every station is now just the kid's Kenney ship in their colour, with no island, trees or waterfall. This applies in the sky, the question screen, the face-off and the projector.
- The user didn't feel a difference between Space Strike and Sky Station. That's correct: both follow the same live rules, and only the number of steps and the art differ. Presentation alone won't make it feel like a different game; that needs rule-level changes, which the user said the team can take as proposals.

## Charged strike (proposal) and the shield moment (2026-10-23)
- The user wants striking to be playful, with longer holds giving more power. Built in `sky-station.html` as a clearly labelled **proposal**, on by default, with a control to switch it off.
  - Hold to charge from 100 to 900 in about 1.5 s, with the number shown live on the button.
  - At full charge the button flashes gold ("MAX 900!") for about 0.35 s, then turns red ("Let go!").
  - Hold past that and the strike overheats: it fizzles, the turn is used, and you lose 100.
  - A tap under 0.18 s sends nothing.
  - Precision scales from 0 to 50% with the charge. Swap doesn't charge.
  - This needs the server to accept how charged the strike was; today every strike is a fixed 500.
- The user said the transition and story after choosing Shield felt off. It's now one continuous moment of about 1.6 s, which a click skips:
  - the cockpit falls away and your ship comes to the centre;
  - the shield builds in its own way: Standard closes the crystal dome, Absorb glows gold, Deflect sweeps a mirror shine, Stealth fades the ship to a ghost;
  - "{Shield} on" appears, then your shielded ship settles back beside the question.
  - The separate shield-on caption was dropped because the moment already says it.

## Controls fixed; zones on the ring; energy art pass (2026-10-23)
- **Prototype controls glitch:** the "Too many strikes on you" checkbox used the cockpit's class name (`ck`), so it was positioned over "End game". Renamed it. The outcome line now reads in plain words. The frame padding now collapses at exactly 1366×657, so the game no longer scrolls or clips at Chromebook size.
- **Charged strike:** the user didn't understand "hold to MAX" and asked for zones in the circle. The ring around the strike orb now shows three zones before you press:
  - blue (70% of the ring): builds from 100 to 700;
  - gold: MAX 900;
  - red: letting go overheats (−100, the strike fizzles).
  - A white knob sweeps the ring over about 2.2 s, and holding to the end also overheats.
  - The button reads "Hold, let go in the gold". It's still a proposal.
- **Art:** the user found the art kiddish and missing the original game's energy (battery style, the Strike & Shield logo). The energy pass keeps the ships and brings back the original language, using real assets from `cf.quizizz.com` that already exist in fe-join:
  - a red-versus-blue arena with light rays and a neon grid floor, replacing the flat navy and low-poly clouds;
  - the real logo in the header, and bolt pips that glow gold as the battery charges;
  - the real variant card art on the cockpit buttons, with card colours per variant;
  - the original gold bolt badge as the strike orb;
  - each shield type's real logo in the header badge and in the shield moment;
  - big words in bold italic with a gold bevel.

## Less text, fighting-game VS header; which variants are live (2026-10-23)
- Removed:
  - the "Your turn" banner, because the two cards make it obvious;
  - the always-on rebound note, which now shows only when you aim at someone you've struck twice: "Strike {name} again and it rebounds";
  - the strike-name line and the result line in the face-off.
- The face-off header is fighting-game style (like Tekken): both names, avatars, points and bars. A loss drains the bar with a red trail and the number counts down; a gain shows green. The big word on the ship says what happened. This matches the real result screen, which already shows the target's score after picking.
- The user didn't understand Swap and Stealth strikes and asked whether all the types were on in the live game. The evidence says probably not:
  - our live session only ever offered Classic Strike and Classic Shield;
  - `InGameApp.vue` marks the Swap, Precision and Stealth strikes and the Stealth shield as "0% probability from now on";
  - Absorption and Deflector have no such note.
  - Confirm with play-api.

## Classic by default (2026-10-23)
- The user agreed to default to Classic for now and to use the other types as edge cases from the prototype controls.
- Every turn now offers Classic strike and Classic shield ("Standard" was renamed "Classic", the live game's name). Classmates follow the same default.
- "Random (all types)" and each specific type stay available under "This turn offers".
- Evidence on which types are live:
  - the fe-join E2E suite forces types through a play-api test endpoint (`/play-api/testDuel`, action `updateDecisionOptions`);
  - the Swap, Precision and Stealth assertions are commented out, while the Absorption test is active;
  - the server can still produce every type, but which ones it offers normally, and how often, is decided in play-api.

## Night cloudscape background (2026-10-23)
- The user shared a daytime anime-style sky (puffy layered clouds, sun rays, wind streaks, lens flare) and asked for a night version as the background.
- Built as one SVG, `prototypes/assets/night-sky.svg`, generated by a small script:
  - a deep blue night with stars and a teal glow at the horizon;
  - a moon with soft rays and a lens flare;
  - puffy cumulus clouds lit on their crowns, in navy, lavender and violet;
  - wind streaks.
- It replaces the grid arena behind the game. A faint red left / blue right edge glow keeps the strike and shield colours.
- Rain and flashes from the storm acts still play over it.
- One static image is cheap for Chromebooks.

## Space background (2026-10-23)
- The user supplied a painted space image (a purple and blue nebula, planets, a ringed planet, stars and shooting stars) to use as the background. It is saved as `prototypes/assets/space-bg.webp` (1787×880, 39 KB) and replaces `night-sky.svg`, which is kept but unused. The faint red/blue edge glow stays.
- Replaced by the user's blue-teal version of the same scene; it is now `assets/space-bg.webp`. The purple version is kept as `assets/space-bg-purple.webp`.

## New spaceships from the art reference (2026-10-23)
- The user shared a painted spaceship sheet (white hull, blue or orange panels, glowing engines) and asked for ships like it in different colours.
- The big angled ship was cut out of the sheet, with its background removed, as `prototypes/assets/ship-base.png`.
- The page recolours it per kid: the blue panels and engine glow take the kid's colour; the white hull, dark parts and cockpit glass stay. Results are cached per colour.
- This replaces the Kenney 3D ships and the three.js renderer, which is no longer loaded.
- In the face-off, the target's ship is mirrored so the two ships face each other.
- 2026-10-23: re-cut from the user's clean sheet (images/6.webp, which already has a transparent background), so the edges and engine glow are clean. Ships now face different ways with a slight tilt each, in the sky and around the question; in the face-off they face each other. The user also sent a shield sheet (images/5.webp): a hex-bubble shield forming, full, cracking on a hit, and reforming. It is not used yet.

## Three-card draw on the windscreen (proposal, 2026-10-23)
- The user asked how players would choose between strike types: a hand of strike cards at strike time, or three random cards. The recommendation was three random cards (surprise plus one decision; no single best card; rare cards feel special). The user agreed and asked for the cards to look like a message appearing on the cockpit windscreen.
- Built in `sky-station.html` as a proposal, on by default, with a "Three-card draw" toggle in the prototype controls:
  - your turn projects three hologram cards onto the windscreen, under "Pick one";
  - they're cyan and coral glass with scanlines and a tilt, and flicker in one after another;
  - rare cards get a gold edge; the chosen card glows and the others fade;
  - keys 1–3 work, and Back from the picker returns to the same three cards.
- Draw rules: there's always at least one strike and one shield, with no duplicates. Classic cards are common (weight 6 for strikes, 5 for shields) and the others rare (weight 1.2 to 1.6).
- It needs the server to offer three options instead of one strike and one shield.

## New ship style shown as a mockup only (2026-10-23)
- The user sent a chunkier, toy-like ship sheet (cream hull, blue panels, orange accents, with red, yellow, purple and black colourways) and asked for a mockup before replacing anything. Its checkerboard background is painted into the image, so it was removed by colour.
- The mockup is `prototypes/mockup-new-ships.html`, a copy of sky-station.html that uses `assets/ship-base-v2.png`, recoloured per kid. `sky-station.html` is unchanged.
- The reference sheet is kept as `assets/ref-ship-sheet-v2.webp`.
- Approved: the user sent the same sheet with a real transparent background (images/8.webp) and asked to replace. `sky-station.html` now uses `assets/ship-base-v2.png`, re-cut from it with clean edges, recoloured per kid. The mockup file stays for reference.

## Space background and drifting assets (2026-10-23)
- The user supplied a plain starry nebula background (now `assets/space/bg.webp`) and an asset sheet of planets, moons, asteroids, nebulae and sparkles, and asked for moving assets that are not cluttered.
- Ten pieces were cut from the sheet into `assets/space/`. They sit at the edges, leaving the middle clear: a big planet top right, a ringed planet top left, moons, three asteroids, a faded blue nebula bottom left and two twinkling sparkles.
- They drift, rotate or twinkle slowly over 40 to 90 s, using transforms only. They stay still in reduced motion.
- The old storm weather (rain, clouds, swirl) is switched off, because it does not belong in space.

## Face-off layout and soft background (2026-10-23)
- Removed "Back to players" from the face-off (Escape still goes back) and the old thin horizon line.
- The ships now sit level on a middle band, facing each other. The strike orb and its zone ring sit centred above the hold button instead of overlapping the scores. The result word lands on the target ship, below the header.
- The background is a pre-blurred, lower-contrast, slightly darker copy (`assets/space/bg-soft.webp`) that drifts slowly over 80 s. The planets, moons, asteroids and nebula use softened copies (`*-soft.png`, blurred and desaturated, at 72% opacity), so the ships and UI stand out. Blur is baked into the images, not done live, to keep Chromebooks fast.

## Reusable animated shield effect (2026-10-23)
- The user supplied a shield reference (`assets/ref-shield-states.webp`) and a brief: a translucent cyan force field with a restrained hex pattern, crisp and not cluttered, wrapping and scaling with any ship, in four states, built with lightweight CSS/SVG, with reduced motion supported.
- Built in `sky-station.html` as one SVG layer (`.st-dome.fx-shield`) inside every ship, sized at 122% of the ship and centred on it. Its parts are a fill, a hex pattern masked to the edge, a rim, a highlight, an impact group clipped to the bubble, and 8 curved shards. The shared gradients, pattern, mask and clip live in one hidden SVG.
- The four states:
  - **Activate** (280 ms): a thin ring scales into the bubble, then the fill comes in.
  - **Idle**: a slow pulse, 2.6 s scale and rim opacity.
  - **Impact** (about 220 ms): a flash and ripple at the strike's angle, via `shieldImpact(stn, angle)`.
  - **Break** (about 420 ms): the bubble goes and the shards fly a short way, spin and fade. Gold shards for Absorb.
  - A shield that simply ends gets a quiet fade instead.
- `shieldBlockBreak(stn, angle, cls)` plays impact, then break. It runs whenever a strike hits a shield: on your ship while answering, in the face-off and on the projector. The shield-status update waits for it, so the bubble is not removed mid-effect.
- Old particle effects on shield hits (big ring, debris, lift puffs, extra sparks) were removed to keep it clean.
- Reduced motion turns every shield animation off: the shield simply appears and disappears.

## Cockpit questions (2026-10-23)
- The user wants questions to feel part of the game, as in Code Busters (the hacking device shows the question) and a game where a character's arrival means a question is coming. The agreed frame: the cockpit is the quiz. The plain version was built first, without a co-pilot character.
- Built in `sky-station.html`, on by default, with a "Cockpit questions" toggle in the prototype controls:
  - a thin canopy frame with a glass glare around the question screen;
  - the question card becomes a windscreen display (cyan glass, scanlines, corner brackets, an "Incoming" label with a blinking light);
  - each question arrives as a transmission (the panel opens from a line, and the answer buttons rise in one after another);
  - the answers sit in a metal dashboard console and press down like real buttons, each with a status light (green right, red wrong);
  - a wrong answer gives a short static flicker on the glass, with no other penalty animation;
  - fill-in-the-blank uses the same console.
- The question types, submit flow and keys 1–4 are unchanged. Reduced motion turns off the blink and static.
- Not done yet: the co-pilot character, and the battery charging from the button, which already happens via the existing bolt that flies to the header.

## Full playthrough and hit reaction (2026-10-23)
- A scripted full game (10 questions, a strike, a shield, a Precision strike, being struck, the end screen) showed no page errors, failed requests or console warnings, and correct score changes.
- The user said a struck spaceship shows no effect, and the run confirmed it: the old jolt moved the ship 6 px. First principles of a hit: contact (white flash on the ship), reaction (knockback away from the bolt, scaled by how hard the strike was), consequence that stays (damage).
- `shipHit(stn, dir, power)` is reusable on any ship:
  - a white flash, then knockback of 14 to 48 px with a tilt, wobbling back over 0.6 s;
  - for about 3 s afterwards the ship is damaged: a darker hull, a limping wobble, smoke puffs and electric sparks.
  - It's used for your strikes in the face-off (scaled by the charge, bigger for Payback), for strikes on you while answering, and for rebounds onto your ship.
- Removed leftover clutter: the big grey rings on hits, while struck and in the shield moment, so the new shield bubble reads clearly.
- The leftover storm words became space ones: "Mission complete", the act titles "Takeoff", "Deep space" and "Final stretch", and the end titles "Ace Striker" and "Space Pilot".

## Flight prototype (2026-10-23), separate file
- The user felt the cockpit-question connection still didn't land: the cockpit wasn't clear, and seeing your own ship from outside contradicted being in the cockpit. They asked for an always-moving ship you steer to choose, with no dependence on skill. This was built as a separate prototype, `prototypes/flight.html`.
- One camera, always following your ship from behind, which never stops flying (scrolling stars, speed streaks, drifting planets). It uses a rear-view ship cut from the user's sheet (`assets/ship-rear.png`), recoloured per kid.
- The question is a steady "Mission" panel at the top. The four answers are gates ahead: pick one (tap or 1–4) and the ship flies itself through it. A right gate glows green, +600 shows, and an energy cell flies into the battery. A wrong gate fizzes and the right one lights.
- Your turn: three card gates (Strike, Shield, Classic) arrive the same way.
- Strike: classmates fly in formation ahead. Tap one, or steer with ←/→ (your ship slides to line up behind them), then Strike. Hits show a laser, knockback and damage; shields show the hex bubble blocking and breaking.
- Being struck: a bolt comes in from the side and hits your ship or shield, with a one-line message under the mission panel.
- The rules are the live game's. A full scripted playthrough had no errors.
- The user did not like the flight prototype (2026-10-23). `flight.html` stays in the folder for reference only; `sky-station.html` is still the main prototype.

## Splat prototype (2026-10-23), copy of sky-station
- The user found the flight gates gimmicky and slow, and picking a target there felt off. They asked to bring in Splatoon.
- `prototypes/splat.html` is a copy of `sky-station.html`; the original is untouched. Only the strike screen changed:
  - your turn shows the class as a map of equal hex patches in random order, each in its kid's colour with avatar and name; your own patch is outlined;
  - one tap on a patch sends a paint bomb arcing from your patch, which splats your colour onto theirs (−500), and the splats stay on the map;
  - a shield shows a glossy coat that blocks and cracks (gold for Absorb); Deflect bounces the bomb to another patch; Rebound sends it back to yours.
  - Answering, cards, shields and the rest are unchanged.
- Open: splats in the striker's colour read like Splatoon ink but do not take ground (the live rule only removes 500). Patches are equal size, so they do not reveal who is leading.

## Two teams in the splat copy (2026-10-23)
- The user said individual colours were too many and asked for two random teams that both paint, built on `splat.html`.
- The class is split at random, half and half, into Team Cyan and Team Coral at the start of each game ("You're on Team Cyan!"). Every ship and patch uses its team colour, a slightly different shade per kid.
- Your turn shows a map: your team on the left (not strikable), the other team on the right, VS in the middle. You can strike only the other team; your splat is in your team colour. Simulated classmates also strike only the other team.
- A header bar shows each team's share of the paint (total power, floored at zero). The end screen leads with "Team Coral wins · 54%".
- This is a rule change for the backend and teacher app (teams, team totals, striking only opponents). Assigning teams from the player ID could keep it mostly client-side.

## Two planets map (2026-10-23)
- The user found the hexagons off. The team map is now two planets in `splat.html`: your team's planet curves in from the left and theirs from the right, with a gap of space between. Each kid is a round landing pad on their planet, nearest the gap first; yours is outlined.
- Bombs arc across the gap and splats stay on the pads. Team labels sit above each planet; Back and Struck me stay on top.

## Paint theme for splat.html (2026-10-23)
- The user asked to change the whole theme of the splat copy to match splatting. The space look was replaced with a turf war in ink:
  - a dark ink background with big team-colour splats (`assets/splat/bg.svg`);
  - chunky sticker lettering (Lilita One) with thick ink outlines;
  - each kid is a glossy ink-blob character with eyes and drips in their team colour, drawn in the page and replacing the spaceship;
  - the question is a white tilted sticker on a team-colour splat, and the answers are wobbly paint tiles with ink outlines;
  - the battery is ink drops in your team colour, and the score is labelled "Ink";
  - your-turn cards are tilted stickers, and the map planets are glossy ink pools with paint droplets;
  - the end screen says "Turf war over!", with titles Ink Rookie, Splat Master and Payback Painter.
- `sky-station.html` keeps the space theme.

## Three face-down cards with a dud (proposal, 2026-10-23)
- The user asked for the three cards to be Classic strike, Classic shield and "Better luck next time" in `sky-station.html`.
- They are dealt face down in a random order, with identical "?" backs. You pick one (tap or 1–3); it flips, then the other two flip so you see what you missed.
- Strike goes to the target sky. Shield goes to the shield moment. The dud ("Better luck next time · No strike or shield this turn") uses up the turn and returns to the questions.
- The pick is final: there is no Back to the cards after picking Strike.
- This is a rule change: today the server always offers both a strike and a shield, and there is no dud.

## List + zoom picker (2026-10-23)
- The user found aiming across 20–30 ships hard and suggested a list where clicking a name zooms that ship. Built in `sky-station.html`, on by default, with a toggle "Picker: list + zoom / sniper sky" in the prototype controls.
- A "Pick someone" list on the left shows avatar and name in random order, with Struck you and Game over tags; it scrolls for big classes. The sky with all ships is on the right.
- Clicking a name (or a ship) makes that ship fly to the centre and grow, inside a slowly turning coral target ring, with its name and a big "Strike {name}" button. The rest of the sky fades back. Clicking another name, or pressing ↑/↓, swaps the zoom.
- Strike or Enter locks on and goes to the face-off.

## Splat prototype dropped (2026-10-23)
- The user asked to chuck the splat prototype. `splat.html` was moved to `prototypes/_scrap/` (its teams, two planets and paint theme are not carried forward). `sky-station.html` is the main prototype.

## Race prototype (2026-10-23), separate file
- The user felt every screen felt different (Q&A, choosing, selecting) and asked to try a race mechanic: everyone on a racetrack that is also the leaderboard, with strike and shield to get ahead, nitro boosts, and Q&A as the checkpoints in between.
- Built as `prototypes/race.html`; `sky-station.html` is untouched. It is one continuous screen:
  - the top is the space racetrack from start to finish, with every racer's ship; your position is your score;
  - the bottom is the checkpoint zone, where each question is a checkpoint; a right answer boosts you forward (+600);
  - orange nitro checkpoints (3, 6 and 9) give +300 extra, a proposal;
  - when the boost meter fills (2, then 3), the checkpoint offers Strike or Shield;
  - you strike by tapping a rival on the track (or ←/→ and Enter); a missile arcs over, and they spin and drop back 500;
  - rivals' shields stay hidden until hit;
  - classmates race and strike each other;
  - the header shows your place (e.g. 3rd of 20), the boost meter and points;
  - the finish is a podium.
- Rules otherwise follow the live game. A full scripted playthrough had no errors.

## Race v2: Mario Kart feel, full-size questions (2026-10-23)
- The user said questions must stay a big container because most have images, and wanted the race to feel continuous like Mario Kart (as a mechanic, not a look).
- `race.html` was reworked in place (v1 backed up in the scratchpad):
  - the camera follows your ship on a scrolling space road that never stops; a minimap strip under the header shows the whole field;
  - only the 8 rivals nearest you are on the track, spread across lanes;
  - a checkpoint gate rolls in and the question opens as a full-size card (image on the left, 2×2 answers; 4 across with no image); the race slows behind it;
  - a right answer puts a boost pad in your lane, and you surge forward, showing "Boost!", +600 and "+2 places";
  - a full boost meter puts an item box on the track; driving through it spins a roulette that lands on Strike or Shield (a proposal; the live game lets you choose);
  - Strike slows the race and puts target rings on nearby rivals; tap one or use "Anyone…" for the full list, then fire a homing shot that makes them spin out and drop back;
  - rivals fire at each other and occasionally at you, from behind;
  - finish line, then podium.
- Sample questions include image questions (ringed planet, fraction pie, bar chart, moon).

## Race: UX check and a student version (2026-10-23)
- The user found race v2 confusing (when did strike and shield come?) and asked for a UX check and reasoning before any change.
- Findings: no goal explained; a meter that did not say what it was for; two meanings of "boost"; the roulette took away the choice; strike mode changed with little signal; position shown three ways; too many events not about you; the question card hid the race.
- Agreed direction: the horizontal view suits the teacher or projector. Students get a vertical, one-direction lane.
- Built `prototypes/race-student.html` (`race.html` is kept as the teacher concept):
  - a 3-step intro ("Race to the finish!");
  - left: your lane flowing toward you, your ship fixed at the bottom, the 2 racers just ahead and 1 just behind, each with place and name; one place badge and one progress bar to the finish;
  - right: the meter in words ("2 more right answers to Strike or Shield") and the big question card with images;
  - when the meter is full, the same card offers the live game's choice, Strike or Shield, with no roulette;
  - Strike lists "Just ahead of you", "Further ahead" and "Right behind you", plus a "Someone else" row of everyone else;
  - only events about you are shown; places are unique, with ties broken by a fixed starting grid.
- Rules are the live game's. A full scripted run had no errors.

## Questions and the race separated (2026-10-23)
- The user said answering while the race moved made it hard to focus, that "Who do you strike?" as a list of names looked bad, and that answers should only fill the meter, as in the live game. Questions and strike/shield must be separate, and the strike choice should be visual.
- `race-student.html` was rebuilt:
  - question mode is full screen, and answers only charge the meter;
  - a "Race time!" wipe leads into race mode;
  - the whole class sits on one track by points, with the top 3 marked; ships slide from their last-turn position to now, with "▲ N since your last turn" and any hits listed;
  - Strike or Shield buttons follow; Strike means tap any ship on the track;
  - then back to the questions.
- HANDOFF.md now opens with the latest state, in case the context is compacted.

## Race mode: fly straight, steer left and right (2026-10-23)
- The user said the question container should stay as it is, that nobody moved in the race, and that they pictured flying straight on continuously while choosing left or right.
- In `race-student.html`, race mode is now:
  - a forward road that scrolls toward you forever, with five lanes; your ship stays at the bottom and steers between lanes (← → or on-screen buttons) and leans as it moves;
  - the 5 racers just ahead fly in the lanes in front, and the 2 just behind fly below you; everyone drifts gently;
  - the racer in your lane is locked as the target (coral ring, aim line, and the button becomes "Strike {name}"); Space fires, and they spin and drop back past you; S shields;
  - the left panel shows your place, the change since your last turn and hits taken; the right panel is a Standings list (top 3, then you and your neighbours) with the target highlighted.
- Question mode is unchanged.
- 2026-10-24: the user asked to keep the original question container layout. `race-student.html` question mode now matches the live game and Sky Station: a question card on top (image inside, above the text, with an n/10 pill) and the 4 answer tiles in one row below. Do not change this layout again.

## Boost lap (proposal, 2026-10-24)
- After the critique ("the race is a picture of the score"), the user asked whether the race could feel like a real race with boost. `race-student.html` now has a boost lap, on by default, with a "Boost lap" toggle in the prototype controls:
  - when the meter fills, you drive for 7 s; boost rings come down the lanes, each within one lane of the last;
  - you steer ← → through them, and a ring one lane away slides into your lane when it is close;
  - each ring is +50, capped at +300 (half a right answer); your place updates live with "Passed!";
  - nothing can be lost, and there are no reflex tests;
  - then "Lap done · +N", then the usual Strike or Shield.
- In 1st place, the racers just behind become the targets.
- Open: in testing, even lazy steering reached the +300 cap, so the lap may be too easy to mean anything. Tune ring spacing, the cap and the magnet with kids.
- This is a rule change: driving adds points beyond right answers.

## 2026-10-24: race-student, Q&A zone and playthrough fixes
- User: "Qna can come as a QnA zone and then when your spaceships flies through it you answer." Built: between questions you cruise; a "Q&A ZONE · n" band comes down the road; flying into it opens the question in the original layout (card on top, 4 answers in a row). You can steer while cruising.
- A scripted 10-question playthrough found these problems, now fixed:
  - With nobody scored, you showed as 15th of 20. Ties now share a place, and before anyone scores the badge says "Ready".
  - The header said "Your turn!" on the last question, but there's no turn after the last question (M1). It now says "Last question".
  - The class sim hit you about 5× more often than anyone else, so 8 of 10 right could finish 19th. Class strikes now land on anyone at a realistic rate.
  - In the lead, the 2 chasers sat in the far edge lanes and were hard to line up with. Now 3 chasers show right behind you, and the label says "Line up with a racer".
  - The boost lap was too easy. Rings can now jump 2 lanes, and the magnet only catches near misses.
- Backup before these changes: scratchpad race-student.v5.html (v4 = before the Q&A zone).

## 2026-10-24: race-chase.html, the race worked out properly (new prototype)
- User pushed back: the race felt half done. Why only the racers in front? Why does the boost give points? Why a top view, not a big screen where everyone flies through something?
- User chose: chase cam (camera behind your ship), and "pick, then the camera flies" for striking.
- The mechanic:
  - How far down the track you are = your score. The whole class is in the race, and nothing is invented.
  - A right answer is the boost: your ship surges 600 forward.
  - Classmates answer at their own pace, so ships pass you, or drop back, live.
  - Every strike outcome happens on the track:
    - hit: the target spins and drops back;
    - blocked: the shield shatters;
    - absorbed: the target glows and surges +500;
    - deflected: the bolt goes on to another ship;
    - rebounded: it comes back and hits you;
    - Swap and Precision are there too.
  - Strike anyone: the picker shows everyone in random order with avatar and name (M9), plus the "hit you" mark and the penalty note (M10), Back (M8) and Skip (M11). Picking someone swoops the camera to them, then you strike.
  - Q&A zones are gates on the track. Fly through one and the question opens in the original layout.
  - The boost lap is a proposal: up to +100, speed only, or off.
- The one real design change: the race shows rank all the time, while the live picker hides it. Confirm with the team.

## 2026-10-24: the chase race becomes race-student.html
- User: "I like the racetrack from the chase. u can build it on race student. However one major issue is … it is difficult to identify mine."
- race-student.html is now the chase-cam race. The top-view version is backed up in the scratchpad as race-student.v6-topview.html, and race-chase.html was folded in (backup race-chase.v1.html).
- Your ship is now always findable:
  - Full colour with a white edge and a teal glow; classmates are slightly dimmed.
  - A bouncing teal marker above it and a "You" tag below it.
  - A halo on the floor under it, and a teal lane strip from the bottom of the screen to it (the strip hides while the camera is swooped to a target).
  - It's always drawn on top. A classmate covering it fades to 30%, and classmates' name tags never sit on it.
  - When the camera swoops away, your ship keeps a readable minimum size.

## 2026-10-24: race payoff pass, then a race strip in Sky Station
- User asked: "questions usually appear 3. u have just put one. also why should i move left and right? … when m striking someone it doesnt feel great. what is the payoff in this game?"
- In race-student.html (backup before this: scratchpad race-student.v7-chase.html):
  - **Question sets:** a Q&A zone now holds up to 3 questions, or until your meter fills; then you're back in the race with one "+1,200" surge.
  - **The strike:** your ship charges at its nose, fires, and the camera rides the bolt down the track. The hit gets a hit-stop, a flash and a shake, then the camera returns to you so the target tumbles back past you.
  - **Near rival:** "Catch Ana · 500 ahead" (or "You lead by …"), with the rival's tag outlined in gold.
  - **Passes:** every pass pops "Passed Ana!" (or "Passed 3!") and is counted.
  - **Photo finish:** after the last question, everyone crosses the line in order of score, you see yourself cross, with confetti. The end screen adds your stats: racers passed, strikes landed, shield saves.
  - Steering was left as it is; the user didn't pick "remove steering".
- Then the user, mid-build: "we can do a small strip like with Q bit face in sky station which continous throughtout the game … at least you can see in the strip that the motive is to finish ahead."
  - Read as Qbit faces. Added to sky-station.html as a proposal, presentation only, toggled with "Race strip" in prototype controls. Backup: scratchpad sky-station.pre-strip.html.
  - A slim strip in the cockpit glass under the top bar, on screen all game.
  - Every racer is their Qbit face, placed by power between start (0, or the lowest negative) and a checkered flag at the top possible score. Yours is bigger, white-ringed and glowing, with "You".
  - Your place sits on the left; the near rival ("Catch Ana 500", gold ring on their face) sits on the right. Passes pop "Passed Ana!".
  - The strip hides while the face-off title or the arena line is showing, since they use the same spot.

## 2026-10-24: Sky Station, the three mystery cards removed
- User: "in sky station remove the three mystery cards. Let me choose between strike and shield because it feels sad if i answer all 3 questions correctly but dont get to strike."
- Removed the three-card draw completely: the face-down cards, "Better luck next time", their styles and markup, the keyboard handling, and the prototype control. Backup: scratchpad sky-station.pre-nodraw.html.
- Every turn now offers the two cards, as in the live game (M4): Classic shield (S) and Classic strike (L). Back from the picker returns to the choice (M8).
- Rule for future proposals: a full meter must always give you a real choice. Never take the turn away by chance.

## 2026-10-25: Sky Station, story and one place
- A senior's critique: they can't tell the story: what the objective is, who they are, what the storytelling is. The flow feels abrupt.
- The user, after a cold playthrough: "The flow feels disjointed with each screen feeling like a new place making you feel abrupt." The user also shared a cockpit reference image (thick struts leaning into a dashboard, amber lights, a reticle in the middle, the charge meter and the Shield and Strike controls on the dashboard).
- What the cold playthrough found:
  - Nothing ever states the premise.
  - An unexplained second ship ("Ana") sits beside every question.
  - The turn arrives with no cause.
  - The goal changes from screen to screen: a race, then a mission, then a power score.
  - The strip covered the end title.
  - Each phase looked like a different place, and the questions and the turn even had different cockpit frames.
- Built (backup: scratchpad sky-station.pre-oneplace.html):
  1. **One place.** A single cockpit frame for the whole game, from questions through your turn, the picker, the face-off and the finish, restyled after the reference with thick struts, amber lamps and a dashboard lip. The turn's own heavier frame is gone. The copy says "ship", not "station", and "Your station: intact" is removed.
  2. **The premise, said once.** After the page loads: "Finish ahead of your class", the strip's light sweeps to the flag, then 3, 2, 1, and the first transmission arrives. Answers are locked until it ends.
  3. **The rival beside you.** The ship next to you while you answer is now the classmate just ahead of you ("Catch Ana"), or the one closest behind if you lead ("Behind you · Ana"). When you pass them, the next one flies in.
  4. **The turn has a cause.** When the meter fills, a charge cell (the meter's battery, in gold with a bolt) flies from the meter in the top bar into the reticle and cracks open into Shield and Strike.
  5. **One goal to the end.** The finish says "You finished 1st of 21", with your power and title underneath. "Mission complete" is gone, and the strip lines everyone up behind the flag in finishing order.
- Not done yet: moving the charge meter and the Shield/Strike controls onto the dashboard, as in the reference.

## 2026-10-26: Sky Station, strip faces and a picker that doesn't scroll
- User: "the Qbits in race look a bit weird though why?" The strip squeezed full-body Qbits into 24px circles, so they read as tiny figures, and tied classmates stacked into vertical totems.
  - Fixed: strip faces are cropped to the head, as in the picker. Tied classmates fan out sideways, at most 3 faces, with a gold "+n" corner badge for the rest. Your face always shows.
- User: "the choosing screen is it easier if kids dont scroll. I like how when i click or hover on a name their spaceship comes."
  - Fixed: the picker's name list is a grid that always fits: 1 column up to 12 names, 2 up to 26, 3 above that, with rows shrinking to fit. Checked at 20 and 40 players, with no scroll.
  - Hovering a name now brings up that ship (after a 140 ms beat, so sweeping the mouse doesn't flicker), as clicking does. Arrow keys move around the grid, and touch still uses taps.
- Backup: scratchpad sky-station.pre-picker-grid.html.

## 2026-10-26: header, no box inside a box
- User: "dont keep the strike and shield inside a circular box. It feels like a box within a box."
- Removed the rounded pill around the Strike & Shield logo, the meter bolts and the power number: they now sit straight on the top bar.

## 2026-10-26: answers match the cockpit theme
- User: "QnA container colours dont match the theme. Make it cohesive to the theme."
- Answers were flat, saturated tiles (red, orange, teal, blue) under a dark cockpit. Each is now a cockpit screen: the same dark glass, scanlines and glow as the question card. Each keeps its own colour (as live) as the rim, a top glow, the key badge and the status light. Hover lights the screen up.
- Right answer: a green glowing screen. Wrong: red. The others dim.
- Backup: scratchpad sky-station.pre-answer-theme.html.

## 2026-10-26: the race strip moves into the top bar
- User: "why dont you move the race track to the top inside the header. The placement feels off."
- The top bar now reads: Wayground and Bonus | Strike & Shield logo, meter and power | your place, the race track and the near rival | game code and menu. The strip has no panel of its own (no box on the windscreen), and the "Passed Ana!" pop drops just below the bar.
- With the windscreen clear, the strip no longer hides during the face-off; the VS header and the arena line sit under it.
- Backup: scratchpad sky-station.pre-strip-header.html.

## 2026-10-26: decluttered after a UI review
- User asked for a clutter review, then "yes" to applying it.
- The struts are now slim and at the edges with one lamp each. Ships beside the question are kept clear of the struts and the screen edge, so names are never cut off.
- The picker shows the list plus one big ship: the sky full of every ship and the "Pick a name, or tap a ship" hint are gone, and the first name is shown on open.
- Removed:
  - "INCOMING" on the question card;
  - the answer status dots, until you answer;
  - the empty reticle and the three lamps on your turn (the charge cell now lands mid-windscreen);
  - "MAX" on the strike ring;
  - a negative "Biggest swing" tile on the end screen.
- The strip shows only you until someone scores. The power float (+600 / −500) plays over the power number, not on the race.
- Left for the team: the live footer Submit is bright on multiple-choice questions even though tapping an answer submits it.
- Backup: scratchpad sky-station.pre-declutter.html.

## 2026-10-26: one line under the top bar
- User asked what the double line in the header was: the top bar's bottom border, plus the cockpit frame's curved canopy rim drawn just below it. Removed the canopy rim; the top bar is now the top of the cockpit.

## 2026-10-26: soft focus falloff
- User: "I still feel the bottom feels cluttered. Try adding soft gradient of black where the focus is not required."
- Added a soft dark falloff over the sky: it darkens toward the bottom (under the answers and the dashboard) and slightly at the far edges, leaving the middle of the windscreen clear. The orange dashboard line is now faint.

## 2026-10-26: new ship art, asteroids beside the question
- User sent a new ship sheet (blue, white and orange, with colour variants) and said: "remove the two ships instead add astroids there which i sent to you and make it floating. Also replace the spaceships."
- Cut the hero three-quarter view from the sheet (it already had transparency) as assets/ship-base-v3.png. Every ship in Sky Station is now this ship, recoloured per kid as before: the blue panels and engine glow take the kid's colour; white, dark parts and orange stay.
- While you answer, the two ships beside the question (yours and the rival) are hidden. Two asteroids from the space assets (rock-1, rock-4) float there instead, drifting and turning slowly (still in reduced motion). The rival still shows on the strip.
- Backup: scratchpad sky-station.pre-ship-v3.html.

## 2026-10-26: picker in the game's style, fly-in, sound, first-person strike
- User:
  - "The UI of selecting opponent does not feel part of the game. Make it feel cohesive to game's UI."
  - "the animation of spaceship's flying in is not working. try something else which is not jarring. Probably flying in from the panel or zooming in."
  - "Add sounds in the game. Do not add generic sounds. Search the web for free copyright music and based on that add sounds."
  - "When I am striking someone else why am I seeing my place from my cockpit?" Read as "plane": you sat in the cockpit and also saw your own ship.
- **Picker:** the list is now a cockpit screen. It uses the question card's glass, scanlines, cyan edge and corner marks, a red-dot "Pick someone" label, Qbits ringed in each kid's colour, and a coral glass row (with a red dot) for the one you're on. The Strike button matches the turn's Strike card. Back and Struck me are glass buttons.
- **Fly-in:** it used to fly from the ship's (now hidden) spot in the sky, which started at the screen corner and jumped. Now the ship grows out of the name you picked in the panel, and the targeting ring settles round it (360 ms).
- **First person:** your ship no longer shows in the face-off. Their ship comes toward you out of the distance, centred and bigger, and your bolt fires from the dashboard. Rebounds and overheats land at the bottom of your windscreen.
- **Sound:** WebSearch and WebFetch were down, so I got Kenney's CC0 packs straight from kenney.nl: Sci-Fi Sounds, Interface Sounds and Music Jingles. 21 sounds (964 KB) are in assets/sfx, with the licences.
  - Answering: right, wrong.
  - Your turn: the charge cell, the cards' jingle.
  - Picking: hover, select, back.
  - The face-off: the face-off whoosh; the charge hum, which rises in pitch while you hold; fire.
  - Outcomes: hit, blocked, absorbed.
  - Shield: shield up.
  - Being struck: incoming, struck.
  - Other: overheat, the 3-2-1 countdown and go, passed someone, the finish jingle.
  - "Sound" in prototype controls mutes it all.
- Backups: scratchpad sky-station.pre-firstperson.html, sky-station.pre-sound.html.

## 2026-10-26: softer bars, centred one-click picker, points
- User list: remove "You lead by 600"; the top and bottom bars feel jarring and boxy, so remove the strokes and soften them; remove the Back button; the names on the left feel off, so centre the list; remove 1–4 from the answers; "what is 3000 power?"; "what is +3 and +4?"; "when do I see my opponent's score after I've picked them?"; "don't make me click twice after selecting my opponent."
- Built (backup: scratchpad sky-station.pre-soft.html):
  - The strip's right side shows only "Catch Ana 500". Nothing shows when you lead or are tied.
  - Tied clusters show up to 3 faces with no "+n" badge.
  - "Power" is now "Points" in the header, on the end screen and in the copy. Kids read it as their score, which is what it is.
  - The top and bottom bars have no border strokes and fade into the scene. Header and footer buttons are soft fills with no outline.
  - The answers have no 1–4 badges; keys 1–4 still work.
  - The picker's Back button is removed (Escape still goes back). **Proposal:** the live game has Back (M8) so a student can still choose Shield. Confirm with the team.
  - The picker is now a centred grid (3–5 columns, never scrolls) under the ship you're looking at. Hovering or arrow keys bring up the ship, with the name above it. One click or tap on a name goes straight to the face-off; the "Strike Ben" button step is gone.
- The opponent's score: the picker hides scores on purpose (live rule M9), so you first see their points in the face-off's VS bars, then watch them drop when the strike lands.

## 2026-10-26: picker, names on top
- User: "Spacing feels off. Why is the airplane so cluttered to the modal. Try putting the names on top and show aircraft below."
- The name grid now sits at the top of the windscreen, and the ship you're on (name above it) sits below with clear space between them.

## 2026-10-26: being struck, sound and feel; the picker back to ship above
- User: the sound when someone strikes them is awful; make the screen shake or glow when hit; what happens with a shield; "names below and spaceship above was better".
- The struck sounds are now Kenney Sci-Fi laserSmall_001 (incoming, quieter) and impactMetal_000 (the hit, a metal clank, quieter) in place of a retro laser and a low boom.
- A hit now shakes the cockpit for about 0.4 s and flashes a red glow at the screen edges. A shield save flashes a blue glow with no shake. Reduced motion keeps the glow and drops the shake.
- The picker is back to the ship above and the names below, with a smaller ship and ring and clear space between them.
- Backup: scratchpad sky-station.pre-ouch.html.

## 2026-10-26: VS header in the cockpit style; space keeps moving
- User: the Qbits in the VS header look very bad, make it cohesive; what happens if I strike someone with a shield; keep the asteroids, stars and planets moving, the game feels static.
- VS header: the Qbits are cropped to the face in a glass ring of their colour (you in teal). The bars are slim glass with a cyan rim, teal for you and coral for them; points are labelled "pts"; VS is a cyan glow instead of the gold slab.
- Motion: the background and planets drift about 3× faster with a larger range. A new layer streams star dust and an asteroid every ~3 s out from the middle of the view, growing as you pass them, as if flying forward. All of it is behind the question and stops with reduced motion.
- Backup: scratchpad sky-station.pre-motion.html.

## 2026-10-26: picker spacing
- User: "The spaceship looks like it is on top of the modal. Clean it up and make sure the spacing is decent."
- Cause: the ship was positioned inside the picker's field, which starts lower than the top bar, and an older fixed-size rule still applied, so it slid down into the list on shorter windows.
- Now the ship and its ring size themselves to the space between the top bar and the list, and are centred in it, with at least 18 px clear above the list.

## 2026-10-26: scattered ships and a targeting scope
- User: put 1/10 at the top centre of the question card; change "Pick someone" to "Tap a name to strike"; imagine the classmates scattered in space, and when you click a name your target detects their ship.
- The question number now sits at the top centre inside the card.
- The list heading reads "Tap a name to strike".
- The picker now scatters every classmate's ship over the space above the list, small, dim and gently bobbing, in random order (no rank, live rule M9). Hovering or arrowing to a name slides four coral scope corners onto that ship, which lights up and grows with the name under it; the rest dim. Clicking locks the scope ("Locked · Fatima") and goes to the face-off, in one click. The centred big-ship preview and the old "Locked on" stamp are gone.
- Backup: scratchpad sky-station.pre-scatter.html.

## 2026-10-26: the scope finds hidden ships; everything flies past
- User: the scattered ships should be unseen until you hover a name, then your target finds them in space; clicking zooms in and says "Target set". The scatter in a pattern looked unnatural. Also: why do some asteroids move and some not; it should feel like flying, with everything passing by.
- Picker: the ships are hidden and placed at random (spread out, new each turn, no rank). Hovering or arrowing to a name sends the scope sweeping (corners blinking) to that spot, where the ship fades in and grows. Clicking zooms the ship and the scope into the middle, the scope turns gold, "Target set · Aiden" holds for about a second, then the face-off.
- Motion: removed every fixed or in-place-drifting planet, moon and asteroid (the old scenery and the two asteroids beside the question). Now everything comes out of the distance at the middle of the view, grows and slides past the edges: planets and moons slowly and wide, asteroids every ~2 s, star dust constantly. The scene starts mid-flight. Off in reduced motion.
- Backup: scratchpad sky-station.pre-flyby.html.

## 2026-10-26: Chromebook performance, smooth flow, less clutter
- User asked to adapt animations for laggy Chromebooks, make every transition flow smoothly, and cut unnecessary clutter.
- Measured with headless Chrome at a 4× slowed CPU. A software GPU exaggerated everything, so the final numbers use the real GPU. After the fixes, every step of the flow (question, answer, turn, picker, scope, target set, charge, strike, back to question) holds 59–61 fps. The one remaining blip is the picker build (~150 ms).
- Fixes:
  - Ship colours are prepared in a background worker (recolour plus PNG encode), with the base scanned once, while the first questions are on screen. They had been ~1.1 s of main-thread work when the turn and picker opened.
  - Sounds decode one at a time when idle, not all on the first click.
  - Hidden things cost nothing: classmates' sky ships and old asteroids are off the page, the hidden scattered ships don't animate or filter, and the old picker spots aren't drawn.
  - No backdrop blur anywhere, no filters on moving fly-by items, the full-screen vignette is gone, and the question screen is a GPU layer only while it moves.
  - The fly-by spawns fewer items.
  - A lite mode turns on by itself (≤4 cores, ≤4 GB memory, or under 45 fps in the first seconds). It thins the fly-by and stops decorative animations, but keeps the motion that tells the story.
- Smoothness (from frame-by-frame film of every transition):
  - Your own ship no longer flashes into the windscreen as the turn opens.
  - The scope appears on the first ship instead of flying in from the corner.
  - The target zoom ends where the face-off ship appears, so the hand-off has no jump; "Target set" sits clear of the list.
- Clutter: removed the "Struck me" filter button (names already carry a bolt mark for who struck you).
- Backup: scratchpad sky-station.pre-perf.html.

## 2026-10-26: the numbers, overheat, and every strike and shield flow
- User: "−200 POINTS 19th of 21" is confusing; overheat shouldn't give negative marking but should teach; struck-with-shield looks abrupt and messy; what happens striking a shielded player; what happens choosing shield; "the flow when someone strikes me is not well done at all."
- Numbers: Points and Place are two labelled things. Place sits after a divider in white with a "PLACE" label ("19th / 21"), and no longer flashes big and green. The race strip starts after the Points group, so the shield badge never covers it. Negative points stay possible (live rule M15).
- Overheat (the charged strike is a proposal): no points lost, and the turn isn't used. "Too hot!" shows beside the dial, the dial's gold zone pulses, and you hold again. It was −100 plus a lost turn.
- Struck while answering, first person: the attacker's face on the race strip lights red and the bolt leaves it, down onto your windscreen (above the question).
  - Hit: the glass cracks, the cockpit shakes, the edges glow red, and Points counts down. A card under the top bar shows their Qbit, "Chloe struck you" and "−500 points".
  - Shielded: a hex shield lights across the windscreen as the bolt lands and fades. A blue card says "Your shield blocked Jonah" and "No points lost · your shield is used up". Absorb shows a gold card (+500); deflect and rebound have their own lines; Stealth says "Someone".
  - The card closes itself after 5 s or with ×. The question never pauses.
- Your strike on a shielded player: as before, plus one line under their ship: "Zoe's shield blocked it · No points lost. Their shield is gone, so your next strike on Zoe will land." (Absorb and rebound have their own lines.)
- Choosing Shield: a hex shield closes across the windscreen with "Classic shield on · It blocks one strike", the shield badge flies up beside Points, and the question rises at once. The big dome over the cards and the empty cockpit gap are gone.
- Backup: scratchpad sky-station.pre-flows.html.

## 2026-10-26: NEW prototype, mapbattle.html (cloned from sky-station.html)
- User: "clone this prototype and build a new version … mapbattle. This has a base like a map. Each player has a circular base. The more points you have the bigger your base. All the players are arranged on the map like a grid, but scattered. When you choose to strike you place an element like a bomb in the adjoining grid where it can affect multiple people."
- Built: questions, header, race strip, sound and all shield flows are unchanged from Sky Station. Choosing Strike opens the map in place of the picker and face-off:
  - Terrain with a grid. Every player is a circular base (Qbit face, ring in their colour) in their own cell, jittered so it doesn't look like a table, placed at random each game and fixed for that game. Base size grows with points (square-root scale). You're white-ringed and labelled "You".
  - Hovering a cell previews the blast: that cell plus the 8 around it light up, the bases inside glow red, and a line names them ("Hits Bella, Chloe…"). Your own cell can't be bombed, and the blast never hits you or a player whose game is over.
  - Clicking drops the bomb: it falls, explodes and shakes the map. Each player in the blast loses points unless their own shield blocks it ("Blocked"); bases shrink to their new size; a summary shows "Hit 5 players · Aiden −500 · Chloe −200 … · Ben's shield blocked it". Then back to the question.
  - Escape goes back to the shield-or-strike choice.
  - Prototype control "Bomb blast": cell −500 and around it −200 (default), everyone in the blast −500, or one player only (the live rule).
- Rule changes in this version (proposals for the team):
  - One strike can hit several players (live: exactly one).
  - The map shows everyone's points as base size, so rank is visible while choosing (live picker hides it, M9).
  - Shield variants other than Classic aren't modelled for bombs yet.

## 2026-10-26: Map Battle, the whole game on one map (territory story)
- User: from now on all suggestions are for mapbattle. Make the flow clear and fit a new story; remove the race; asked how the winner is decided and what defines the circle.
- Answered: the winner is the most points when the last question ends (live rule). The circle is your points drawn as land: its area grows with points (square-root radius), so twice the points looks twice as big, with a small minimum so nobody vanishes.
- User chose: everything on the map, keeping the space sector look.
- Built (backup: scratchpad mapbattle.v1.html):
  - The race strip is gone.
  - The cockpit frame, passing asteroids and space act titles are gone.
  - One map is always on screen.
  - The opening shows the whole map and "Grow the biggest territory".
  - While answering, the camera pans so your base sits in the open space left of the question, and the other bases dim. A right answer grows your base with "+600".
  - When the meter fills, the camera pulls back to the whole map and Shield and Strike rise. The Strike card says "Drop a bomb on the map".
  - Strike: aim and drop on the same map (no separate screen).
  - Shield: a glowing dome over your base for as long as it lasts.
  - Bombed while answering: a bomb drops on your base, which explodes and shakes, plus a card "Carlos bombed your base · −500 points". With a shield, the dome takes it ("Blocked").
  - End: the camera pulls back, a gold crown drops on the biggest territory, then the result card.
- Still from the old story: the end title ("Ace Striker") and the header logo.

## 2026-10-26: Map Battle, target-style turn, glowing aim, class size
- User: Strike and Shield look like cockpit cards and don't fit the map; it should feel like striking and defending, target style. The map should glow and show what gets hit on hover. How do I strategise? What about 40 students, or only 5?
- The turn: no dashboard cards. On the map your base gets a pulsing white ring, with two glowing rings beside it: a blue SHIELD orb (shield icon) and a red STRIKE target (turning dashed ring with a crosshair). They move to the other side if your base is near an edge.
- Aiming:
  - The grid glows brighter.
  - The blast area is a glowing red disc with a turning target ring and a crosshair.
  - Every base inside pulses red with a red tag showing exactly what it would lose (−500 or −200).
  - The bottom line reads "Hits 4 · Ana, Bella, Carlos, Lily · up to −1,100".
- Strategy cues: players who struck you carry a small bolt badge on their base. Base sizes show who's ahead.
- Class size:
  - 5 players (new option): the map is more open, and the blast is a plus shape (cell and 4 sides), so one bomb can't take out the class.
  - 20 players: 3×3 blast.
  - 40 players: the map packs tighter and only bases you're aiming at (and yours) show names, to cut clutter.
- Backup: scratchpad mapbattle.v2.html.

## 2026-10-26: Map Battle, card deck and crosshair aim
- User: the target-ring Shield and Strike are hard to grasp; bring back the cards at the bottom like a strategy card deck. The big target circle is confusing; show just a cross and the grid intensity, and allow striking at a junction as well as inside a square.
- The turn: the Classic shield and Classic strike cards sit at the bottom of the map as a fanned hand (tilted ±6°). Hovering or focusing a card lifts it straight and glows it blue or red. The ring version is gone.
- Aiming: a small white crosshair (a circle inside a square, a diamond on a junction) follows the pointer. The squares glow by how hard they are hit, with red tags on each base.
  - Inside a square: that square −500 (brightest), the squares around it −200 (faint); in a class of 10 or fewer, only the 4 sides.
  - On a junction (pointer within about a quarter of a square from a corner): the 4 squares meeting there glow medium, −300 each.
  - A spot whose blast would include your own square cannot be picked ("That would hit you").
- Backup: scratchpad mapbattle.v3.html.

## 2026-10-26: Map Battle, no bottom bar
- User: "Remove the bottom nav bar."
- Removed the footer (Maya, Tools, Hint, power-ups, Skip, Submit); the question and answers now use that space.
- Without Submit, choosing the missing word in a fill-in-the-blank question submits it straight away, as tapping a multiple-choice answer does.
- Note for the team: Hint, power-ups and Skip are live features; this hides them in the prototype only.
- Backup: scratchpad mapbattle.v4.html.

## 2026-10-26: Map Battle, the map remembers strikes
- User: "I keep getting attacked, but do I see some effect on the map the next time I strike?"
- Before: only your base shrinking and a bolt badge on who hit you; strikes between classmates left no trace.
- Now every strike on the map (yours, on you, between classmates) leaves a dashed trail from the attacker to the target and, if it landed, a red scorch ring around the target. The trail is red, bold red when it hit you, gold for yours and blue if a shield blocked it. Marks fade over 3 questions and stay faint behind the question.
- When your turn opens, the trails animate and a line sums it up: "While you answered · Bella hit you · 4 other strikes on the map".
- The bolt badge on an attacker counts repeat hits (×2). Payback is a visible choice.
- Backup: scratchpad mapbattle.v5.html.
- 2026-10-26: user found the trails confusing; removed them. Scorch rings on hit bases, the "While you answered" line and the ×n attacker badge stay.

## 2026-10-26: NEW mapbattle-spy.html, a spy story with two looks (cyan tactical, green radar)
- User: "I want to see two UIs for the game. Like you are a spy getting coded messages to attack something. One UI in blue cyan like the moodboard and another the green type." Moodboard: Figma Game-consistency, node 87:17467 (radar and tactical screens: cyan or navy with world map, rings and sweep; green phosphor radar with a red grid and red lock brackets).
- Cloned from mapbattle.html. The mechanic is unchanged. One file with both looks: "Look" in prototype controls, or ?theme=cyan / ?theme=green (remembered per browser).
- Spy layer:
  - The map is a radar screen: rings, compass ticks and a sweeping beam (slower in lite mode, still with reduced motion), with A–L / 1–n coordinates along the grid edges.
  - Bases are blips: Qbit in a ring of the theme colour, mono codename labels. Targets get red corner lock brackets (from the moodboard).
  - Aim line: "TARGET F2 · Hits 5 · … · up to −1,000"; junctions read "C4·D5".
  - Questions: "TRANSMISSION 1/10" on the card, and the text arrives scrambled and decodes in about 0.45 s.
  - The turn cards are dark "CLASSIFIED" dossiers with a glowing edge (shield in the theme colour, strike red); the Strike card says "Call a strike on coordinates".
  - Opening: "Agent, decode the messages. Control the most ground." Panels and readouts use Share Tech Mono.
- Green: black and phosphor green, with a red grid like the moodboard; answers in four greens and yellows; Qbits slightly green-tinted.
- Cyan: deep navy, cyan and blue.

## 2026-10-26: mapbattle-spy, the holo-table
- User wanted the map to look cool: a perspective map, folded corners or a radar view. Five directions were brainstormed (holo-table, folded field map, radar scope with fading blips, satellite + HUD, holo-table + radar). The user chose holo-table + radar.
- While answering (and in the opening), the map lies on a table tilted about 52°, with a lit rim and a fog fade into the far distance. The radar rings and sweep are projected on the table.
- Bases stand up as holograms (counter-rotated, so faces stay readable) on a short beam of light.
- On your turn the camera drops to straight top-down for the cards and for aiming (precise targeting), and tilts back for the next question. The camera does not pan to your base while tilted.
- It is one tilted layer, cheap for Chromebooks; transitions are instant in reduced motion.
- Backup: scratchpad mapbattle-spy.v1.html.

## 2026-10-26: mapbattle-spy, scan beam instead of the round radar
- User: "the circle radar doesnt feel right". Likely reason: a round radar on a square grid table, not lined up with the bases.
- Removed the radar disc, rings, ticks and rotating sweep. A scan beam now crosses the whole table left to right every 6 s (12 s in lite mode, off in reduced motion), and each blip pings as the beam passes it. The grid and coordinates stay.
- Backup: scratchpad mapbattle-spy.v2.html.

## 2026-10-26: mapbattle-spy, green from the reference
- User shared a reference (mint green HUD on near-black: grid with a plus at each crossing, contour lines, corner brackets, stencil type) and asked for that green UI and the plus marks.
- Green look restyled: mint #1effa0 on #010d06, thin mint grid with a plus at every crossing (on the table and in the aiming view), faint generated contour lines, stencil font (Saira Stencil One) for the opening line, card titles and points, mono for readouts, square corners and corner brackets on the question card and readouts. The old red grid and the red edge glow are gone.
- Cyan look also gets the plus marks (fainter).
- Backup: scratchpad mapbattle-spy.v3.html.

## 2026-10-26: Map Battle story LOCKED, and a living design doc
- User: keep it simple, but a more territorial story. Locked: "You run a radio tower. Everything your signal reaches is your territory. Answer right to boost your signal and claim more ground. When your meter is full, Strike to jam an area and push rivals back, or Shield to raise a firewall. The most territory at the end wins." Cards stay titled Strike and Shield (subtitles: Jam an area, Firewall). Plain names, no codenames.
- The design reference doc (story, rules kept vs proposals, flow diagram, map, edge cases, look and feel, open decisions, files): https://claude.ai/artifact/Nvpn7akWJYK1cZSCfFxQ5g. Keep it updated with every decision.

## 2026-10-26: NEW mapbattle-station.html, space + cockpit radar + sectors + customiser
- User: the terrain felt random and the map came and went; everyone liked the Sky Station space feel. Suggested: everyone in space, the map as a radar grid, and something kids can customise (like their spaceship). Brainstormed four ways to show players (ship in cell, claimed sectors, station + ship, blips) and five customisations.
- User chose: space with cockpit + radar; ship in its home square + claimed squares in your colour; ship colour + decal first. "If this doesn't go well, I'll ask you to go back": built as a NEW file from mapbattle.html; mapbattle-spy.html and mapbattle.html are untouched.
- Story revised in the doc: you command a ship; your sector is the squares your sensors cover; Strike jams an area, Shield is a deflector; the biggest sector wins.
- Built:
  - **Launch:** before the countdown, "Your ship": 8 colours, 4 decals (none, stripes, flames, stars), Launch.
  - **While answering:** the Sky Station cockpit is back, with a small RADAR screen on the dashboard (top left) showing every sector; passing space objects are back.
  - **Your turn:** the radar grows to fill the windscreen; the strategy cards and aiming happen on it.
  - **Sectors:** about 9 squares per player, at least 60; home squares spread at least 2 apart. Sector = 1 home square + 1 square per 600 points, growing into free neighbouring squares nearest home; it shrinks from the farthest square; it scales down evenly if the grid fills. Ships sit in home squares with a Qbit + name tag.
  - **Proposal:** a strike hits anyone with a square in the blast, at their strongest square.
  - **Jammed while answering:** first-person windscreen crack + card, and your squares flicker on the radar.
- Not yet: the decal only shows on the radar ship and the launch screen, not on face-off or end screens; Chromebook performance not re-measured.

## 2026-10-26: mapbattle-station, no customiser, a 20-player grid, plus marks, a radar scan
- User: remove customisation (kids do it outside the game); make the grid for 20 students; the plus signs between grid squares were exciting; add a radar/scanner transition before the grid shows, "right now I wonder where it's coming from".
- The customiser screen is gone; the ship arrives already dressed (prototype: teal, no decal). The colour and decal code stays for when the outside customiser feeds it.
- The grid is designed for 20 students: 16×9 squares (about 7 each); bigger classes scale from it.
- A mint-cyan plus at every grid crossing (120 on the 16×9 grid).
- Scan: whenever the radar opens to full (your turn), the windscreen shows an empty radar with "SCANNING SECTOR", then a ping ring travels out from your ship and the grid, sectors and ships draw in behind it (circular reveal, 1.1 s). The Strike and Shield cards wait until the scan ends. The small radar does a smaller ping when the game starts. Off in reduced motion.
- Backup: scratchpad mapbattle-station.v1.html.

## 2026-10-26: mapbattle-station, bigger squares, outlined sectors
- User: the grid is very tight compared with Spy (why?); remove the colours and use just boundaries for occupied area.
- Why: Spy had about 2.5 squares per player (a player was one square); Station had about 7 per player so sectors could grow.
- Now a 12×6 grid for 20 students (about 3.6 squares each, close to Spy), and a sector grows 1 square per 1,200 points (every 2 right answers), scaled down evenly if the grid fills.
- Sectors are outlines only: a 2.5 px boundary in the owner colour (3.5 px for yours) with a soft glow, drawn only on the outer edge; no fill. Blast squares still tint red while aiming.
- Backup: scratchpad mapbattle-station.v2.html.

## 2026-10-26: mapbattle-station, circles and one colour (the Spy calm)
- User asked why Spy's map feels cleaner: circles, or Station's many colours making it toyish? Diagnosis: mostly the 20 saturated colours (sci-fi screens are monochrome, colour only for meaning), then the busy marks per player, then the jagged square outlines; the circle-on-a-grid reads as range on a coordinate system, like real tactical displays.
- User: keep the ships' colours (kids customise them); remove the other colour.
- Territory is a circle again (area follows points, radius 0.45–1.2 squares), all in cyan (thin ring, faint fill); yours is white; hit circles turn red while aiming. Ships keep their own colours; name tags are cyan, yours white. Square outlines are gone.
- Damage (proposal): a ship inside the blast takes its square's hit (500 centre, 200 around, 300 junction); a blast that only touches a territory circle costs 200.
- Backup: scratchpad mapbattle-station.v3.html.

## 2026-10-26: mapbattle-station, square zones and a Qbit option
- User: "instead of circles can we keep square? circles feel off. Also if we want to use Qbits then can we use that?"
- Territory is a square zone centred on the ship (area follows points), still one colour (cyan, yours white, red when targeted); the hit test is square-on-square.
- New prototype control "Radar shows": Ships (default, customised colours) or Qbits (each player is their Qbit face in a cyan ring with a name chip; yours white-ringed). Same rules either way.
- Backup: scratchpad mapbattle-station.v4.html.

## 2026-10-26: mapbattle-station, power inside your own square; Qbits in the cockpit
- User: the overlapping squares are confusing; the Qbits are missing in the station version.
- Diagnosis: any territory that grows into shared space collides; Spy never did because a mark grew inside its own square.
- User chose: A, power inside your square (story: the most powerful sector wins), and the Qbit in the cockpit.
- Each player owns one grid square. A cyan power square (yours white, red when targeted) grows from about 72% to 96% of the grid square as points grow (area follows points), so it never overlaps.
- The ship (customised colour) fills about 74% of the square, with the kid's Qbit in the cockpit (as in Sky Station) and a name tag. The "Radar shows" switch is removed.
- Hits (proposal): every ship whose square is in the blast, at that square's strength (500 centre, 200 around, 300 per junction square).
- Backup: scratchpad mapbattle-station.v5.html.

## 2026-10-26: mapbattle-station, one outlined square per ship, Qbit pilot badge, radar search
- User: a square within a square looks bad; each ship should occupy one square with a boundary in one colour; before the grid shows, a radar should search and the grid slowly form; the Qbit cannot sit on the ship, it needs a UI treatment: a Qbit circle with a half-pill name attached. User also shared three radar references (round scope, degree ring, rings and crosshair, sweeping beam with a bright edge, bracketed blips).
- Each ship owns one grid square, outlined (cyan 1.5 px, yours white 2.5 px, red tint when targeted). No inner power square; points show only in the header (trade-off: the map no longer shows who leads).
- The pilot badge sits under the ship: a 26 px Qbit circle with a half-pill name tab attached (yours white); names hide in big classes except yours and targets.
- Turn transition, about 3.2 s, cards held until it ends: 1) a radar scope (4 rings, crosshair, degree marks 0–330, a 1.4 s sweep with a bright edge) over the dark screen with "SEARCHING"; a bracketed blip lights for each ship as the beam passes its bearing (yours white). 2) The scope fades out and the grid forms from the centre outward, plus marks popping in by distance. 3) Ships and their squares appear in the order the beam found them. Off in reduced motion.
- Fixed: ships sat half a square above their outlines (a margin measured against the map width).
- Backup: scratchpad mapbattle-station.v6.html.

## 2026-10-26: mapbattle-station, territory toggle (two directions + current)
- User framed two directions and asked to build both with a prototype toggle before deciding: 1) a circle around each ship, bigger = more area held, over a soft grid; 2) each ship claims more squares as it wins (concerns: same colour makes ownership hard to read, and counting squares is hard).
- Prototype control "Territory": 1. Circles (default) / 2. Claimed squares / One square each (the previous version).
- Circles: area follows points, minimum about 0.42 of a square, capped at half the distance to the nearest ship so circles never overlap; grid and plus marks softer. Hits: ship whose square is in the blast takes that square's hit; a blast that only touches a circle costs 200.
- Claimed squares: 1 square + 1 per 1,200 points, outlined in one colour (yours white); the pilot badge shows a count of squares held. Hits: every player with a square in the blast, at the strongest square.
- Backup: scratchpad mapbattle-station.v7.html.

## 2026-10-26: mapbattle-station, the radar comes alive (juice pass)
- User: without movement or animation the game feels bleh; go through the full flow and add transitions, animation and sound so it feels like an exciting strategy game.
- Right answer: an energy streak flies from the chosen answer into the small radar, which flashes green, with a chime.
- Meter full: "FULLY CHARGED" flashes gold with an alarm before the radar search.
- Cards are dealt in from below with a spin (staggered); hovering a card ticks.
- Idle radar: ships bob out of step, circles breathe, your ring pulses, a slow sweep keeps scanning the full and small radar.
- Aiming: the crosshair snaps with a pop and a tick on each new target; targeted ships jitter; predicted damage tags pop in.
- Strike: your ship recoils, a missile arcs from your ship with a trail, a red lock bracket closes on the target; impact = two shockwave rings, the blast squares flash outward from the centre, the radar punches, each hit ship is knocked away from the blast and flashes, big damage numbers, a hit sound per ship.
- Lite mode (slow Chromebooks) stops the bob and breathing and slows the sweep; reduced motion stops all of it. Measured on a 4× slowed CPU: 60 fps through question, answer and turn.
- Backup: scratchpad mapbattle-station.v8.html.

## 2026-10-26: mapbattle-station, transitions in order
- User: "the transitions are off". Filmed every 0.25 s: the radar grew with ships visible, the alarm played over the opening radar, ships vanished for the search and came back, cards popped, and on the way back the question rose while the radar was still big.
- Now one order: "FULLY CHARGED" over the cockpit with the radar still small (0.9 s); the radar opens with the search scope already sweeping inside it; the grid forms; ships appear where found; cards are dealt (about 4.2 s total). Coming back: the radar shrinks to the dashboard first (0.65 s), then the question rises.
- Backup: scratchpad mapbattle-station.v9.html.

## 2026-10-26: mapbattle-station, you-are-here marker; sound redesigned with ambient music
- User: put a "you are here" marker; the sounds after a correct answer are irritating, mechanical, clinking, not spaceship sounds; the static noise is disturbing; add background music for a vibe, then pick sound effects that feel radio-ish but not irritating or stagey over a long game.
- You: your ship art is hidden on the radar; a glowing white diamond with a ping ring every 1.8 s, your Qbit badge "You" under it (classmates stay ships).
- Sound: every cue is now synthesised in the browser (no sample files, so no licensing): soft sine and triangle tones through a quiet space echo and a compressor. Right = two soft rising notes (E5, B5); wrong = one low soft falling note; hover = a barely-there tick; impacts = a round low thump (no noise, so no static); shield = a gentle shimmer chord; incoming = a short two-tone radio chirp. Each cue is under 1 s.
- Music: a slow ambient pad (A minor, F, C, G; 8 s per chord, detuned saw and triangle through a slow-moving low-pass), a soft sub, and an occasional distant radio blip. Quiet; it ducks during strikes. "Music: on/off" sits beside "Sound" in prototype controls.
- Backup: scratchpad mapbattle-station.v10.html.

## 2026-10-26: mapbattle-station, energetic music (CC0 tracks)
- User: the music is sad; find copyright-free energetic music that excites middle schoolers to strike and shield without breaking concentration.
- Web search was down, so I searched OpenGameArt directly for CC0 tracks and downloaded 4 (credits in assets/music/CREDITS.txt): Space Cadet Training Montage (Zane Little; upbeat, motivational, default), Interstellar Fleet 1 (Zane Little; chiptune, about 129 BPM), Happy Wireframes (Bobjt; jovial space cruise, about 108 BPM), Boundless (Centurion_of_war; upbeat spacey). About 12 MB total.
- Prototype control "Music" picks a track (or the old ambient pad, or off). Each loops; it plays at about 45% while you answer (focus) and comes up to full on your turn, dipping under strikes.
- Not heard yet: no audio playback in testing; the user should pick by ear.

## 2026-10-26: mapbattle-station, UI polish brief
- User sent a UI polish brief (refine, do not redesign; keep mechanics, positions, targeting, scoring). The screenshot and mockup it refers to were not attached; the current prototype was used as the source of truth.
- Markers: idle circles thin and low-contrast (1 px), no breathing, no continuous glow; the ship bob is reduced to 1 px; threatened = red-orange outline; the core-cell target gets a stronger 2.5 px outline; compact name tags under ships.
- Targeting: translucent tint; surrounding cells dashed (not colour alone); the selected cell crisp solid red-orange with one pulse when it changes; a reticle with four ticks and a ring (diamond on a junction); smaller predicted-damage tags.
- Action panel (angular, navy, cyan border) replaces the hint line and result banner: icon + "N ships in range" + each player with their potential loss and a total + a red-orange STRIKE button (Enter) + Back. Disabled with a reason when nothing is in range or the blast covers your own square. Firing shows "Striking…"; then the result in the same panel: "5 ships hit · 1,300 points lost" (or who blocked). It moves to the top when the blast is in the bottom two rows. Clicking the map still strikes in one click.
- Strike feedback shortened: missile 0.56 s, no radar punch; the summary holds about 2.2 s; nothing stale left (checked: 0 damage tags or highlights after).
- Header: power pips and points grouped in a gold-edged chip, inactive pips dimmer, menu and fullscreen at 75% opacity.
- Backup: scratchpad mapbattle-station.v11.html.
- 2026-10-26: hover blast squares back to plain red fill (no dashed outlines); the selected square keeps its solid outline.

## 2026-10-26: mapbattle-station, cockpit art, header stripped, lasers, older sounds back
- User shared a cockpit window frame (navy panels, orange lights, blue glass struts, transparent window) to try. Saved as assets/cockpit-frame.webp, full screen behind the questions and controls, replacing the drawn frame. The full radar now sits inside the window (inset 9% 11% 19%) and relays out to fit it; the small radar sits top left.
- User: remove the header, keep only the battery and points. The top bar, logo, Bonus, game code, menu and fullscreen are hidden; the battery and points chip floats top left.
- User: the older sound effects were better; strike and shield sounds should be very spacey (like shooting games); US kids, so no bombs, make it a strike or laser. The synthesised cues are off and the Kenney samples are back, with new spacey picks: fire = laserLarge_000, hit = forceField_002 (energy zap, not an explosion), blocked = forceField_004, struck = laserRetro_000, incoming = laserSmall_003. The strike is now a laser: your marker charges for a beat, then a beam snaps to the target and fades; the impact is an energy burst, not a fireball. Copy says strike or fire, never bomb.
- Backup: scratchpad mapbattle-station.v12.html.

## 2026-10-26: mapbattle-station, new cockpit frame; the grid takes the screen on your turn
- User shared a cleaner cockpit frame (fake checkerboard background). Removed the checkerboard by flood fill from the centre and the image edges: assets/cockpit-frame2.png with real transparency, now the frame.
- User: the cockpit takes too much space on the turn, the grid should be bigger; remove the "N ships in range / Strike" panel and the points (repetitive; they can see it on the map).
- On your turn the cockpit frame scales up 1.22× so only its edges show, and the radar fills the window (inset 2.5% 3.5%). The action panel is hidden (one click on the map strikes; Enter also works). The battery and points chip is hidden on the turn and returns for questions. Damage tags on ships stay.
- Backup: scratchpad mapbattle-station.v13.html.

## 2026-10-27: mapbattle-station, "Fully charged" transition glitch fixed
- User: a glitch in the transition when "Fully charged" shows. Filmed every 0.12 s: the small radar vanished during the alarm and then jumped. Causes: (1) the radar used a class "hold" that is also the old Sky Station strike-button class (translate -50%), which threw it off-screen; renamed to "rhold". (2) The radar changed state on a 250 ms timer before the hold was set; it now stays small until the opening starts. (3) Question and turn used different radar boxes; now one box, scaled from its corner. (4) The cockpit frame zoomed at the alarm; it now pulls back only as the radar opens.
- Sequence now: alarm over the cockpit with the small radar in place, then the radar empties and grows from its corner with the search scope inside, then the grid and ships.
- Backup: scratchpad mapbattle-station.v14.html.

## 2026-10-27: Sound Lab (pick sounds by ear)
- User: the sound is not landing, explore more. I cannot hear audio, so built prototypes/sound-lab.html: 10 moments (right, wrong, fully charged, select, fire, hit, blocked, shield, struck, hover), each with 4–9 candidates (59 total) to play and tick. Picks save in the browser (localStorage "sns.sfx") and mapbattle-station.html loads them on its next load (checked).
- New CC0 sources from OpenGameArt (web search down, browsed directly): Kenney 63 Digital sound effects, rubberduck 50 Sci-Fi SFX, 60 Sci-Fi SFX and 50 retro/synth SFX, bart Space Laser, Spring Spring Power-Up Sound Effects; plus the current Kenney Sci-Fi picks. Files in assets/sfx-lab with CREDITS.txt and catalog.json.

## 2026-10-27: mapbattle-station, you leave the map for a ship card; circles explained
- User raised 3 major issues: (1) I don't know my place in the game; (2) a new player can't tell what the base and circle mean, it feels random, and gameplay depends on it; (3) what happens when I have a shield? Proposed: take me off the map, keep my ship's UI top right wearing the shield, and break it when someone strikes me.
- Your ship card, top right on every screen (top aligned with the points chip; the small radar moves to its left): your ship in your colour, your Qbit "You" tag, and your place, e.g. "5th of 21" (1 + everyone with more points; ties share a place). The place pops green when you climb and red when you drop.
- You are no longer on the map. The 2 × 2 squares under the card and its key stay empty; your strikes leave from that corner. No spot can hit you, so the "That would hit you" block is gone.
- Shield: the emblem flies from the card you picked to your ship card and a hex dome closes over the ship; it stays while the shield lasts. A shielded strike's bolt now flies to the card, the dome cracks and shatters into shards, then the toast appears. The old hex wall across the glass is hidden. Struck with no shield: the windscreen cracks (kept), the card jolts with a red edge and shows the points lost.
- Circles: size now comes from points alone (radius 0.34 to 0.96 of a square, area follows points, the leader is always biggest). Before, a circle was capped at half the gap to the nearest ship, so a high scorer could look small, which made sizes feel random. Ships are at least 2 squares apart, so circles still don't meet.
- Every name tag on the turn map shows that player's points, so a circle's size has a number to match. A key under the card on your turn: two circles, "Bigger circle = more points".
- The big radar's dashed range rings are hidden on the turn map (they read as more circles); the small radar keeps them.
- Rule changes (proposals for the team): points and place are visible on the map (live picker hides them, M9).
- Backup: scratchpad mapbattle-station.v24.html.

## 2026-10-27: mapbattle-station, the turn map is a grid over the sky, not a screen
- User: when the grid comes it should feel like the sky has spaceships and I've overlaid my grid on top of it; right now it feels like a screen.
- On your turn the map's dark panel, edge line and scanlines are gone: space and the passing asteroids show through the cockpit glass, with a light vignette at the edges.
- The grid is a thin glowing cyan overlay that fades toward the edges; four corner brackets mark where it ends.
- Ships get a soft shadow and a faint glow in their own colour, so they read as craft out in space.
- Unchanged: the small radar keeps its dark screen; the idle sweep, circles, name tags and scan opening stay.
- Backup: scratchpad mapbattle-station.v25.html.

## 2026-10-27: mapbattle-station, territory looks like land you hold; the leaderboard is on the map
- User: the circle doesn't feel like territory; when I open Strike I can't tell whether it represents the leaderboard. Offered: ranks with a power glow, ship size, filled land, or a toggle. User: no, territory is the main idea; think of other ways.
- Territory is now filled in its owner's ship colour with a solid border and an inner glow, like borders on a strategy map, instead of a thin cyan ring.
- A flag is planted on the edge of each territory with the owner's place (#2, #3…). The top 3 flags are gold, silver and bronze, and #1's flag is taller. When a player climbs, their flag pops. Flags move to the right edge near the top of the map and to the left edge near the right side, so they never get cut off.
- One place per player: equal points go to whoever is earlier in the class list (you first), the same rule as your card, so the map and the card always agree.
- Struck land shrinks over 0.7 s with a red flash; growing land eases out the same way.
- The key under your card: "Biggest territory wins" and a gold flag with "Place".
- Removed: the points pill on each name tag (the flag carries the leaderboard now).
- Known: two flags can touch when ships are close at the right edge (seen with Dev and Priya).
- Backup: scratchpad mapbattle-station.v26.html.

## 2026-10-27: mapbattle-station, calmer territory colour
- User: the colours don't look great (territories filled and bordered in each owner's ship colour).
- Territories now share one tactical tint: a faint cyan fill with a hex texture and a thin cyan border, so they still read as land. Each territory holds one ship, so ownership reads without a colour per player.
- Colour is kept only for meaning: the ships (kids customise them), the top 3 (gold, silver and bronze border and flag), and red for land in the blast.
- Other flags are navy with a light number.
- Backup: scratchpad mapbattle-station.v27.html.

## 2026-10-27: mapbattle-station, a round radar on the question screen
- User shared a reference (round scope, thick cyan rim, rings and crosshair, a glowing arrow in the centre, red dots) and asked for that top-right UI on the question screen, with dots moving.
- The small rectangular map is replaced while you answer by a 124 px round radar just left of your ship card, tops aligned. It has a thick cyan rim, 3 rings, crosshair and diagonals, a notch at the top, and your ship as a glowing arrow in the centre.
- Each classmate is a small red blip placed where their ship is on the battlefield. Blips drift a few pixels and light up as the 4 s sweep passes, then fade, as on a real scope. Players whose game is over are grey.
- When someone strikes you, their blip flares and a red line runs from it to your arrow, which jolts (not for Stealth strikes). While your shield is up, a ring circles your arrow.
- Turn transitions: the small battlefield is centred on the radar and cut to a circle, so on your turn it opens out of the radar, and afterwards it closes back into it.
- Reduced motion: no sweep or drift, blips stay steady.
- Backup: scratchpad mapbattle-station.v28.html.

## 2026-10-28: mapbattle-station, territory is coloured land on the grid, and the game says its goal
- User: nobody can tell what the circles mean unless told that the goal is to expand your territory by answering. Offered: show your land, grow it on every right answer, state the goal once, make the turn the payoff. User: go with grid and colours, the circle isn't clear. Then: remove the numbers.
- Territory is now land on the grid: every map square is 2 x 2 tiles, filled in the owner's ship colour, with a border only on the land's outer edge. Everyone starts with their home square (4 tiles) and claims 1 tile per right answer. A strike takes tiles back (they flash red). If the map fills, everyone's land is scaled down together, so the biggest land still leads. The leader's land has a faint gold glow.
- A strike hits a player if the blast covers any of their tiles (was: their territory circle).
- Your land is on the map too, with a white edge and your "You" tag on it (your ship stays in the card). Your home is now an open square away from the edges and the Shield and Strike cards, not the corner under the card. The squares under the card stay empty.
- Your card has a new slot between your ship and your place showing the shape of your land. On a right answer, a tile in your colour flies from your answer into that slot and the new tile pops in.
- The opening says the goal once: "Answer right to claim land / Most land wins", with tiles filling in. The key on your turn says the same.
- Numbers removed: the count badge on each name tag and the points number in the top-left chip (it keeps the energy bolts). Your place in the card (e.g. 4th of 21) stays.
- The circle mode and the one-square mode are still under Prototype controls, Territory.
- Known: the key under your card can cover the name tag of a player whose home is just left of the card.
- Backup: scratchpad mapbattle-station.v29-before-grid-territory.html.

## 2026-10-28: mapbattle-station, one free move of your base
- User asked whether letting players choose their base would be heavy for dev. Offered: choose from 3 server-picked spots, choose a region, or one free move. User: try one free move.
- On your turn, a "Move base" button with a gold "Free" tag sits under your "You" tag on the map. It shows only until you use it, once per game.
- Tapping it hides the Shield and Strike cards and the key, and dashed outlines mark the squares you can move to: not under your card, not under the Shield and Strike cards, not anyone's home, and with no one else's land on them. A bar at the bottom says "Tap a square for your new base" with Cancel (Esc also cancels).
- Tapping a square moves your home there. Your land is cleared and regrows around it at the same size (old tiles flash out, new ones pop in), your card's land shape updates, and the cards come back so you can Shield or Strike.
- Dev note: the server owns the move (checks the square is still open, then sends the new home to everyone). No pick step before the game.
- Backup: scratchpad mapbattle-station.v30-before-move-base.html.

## 2026-10-28: mapbattle-station, Bauhaus style tried and rejected; land goes back to one calm colour
- User asked to try a minimal Bauhaus style (paper, black ink, flat red, blue and yellow, Jost type, Mondrian-like map, black arrowhead ships). User: "yuck, go back".
- Reverted to the version before it (scratchpad mapbattle-station.v31-before-bauhaus.html). The rejected file is kept at scratchpad mapbattle-station.bauhaus-rejected.html.
- User also: remove the colourful grids. Land tiles are now one calm cyan tint with a thin edge for every player (no colour per player); your land is brighter with a white edge. The land shape in your card, the tile that flies to it and the key use the same cyan. The leader's faint gold glow stays.
- Don't propose a flat, paper or primary-colour restyle again; the space cockpit look stays.

## 2026-10-28: mapbattle-station, back to circles; Qbits instead of spaceships
- User: go back to circles instead of grids, and use Qbits instead of spaceships.
- Territory is a circle again (Prototype controls, Territory: Circles is the default; Land tiles is still there). Calm cyan circles as before, size follows points. Rank flags (#2, #3…) are hidden, keeping the map free of numbers; the top 3 keep their gold, silver and bronze edge.
- Your circle is now on the map with a white edge and your "You" tag (your Qbit lives in the card). Move base keeps a square of space from everyone else's home, so circles don't overlap.
- Every ship is now the player's Qbit: on the map each Qbit floats gently over its circle, the name tag shows the name only (the face would repeat the Qbit). Your card shows your Qbit under the shield dome, with a "You" pill.
- Your card's land slot shows your circle inside a dashed gold ring the size of the biggest circle; the ring turns solid when you are the biggest. A right answer sends a cyan dot from your answer to the card; your circle grows and pops.
- Goal copy: "Answer right to grow your land / Biggest land wins" (opening and key), with a growing circle icon.
- Backup: scratchpad mapbattle-station.v32-before-circles-qbits.html.

## 2026-10-28: mapbattle-station, a Strike takes land, never hurts a Qbit
- User: the game is getting too close to the narrative of the US bombing and hitting kids; let's avoid it. Discussed: the airstrike cues are a top-down map, a crosshair, an area blast hitting several people, red flashes on the people hit, red "enemy" radar blips; Qbits made it worse (a child, not a vehicle). User agreed to: a Strike steals a slice of land.
- Strike no longer aims a crosshair or blasts an area. You pick one rival (back to the live rule of one target): hovering a classmate's circle edges it in gold and outlines a slice facing you, with "Take land from <name>". Tap it: a gold beam reaches their land, the slice lifts off and flies into your circle; their circle shrinks, yours grows. Their Qbit wobbles with three dizzy stars; nothing red. Esc goes back.
- A shielded rival: a cyan ring flashes round their land with "Locked"; nothing moves; their shield is used up.
- PROPOSAL (rule change): a strike moves land. What the target loses (500), the striker gains. Live: only the target loses. Applies to classmates' strikes too.
- Removed harm cues: red flashes on Qbits and circles, scorches, damage numbers on the map and your card, the red jolt on your card, the red screen edge, the area blast. Radar classmates are cyan dots; a strike on you is a gold beam on the radar.
- Copy: Strike card "Take some land"; Shield card "Locks your land"; shield note "Your land is locked for one strike"; when someone strikes you: "<name> took some of your land / Answer right to grow it back" in a navy note; a blocked strike: "Your land is safe"; turn scan: "Finding classmates" / "Classmates found".
- Kept: the windscreen crack when your land is taken (damage to your cockpit, not a person). Say if it should go.
- Backup: scratchpad mapbattle-station.v33-before-steal.html.

## 2026-10-28: mapbattle-station, land stealing reverted; back to the laser strike
- User: the land aspect isn't working; go back to lasers; they'll think of another way to avoid the bombing narrative.
- Reverted to the version before "a Strike takes land" (scratchpad mapbattle-station.v33-before-steal.html): circles, Qbits, the area laser strike, and the earlier copy. The rejected version is kept at scratchpad mapbattle-station.steal-rejected.html.
- Open: the airstrike/children association is still unsolved; the user is thinking about it.

## 2026-10-28: mapbattle-station, spaceships back
- User: bring the spaceships back.
- Removed the Qbit swap: classmates are their spaceships again on the map, with the Qbit face in the name tag; your card shows your ship under the shield dome with the Qbit "You" tag. Circles, the laser strike and the goal copy are unchanged.
- Backup: scratchpad mapbattle-station.v34-before-ships-back.html.

## 2026-10-28: mapbattle-station, circles that tell the truth; struck on the map; the winner crowned
- User is handing off to a developer tomorrow and asked how land growth, choosing a base, being struck on the map, winning and points work. Found three gaps; user said yes to fixing them with overlapping circles. User: don't write the handoff yet.
- Circle size now uses a fixed scale: radius = square × (0.30 + 0.85 × √(points ÷ most possible points)), where most possible = questions × 600 (or the top score if someone passes it). Before, sizes were relative to the leader and capped at half the distance to the nearest neighbour, so a circle could stay the same size after losing 500 points. Circles may now overlap as see-through areas.
- A circle that grows gets a short white pulse. Your circle flashes red when it shrinks.
- Struck while the map is open: the striker's laser runs from their ship to your circle (from above the map for Stealth); on impact your circle flashes red and only then shrinks; a shield outcome flashes a cyan ring instead. The card and note react as before.
- The end: the map stays, the biggest circle turns gold and gets the crown at its top edge, then the result card shows over it. The shield note is hidden on the end screens.
- Backup: scratchpad mapbattle-station.v35-before-handoff-fixes.html.

## 2026-10-28: mapbattle-station, one HUD panel at top right on the question screen
- User (screenshot of the radar, the ship card and the land box): looks really bad, not well laid out, I don't know what they do.
- The radar, your ship and your place now sit in one panel. The radar has a job: its centre is your land (cyan disc, white edge) inside a dashed gold ring the size of the biggest land, both on the map's scale (solid gold when you are the biggest). Classmates are the dots around it. Your land pulses when it grows and flashes red when it shrinks.
- A three-line legend under your ship: Your land, Biggest land, Classmates.
- The separate land box in the card is gone. The dot from a right answer now flies into the radar's centre.
- On your turn (map open) the card is on its own again, without the land box; the map shows the land.
- Backup: scratchpad mapbattle-station.v36-before-hud-panel.html.

## 2026-10-28: mapbattle-station, top right is just the radar and your place in land
- User: the UI is unnecessary; I only want a radar and my position; "7th of 21" feels like a race; how can I show my land is 7th biggest?
- Removed the ship card, its legend and the combined panel. Top right is the radar alone: your land is the cyan disc in its centre inside a dashed gold ring the size of the biggest land (solid when you're the biggest); classmates are the dots.
- Under the radar, one tag: "7th biggest land", or a crown and "Biggest land" in gold when you're first. It flashes green when you climb and red when you drop. On your turn (radar hidden) the same tag sits in the top-right corner, with the goal key under it.
- Your shield: on the question screen it's the ring round your arrow on the radar, and it breaks there when a strike hits it. Choosing Shield on your turn flies the shield into your circle on the map, and the dome closes over it.
- A strike on you with a shield flies to the radar's centre (or your circle when the map is open), not to the old card.
- Backup: scratchpad mapbattle-station.v37-before-radar-only.html.

## 2026-10-28: mapbattle-station, the HUD is part of the cockpit
- User (shared a green air-traffic radar with small planes): instead of red dots, show small ships flying on the radar, in our art style; the UI should feel like the spaceship's controls, not floating on top; scores can be digital boards hanging in the ship.
- Radar: mounted in the top-right corner as an instrument: a metal bezel with four screws, a glass reflection over the screen, and a bracket up to the frame. Classmates are small white-cyan ships, each facing the way it drifts; they brighten as the sweep passes and stay visible (dimmer) in between. An attacker's ship flares orange-red. Your land disc and the biggest-land ring stay in the centre.
- Your place ("13th biggest land") is a digital board hanging from the ceiling on two struts, just left of the radar: a dark screen with a metal frame and glowing cyan LED type (gold, with a crown, when you're first). It flickers when your place changes. It stays put on every screen.
- The energy meter (top left) is the same hanging board, with the bolts lighting amber.
- The goal key on your turn is a thin strip of the same screen.
- Backup: scratchpad mapbattle-station.v38-before-cockpit-hud.html.

## 2026-10-28: mapbattle-station, a lighter HUD; the board shows rank
- User (screenshot of the radar): the UI feels so heavy, make it thinner; instead of "biggest land" show my rank.
- Radar: the bezel is a thin metal ring (about 4 px) with tiny rivets; the cyan rim is a 2 px hairline; grid lines fainter; the bracket is two thin rods. Ships are smaller (8 px) with less glow; the arrow is smaller; your land disc and the biggest-land ring are hairlines; the shield ring is smaller.
- The board now reads "RANK 8" (a crown with "RANK 1" in gold when you're first). Rank is by land, which is by points.
- Boards: 1.5 px frames, thin struts, smaller padding. The goal strip on your turn is slimmer too.
- Backup: scratchpad mapbattle-station.v39-before-thin-hud.html.

## 2026-10-28: mapbattle-station, Style "Neon Bauhaus" (switchable)
- User: a prototype that is Bauhaus meets sci-fi cyberpunk cyan neon; must be able to go back to the current state.
- Added Prototype controls, Style: "Neon Bauhaus" (default) or "Cockpit (previous)". The choice is remembered in the browser. Cockpit is exactly the look before this change.
- Neon Bauhaus: near-black background with a neon Bauhaus composition (a large cyan circle, a magenta triangle outline, a cyan bar, a yellow bar, a filled magenta dot), a horizon line, and a cyan grid floor scrolling toward you. The cockpit frame, starfield and space art are off; asteroids and planets are black silhouettes with a cyan neon edge. Geometric sans (Jost) for content, a mono face for HUD labels.
- Question: black panel with a cyan neon edge and a magenta dot in its corner; the number is a solid cyan block.
- Answers: four black frames with neon edges (cyan, magenta, yellow, pale cyan), each marked by its Bauhaus shape (circle, square, triangle, half-circle). Right is green neon; wrong magenta.
- Radar and boards: neon outlines, no metal. Rank board cyan (yellow when first).
- Map: cyan grid; land as cyan neon outlines; ships recoloured cyan monochrome with glow; your land white; the leader yellow. The composition dims behind the map. Aim area, crosshair, damage tags and the laser are magenta.
- Your turn: Shield is a black card with a cyan neon ring; Strike a black card with a magenta triangle.
- Notes, opening, result card: black with neon edges (strike notes magenta, result yellow).
- Backup: scratchpad mapbattle-station.v40-before-neon.html.

## 2026-10-28: mapbattle-station, Style "Spacetime" (switchable)
- User: from a UI angle, make the game look like Lovers in a Dangerous Spacetime (Steam); they can ask GPT to generate assets.
- Studied the store screenshots: flat neon-pastel vector art, deep violet space with soft nebula blobs and four-point sparkles, round cross-section ships, chunky rounded shapes, saturated pink, orange, teal and purple with soft glow, a round dark minimap.
- Added Style "Spacetime" (now the default); "Neon Bauhaus" and "Cockpit (previous)" are still in Prototype controls, Style.
- Spacetime, with CSS stand-ins: violet nebula background with twinkling four-point sparkles (pink, teal, white); asteroids and planets kept, shifted warmer; no cockpit frame. Rounded type (Fredoka). Question: a dark rounded panel with a pink glowing edge and a pink pill number. Answers: four chunky candy tiles (pink, orange, teal, purple) with a darker lip underneath and a faint room grid; they press down on click. Radar: dark disc with a thick purple glowing rim and a pink sweep. Rank and energy: rounded pills with purple rims. Map: each player's land is a round glowing disc in their ship colour with faint inner rings; yours white-rimmed; the leader orange; a dotted grid. Laser: a thick yellow-orange beam. Turn cards: chunky teal Shield and pink Strike with the existing art.
- Art list for GPT: spacetime-asset-list.md (style line, 10 asset types, file names, sizes, prompts, no-violence note).
- Backup: scratchpad mapbattle-station.v41-before-spacetime.html.

## 2026-10-28: mapbattle-station, Spacetime gets one palette
- User: I made it extremely colourful (purple, pink, blue everywhere); in each reference screenshot one colour dominates; keep the feeling of the environment and elements but not so toyish, so there's a clear palette.
- Palette: a deep violet world (#0d0a1f to #5a46a0, about 70% of the screen: space, nebulae, rocks, panels, everyone else's land); hot pink #ff4fa3 is the one hero colour (you and your actions: your land, your tag, the question edge, Strike, the laser, the radar's land disc); teal #2de2d0 only for Shield and correct; gold #ffc547 only for the leader, the crown and energy.
- Answers: four matching violet tiles with a darker lip, told apart by a shape mark (circle, square, triangle, half-circle), not colour. Hover lights the edge and mark pink; right is teal; wrong keeps a pink edge and dims.
- Map: everyone else's land is a muted violet disc; yours is the one pink disc; the leader's rim is gold. Other ships are desaturated so the scene has one hero; a ship lights up when it's in your blast. Asteroids and planets are tinted violet.
- Turn cards: dark violet with a teal (Shield) or pink (Strike) edge and lip; their pictures are tinted to match.
- spacetime-asset-list.md rewritten around this palette (palette table, new style line, land in violet/pink/gold only, classmates' ships muted and told apart by shape).
- Backup: scratchpad mapbattle-station.v42-before-spacetime-palette.html.

## 2026-10-28: mapbattle-station, Spacetime goes warm (no purple or pink); new type
- User shared another reference screenshot (orange round ship, maroon space, red wireframe rocks, blue boss arm, lime projectiles, slim pink side meter, slim bottom bar, dark round minimap with red dots): don't go heavily purple or pink; borrow this style; the Fredoka font doesn't look good.
- Palette: a dark maroon-umber world (about 75%), one hero orange (#ffa23a) for you; small accents only: cool blue Shield, lime Strike/laser/correct, red wrong/lost land, yellow leader and crown. No purple, no pink.
- World: maroon space with soft red and orange bokeh discs and faint dust (no sparkles); rocks and planets tinted to red silhouettes with a lighter rim.
- Type: Rubik (clean geometric, readable) replaces Fredoka.
- Question: dark umber panel, thin orange line, faint circuit linework inside. Answers: dark umber tiles with a thin warm rim and a shape mark; hover lights them orange; right is lime; wrong red.
- HUD: radar is a dark disc with a thin red rim and a faint square grid (like the reference minimap), classmates as small red ships, you orange. Rank is a thin dark pill (yellow when first). Energy is a slim capsule meter that fills orange toward your next turn and pulses when full.
- Map: everyone else's land is dark umber with a thin warm rim; yours is the glowing orange disc with cross lines; the leader's rim yellow. Other ships muted; aim area and laser lime.
- Turn: Shield card edged cool blue, Strike card edged lime (its picture recoloured lime), on dark umber.
- spacetime-asset-list.md rewritten for this palette.
- Backup: scratchpad mapbattle-station.v43-before-spacetime-warm.html.

## 2026-10-28: mapbattle-station, Spacetime gets a holographic tactical HUD
- User shared a tactical space-game screenshot (round glass buttons with glowing cyan rims and inner grids, a cyan grid with crosses, small rectangular label plates, a thin screen frame with corner dots, cyan/green/red/yellow meaning): do this type of UI, but keep the Lovers in a Dangerous Spacetime look for the environment.
- The warm Spacetime world stays (maroon space, bokeh, red rocks). The UI layer on top is now holographic glass: dark teal panels with a faint inner grid, a glowing cyan rim and soft inner light.
- Colour meaning: cyan is the interface; green is you; red marks classmates' name plates; yellow is Strike, the aim area and the laser; gold is the leader. Type: Exo 2 for reading, Chakra Petch for numbers and labels.
- Question: glass panel with cyan corner brackets; the number in a small plate. Answers: glass panels with a cyan outline shape mark; hover brightens; right green; wrong red.
- Screen: a thin cyan frame line round the whole screen with dots in the corners.
- Energy: a round glass button with a bolt; its rim fills as a ring toward your next turn; it turns yellow and glows when your turn is ready. Rank: a label plate ("RANK 9"; gold when first). Radar: a round glass button with a grid, classmates red, you green.
- Map: thin cyan cell lines with glowing crosses at every corner and a fine sub-grid; other land neutral warm; yours green; leader gold; name plates rectangular glass (red for classmates, green for you). Laser: thin yellow beam.
- Turn: Shield and Strike are glass cards with a round glass medallion for the picture (cyan Shield, yellow Strike).
- Backup: scratchpad mapbattle-station.v44-before-holo-ui.html.

## 2026-10-28: mapbattle-station, Style "Neon Cosmic" from the user's art direction
- User: the holographic version isn't looking good; gave an art direction, "Neon Cosmic Vector": stylized 2D arcade space; flat-shaded geometric illustrations; translucent cosmic forms; deep navy space; luminous cyan and teal; selective neon magenta, coral and orange accents; sharp compact HUD panels with thin neon outlines; segmented indicators; circular radar; bold arcade type; energetic, competitive, slightly futuristic, for middle school; readable. Palette: navy #090D32, deep blue #17276B, cyan #00D9F5, teal #14D9BC, violet #A832FF, magenta #F32DCE, coral #FF654F, orange #FFAA39, gold #FFD64A, ice white #F4F6FF.
- Added Style "Neon Cosmic" (now the default). Spacetime, Neon Bauhaus and Cockpit stay in Prototype controls, Style.
- World: navy gradient space with translucent flat-shaded faceted forms (teal, cyan, violet, a little magenta), two outlined orbs, twinkling ice-white stars; asteroids and planets recoloured cool blue.
- Accents with one job each: orange is you (your land, your radar arrow, your tag, Move base); magenta is Strike (card, aim area, laser); teal is Shield and correct; coral is wrong and lost land; gold is the leader and the result; violet is classmates' land.
- HUD: square, compact panels with a thin cyan outline and a small filled corner accent in the outline colour. Energy is a segmented indicator ("ENERGY" and one slanted segment per right answer needed; segments go orange and pulse when your turn is ready). Rank is a compact plate ("RANK 7", number in Russo One; gold when first). Circular radar: navy disc, cyan rim, rings, teal sweep, classmates as ice-white ships, you orange.
- Type: Russo One (bold arcade) for numbers, titles and card names; Exo 2 for reading.
- Question: navy panel, cyan outline and corner accent; the number on a slanted cyan tab. Answers: four navy panels with a cyan outline shape (circle, square, triangle, diamond); hover brightens cyan; right is teal with a slanted "CORRECT" tab; wrong coral.
- Map: fine cyan grid; classmates' land translucent violet; yours orange; leader gold; name tags as slanted plates. Turn cards: Shield teal and Strike magenta, notched art frames.
- Tried cut (notched) corners first; they clipped the question number and broke the outlines, so panels are square with a corner accent instead.
- Backup: scratchpad mapbattle-station.v45-before-neon-cosmic.html.

## 2026-10-28: mapbattle-station, Spacetime rebuilt from the user's mock
- User shared a mock (pink-and-white hero ship in a teal bubble; big translucent low-poly planets in teal and orange-magenta; translucent purple rocks; cyan four-point sparkles; dotted orbits; top-left round ship badge on a long slanted cyan/yellow bar; top-right slanted pill with a gold star coin and score; bottom-left radar with a thick magenta rim, cyan arc pieces, an ice triangle and pink-red dots; bottom-right slanted ability cards with icons, segment bars and slanted magenta number badges): "this is exactly what is in my head for Spacetime".
- Spacetime is the default style again and now follows this mock. The earlier warm version is kept as "Spacetime (warm, earlier)"; Neon Cosmic and the others are still in Prototype controls, Style.
- World: indigo space; big translucent low-poly orbs (a jittered triangle mesh clipped to a circle, soft fill, glowing rim) in teal, orange-magenta, magenta-orange and violet; dotted orbit arcs; cyan four-point sparkles and soft dots; asteroids recoloured translucent purple.
- HUD: top left, your ship in a round badge attached to a long slanted bar whose segments fill cyan toward your turn and turn yellow-orange and pulse when it's ready. Top right, a slanted pill with a gold star coin, "RANK" and the number. Radar: dark disc, thick magenta rim, cyan and blue arc pieces outside, an ice-blue arrow for you, classmates as pink-red dots with white centres (dots, as in the mock, replacing the small ships).
- Cards: the question and the four answers are slanted "ability cards" (navy, thin blue outline); each answer has a slanted number badge (1 to 4) with a magenta outline, like the mock's counters; the question number is a slanted magenta tab. Hover cyan; right teal with a "CORRECT" tab; wrong pink.
- Map: your land is a teal translucent bubble; classmates' land translucent violet with soft facets; the leader gold; your laser and the aim area yellow; strikes on you pink-red; name tags as slanted plates. Turn: Shield and Strike are slanted cards (Shield gold-edged, Strike cyan-edged).
- Type: Exo 2, bold and extra-bold for numbers.
- Backup: scratchpad mapbattle-station.v46-before-spacetime2.html.

## 2026-10-28: mapbattle-station, the user's ship and laser art in Spacetime
- User shared a sprite sheet (pink-and-white rocket with orange fins and a cyan flame in several sizes; pink, purple, red-orange and green variants; two top-down views; cyan, magenta, yellow and teal laser bolts): use these for Spacetime.
- Cut into prototypes/assets/spacetime/ from the sheet's own transparency: ship-hero, ship-pink, ship-purple, ship-red, ship-green, ship-up, ship-up-engine, laser-cyan, laser-magenta, laser-yellow, laser-teal (PNG, resized for 2x screens, 650 KB in all).
- Classmates on the map fly the pink, purple, red and green ships (each player keeps one), bobbing gently; your hero ship sits in the top-left badge. The strike beam is the yellow laser sprite. The blast squares' impact is a soft yellow pulse with a yellow ring instead of a white flash.
- Unused for now: the top-down ships and the cyan, magenta and teal lasers (ideas: magenta for strikes on you, cyan or teal for Shield).

## 2026-10-28: mapbattle-station, Spacetime calmer (light pass)
- User: it looks great but feels extremely colourful; everything fights for attention; figure it out before building. Agreed approach: a colour budget in three tiers (full colour and glow only for what matters now; classmates quiet; atmosphere low). User: one colour for all classmates' ships (the Qbit face and name identify them); try a light pass first, a strong pass later.
- Classmates: all fly the same ship (the purple sprite), desaturated and still (no bob). A ship lights up to full colour when it's in your blast (yellow glow), when it struck you (pink), or when its player leads (gold).
- Atmosphere: planets at about 60% (45% on your turn), half the sparkles twinkling more slowly, no dotted orbits behind the map, asteroids at 45%; the scene dims slightly behind the question while you answer.
- Land: classmates' circles have a thin quiet rim and no glow; only your land (teal) and the leader's (gold) glow. Name tags' outlines quieter.
- UI: less glow on the question, answers and turn cards; hover and correct keep a smaller glow; the radar rim thinner with less glow and its outer arcs dimmer; the ship badge's glow reduced.
- Next, if wanted: the strong pass (one quiet outline colour for all chrome, the radar rim blue, magenta only for strikes on you, two planets pushed to the corners, motion only where attention is needed).
- Backup: scratchpad mapbattle-station.v47-before-calm-light.html.

## 2026-10-28: mapbattle-station, the user's environment art in Spacetime
- User shared an environment sheet (low-poly translucent planets in teal, orange-magenta and violet with moons; purple, blue and orange low-poly rocks; small orbs; crystals; stations; ring pieces) and two backgrounds (a calm navy-purple nebula; a colourful one with pink, orange and cyan clouds): use whichever works.
- Chose the calm navy nebula as the backdrop: the colourful one would undo the light calm pass.
- Cut from the sheet's transparency into assets/spacetime/: planet-teal, planet-orange, planet-violet, rock-1 to rock-5, orb-1 to orb-3, crystal-1, crystal-2 (each cleaned to its main shape); bg-space.jpg from the calm background.
- Spacetime now uses: the nebula backdrop (its own stars, so the drawn sparkles, orbs and orbits are off); three planets at the edges, partly off screen and soft (about 40 to 50%, lower on your turn): teal at the left, orange top right behind the radar, violet bottom right. Everything that flies past is swapped for the low-poly rocks (mostly purple, one blue) and small orbs (at half opacity) while the style is on.
- Unused for now: the colourful background, the orange rock, the crystals, the stations and the ring pieces.
- Backup: scratchpad mapbattle-station.v48-before-env-art.html.

## 2026-10-28: mapbattle-station, aim only at pluses; ships inside their land, each heading its own way

User: when striking, you shouldn't be able to aim at a player, only at the plus signs between them; the circle doesn't feel like it covers the ship; every ship faces the same way, which feels unnatural.

- Aiming: the pointer always snaps to the nearest plus (a crossing of four squares); there is no more aiming inside a square, so you can never put the crosshair on a ship. The strike hits the four squares around that plus. The idle hint reads "Aim at a plus between lands".
- Ships fit their land: each ship is centred on its circle and sized to 60% of the circle's width (34 to 104 px), so the circle always wraps it; a small land has a small ship.
- Headings: each classmate's ship has its own heading from their name (the same every game), within 70 degrees of left or right so no ship looks upside down; ships facing left are mirrored. Each sways slowly by 5 degrees on its own timing (off under reduced motion).
- Backup: scratchpad mapbattle-station.v49-before-plus-aim.html.

## 2026-10-28: mapbattle-station, the user's cockpit art in Spacetime

User: "use this cockpit for spacetime" (a cockpit frame: window pillars, a top bar, a dashboard with three screens).

- The art is in assets/spacetime/cockpit.webp (196 KB). The transparent area outside the window was filled with a dark hull colour so space only shows through the glass.
- Drawn as one border-image layer: the top bar, the corners and the dashboard keep their drawn shape (scaled to the screen width); only the window pillars stretch to the screen height. Toned down slightly (saturation .88, brightness .92).
- While you answer, the question and the answers sit inside the window; the radar sits in the dashboard's centre screen and your rank on the right-hand screen. The energy bar stays top left.
- On your turn the cockpit opens out (grows past the screen edges and fades) so the map has the whole screen; the rank goes back to the top right.
- Backup: scratchpad mapbattle-station.v50-before-cockpit.html.

## 2026-10-28: mapbattle-station, Neon Cosmic redone from the user's Figma reference

User: "make neon cosmic in this style" (Figma Game-consistency, section "Neon cosmic": a tactical space battle with a cyan grid of plus marks, round glossy cyan buttons, translucent teal number plates and neon green ships; and a dark cockpit lit by thin cyan neon lines).

- Backdrop: assets/cosmic/deep-space.jpg, generated: near-black space, a soft blue-violet nebula on the left, a faint warm glow low right, dense fine stars. The earlier flat-shaded forms are off.
- Cockpit: an SVG drawn for 1366 x 657 (stretched to fit): dark hull round the window, thin glowing cyan lines along the window, the pillars, the ceiling module and the dashboard, two small violet lamps. As in Spacetime: the question and answers sit inside the window, the radar is on the centre dashboard screen, your rank on the right-hand screen; on your turn the cockpit opens out.
- Panels: dark glass with rounded corners and a thin cyan edge. Each answer's mark sits in a round glossy cyan button.
- Plates: the question count, your rank and every name tag are translucent teal plates with a lighter edge. Orbitron for the question count; the rank digit stays in Exo 2 because Orbitron's 7 reads as a bracket.
- Map: a cyan grid with bright glowing plus marks; land is a thin cyan ring (yours brighter and thicker, the leader gold).
- Ships: every classmate flies the same green hologram ship (assets/cosmic/ship-holo.png, made from the Spacetime ship); it fits inside their land and has its own heading, as in Spacetime. A ship in your strike's path turns magenta.
- Backup: scratchpad mapbattle-station.v51-before-cosmic2.html.

## 2026-10-28: mapbattle-station, Spacetime gets the blue cockpit

User: picked the blue cockpit of two new cockpit arts ("put blue then if i dont like u can put the other one"); the purple one with orange trim is the fallback.

- Why blue: one colour family with a few small amber lamps (fits the calm single-colour pass); its dashboard has three screens, so all instruments sit on it; no top bar and thin pillars, so the question gets more room; the same 3:1 shape as the previous cockpit.
- assets/spacetime/cockpit-blue.webp (97 KB), the transparent area outside the pillars filled with dark navy hull. The previous pink-and-yellow cockpit.webp is kept.
- Slices: top 0, sides 420, dashboard 197. The question area runs from 56 px down to the dashboard.
- On the dashboard while you answer: the energy bar on the left screen (at 72%), the radar on the centre screen (at 74%, over the radar drawn there), your rank on the right screen. On your turn they go back to the top and the cockpit opens out as before.
- Backup: scratchpad mapbattle-station.v52-before-blue-cockpit.html.

## 2026-10-28: mapbattle-station, Spacetime tries the purple cockpit

User: "try this" (a purple cockpit with orange lamps, 1920 x 1080).

- assets/spacetime/cockpit-purple.webp (63 KB), the transparent area outside the pillars filled with dark violet hull. The blue (cockpit-blue.webp) and the first (cockpit.webp) are kept.
- The art is 16:9, so it is not stretched: it spans the full width, sits on the bottom edge and loses a little of its empty top. Its dashboard is taller (about 190 px at 1366 wide) and its pillars slope in, so the question area is narrower (66% of the width) and ends above the dashboard.
- On the dashboard while you answer: the radar on the centre console (at 74%), the energy bar on the left panel (at 60%), your rank on the right panel. On your turn they go back to the top and the cockpit opens out as before.
- Backup (blue cockpit): scratchpad mapbattle-station.v53-before-purple-cockpit.html.

## 2026-10-28: mapbattle-station, cockpits keep the question container whole; instruments hang from the top

User: the cockpit squeezed the question container ("That is something we cannot do"); keep its size, as a modal or with padding. The instruments can't sit on the dashboard: hang them from the top, as in the Cockpit style. Also asked what the meter means.

- The question screen is back to its own size and position (Figma 124:34599) in Spacetime and Neon Cosmic. The cockpit art now sits behind it (one layer below the question screen) and never changes its layout.
- The answers sit in one padded panel (12 px padding, 16 px corners, dark glass with a thin rim), like a modal over the dashboard; the fill-in-the-blank card gets the same panel.
- The energy bar, your rank and the radar are back at the top, a little lower, each hung on two thin wires from the top edge (violet in Spacetime, cyan in Neon Cosmic). The wires show only while you answer.
- Backup: scratchpad mapbattle-station.v54-before-hung-hud.html.

## 2026-10-28: mapbattle-station, two styles removed; Neon Candy mockup

User: remove Spacetime (warm, earlier) and Neon Bauhaus. Then: "if I had to say that the Spacetime theme is neon candy vibes, then what would you change?" A mockup, with a main colour other than purple ("We've already done a game in purple"), pastel pink or candy.

- The style switch now offers: Spacetime, Neon Candy (mockup), Neon Cosmic, Cockpit (previous). A saved choice of a removed style falls back to Spacetime. The removed styles' CSS is still in the file but nothing switches it on.
- Neon Candy is Spacetime's layout (same cockpit, hung HUD, answers panel, map) in a candy palette:
  - Main colour hot pink #ff4fa3 on a pastel candy-pink sky (assets/candy/candy-sky.jpg, generated: pink fading to peach, soft clouds, white sparkles). Berry #6b1d4a is the dark text colour, because white on pastel can't be read.
  - Mint means right and Shield; lemon is your energy when full and the laser; gold the leader; coral wrong.
  - Cards are cream with a hot-pink edge, a glossy top and a soft drop, with rounded "jelly" corners instead of Spacetime's slants; badges and pills are hot-pink candy pills; the answers panel is frosted pink glass.
  - The cockpit is the purple art tinted pink with lemon lamps (a CSS filter for the mockup; real art would be better).
  - Ships, rocks and planets are the Spacetime art recoloured from purple to pink (assets/candy/). Land is a soft white bubble; yours hot pink; the leader gold. The grid and plus marks are white. The windscreen crack is drawn in berry so it shows on the pale sky.
- Not restyled yet: the Shield and Strike card art (still blue and red) and the "struck you" note (still navy).
- Backup: scratchpad mapbattle-station.v55-before-candy.html.

## 2026-10-28: mapbattle-station, Neon Candy removed

User: "remove candy". The option, its style block and its art (assets/candy/) are gone; a saved choice of it falls back to Spacetime. The switch now offers Spacetime, Neon Cosmic and Cockpit (previous). The user is choosing between those three.
- Backup with Neon Candy: scratchpad mapbattle-station.v56-before-remove-candy.html (its art would need regenerating).

## 2026-10-28: mapbattle-station, Spacetime v2 (teal)

User: "create spacetime v2 with teal", following the advice to keep Spacetime's dark space and change only its main hue, because the team already made a purple game.

- A new switch option, "Spacetime v2 (teal)". Spacetime itself is unchanged.
- The same layout, cockpit, hung HUD, answers panel and map as Spacetime; the main colour moves from purple to deep teal:
  - Art recoloured from purple to teal into assets/teal/: the nebula background, the classmates' ship, the violet planet, the rocks and orbs, and the blue cockpit (cockpit-teal.webp, with its amber lamps kept).
  - Cards: dark teal fill inside a teal outline; number badges and the question count outlined in light aqua. The radar is a dark teal disc with an aqua rim; classmates are white dots, attackers pink.
- Teal is now the world colour, so "you" moves to warm orange (your land ring, your "You" tag, your radar disc, the Move base "Free" tag). Right answers are green; the leader stays gold; strikes on you stay pink-red; the energy bar and the laser stay yellow.
- Backup: scratchpad mapbattle-station.v57-before-teal.html.

## 2026-10-28: mapbattle-station, Cockpit style flies the Spacetime ship; music choice remembered

User: "can u replace the spaceship in cockpit with the spaceship from spacetime"; "idk where the music is playing can u switch it off".

- The Cockpit (previous) style now gives every classmate the Spacetime ship, sized to their land, each with its own heading (as in Spacetime). The style gets a body class, ckstyle, for this. Not yet checked on screen (the check was interrupted).
- Music: switched off in the user's browser pane (Prototype controls → Music: Off). The Music choice is now remembered in the browser, so a reload no longer restarts the default track. The default for a new viewer is still "city".
- Backup: scratchpad mapbattle-station.v58-before-ck-ships.html.

## 2026-10-28: mapbattle-station, Spacetime: straight shapes, scan lines, a board transition, a tumble when struck

User: when someone hits you, make the cockpit shake a little, as if the ship tumbled. No slants on the question and answer cards: keep them normal, with scan lines running so the Q&A feels like a message coming in. The hung boards at the top shouldn't have a slanted cut either. And try a perspective transition, like Spy Station's board that tilts and comes straight ("These are the things that make it feel very real").

Applies to Spacetime and Spacetime v2:
- Straight: the question card, answer cards, number badges, the question count, the rank board, the energy bar, notes and name tags lose their slanted cuts and become rounded rectangles. The Shield and Strike turn cards keep theirs for now.
- Scan lines: the question and answer cards carry fine horizontal scan lines and a soft bright band that sweeps down every 4.2 s, offset card by card.
- Board transition (after Spy Station's holo-table): each new question swings up from tilted back to face you (0.75 s), its answers flipping up one after another. When your turn opens, the radar scan and map arrive as a tilted table and straighten to top-down over 2.4 s as the contacts land.
- Tumble: a strike that hits you (the windscreen crack) makes the cockpit lurch and settle while the space outside swings the other way; the question jolts; the hung boards swing on their wires (about 1 s). A strike your shield blocks gives a small bump. All of it is off under reduced motion.
- Backup: scratchpad mapbattle-station.v59-before-straight-tumble.html.

## 2026-10-28: mapbattle-station, map transition: pull back from your ship; plus marks as bright stars

User: the tilted-table map transition "is not feeling part of the storytelling", try a different one. And once the grid comes in, make the small plus signs like stars that stand out; they merge with the background stars.

Spacetime and Spacetime v2:
- Your turn now opens with the camera close on your own ship (2.8x) pulling back to the whole battlefield over 2.3 s, while the scan rings spread out from you: you first, then everyone around you. The tilted-table transition is removed. The question's board swing-in stays.
- The plus marks are bright white four-point stars, 18 px, with a cyan glow (aqua in v2): bigger and brighter than any background star. The sky dims a little on your turn so they stand out.
- Radar Green style: started (recoloured art in assets/green/), paused when the user switched to this; not yet in the style switch.
- Backup: scratchpad mapbattle-station.v60-before-zoomout.html.

## 2026-10-28: mapbattle-station, plus marks toned down

User: "the plus is too overpowering i cant focus on anything else".
- The plus marks stay four-point stars (so they don't read as background stars) but are small and soft: 12 px, no glow, 42% opacity, 62% while you aim. The sky dims less on your turn (85%).

## 2026-10-28: mapbattle-station, Spacetime gets the neon cockpit

User: "use this for cockpit" (a neon cockpit frame: blue-violet pillars with pink and amber lights, a glass radar screen on the dashboard, side windows).
- assets/spacetime/cockpit-neon.webp (174 KB, from the user's "Neon Futuristic Cockpit HUD Frame"), the transparent area outside the frame filled with dark indigo hull; its translucent side windows are kept.
- Spacetime only (v2 keeps its teal cockpit). The art is close to the screen's shape, so it spans the full width, sits on the bottom edge and is not stretched. The question container keeps its size over it.
- The earlier cockpits (cockpit.webp, cockpit-blue.webp, cockpit-purple.webp) are kept.
- Backup: scratchpad mapbattle-station.v61-before-neon-cockpit.html.

## 2026-10-28: mapbattle-station, the planets turn

User: "rotate the planets they feel too static".
- Spacetime and v2: the three edge planets turn slowly, each at its own speed (one turn in 70 s, 95 s reversed, 120 s), and drift about 15 px back and forth (19 to 27 s). Off under reduced motion.

## 2026-10-28: mapbattle-station, space critters and an Easter egg

User: add space creatures, minimal geometric shapes moving around in space (references: pale striped critters with a pink head, one big eye and toothy jaws; a simple flat ship). If one comes on screen and you hit it, an Easter egg.

Spacetime and v2:
- Two drawn critters (inline SVG, no art files), flat shapes with a light outline:
  - Space Chomper: a pale green striped tail that wiggles, a pink head, one dark eye with a green glint, toothy jaws that chomp.
  - Space Jelly: a pale cyan dome with a highlight and one eye, three wavy tentacles; the bell pulses.
- One swims across space every 15 to 35 s (at most two at once), on a gentle wave, behind the cockpit, the question and the map, in 15 to 23 s.
- Easter egg: tap a critter (not while aiming a strike, and not on a button or answer), or catch it in your strike's blast. It spins, its eye becomes a gold star, sparkles burst out, it zips away, and a note says "You booped a Space Chomper!" or "Your laser tickled a Space Jelly!" with "Secret critters found: n". No points change. Off under reduced motion.
- Prototype hook: __critter('chomper') or __critter('jelly') in the console sends one across now.
- Backup: scratchpad mapbattle-station.v62-before-critters.html.

## 2026-10-28: mapbattle-station, critters: a funny splat instead of a secret

User: "I didn't mean literally an Easter egg... something like a funny thing comes or a splash comes."
- Tap a critter: it rushes at you and splats on the windscreen like a bug on glass: a goo splat in its colour with drips, its eye in the middle blinking twice, a comic burst saying "SPLAT!" (Chomper) or "BLOOP!" (Jelly). The splat wobbles, holds, then slides down the glass and fades (2.7 s).
- Catch one in your strike's blast: a comic "ZAP!", a puff of bubbles, and it spins away dizzy with star eyes.
- The "You booped…" note and the "Secret critters found" count are removed. No points change.
- Console hooks for reviews: __critter('chomper' | 'jelly') sends one across; __critterTap() splats one; __critterZap() zaps one.
- Backup: scratchpad mapbattle-station.v63-before-splat.html.
