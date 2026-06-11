# 036 — Sivam Nocab

**AppADay · Day 036 · June 12, 2026 · Category: G**

A browser-based typing tutor with a retro CRT phosphor-green aesthetic, inspired by classic typing trainers. Seven lesson tracks take you from basic home row drills through symbols and real sentences, with live WPM, accuracy, and a letter-grade on every run.

## Features

- 7 lesson tracks: Home Row, Top Row, Full Alpha, Numbers, Common Words, Sentences, Symbols
- Each lesson has 4 passages that cycle on completion
- Live WPM and accuracy update as you type
- Character-by-character feedback — green for correct, red for wrong
- S / A / B / C / D grading system on completion
- Best WPM and completion streak persisted via localStorage
- CRT scanline and phosphor flicker aesthetic
- Fully mobile-friendly, single-file, no dependencies

## How to Play

Select a lesson track, then start typing in the input field. The target text highlights your position as you go. Finish the passage to see your grade, WPM, accuracy, and time. Hit "Next Lesson" to advance.

## Grading

| Grade | Requirement |
|-------|-------------|
| S | ≥98% accuracy AND ≥60 WPM |
| A | ≥95% accuracy AND ≥45 WPM |
| B | ≥90% accuracy AND ≥30 WPM |
| C | ≥80% accuracy AND ≥20 WPM |
| D | Below C thresholds |

## Tech

Single-file vanilla HTML/CSS/JS. Google Fonts (Share Tech Mono, VT323). No frameworks, no build step.

[← AppADay Portfolio](https://augustineiacopelli.github.io/appaday/)
