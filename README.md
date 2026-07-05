# GMAT Focus 2025–26 — Prep Hub (hostable bundle)

Self-contained website with no external dependencies. Works fully offline. `index.html` is the home page.

## Files

| File | Purpose |
|---|---|
| `index.html` | Landing hub — section overview + progress bars |
| `GMAT_Quant.html` | **Quantitative Review** — 33 topics, OG Ch. 3 complete coverage |
| `GMAT_DI.html` | **Data Insights Review** — 19 topics, charts + DS strategy + all 5 DI question types |
| `GMAT_Verbal.html` | **Verbal Review** — 20 topics, all RC & CR question families + argument analyzer |
| `GMAT_Concepts.html` | Original 28-topic combined concept tutor (still works; now also links to new section pages) |
| `GMAT_Practice.html` | **Timed Practice** — 798 official questions, timer, error log with "why likely wrong" analysis |
| `GMAT_Planner.html` | **Study Planner & Tracker** — exam-date setup, phased week-by-week plan (30% fundamentals / 40% practice / 30% mocks), 6 GMAC mock scheduling, daily study log, accuracy traffic lights, mock score trend & "ready to book" alert. Dark-mode friendly. |
| `GMAT_Review_Handbook.pdf` | 12-page concept handbook |
| `GMAT_Cheat_Sheet.pdf` | 5-page formula cheat sheet |

## What's in each section tutor

### GMAT_Quant.html — 33 topics
- **Number Theory**: Integers & divisibility, GCF/LCM, Primes, Fractions, Decimals, Percents, Exponents, Ratios
- **Algebra**: Expressions, Linear equations, Systems, Quadratics, Inequalities, Absolute value, Functions
- **Coordinate Geometry**: Distance & midpoint, Lines & slope
- **Euclidean Geometry**: Triangles, Quadrilaterals, Circles, 3D Solids
- **Word Problems**: Rate/Time/Distance, Work, Mixtures, Interest/Profit, Sequences
- **Statistics & Counting**: Mean/Median/SD, Counting methods, Probability

Each topic: concept explanation · key formulas · GMAT tips · common traps · interactive tool · worked examples · flashcards.

### GMAT_DI.html — 19 topics
- **Reading Data**: Data types, Tables, Bar charts, Histograms, Line graphs, Scatterplots, Pie charts
- **Interpreting Data**: Descriptive stats, Distributions, Correlation vs causation, Common traps
- **Data Sufficiency**: DS format & the 5 choices (with visual decision tree), DS strategy, DS traps
- **DI Question Types**: Multi-Source Reasoning, Table Analysis, Graphics Interpretation, Two-Part Analysis

Includes: DS decision tree diagram, interactive bar/histogram/scatterplot demos.

### GMAT_Verbal.html — 20 topics
- **Reading Comprehension**: Passage types, Active reading strategy, Main idea, Detail, Inference, Application, Evaluation, Wrong-answer traps
- **Critical Reasoning**: Anatomy of an argument, Claim types, Assumption questions, Strengthen, Weaken, Must-Be-True, Explain a Discrepancy, Flaw/Boldface/Evaluate, Universal CR strategy

Includes: interactive argument analyzer, premise/conclusion cue-word reference, all 8 CR question type cards.

## Practice app enhancements

- **Question pool modes**: Default is the **full question bank**. Optional modes: *Unseen only* (skip attempted questions) and *Review: mistakes & flagged* (a dedicated review mode). Questions whose figure/diagram wasn't captured from the printed book are skipped by default (uncheck to include them with an in-quiz notice pointing to the OG question number).
- **Timer**: Shows `Q X/Y · this Q: MM:SS` and total time remaining. Turns red at 2 minutes remaining (was 1 minute). Auto-ends session when time expires.
- **Error log**: Each mistake now shows a **"Why likely wrong"** panel with question-type-specific traps and likely error patterns (adjacent-answer slips, C-trap for DS, opposite-direction for CR, out-of-scope for RC, etc.).
- **Results review**: Same "why likely wrong" analysis appears on every incorrect answer in the post-session review.
- **Section links**: Quick-access buttons to Quant/DI/Verbal review tutors from the practice home page.

## How to host

### GitHub Pages
1. Create a repository and upload the contents of this folder.
2. Settings → Pages → deploy from `main` branch, root folder.
3. Site appears at `https://<username>.github.io/<repo>/`.

### Netlify Drop
1. Go to https://app.netlify.com/drop
2. Drag the entire `gmat-prep-site` folder onto the page.
3. Get a live link instantly.

### Local
Open `index.html` directly in any browser — everything works offline.

## Progress & privacy notes
- Progress (learned topics, error log, session scores) saves in the browser's localStorage on the current device. Does NOT sync between devices.
- Practice questions, answer keys, and explanations are from the GMAT Official Guide 2025–2026 (© GMAC). Keep for personal use — do not publish on a public URL.
- Three DI question types (Graphics Interpretation, Multi-Source Reasoning, Table Analysis) are online-only and not in the printed book; practice those at mba.com.
