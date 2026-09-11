# The Yard

An early-stage education venture exploring AI-assisted expert mentorship for young learners.

- Product and venture page: https://henryatharvard.github.io/theyard/
- Venture brief: [venture-brief.md](venture-brief.md)
- Original campus/brand concept: https://henryatharvard.github.io/theyard/vision.html
- Naming comparison: https://henryatharvard.github.io/theyard/names.html

## Product prototype

The homepage includes three connected local demo views: a student submits practice, a mentor assigns the next task, and a parent sees the activity sequence. There are no accounts, network writes, stored learner records, or live AI. Reset restores the prepared sample.

An interactive pilot model exposes assumptions about cohort size, price, mentor preparation, and delivery costs. Proposed program details, economics, and outcomes are hypotheses. The page does not enroll learners or collect payments.

## Run

Open `index.html` directly, or run `python -m http.server 8766 --bind 127.0.0.1` and visit `http://localhost:8766/`. Serve the complete repository so the local images and downloadable brief are available. There is no package installation or build step. GitHub Pages publishes `main` from `/`; `.nojekyll` disables Jekyll processing.

## Brand exploration

`vision.html` preserves the initial illustration-led landing page and its nine downloadable activities. `names.html` previews that concept as The Yard, The Grove, The Commons, Longview, Openfield, or Wonder & Work. These are working names, not cleared brands. Initial research found existing uses of The Yard.

Original illustrations were generated with the built-in imagegen tool. Assets and prompts are documented in [ARTWORK.md](ARTWORK.md).

## Validation

The initial brand concept was checked in Chrome on phone, tablet, and desktop, including all activities, name variants, and downloads. The revised product page is checked for responsive layout, the student-to-mentor-to-parent workflow, keyboard tab navigation, reset behavior, form validation, and pilot economics calculations. Live publication is checked against committed files and exercised in Chrome.
