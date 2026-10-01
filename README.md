# Counterpoint Sudoku

A browser game for practising Fux-style species counterpoint (species 1–4).

1. Pick a species.
2. Pick a cantus firmus (Fux's six modal canti plus a few short ones) and whether the counterpoint goes above or below.
3. Fill one note into each empty beat. Every note is checked immediately:
   green = correct, amber = allowed but weak style, red = breaks a rule, blue = depends on the next note.

It checks consonance/dissonance, passing and neighbour tones, the cambiata, suspensions (7–6, 4–3, 2–3),
parallel and direct 5ths/octaves, melodic leaps, openings and cadences (with the raised leading tone).
Below the grid, the counterpoint is drawn in staff notation (VexFlow), with each note coloured the same way.

Game layer: points (with streak bonuses), a mistakes counter, a timer, 1–3 stars per puzzle, ranks from Choirboy to Palestrina Reborn, a trophy shelf saved in the browser, a joke when you break a rule, and a win screen with a GIF, a classical-music joke and confetti.

"Show safe notes" marks the pitches that won't add an error. "Play" plays both voices.

It's a single `index.html` with no build step. Open it in a browser, or turn on GitHub Pages for this branch.
