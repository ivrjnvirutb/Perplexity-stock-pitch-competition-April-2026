# Perplexity Computer — Spec & Reference Guide
> Last updated: April 2, 2026 | Source: Official Perplexity docs, changelogs, independent reviews, screenshots
> **Your account:** Pro subscriber (Computer access confirmed)

---

## 🧠 What It Is
Perplexity Computer is a **cloud-based, multi-model AI agent** launched February 25, 2026. It's not a chatbot — it's a **general-purpose digital worker** that takes a high-level goal, breaks it into subtasks, spins up specialized sub-agents, and runs workflows that can last hours, days, or even months with minimal oversight.

---

## ⚙️ Core Architecture
| Component | Detail |
|---|---|
| **Core Reasoning Engine** | Claude Opus 4.6 |
| **Total Models Orchestrated** | 19–20 frontier models |
| **Research Sub-agent** | Gemini |
| **Image Generation** | Nano Banana |
| **Video Generation** | Veo 3.1 |
| **Fast/Lightweight Tasks** | Grok |
| **Long-Context Recall** | GPT-5.2 |
| **Coding Sub-agent** | GPT-5.3-Codex (added March 2026) |
| **Compute Environment** | Isolated cloud sandbox with real filesystem + browser |
| **App Integrations** | 400+ (Slack, Gmail, GitHub, Notion, HubSpot, Google Drive, etc.) |

---

## 🏦 Stock Pitch Competition Context (Active Now)
Perplexity is running a **Stock Pitch Competition** (started March 30, 2026) for students at US undergraduate/graduate programs. Prizes up to **$17,500**. Judges: Philippe Laffont (Coatue), Dan Loeb (Third Point), Ken Hao (Silver Lake). Judged on: creative use of Computer, unique analysis, differentiated thesis. This context is useful — the example prompts below are the official competition reference prompts, which represent the **highest-value research workflows** Computer is designed for.

---

## 🚀 Latest Features (as of April 2026)
- **Skills** — Auto-loaded capabilities triggered by task type (no manual config). Example: *"Create a skill that takes a company name and produces a one-page competitive brief with funding history, product overview, and recent news."*
- **Model Council** ⭐ — Runs GPT-5.4, Claude Opus 4.6, and Gemini 3.1 Pro **in parallel**, then synthesizes where they agree, disagree, and what each uniquely contributes. You choose the orchestrator model. Use cases:
  - *"Use Model Council to analyze whether TSLA is overvalued — compare bull and bear cases with data from latest earnings."*
  - *"Here's my pitch deck. Use Model Council to identify the three weakest assumptions and how each model would challenge them."*
- **Voice Mode** — Interact with Computer via voice
- **GPT-5.3-Codex Coding Sub-agent** — Dedicated coding agent added March 2026
- **GPT-5.4 Access** — Available to Pro and Max subscribers
- **Personal Computer** — Mac Mini-based local agent (launched March 11, 2026) with 24/7 uptime and local file access
- **Enterprise Tier** — SOC 2 Type II, SAML SSO, SCIM, audit logs, Slack @computer integration
- **Premium Sources** — Paywalled data from Statista, CB Insights, PitchBook
- **Perplexity Finance** — 40+ live tools: SEC filings, FactSet, S&P Global, Coinbase, LSEG
- **Own AI-Optimized Search Index** — No longer dependent on third-party search APIs

---

## 🏆 Unique Capabilities (Things No Other AI Tool Does)
1. **True multi-model orchestration** — 19+ models running in parallel, each assigned the best job. No other tool does this natively without custom setup.
2. **Asynchronous long-running workflows** — Tasks run for hours/days/months in the cloud, even after you close the browser. You come back to finished results.
3. **Managed cloud sandbox** — Zero environment setup. No PATH errors, no dependency hell. Every session starts clean. (vs. OpenClaw which runs locally)
4. **Parallel sub-agent spawning** — Need to research 10 competitors at once? 10 sub-agents spin up simultaneously, sharing the same workspace, then synthesize results.
5. **Persistent cross-session memory** — Remembers your past work, preferences, files, and company context. Never re-explain yourself.
6. **Model-agnostic harness** — You can choose or switch the model for specific subtasks. Token budgets and spending caps are user-controlled.
7. **Best-in-class context compaction** — Maintains coherent context across multi-day sessions through multiple compactions without losing the thread.
8. **Draco benchmark** — Perplexity's own complex research benchmark where it outperforms Gemini Deep Research and others.

---

## 📋 Official Example Prompts (From Perplexity's Own Help Center)

### 🔬 Deep Research
```
Scan ClinicalTrials.gov, public filings, CB Insights, and Polymarket where FDA 
approval odds are not reflected in stock prices to identify mispriced biopharma names.
```
```
Use Statista's NATO defense budget data and recent Congressional budget resolutions 
to find which defense subsectors are getting the biggest funding increases.
```
```
Use PitchBook, 10-K debt footnotes of mid-market borrowers, and Statista to analyze 
which institutions have the most exposure if private credit stress spreads.
```
```
Analyze Polymarket odds, conflict-driven oil volatility, and underreported rare-earth 
supply shocks to map downstream supply-chain risk and surface mispriced equities.
```
```
Research AI data center power commitments and U.S. grid capacity to identify which 
power, nuclear, and gas equities are best positioned for rising AI electricity demand.
```

### 💰 Financial Modeling
```
Pull the 8 closest public comps for Duolingo using CB Insights or PitchBook for peer 
identification. Build an EV/Revenue and EV/EBITDA trading comps table.
```
```
Build a 5-year DCF for Celsius Holdings using revenue and margin assumptions from 
their 10-K and most recent 10-Q. Create bull, base, and bear scenarios.
```
```
Build a scenario model showing how Ares' fee revenue changes if private credit 
default rates rise from 9.2% to 12% and 15%, given its $391.5B credit AUM.
```

### 🏗️ Generating Assets / Web Apps
```
Build a web app for a long investment thesis on Centrus Energy (LEU).
```
```
Build a web app for a long investment thesis on Datadog (DDOG).
```
```
Build a government and regulatory filings tracker.
```

### 🛠️ General Workflow Examples (From Official UI)
```
Find the best credit cards for travel rewards and compare their annual fees and perks.
```
```
Plan a 7-day trip to Japan with flights, hotels, and a daily itinerary.
```
```
Search daily for properties under $1M in this neighborhood that have 
short term rental licenses.
```
```
Analyze my monthly spending and build a budget with savings targets.
```
```
Scan top travel sites each morning for the best flights to Tokyo and send me the options.
```
```
Create an interactive dashboard that visualizes US population growth by state 
over the last 20 years.
```
```
Compare the top 10 project management tools and create a report with pricing, 
pros, and cons.
```
```
Build a workout plan for the next month based on my health data.
```

---

## 🎯 Best Use Cases for Research Projects

### 1. Deep Research Briefs
- Produce 1,500–3,000 word reports with 10–20 cited sources from a single prompt
- Access paywalled data (Statista, PitchBook, CB Insights)
- Financial research via SEC filings, FactSet, S&P Global

### 2. Competitive Intelligence Monitoring
- Set up scheduled daily monitors on competitors
- Tracks blog posts, pricing changes, feature launches, LinkedIn hires, funding rounds
- Delivers morning summaries; silent if nothing changed

### 3. End-to-End Project Execution
- Research → Design → Code → Deploy — all in one conversation
- One sub-agent drafts a document while another gathers the data for it
- Example: Research 500 companies → build a filterable web dashboard (3 hrs research + 15 min build)

### 4. Content Repurposing at Scale
- Turn a 45-min podcast into: blog post, Twitter threads, LinkedIn posts, email newsletter, YouTube description — all in parallel

### 5. App & Tool Building (No-Code Friendly)
- Internal dashboards, landing pages, data pipelines, Slack bots
- GPT-5.3-Codex handles architecture, code gen, and deployment
- Frontend and backend sub-agents work simultaneously

---

## 💡 Tips for Optimal Use
- **Describe outcomes, not steps** — "Build me a competitive analysis dashboard for 5 SaaS companies" beats "Search Google, then write a report..."
- **Be specific about deliverables** — Mention format (spreadsheet, web app, PDF, slides) in your prompt
- **Use checkpoints** — Computer surfaces review points mid-task; use them to steer direction early
- **Leverage persistent memory** — Tell it your company context, preferences, and style once; it remembers forever
- **Run multiple tasks in parallel** — You can have dozens of active Computer sessions simultaneously
- **Watch your credits** — Complex multi-day workflows burn credits faster; simple research uses fewer
- **Use Skills** — They load automatically, but knowing which ones exist helps you prompt more specifically
- **Personal Computer for sensitive data** — If your project involves proprietary files, use the Mac Mini local version so files never leave your machine

---

## 💰 Pricing
| Tier | Price | Computer Access | Key Features |
|---|---|---|---|
| **Free** | $0 | ❌ | Basic search only |
| **Pro** | ~$20/mo | ✅ Limited | Computer access, standard models |
| **Max** | $200/mo or $2,000/yr | ✅ Full | 10,000 credits/mo, all 19 models, Model Council, Premium Sources |
| **Enterprise Max** | $325/seat/mo or $3,250/yr | ✅ Full | + SOC 2, SSO, audit logs, SCIM, Slack @computer |
| **Personal Computer** | Mac Mini hardware (separate) | ✅ Local | Local file access, 24/7, offline capable |

> ⚠️ Credit cost per task type is not publicly documented — budget conservatively for long workflows.
> 📌 **Your account is Pro** — you have Computer access with some limits vs. Max tier.

---

## 🆚 vs. Competitors
| Feature | Perplexity Computer | Claude CoWork | OpenClaw |
|---|---|---|---|
| Multi-model orchestration | ✅ 19+ models | ❌ Single model | ❌ Single model |
| Cloud sandbox (no setup) | ✅ Managed | ✅ Managed | ❌ Runs locally |
| Persistent memory | ✅ | ✅ | ✅ |
| Local file access | ✅ (Personal Computer) | ❌ | ✅ |
| App integrations | ✅ 400+ | Limited | Limited |
| Async long-running tasks | ✅ Hours/months | Limited | Limited |
| Paywalled data access | ✅ Statista, PitchBook, CB Insights | ❌ | ❌ |
| Newbie-friendliness | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |

---

## 🤖 Claude Code Handoff Notes
> Use this section to orient Claude Code when building a project plan for Perplexity Computer to execute.

**Key things Claude Code should know:**
- Perplexity Computer takes **outcome-based prompts**, not step-by-step instructions
- Tasks run **asynchronously** — design workflows that can run unattended for hours
- Each task is organized as a **Task** (not a conversation) in the left sidebar
- Sub-agents can run in **parallel** — design for parallelism, not serial steps
- Computer has **persistent memory** — set context once, reference it across tasks
- **Model Council** is available for high-stakes decisions requiring multi-model consensus
- **Premium data sources** (PitchBook, CB Insights, Statista, SEC, FactSet) are natively accessible — no scraping needed
- Output formats: web apps, dashboards, PDFs, spreadsheets, reports — specify in prompt
- **Skills** auto-load — but explicitly naming the skill type in your prompt helps
- For Claude Code project plans: structure as a sequence of Perplexity Computer **Tasks**, each with a clear outcome, data sources, and output format

**Recommended project plan structure for Perplexity Computer:**
```
Task 1: [Research/Data Gathering] — sources, output format
Task 2: [Analysis/Modeling] — inputs from Task 1, methodology, scenarios
Task 3: [Asset Generation] — web app / dashboard / report from Task 2
Task 4: [Monitoring/Automation] — scheduled follow-ups if needed
```

---

## 📎 Key Links
- Official blog: https://www.perplexity.ai/hub/blog/introducing-perplexity-computer
- March 2026 expansion: https://www.perplexity.ai/hub/blog/everything-is-computer
- Changelog: https://www.perplexity.ai/changelog
- Help Center (Skills): https://www.perplexity.ai/help-center/en/articles/13914413-how-to-use-computer-skills
- Stock Pitch Competition: https://pplx.ai/pitch
