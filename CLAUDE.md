# CLAUDE.md — Perplexity Stock Pitch Competition: Project Briefing

> **Mission:** Design and orchestrate a Perplexity Computer workflow to produce a winning investment pitch for the Perplexity Stock Pitch Competition (March 30 – April 2026).
> **Prize pool:** Up to $17,500 | **Audience:** Philippe Laffont, Dan Loeb, Ken Hao

---

## 🚨 Most Important Rule: The Submission IS a Perplexity Computer Asset

The final submission must be a **Perplexity Computer-generated asset** — a web app, dashboard, or interactive report built and deployed entirely inside Perplexity Computer. This is not a pitch deck we build externally and attach. The artifact itself is the submission.

This has two critical implications:

**1. The methodology must be visible inside the artifact.**
Judges evaluate *creative use of Perplexity Computer*. That means the final web app must show its own provenance — which tasks used Model Council, which sub-agents ran in parallel, which premium data sources were accessed, and how the multi-model orchestration shaped the analysis. The process is part of the product.

**2. Every task must be designed to feed the final asset.**
Research, financial modeling, Model Council stress tests — all of it flows into one polished, Perplexity-native interactive submission. Claude Code's job is to design the task sequence AND the architecture of that final asset so every upstream task's output has a clear home in the final deliverable.

---

## 🎯 Project Objective

Pitch a **long investment thesis** on an NYSE or NASDAQ listed stock (market cap > $1B) in the sector of **AI transformation infrastructure** — companies solving the *inherent flaws* in current AI systems, not merely deploying AI.

The pitch must be judged on:
1. **Creative use of Perplexity Computer** — the artifact must make this legible and impressive
2. **Unique data and financial analysis** that goes beyond traditional research methods
3. **A differentiated, defensible thesis**

Read `JUDGES.md` for deep profiles on each judge and what resonates with them.
Read `THESIS_FRAMEWORK.md` for the intellectual architecture of the pitch.
Read `PERPLEXITY_TASKS.md` for the full sequence of Perplexity Computer tasks to execute.

---

## 🏗️ What Claude Code Should Build

Claude Code's job is to:
1. **Design the Perplexity Computer task sequence** — the prompt chain that generates all research, analysis, and modeling
2. **Architect the final submission asset** — a detailed spec for the interactive web app that Perplexity Computer will build as the capstone task, including every section, what data populates it, and how Perplexity's own methodology is surfaced within it
3. **Write every prompt** ready to paste into Perplexity Computer, in order

Claude Code does NOT execute the research — it architects the workflow and writes the prompts.

### The Submission Asset: One Narrative-Driven Story Web App

The app tells a story in chapters — earning the answer, not opening with it.
Civilizational history → economic cycles → AI's place in that arc → full universe 
across the risk/reward spectrum → rigorous comparative analysis → the winner → 
the financial case → the stress test → how it was all built.

| Chapter | Content | Source Task | Perplexity Capability |
|---|---|---|---|
| 1: The World Before the Answer | History of tech paradigm shifts, economic cycles, capitalism, civilizational AI | Task 1 | 4 parallel research sub-agents, Statista, PitchBook |
| 2: Locating the Opportunity | Full AI infrastructure universe across 5 risk/reward tiers | Task 2 | 7 parallel sub-agents (one per AI flaw category) |
| 3: The Comparative Analysis | 5 tier finalists head-to-head → the selection | Task 3 | 7-dimension scoring matrix, CB Insights, PitchBook |
| 4: The Company | Deep dive: business, financials, market, alt data | Task 4 | 4 simultaneous sub-agents, SEC EDGAR, FactSet, hiring data |
| 5: The Financial Case | DCF scenarios, trading comps, sensitivity, catalyst calendar | Task 5 | FactSet, S&P Global, PitchBook comps |
| 6: The Stress Test | Model Council: 3 models × 5 questions in parallel | Task 6 | Model Council: GPT-5.4 + Claude Opus 4.6 + Gemini 3.1 Pro |
| 7: The Recommendation | Final thesis, conviction pillars per judge, risks | Synthesis | — |
| 8: How This Was Built | Full process log — the creative use showcase | All tasks | Workflow diagram, capability stats, task logs |

---

## ⚙️ Perplexity Computer Constraints (Read Before Designing Tasks)

- **Account tier: Pro** — Computer access is available but credits are limited vs. Max
- Tasks run **asynchronously** — design for unattended execution (hours)
- Each task = one Perplexity Computer **Task** (left sidebar), not a chat
- Sub-agents run in **parallel** where possible — design for this explicitly
- **Premium data sources available:** PitchBook, CB Insights, Statista, SEC/EDGAR, FactSet, S&P Global
- **Model Council available:** Runs GPT-5.4, Claude Opus 4.6, and Gemini 3.1 Pro in parallel
- Output formats: web apps, PDFs, spreadsheets — the final submission must be a **web app**
- Always use **outcome-based prompts** ("Build X with Y data, output as Z"), never step-by-step

---

## 📁 File Map

```
CLAUDE.md               ← This file. Master briefing.
JUDGES.md               ← Deep profiles on Laffont, Loeb, Hao
THESIS_FRAMEWORK.md     ← Intellectual architecture of the pitch
PERPLEXITY_TASKS.md     ← Full task sequence + submission asset spec for Perplexity Computer
```
