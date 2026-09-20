# Ready Queue

A self-test quiz for an Operating Systems course. 52 multiple-choice questions from three real quizzes, with every answer checked against the Chapter 1 and Chapter 3 course slides (Silberschatz, Operating System Concepts, 10th ed.).

## Run it

It is a single static file with no build step and no dependencies. Open `index.html` in a browser.

## Decks

| Deck | Questions |
| --- | --- |
| Dr. Haifa, Quiz 1 | 5 |
| Quiz 1, Set 2 | 16 |
| Dr. Sohail, Summer 2024 | 31 |
| Full Queue (all three) | 52 |

Your best score per deck is saved in the browser's `localStorage`, on that device only.

## Notes

- Questions and answers live in the `FILE1`, `FILE2` and `FILE3` data near the top of the `<script>` in `index.html`. Each question has `q`, `options`, `correct` (the index of the right option), and an optional `note`. Slide references are in the `REFS` table below the data.
- The questions came from screenshots of student attempts, not an official answer key, so the answers were re-derived from the slides. Three picks in the screenshots were changed: the fork() output question (Haifa, Q5), the process control block question (Set 2, Q2) and the device controller question (Set 2, Q13).
- A few answers are not on the supplied slides (firmware, and shared memory vs message passing). Those are marked "Not on the slides" and rely on the textbook.
- Fonts (IBM Plex Sans and Mono) load from Google Fonts, with system fallbacks if offline.
