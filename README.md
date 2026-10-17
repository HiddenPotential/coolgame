# 😡 Wacky Rage Golf

Three courses of pixel-art 3D mini golf, nine holes each. Every single hole is out to get you.

Pick a course on the course map (🗺️):

- 🌳 **Meadow Links**: green grass, ponds, and a hand that lives in the cup.
- 🌵 **Dune Desert**: quicksand, cactus bumpers, camels crossing, vultures, sandstorms, mirage cups and a sinkhole.
- 🌙 **Moon Base**: low gravity (lobs float, things roll further), black holes that suck your item in, asteroids, the space void, and the UFO is home.

A minimap in the corner shows the whole hole. The holes of Meadow Links:

| # | Hole | What it does to you |
| --- | --- | --- |
| 1 | Free Hole-in-One | A short, straight putt. It goes in, you get confetti, and then a hand comes out of the cup and throws it back. |
| 2 | Shy Cup | The cup runs away from your item (until it gets tired). |
| 3 | Closed for Lunch | A lid slams over the cup on slow putts. Hit it firmly, with an egg. |
| 4 | Breezy Point | "Wind: 0 mph." A sudden gust blows your item away from the cup, sometimes into the water. |
| 5 | Crow's Nest | Leave your item near the cup and a bird grabs it and drops it in a sand trap (or the pond). |
| 6 | Pick a Cup | Three cups, two trapdoors. Fall in a fake and you go back to the tee and the cups shuffle. |
| 7 | Whack-a-Mole | Someone lives in the cup and pops up to swat your item away. |
| 8 | Moving Day | "Pin position updated." The hole moves when you get close. |
| 9 | The Final Insult | A UFO beams your item out of the cup and flies it back to the tee. Plus wind. Plus the bird. |

On top of these, the desert and moon add **VAR review**, which watches your putt go in and then disallows it.

Every troll has a limit, so every hole can be finished, and the mercy rule ends a hole at 12 strokes.
A rage meter tracks how it's going, and a commentator helps by telling you it's a skill issue.

You hit 3D models of a watermelon, orange, egg, coconut, bagel, jelly, pineapple, sock and pumpkin with:

| Club | What it does |
| --- | --- |
| Putter | Gentle and accurate, for short putts |
| 7 Iron | The solid all-rounder |
| Wedge | Pops it up over water and sand |
| Driver | Huge power, a little wild |

## Play

Open `index.html` in a browser. No build step. The 3D view uses [three.js](https://threejs.org/) from a CDN, so you need an internet connection.

- Drag anywhere on the course to pull back and aim, then let go to swing.
- Keys `1`–`4` pick a club, `M` mutes, `Esc` cancels a shot, `C` (or 🎥) switches between the overview and a camera that follows the item, `P` (or 👾) turns the pixel look on and off.
- Jump straight to a hole with `?course=moon&hole=5` (courses: `meadow`, `desert`, `moon`).
