# Runway

A Game Boy–style browser game about the cost of not choosing.

Runway is an interactive design-research prototype exploring how young people
navigate options paralysis and fear-based decision-making during the transition
into open-ended adult life. The core mechanic is **finitude**: you have a finite
budget of weeks, spending is never refunded, and dithering is taxed — so the felt
weight of a big commitment is built into play rather than described.

Players explore a plaza of career paths (Medicine, Building/software, Sound/music,
Research). Each path runs on a fidelity ladder — **glimpse → micro-trial → deep dive
→ commit** — and the bigger rungs drop you inside the profession's own building to
actually do the work:

- **Hospital** — ESI triage; a night shift where more patients destabilize than
  one person can reach.
- **The Garage** — hunt the broken line and ship; fix a bug cascade against a demo clock.
- **The Studio** — program a beat on a step sequencer; mix it until it sits in the pocket.
- **The Lab** — an experiment that won't replicate (change one variable at a time);
  the long question, where a signal only emerges after many noisy trials.

Committing to a path closes the others and opens your real next steps along the road.

## Run it

It's a single self-contained HTML file — no build step, no dependencies.

- Double-click `runway-gb.html` to open it in any modern browser, **or**
- Rename it to `index.html` and enable GitHub Pages for a live playable link.

## Controls

- **WASD / arrow keys** — move
- **SPACE** — interact / advance dialogue (walk into the LIFE door to enter the plaza)
- **B** — bag (keepsakes you collect along each path)
- **ESC** — pause / restart
- In tasks: **P** play, **ENTER** lock/confirm

## Status

Working prototype, actively iterating. Known rough edges: placeholder block-figure
sprites, no hard world boundaries, and deliberately simple turn-based task mechanics.

## Background

Part of an independent design-research project ("Lost") studying identity development
and decision-making in the transition into college and adult life. Grounded in
Acceptance & Commitment Therapy, Self-Determination Theory, Marcia's identity-status
model, peak–end memory theory, and regret-asymmetry research.
