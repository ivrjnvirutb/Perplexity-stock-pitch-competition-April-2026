# Perplexity Stock Pitch Competition — April 2026

**Ticker:** CRDO (Credo Technology Group)  
**Competition:** Perplexity Stock Pitch Competition (March 30 – April 2026)  
**Prize Pool:** Up to $17,500  
**Judges:** Philippe Laffont (Coatue), Dan Loeb (Third Point), Ken Hao (Silver Lake)

---

## Thesis in One Sentence

Credo Technology Group (CRDO) is the critical, underpriced provider of high-speed connectivity silicon that every hyperscaler AI data center depends on — and the market is still pricing it as a speculative semiconductor, not the infrastructure pick-and-shovel it has become.

---

## The Narrative Arc

Every civilizational technology shift — digital, internet, mobile — created one generation of application winners and one generation of infrastructure immortals. We are five years into the AI shift and still in its infrastructural phase. This pitch identifies the company solving a **specific, quantifiable structural flaw in AI deployment** and makes the financial case for why it is being underpriced today.

The thesis tracks the intellectual priorities of all three judges:
- **Laffont (Coatue):** Infrastructure-before-apps thesis, behavioral data over consensus, historical paradigm framing
- **Loeb (Third Point):** Catalyst-driven re-rating, surgical valuation, non-consensus demolition of market assumptions
- **Hao (Silver Lake):** Semiconductor defensibility, programmable compute, 5–10 year compounding story

---

## Workflow Architecture

This project was designed and orchestrated in Claude Code and executed entirely inside **Perplexity Computer** — the final submission is itself a Perplexity-native web application. The methodology is visible inside the artifact.

### Stage Map

| Stage | Folder | Task | Perplexity Capability Used |
|---|---|---|---|
| 1 | [stage_01_history/](stage_01_history/) | Civilizational history of tech paradigm shifts | 4 parallel sub-agents, Statista, PitchBook |
| 2 | [stage_02_universe/](stage_02_universe/) | Full AI infrastructure stock universe across 5 risk/reward tiers | 7 parallel sub-agents (one per AI flaw category) |
| 3 | [stage_03_comparative/](stage_03_comparative/) | 7-dimension comparative analysis → stock selection | CB Insights, PitchBook, scoring matrix |
| 4 | [stage_04_deepdive/](stage_04_deepdive/) | CRDO deep dive: business, financials, alt data | 4 simultaneous sub-agents, SEC EDGAR, FactSet, hiring data |
| 5 | [stage_05_financials/](stage_05_financials/) | DCF scenarios, trading comps, catalyst calendar | FactSet, S&P Global, PitchBook comps |
| 6 | [stage_06_model_council/](stage_06_model_council/) | Model Council stress test: 3 models × 5 questions | GPT-5.4 + Claude Opus 4.6 + Gemini 3.1 Pro |
| 7 | [stage_07_submission/](stage_07_submission/) | Final interactive web app submission | Full Perplexity Computer orchestration |

---

## Submission Asset

The final deliverable is a narrative-driven web application built and deployed inside Perplexity Computer. It tells the investment story in eight chapters — earning the answer, not opening with it:

1. **The World Before the Answer** — Civilizational history of tech paradigm shifts
2. **Locating the Opportunity** — Full AI infrastructure universe across 5 risk/reward tiers
3. **The Comparative Analysis** — Head-to-head finalists → the selection rationale
4. **The Company** — CRDO deep dive: moat, financials, alternative data signals
5. **The Financial Case** — DCF scenarios, trading comps, sensitivity analysis, catalyst calendar
6. **The Stress Test** — Model Council: 3 AI models debate 5 adversarial questions in parallel
7. **The Recommendation** — Final thesis, conviction pillars per judge, risks
8. **How This Was Built** — Full Perplexity Computer process log — the creative use showcase

---

## Key Files

| File | Purpose |
|---|---|
| [CLAUDE.md](CLAUDE.md) | Master project briefing and submission architecture |
| [THESIS_FRAMEWORK.md](THESIS_FRAMEWORK.md) | Intellectual architecture of the pitch |
| [JUDGES.md](JUDGES.md) | Deep profiles on Laffont, Loeb, and Hao |
| [PERPLEXITY_TASKS.md](PERPLEXITY_TASKS.md) | Full Perplexity Computer task sequence and prompts |
| [SUBMISSION_PROMPTS.md](SUBMISSION_PROMPTS.md) | Ready-to-paste prompts for each Perplexity task |

---

## Sector Thesis

AI systems have six structural flaws limiting commercial deployment at scale: hallucination, training data quality, context management, inference efficiency, simulation environments, and human behavioral data gaps. This pitch focuses on companies building the specialized infrastructure that solves these flaws — the picks-and-shovels of the AI buildout, not the AI apps themselves.

CRDO sits at the intersection of inference efficiency and AI data center connectivity — a bottleneck that grows more critical as hyperscaler AI training and inference workloads double every 12–18 months.
