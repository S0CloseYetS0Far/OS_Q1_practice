# Ready Queue

A self-test quiz for an Operating Systems course. 50 multiple-choice questions from three real quizzes, each answer re-checked against standard OS material.

## Run it

It is a single static file with no build step and no dependencies. Open `index.html` in a browser.

## Decks

| Deck | Questions |
| --- | --- |
| Dr. Haifa, Quiz 1 | 5 |
| Quiz 1, Set 2 | 16 |
| Dr. Sohail, Summer 2024 | 29 |
| Full Queue (all three) | 50 |

Your best score per deck is saved in the browser's `localStorage`, on that device only.

## Notes

- Questions and answers live in the `DECKS` data near the top of the `<script>` in `index.html`. Each question has `q`, `options`, `correct` (the index of the right option), and an optional `note`.
- One answer was corrected from the original student attempt: the device-controller question in Set 2, where "All of the mentioned" includes a false claim (data is copied to main memory, not ROM).
- Fonts (IBM Plex Sans and Mono) load from Google Fonts, with system fallbacks if offline.
