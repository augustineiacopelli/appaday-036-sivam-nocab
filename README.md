# 036 — Sivam Nocab

**AppADay · Day 036 · June 12, 2026 · Category: G**

A browser-based typing tutor with a retro CRT phosphor-green aesthetic, inspired by classic typing trainers. Seven lesson tracks take you from basic home row drills through symbols and real sentences, with live WPM, accuracy, and a letter-grade on every run. Supports multiple local operator profiles, each with saved progress.

## Features

- 7 lesson tracks: Home Row, Top Row, Full Alpha, Numbers, Common Words, Sentences, Symbols
- Each lesson has 4 passages that cycle on completion
- Live WPM and accuracy update as you type
- Character-by-character feedback — green for correct, red for wrong
- S / A / B / C / D grading system on completion
- Operator login screen with multiple local profiles, each tracking its own best WPM, streak, and current lesson position
- Progress resumes automatically where each operator left off
- CRT scanline and phosphor flicker aesthetic
- Fully mobile-friendly, single-file, no dependencies

## How to Play

On launch, pick an existing operator or create a new one by entering a name. Select a lesson track, then start typing in the input field. The target text highlights your position as you go. Finish the passage to see your grade, WPM, accuracy, and time. Hit "Next Lesson" to advance. Your lesson position, best WPM, and streak are saved automatically. Use "Switch" in the header to log in as a different operator.

## Grading

| Grade | Requirement |
|-------|-------------|
| S | ≥98% accuracy AND ≥60 WPM |
| A | ≥95% accuracy AND ≥45 WPM |
| B | ≥90% accuracy AND ≥30 WPM |
| C | ≥80% accuracy AND ≥20 WPM |
| D | Below C thresholds |

## Profiles & Storage

Profiles are stored locally in the browser via localStorage — there is no account system or server. Each device/browser maintains its own set of profiles, so progress won't sync across devices.

## Tech

Single-file vanilla HTML/CSS/JS. Google Fonts (Share Tech Mono, VT323). No frameworks, no build step.

[← AppADay Portfolio](https://augustineiacopelli.github.io/appaday/)
