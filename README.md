# Runway

A Game Boy–style browser game about starting somewhere without having it all figured out.

Runway is an interactive design-research prototype exploring how young people navigate
options paralysis and fear-based decision-making in the transition into open-ended adult
life. It holds two ideas together:

- **Time is finite.** Weeks spend, nothing refunds, and you cannot try everything.
- **Choosing is not permanent.** Picking a direction is a starting point, not a cage.

The second idea is what makes the first survivable. The game taxes *dithering*, not
*switching* — grounded in regret-asymmetry research, where inaction tends to generate
more long-run regret than action.

## Act I — the plaza

Four paths (Medicine, Building, Sound, Research), each on a fidelity ladder:
**glimpse → micro-trial → deep dive → start**. Glimpses are cheap signs. The trials put
you inside the profession's own building to do the actual work:

| Building | Micro-trial | Deep dive |
|---|---|---|
| Hospital | ESI triage — drag patient cards into acuity bins | Night shift — four patients, one of you, a clock |
| The Garage | Type the corrected line of broken code | Ship the demo against a countdown |
| The Studio | Program a beat on a step sequencer | Mix it until it sits in the pocket |
| The Lab | An experiment that won't replicate — change one variable at a time | The long question — run trials until a signal emerges |

## Act II — the work

Starting a path opens the second act rather than ending the game. You work a week of the
*actual* job — allocating too few hours across patients/features/experiments, admin, and
the people who love you — then reach a crossroads: **go deeper** (specialize), **go
sideways** (switch industries), or **stay**. Switching costs real time but carries your
skills with you, visibly. The game ends on a retrospective that draws your path as a line
and observes that it isn't straight, and that almost nobody's is.

## Run it

Single self-contained HTML file — no build step, no dependencies.
Open `index.html` in any modern browser, or serve it via GitHub Pages for a playable link.

## Controls

- **WASD / arrows** — move
- **SPACE** — interact and advance dialogue (walk into the LIFE door to begin)
- **Mouse** — drag and click inside tasks; **typing** for the debugging task
- **B** — bag · **ESC** — pause / restart

## Status

Working prototype, actively iterating. Known rough edges: placeholder block-figure sprites,
no hard world boundaries, and a day/night cycle that is currently a tint rather than a full
palette swap.

## Background

Part of an independent design-research project studying identity development and
decision-making in emerging adulthood. Grounded in Acceptance & Commitment Therapy,
Self-Determination Theory, Marcia's identity-status model, peak–end memory theory, and
regret-asymmetry research.
