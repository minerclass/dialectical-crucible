# The Dialectical Crucible

A short browser game about what holds an argument up. You build a three-level argument tower under a fixed energy budget, cap it with a thesis, and then watch objections test it. Pillars you built by hand stay standing. Gold-clad AI shortcuts cost nothing and shear away.

Allow about ten minutes. Written for grades 9-12 and for teacher professional learning.

Play it at <https://minerclass.github.io/dialectical-crucible/>.

## How it works

- **Three levels.** Primary evidence at the foundation, warrants and logic above it, counter-claims and rebuttals at the top.
- **A budget of six energy.** Each level has two pillars. A stone pillar costs 2 energy and a gold pillar costs 0. Cross-bracing a level costs 1.
- **Three meters.** Authorship, Stability, and Friction change as you build.
- **A prediction before the test.** You forecast how many of the six pillars will crack. Keys 0-6 select the forecast.
- **A debrief.** The evaluation report compares your forecast with the result, analyses each pillar, and can be printed.

## Run it locally

Open `index.html` in a current browser. There is no build step, framework, package manager, or account. The page links one shared stylesheet, `https://minerclass.github.io/tokens.css`, and falls back to its own colours when that file is unavailable.

## Conceptual grounding

Pedagogical friction, productive and exclusionary friction, and unproductive success as used here come from the framework Micah Miner is developing in his dissertation research. They are presented as proposals in progress, not as established terms or completed findings.

"Existential authorship" in the game refers to the existential dimension of that framework, the question of whose thinking the work carries.

## What this does not claim

- All scores, stats, and achievements are illustrative models of the pedagogical friction framework, not validated learning assessment instruments.
- The students in the game are fictional design profiles. They are not participants and do not represent real learners.
- Nothing here calls an AI service. The "AI" choices are scripted teaching examples.
- The game does not measure learning, does not evidence any dissertation claim, and reports no findings.
- No participant, student, or staff data is used, collected, stored, or transmitted.

## Accessibility

The layout adapts to phone widths under 480px. Animation respects the system reduced-motion setting. A contrast check on September 1, 2026 found no failures, with the tightest pair at 6.66. Keyboard operation of the building controls has not been audited.

## Implementation

Everything lives in one file, `index.html`, with inline CSS and JavaScript. The tower is drawn in SVG. GitHub Pages publishes from `main` through `.github/workflows/pages.yml`.

## Logs

`BUILD_LOG.md` records how the game was built and what was verified. `AGENT_LOG.md` is an append-only record of agent-assisted changes. Neither file holds participant data, credentials, or tokens.

## Related

- Games hub: <https://minerclass.github.io/games-hub/>
- Dissertation overview: <https://minerclass.github.io/dissertation-overview/>
