# Growth For Impact — Resume Screening Prototype

A single-page web app that **scores and ranks resumes against real job descriptions**, built as a screening prototype for Growth For Impact.

## What it does

- Loads a dataset of **47 real resumes** (`data.json`) and evaluates every candidate against two live roles:
  - **JD1 — Life Cycle Assessment (LCA) Consultant** (2–3+ yrs, GaBi/SimaPro, ISO 14040/14044)
  - **JD2 — UI/UX Design Intern** (0–1 yr, Figma, user research, prototyping)
- Applies a transparent scoring model per job description and produces a ranked shortlist per role.
- Runs entirely in the browser — no backend, no build step.

## Run it

```bash
# any static server works, for example:
npx serve .
# then open the served URL in a browser
```

Opening `index.html` directly also works in most browsers.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The complete app — UI, scoring logic and ranking views |
| `data.json` | Resume dataset and scoring metadata (47 resumes, generated 2026-11-13) |

## Note

This is a **prototype** built for evaluation: the dataset is a fixed snapshot and the scoring is a rules-based model, not a trained ML ranker.
