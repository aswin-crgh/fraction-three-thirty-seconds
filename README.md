# What fraction of the whole square is striped?

An interactive, narrated applet (browser text-to-speech, Indian English) that solves the striped-square problem by nesting:
whole square → little square (1/4) → triangle or rectangle (1/8) → tiny triangles (1/32), arriving at **3/32**.

- Single self-contained `index.html` — no build, no dependencies.
- Works in landscape (figure left, panel right) and portrait / phone (figure on top, panel below); rotating rebuilds the current step.
- ‹ › arrows (or ← → keys) revisit earlier steps; a revisited step holds until you move on.
- Two valid routes: the slanted or the vertical half-line of the little square.

Test helpers: `?mute`, `?speed=3`, `?auto` (answers correctly), `?auto=vert` (takes the vertical route).
