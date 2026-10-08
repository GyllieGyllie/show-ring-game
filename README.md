# Show Ring

Build a show-jumping course in 2D, then ride it in first-person 3D.

**Play:** open the GitHub Pages link for this repository (Settings → Pages).

## Build
- Set the arena width and length.
- Add verticals, oxers, triple bars, walls and liverpools.
- Drag a fence to move it, and drag its gold handle to turn it. Set height, rail length, spread and colour, and change the jumping order.
- The dashed riding line shows the distance and stride count between fences, plus the course length and time allowed (350 m/min).
- Courses save automatically in your browser.

## Ride
- The horse follows the line. Hold + / − (or ↑ / ↓) to change pace.
- Tap the view, the Jump button or Space to take off.
- Bad timing knocks rails, and you see them fall in slow motion.
- Scoring: 4 faults per knockdown or refusal, eliminated on the second refusal, and 1 time fault per started second over the time allowed.
- **Watch a round** lets the computer ride the course.

Works on desktop and mobile (hold the phone sideways for riding).

Single static page: `index.html` + `vendor/` (three.js r157, htm/Preact). No build step.
