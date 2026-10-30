# Spacetime style: art to generate

The prototype's "Spacetime" style (Prototype controls → Style) uses CSS stand-ins. Generate these to replace them. Drop the files in `prototypes/assets/spacetime/` with the names below and tell me; I'll wire them in.

## The palette (one dominant hue, as in each scene of the reference)

| Role | Colour | Used for | Share of the screen |
|---|---|---|---|
| World | Maroon-umber: #100403, #1c0806, #28100b, #3a1a12, #5c2c1e, #8a4630 | Space, bokeh, rocks, panels, everyone else's land and ships | about 75% |
| Hero | Orange #ffa23a (light #ffc46e) | You: your land, your ship, your meter, the main edges | about 15% |
| Shield | Cool blue #4f8dff | The Shield card and shield effects only | small |
| Strike | Lime #b6f03c | Strike, the laser, correct answers | small |
| Danger | Red #ff4b3e | Wrong answers, losing land | small |
| Leader | Yellow #ffe05a | The leader, the crown | small |

No purple, no pink. Other players' ships are muted so the scene has one hero.

## Style line for every prompt

Paste this at the start of each prompt:

> Flat 2D vector game art. Palette: a dark maroon-umber world (#100403 to #8a4630) with one hero colour, warm orange #ffa23a; small touches of cool blue #4f8dff, lime #b6f03c, red #ff4b3e or yellow #ffe05a only where stated. No purple, no pink. Bold simple shapes, fine lighter linework for detail (like circuit lines), soft outer glow on the bright parts, no texture noise, no text, no logos. Calm and warm, not toyish. For children aged 8 to 14. Original design: do not copy any existing game's characters or ships.

Every asset except the background needs a transparent background (PNG).

## The list

| # | File | Size | What it is | Prompt (after the style line) |
|---|---|---|---|---|
| 1 | `bg-space.png` | 2732 × 1314 | The backdrop for every screen | Wide space scene in the maroon world palette only: deep red-brown space with large soft out-of-focus bokeh discs in dark red and burnt orange, faint dust. A few distant tiny planets. Leave the centre calm and dark, because UI sits on it. No stars (the game adds sparkles). |
| 2 | `land-other.png`, `land-you.png`, `land-leader.png` | 512 × 512, 3 files | A player's land: umber for everyone else, orange for you, a yellow rim for the leader | A perfectly round space station cross-section filling the frame: a thick rim, inside it a few simple rooms, ladders and corridors drawn as flat shapes in darker tones of [umber / orange / umber with a yellow rim]. Small round nubs on the rim. Calm and readable when shrunk to 80 px. |
| 3 | `ship-you.png`, `ship-{1..6}.png` | 256 × 256, 7 files | Your ship (orange) and six classmate ships (muted umber tones, each a different body shape so players differ by shape, not colour) | A small chunky spaceship seen from above, nose to the right, rounded body in [orange / muted umber], a glass bubble cockpit, two stubby wings, a soft engine glow at the back. Friendly, not military. |
| 4 | `rock-{1..4}.png` | 256 × 256, 4 files | Drifting asteroids and crystals | A floating space rock made of a few faceted low-poly planes drawn as thin red wireframe lines over a translucent dark red fill, low-poly. Four different shapes. |
| 5 | `planet-{1,2}.png` | 512 × 512, 2 files | Large background planets | A round planet with flat bands or blob patches in burnt orange and red tones, with a faint glow ring. One ringed, one plain. |
| 6 | `icon-shield.png` | 512 × 512 | The Shield card's picture | A round glowing force-field bubble with a hexagon pattern, cool blue and white, with small sparkles. |
| 7 | `icon-strike.png` | 512 × 512 | The Strike card's picture | A bright laser beam bolt shooting diagonally, white core with a lime #b6f03c glow, with a few star sparkles. Playful, not a weapon. |
| 8 | `fx-hit.png` | 512 × 512 | What appears where a laser lands | A burst of star-shaped sparkles and small rings in lime and white, radiating from the centre. Celebratory and cartoonish, not an explosion: no fire, no smoke, no debris. |
| 9 | `fx-shield-pop.png` | 512 × 512 | A shield blocking a strike | A cool blue force-field bubble cracking into a few rounded shards, with sparkles. |
| 10 | `crown.png` | 256 × 256 | The winner's crown | A chunky cartoon crown in yellow #ffe05a with a small orange gem and a soft glow. |

## Notes

- **One hero:** only you are orange. Classmates differ by ship shape and name tag, not by colour.
- **Check at real size:** land discs show at 60 to 220 px, ships at about 70 px, rocks at 20 to 120 px. If a detail vanishes at that size, ask for a simpler version.
- **No violence:** the hit burst and the strike icon must read as sparkly and playful (see the airstrike concern in the decision log).
