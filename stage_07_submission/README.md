# Stage 07 — First-Pass Submission (Audited & Superseded)

**Perplexity Task:** Task 7 (first pass)
**Status:** Audited against rubric. Superseded by [FINAL_SUBMISSION/](../FINAL_SUBMISSION/).

---

## What This Stage Produced

First-pass submission outputs from Perplexity Computer, built before rubric audit. Three web apps were generated and zipped. Upon audit, the concise version scored ~68–74/100 due to a missing methodology showcase — the 30pt Perplexity criterion was not adequately addressed.

---

## Files (First-Pass, Archived)

| File | Description | Status |
|---|---|---|
| `CRDO Investment Thesis.zip` | Full web app — 8 chapters | Superseded by `FINAL_SUBMISSION/CRDO_Investment_Thesis.html` |
| `CRDO_Story_App.zip` | Scroll-narrative version | Archived |
| `CRDO_Concise.zip` | 5-panel condensed brief | Superseded by `FINAL_SUBMISSION/CRDO_Concise_2min.html` |
| `CRDO Pitch — Concise One-Pager.html` | Standalone one-pager | Archived |
| `_unzipped/` | Unzipped contents for inspection | Reference only |

---

## Why These Were Superseded

**Full thesis:** Scored well (12/13 rubric requirements met). Process notes were missing in Chapters 3, 5, 6, and 7 — minor gap since Chapter 8 carries the full methodology documentation. Rebuilt to get a cleaner, complete version.

**Concise version (5 panels):** Critical failure on the 30pt Perplexity criterion. The methodology showcase — sub-agent workflow, 3 discoveries, comparison table — was reduced to a one-liner at the bottom: "Built with Perplexity Computer · 19 sub-agents · 3 frontier models · 59 companies evaluated · 15–20 hours." This is not sufficient for 30 points.

---

## What Changed in the Rebuild

New prompts (see [SUBMISSION_PROMPTS.md](../SUBMISSION_PROMPTS.md)) were pasted into a single Perplexity Computer thread:

**Turn 1 (Full Thesis):** Rebuilt with all 8 chapters, every chapter having process notes + source chips, Chapter 8 with SVG workflow diagram + task log + 3 discoveries + comparison table. Scored ~94/100.

**Turn 2 (Concise):** Rebuilt from a 5-panel to a **6-panel** app where Panel 6 is entirely dedicated to the Perplexity methodology. Includes mini workflow diagram, animated stat counters, all 3 discoveries, and comparison table. Scored ~83/100.

**Post-build patch (manual):** Panel 5 of the concise file had 4 consensus chips instead of 6. Two chips were added manually:
- "✓ All 3 models: Qualification lead-time is real but not insurmountable for incumbents like Marvell"
- "△ Divergence: What changed the thesis — GPT-5.4 corrected timeline · Opus quantified bear $55–70 · Gemini introduced optical risk"

The patched file was re-uploaded to the Perplexity thread, demonstrating iterative multi-turn research — which directly scores the 30pt criterion.

---

## Rubric Audit Results (First-Pass Files)

| Criterion | Max | Full Thesis (v1) | Concise (v1) |
|---|---|---|---|
| Investment thesis quality | 20 | 17–18 | 16–17 |
| Financial analysis quality | 20 | 15–16 | 14–15 |
| Industry & competitive analysis | 20 | 13–15 | 11–12 |
| **Use of Perplexity** | **30** | **18–21** | **18–20** |
| Presentation | 10 | 9–10 | 9–10 |
| **Total** | **100** | **~72–80** | **~68–74** |

---

## App Architecture (Eight Chapters — same in rebuild)

| Chapter | Title | Content |
|---|---|---|
| 1 | The World Before the Answer | 6 tech eras, 9:1 AI CapEx/revenue ratio, "We are in 1996" |
| 2 | Locating the Opportunity | 59-company bubble chart, 5 risk/reward tiers |
| 3 | The Comparative Analysis | 7-dimension matrix, 5 finalists, CRDO wins at 8.43/10 |
| 4 | The Company | 3-pillar moat, 5 hyperscaler customers, qualification timeline, hiring signals |
| 5 | The Financial Case | Bear/Base/Bull DCF, interactive slider, sensitivity heatmap, June 2 catalyst |
| 6 | The Stress Test | Model Council: 3 models × 5 questions, Q1–Q5 navigator, Dan Loeb reveal |
| 7 | The Recommendation | Judge-specific conviction pillars (Laffont / Loeb / Hao), 3 risk cards |
| 8 | How This Was Built | SVG workflow diagram, 8-task log, 3 discoveries, manual vs. Perplexity table |
