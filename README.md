# Perplexity Stock Pitch Competition — April 2026

**Ticker:** CRDO (Credo Technology Group, NASDAQ)
**Competition:** Perplexity Stock Pitch Competition (March 30 – April 2026)
**Prize Pool:** Up to $17,500
**Judges:** Philippe Laffont (Coatue), Dan Loeb (Third Point), Ken Hao (Silver Lake)

---

## Thesis in One Sentence

Credo Technology Group is the only commercially validated 224G SerDes AEC stack at hyperscale — every NVL72-class AI factory rack must use its technology — trading at a 41.5% discount to peers with a binary catalyst on June 2, 2026.

---

## The Pitch

**Long CRDO. Base case $181. +78% upside. Entry at $101.45.**

Bear / Base / Bull: $71 / $181 / $358. June 2 Q4 FY2026 earnings is the binary event. Options IV at the 33rd percentile — historically cheap for the magnitude of the catalyst.

The non-consensus insight: CRDO is not a semiconductor company. It is the owner of the only commercially validated Active Electrical Cable (AEC) IP stack for 224G SerDes at scale — making it the mandatory toll gate for any AI cluster scaling beyond 400G interconnect. Every NVL72 rack, every TPU pod, every custom Trainium cluster at 800G or higher requires Credo's retimer and AEC technology. The moat is IP-plus-yield: 100+ patents, ITC enforced, 4+ year hyperscaler qualification head start. A competitor starting today cannot reach production volume before 2029.

---

## Why This Pitch, Why This Stock

CRDO was selected from a universe of 59 companies across 7 AI transformation categories. It scored highest (8.43/10) on a 7-dimension comparative matrix, winning specifically on:

- **Non-consensus advantage (9/10):** Coatue, Citadel, and Tiger all own NVDA. CRDO's AEC/SerDes IP moat requires understanding 224G signal integrity physics — a technical depth standard institutional research cannot reach.
- **Valuation vs. opportunity (9/10):** 8.6x NTM EV/Revenue vs. peer median 14.7x, at +90% NTM revenue growth vs. peer median +32%.
- **Data advantage (9/10):** IEEE patents, hyperscaler procurement benchmarks, and DesignCon technical filings — uniquely accessible through Perplexity's premium data sources.

NVIDIA scored highest overall (8.80/10) but was rejected for the pitch: every judge in the room already owns it and knows the thesis better than any presentation can explain. CRDO is the non-obvious answer.

---

## Financial Snapshot (as of April 2, 2026)

| Metric | Value |
|---|---|
| Current price | $101.45 |
| Revenue Q3 FY2026 | $407M (+1,169% over 9 quarters) |
| Gross margin | 68.5% (record high) |
| Net cash | $1.29B |
| Guidance beat rate | 10/11 quarters (83%) |
| EV/NTM Revenue | 8.6x vs. peer median 14.7x |
| Analyst consensus | 15 Buy / 2 Hold / 0 Sell · $200 median PT |
| Hyperscaler customers | 5 (AWS, Microsoft, xAI, Google, Meta) |

---

## Workflow Architecture

This project was designed in Claude Code and executed inside **Perplexity Computer**. The final submission is a Perplexity-native web application — the methodology is visible inside the artifact itself.

### Stage Map

| Stage | Folder | Task | Perplexity Capability |
|---|---|---|---|
| 1 | [stage_01_history/](stage_01_history/) | Civilizational history & tech paradigm shifts | 4 parallel sub-agents · 118 sources · Statista, Goldman Sachs, NBER |
| 2 | [stage_02_universe/](stage_02_universe/) | AI infrastructure stock universe across 5 tiers | 7 parallel sub-agents (one per AI category) · 59 companies · CB Insights, PitchBook |
| 3 | [stage_03_comparative/](stage_03_comparative/) | 7-dimension comparative → CRDO selection | 5 parallel sub-agents · scoring matrix · CB Insights, PitchBook |
| 4 | [stage_04_deepdive/](stage_04_deepdive/) | CRDO deep dive: business, financials, alt data | 4 parallel sub-agents · SEC EDGAR, FactSet, IEEE Patents, LinkedIn |
| 5 | [stage_05_financials/](stage_05_financials/) | DCF, trading comps, sensitivity, catalyst calendar | FactSet, S&P Global, PitchBook |
| 6 | [stage_06_model_council/](stage_06_model_council/) | Model Council stress test: 3 models × 5 questions | GPT-5.4 + Claude Opus 4.6 + Gemini 3.1 Pro |
| 7 | [stage_07_pre_submission/](stage_07_pre_submission/) | First-pass submission web apps (audited, superseded) | Full Perplexity Computer orchestration |
| — | [FINAL_SUBMISSION/](FINAL_SUBMISSION/) | **Rebuilt, rubric-verified final deliverables** | Rebuilt from scratch with all 8 chapters + Panel 6 process showcase |

---

## Final Submission

Three deliverables in [FINAL_SUBMISSION/](FINAL_SUBMISSION/) plus a video:

| File | Purpose | Rubric Score (est.) |
|---|---|---|
| `CRDO_Investment_Thesis.html` | Full 8-chapter interactive thesis | ~94/100 |
| `CRDO_Concise_2min.html` | 6-panel 2-minute video companion | ~83/100 |
| `Perplexity Computer Competition video submission.mp4` | Video walkthrough of the submission | — |

Both HTML files submitted in a single Perplexity Computer thread — the thread itself is the submission, demonstrating multi-turn iterative research.

### Eight Chapters (Full Thesis)

1. **The World Before the Answer** — 6 tech eras, 9:1 AI CapEx/revenue ratio, "We are in 1996"
2. **Locating the Opportunity** — 59-company bubble chart, 5 risk/reward tiers
3. **The Comparative Analysis** — 7-dimension matrix, 5 finalists, CRDO wins at 8.43/10
4. **The Company** — 3-pillar moat, 5 hyperscaler customers, qualification timeline, hiring signals
5. **The Financial Case** — Bear/Base/Bull DCF, interactive slider, sensitivity heatmap, June 2 catalyst
6. **The Stress Test** — Model Council: 3 models × 5 questions, Q1–Q5 navigator, Dan Loeb question reveal
7. **The Recommendation** — Judge-specific conviction pillars, 3 risk cards with exit signals
8. **How This Was Built** — SVG workflow diagram, 8-task log, 3 discoveries, manual vs. Perplexity comparison

---

## Key Files

| File | Purpose |
|---|---|
| [CLAUDE.md](CLAUDE.md) | Master project briefing and submission architecture |
| [THESIS_FRAMEWORK.md](THESIS_FRAMEWORK.md) | Intellectual architecture of the pitch |
| [JUDGES.md](JUDGES.md) | Deep profiles on Laffont, Loeb, and Hao |
| [PERPLEXITY_TASKS.md](PERPLEXITY_TASKS.md) | Original Perplexity Computer task sequence |
| [SUBMISSION_PROMPTS.md](SUBMISSION_PROMPTS.md) | Final ready-to-paste prompts used for the rebuilt submission |
| [all_project_threads.md](all_project_threads.md) | Perplexity Computer thread links |
| [github_repo_link.md](github_repo_link.md) | Link to this GitHub repository |
| [workflow_viz.html](workflow_viz.html) | Screenshare-ready Claude Code pipeline visualization |
