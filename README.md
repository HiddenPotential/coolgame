# 😡 Wacky Rage Golf

Three courses of pixel-art 3D mini golf, nine holes each. Every single hole is out to get you.

Pick a course on the course map (🗺️):

- 🌳 **Meadow Links**: green grass, ponds, and a hand that lives in the cup.
- 🌵 **Dune Desert**: quicksand, cactus bumpers, camels crossing, vultures, sandstorms, mirage cups and a sinkhole.
- 🌙 **Moon Base**: low gravity (lobs float, things roll further), black holes that suck your ball in, asteroids, the space void, and the UFO is home.

A minimap in the corner shows the whole hole. The holes of Meadow Links:

| # | Hole | What it does to you |
| --- | --- | --- |
| 1 | Free Hole-in-One | A short, straight putt. It goes in, you get confetti, and then a hand comes out of the cup and throws it back. |
| 2 | Shy Cup | The cup runs away from your ball (until it gets tired). |
| 3 | Closed for Lunch | A lid slams over the cup on slow putts. Hit it firmly. |
| 4 | Breezy Point | "Wind: 0 mph." A sudden gust blows your ball away from the cup, sometimes into the water. |
| 5 | Crow's Nest | Leave your ball near the cup and a bird grabs it and drops it in a sand trap (or the pond). |
| 6 | Pick a Cup | Three cups, two trapdoors. Fall in a fake and you go back to the tee and the cups shuffle. |
| 7 | Whack-a-Mole | Someone lives in the cup and pops up to swat your ball away. |
| 8 | Moving Day | "Pin position updated." The hole moves when you get close. |
| 9 | The Final Insult | A UFO beams your ball out of the cup and flies it back to the tee. Plus wind. Plus the bird. |

On top of these, the desert and moon add **VAR review**, which watches your putt go in and then disallows it.

And on every hole, on every course, **the ground crumbles**. Weak spots are hidden all over the course and look exactly like normal ground.
Bits of the course crack and fall away on their own, sometimes the ground cracks as you roll over it, and if your item stops on a weak spot
(or near the cup, where it's most annoying) the ground starts shaking under it: you have about a second to hit it out of there.
Fall into a hole and it's +1 stroke, back to where you hit from. A wedge lob flies over holes. The tee and the cups never crumble.

On top of that, every hole has two more surprises, once each:
- **Teeter:** stop right next to the cup and the ball creeps up to the lip, wobbles with a drumroll... and rolls back out.
- **Sloped green:** stop close to the cup and the green turns out to slope back toward where you hit from.

No two rounds play the same: every time a hole loads it secretly adds a random extra troll or two (wind, the eagle,
a cup that moves, the hand, the mole, the lid, VAR or the UFO), and usually rolls a random condition, shown on the
intro card and next to the hole name: 🧊 icy green, 🍯 sticky green, 🏀 bouncy walls, 🫨 shaky hands, 🎲 random power,
🌬️ a steady breeze or 😵 hiccups. The intro hints whether something extra is hiding. It doesn't always tell the truth.

Slide past the cup and the crowd groans. The 🏳️ Give up button refuses to let you quit (and hops somewhere else),
and the score card counts how many times you tried.

Every troll has a limit, so every hole can be finished. There is no mercy rule: a hole doesn't end until the ball is in.
Each course has its own chiptune, made in the browser with Web Audio, that speeds up as your rage climbs and goes quiet while the ball teeters.
A rage meter tracks how it's going, and a commentator helps by telling you it's a skill issue (and gets meaner as the meter climbs).

You hit a real 3D golf ball with:

| Club | What it does |
| --- | --- |
| Putter | Gentle and accurate, for short putts |
| 7 Iron | The solid all-rounder |
| Wedge | Pops it up over water and sand |
| Driver | Huge power, a little wild |

## Play

Open `index.html` in a browser. No build step. The 3D view uses [three.js](https://threejs.org/) from a CDN, so you need an internet connection.

- Drag anywhere on the course to pull back and aim, then let go to swing.
- Keys `1`–`4` pick a club, `M` mutes everything, `N` (or 🎵) turns the music on and off, `Esc` cancels a shot, `C` (or 🎥) switches between the overview and a camera that follows the ball, `P` (or 👾) turns the pixel look on and off.
- Jump straight to a hole with `?course=moon&hole=5` (courses: `meadow`, `desert`, `moon`).
