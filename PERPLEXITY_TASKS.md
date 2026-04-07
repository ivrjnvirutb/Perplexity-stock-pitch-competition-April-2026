# PERPLEXITY_TASKS.md — Perplexity Computer Execution Plan

> **The submission is a Perplexity Computer-built interactive web app.**
> It must tell a story — from civilizational history → economic cycles → AI's place in that arc →
> a range of investment candidates across the risk/reward spectrum → rigorous comparative analysis →
> a final recommendation — with the Perplexity process itself woven into the narrative as evidence.
>
> The judges should feel like they are watching an analyst think, not reading a finished report.
> Every section answers: "Why did we look here next?" before showing what we found.
>
> ⚠️ Account tier: Pro — credits are limited. Prioritize Tasks 0, 2, 3, 4, 6, 7.
> 💡 Use Perplexity checkpoints mid-task to steer before long runs commit.

---

## TASK 0 — Set Persistent Memory Context
**Paste this FIRST into Perplexity Computer memory settings before any other task.**

```
PROJECT CONTEXT — PERPLEXITY STOCK PITCH COMPETITION (APRIL 2026)

MISSION: Build a winning stock pitch as a Perplexity Computer-generated interactive 
web app. The app tells a complete story: civilizational history of technology →
economic cycles and capitalism → AI as the next paradigm shift → a universe of 
investment candidates across the risk/reward spectrum → rigorous comparative 
analysis → a final single-stock recommendation with full financial backing.

The submission is judged on: (1) creative use of Perplexity Computer, 
(2) unique non-consensus analysis, (3) differentiated thesis.

SECTOR: AI transformation infrastructure — companies solving the structural, 
inherent flaws in current AI systems: training data quality, inference efficiency, 
context/memory management, simulation environments for agent/robotics training, 
human behavioral data collection for embodied AI, diffusion model R&D, AI 
verification and alignment. Companies transforming AI, not just deploying it.

STOCK UNIVERSE: NYSE or NASDAQ listed, market cap > $1B.
CANDIDATE APPROACH: We want a RANGE across the risk/reward spectrum — from 
conservative/large-cap infrastructure plays to speculative/high-growth pure-plays — 
so we can run a genuine comparative analysis before selecting the best pitch candidate.

JUDGES:
— Philippe Laffont (Coatue): historical tech cycles, "token economy" thesis, 
  infrastructure-before-apps, non-consensus behavioral data. MIT CS degree, 
  engineer mindset. Invested in Anthropic.
— Dan Loeb (Third Point): activist-event-driven, surgical valuation, specific 
  catalyst required, destroys hand-waving, warned AI is already eroding software moats.
— Ken Hao (Silver Lake): semiconductor/large-cap tech, led $8.75B Altera FPGA 
  acquisition, edge AI and robotics, long-term operational transformation, 
  Harvard Economics, Met trustee — appreciates elegance.

NARRATIVE RULE: Every task should feel like a chapter in a story. Each chapter 
answers "why did we look here next?" before showing what we found. The dashboard 
reproduces this journey, not just its conclusions.

PROCESS VISIBILITY RULE: Log every Perplexity capability used in each task 
(which models, which data sources, parallel sub-agents, Model Council). 
This feeds the dashboard's process narrative — the HOW is as important as the WHAT.

ALWAYS: Cite premium sources (PitchBook, CB Insights, Statista, SEC/EDGAR, 
FactSet, S&P Global). Bull/base/bear scenarios with genuinely different assumptions. 
Write for institutional investors. No MBA-speak. Data first.
```

---

## TASK 1 — The Historical Foundation: Technology, Economic Cycles, Capitalism
**Runtime estimate:** 2–3 hrs | **Output:** paradigm_data.json + Task1_History.pdf
**Story purpose:** Chapter 1. Establish WHY any of this matters before touching a stock.

```
Research the history of technology as a driver of economic transformation, 
capitalist evolution, and civilizational change. This is the foundational 
argument that earns the right to make an investment claim later.

Run 4 parallel research sub-agents:

SUB-AGENT 1 — The History of Technology Paradigm Shifts (1750–present)
Using Statista, academic economic databases, and historical market data:
— The Industrial Revolution (steam, mechanization): how it restructured labor, 
  capital, and the concept of the firm
— Electrification (1880s–1920s): the 30-year gap between invention and economic 
  impact; which companies captured value and why (infrastructure vs. application)
— The Digital Computing Age (1950s–1990s): IBM mainframe dominance → PC era → 
  productivity paradox → eventual GDP impact. Value capture: infrastructure vs. apps.
— The Internet Age (1993–2010s): infrastructure phase duration, infrastructure vs. 
  application market cap ratio at each stage, which bottleneck companies became 
  generational wealth creators (Cisco, Oracle, eventually AWS)
— Mobile (2007–2020s): same analysis
For each era collect: infrastructure phase duration (years), infrastructure/app 
value capture ratio, key enabling bottleneck, bottleneck solver(s), 
10-year return of bottleneck solver from inflection point

SUB-AGENT 2 — Economic Cycles and Capitalism's Response to Technology Shocks
Using academic sources, IMF/World Bank data, Statista:
— Kondratiev waves / long economic cycles: how each ~50-year wave corresponds 
  to a technology cluster and what the investment implications were at each wave's start
— Creative destruction patterns: what incumbent industries were displaced in each 
  era, how long displacement took, and what the market mispriced during the transition
— Capital allocation cycles: how institutional capital (banks, PE, public markets) 
  historically under- then over-allocated to new paradigm infrastructure
— Historical P/E expansion/contraction patterns during technology paradigm transitions
  (e.g., what happened to the market multiple when the internet went mainstream)

SUB-AGENT 3 — AI's Place in This Arc: Where Are We Now?
Using PitchBook VC deployment data, CB Insights, public market data, Statista:
— VC deployment into AI infrastructure vs. AI applications (2020–2026): 
  is the ratio consistent with where previous paradigms were at equivalent maturity?
— Public market valuations: how are current AI infrastructure companies valued 
  relative to comparable internet infrastructure companies at equivalent stages?
— Corporate capex into AI: which sectors are deploying fastest, what does that 
  signal about where we are in the adoption curve?
— 3 non-consensus data points that show the market is still in the infrastructure 
  pricing phase, not yet the application pricing phase

SUB-AGENT 4 — The Lightbulb Parallel: Civilizational Impact of AI
Using academic sources, Statista, think tank research (McKinsey Global Institute, etc.):
— Quantify the scope of cognitive labor that AI can automate (% of tasks, 
  not just jobs — the McKinsey framework)
— Historical analogues for automation of previously human-only capabilities: 
  accounting automation, legal research automation, medical imaging — what happened 
  to those industries and the companies that enabled the automation?
— Why AI is different from prior automations: it is the first general-purpose 
  cognitive tool, not domain-specific — and what the economic implications of 
  that generality are

Synthesize all 4 sub-agents into:
1. "paradigm_data.json" — structured, chart-ready data for every analysis above
   Include: era_timeline[], value_capture_ratios[], kondratiev_waves[], 
   ai_positioning_data{}, cognitive_labor_analysis{}
2. "Task1_History.pdf" — readable narrative version with executive summary

Log: 4 sub-agents ran in parallel, data sources per agent, total runtime.
```

---

## TASK 2 — Build the Candidate Universe Across the Risk/Reward Spectrum
**Runtime estimate:** 2–3 hrs | **Output:** universe_data.json + AI_Universe.xlsx
**Story purpose:** Chapter 2. Now that we know WHY this sector matters, WHERE do we look?
[CAN RUN IN PARALLEL WITH TASK 1]

```
Build a comprehensive universe of public AI transformation infrastructure companies 
(NYSE/NASDAQ, market cap > $1B) organized explicitly across a risk/reward spectrum 
from conservative to speculative.

STEP 1 — Universe Construction
Run 7 parallel sub-agents, one per structural AI flaw category:
  Category 1: Training data quality, curation, synthetic data generation
  Category 2: AI inference efficiency and cost optimization
  Category 3: Context management, persistent memory, RAG infrastructure
  Category 4: Simulation environments for agent/robotics training
  Category 5: Human behavioral data collection for embodied AI
  Category 6: Diffusion model R&D and next-gen generative architecture
  Category 7: AI verification, evaluation, alignment infrastructure

Each sub-agent uses PitchBook, CB Insights, SEC EDGAR, and financial databases 
to find every qualifying public company in its category.

STEP 2 — Data Collection Per Company
For each company in the universe collect:
— Ticker, exchange, current market cap, founding year
— Category (from 7 above) and one-sentence business description
— Revenue TTM, Revenue Growth YoY, Gross Margin, R&D as % of Revenue
— Moat type: proprietary dataset / HW-SW integration / network effects / 
  regulatory / switching costs
— Recent significant catalyst (last 6 months)
— Analyst consensus price target vs. current price (upside/downside %)
— One-sentence "why underpriced" hypothesis

STEP 3 — Risk/Reward Classification
Classify every company into one of 5 risk/reward tiers:

TIER 1 — CONSERVATIVE (Low risk, steady compounding)
  Profile: Large-cap (>$20B), diversified revenue, AI infrastructure as one 
  of multiple durable business lines, strong FCF, proven management
  Examples: semiconductor IP/tools companies, enterprise data infrastructure

TIER 2 — ESTABLISHED GROWTH (Moderate risk, above-market returns)
  Profile: Mid-to-large cap ($5B–$20B), AI infrastructure as primary revenue 
  driver, proven product-market fit, growing but not yet dominant market share
  
TIER 3 — HIGH CONVICTION GROWTH (Moderate-high risk, significant upside)
  Profile: Mid-cap ($1B–$5B), pure-play on one structural AI flaw, clear moat, 
  specific near-term catalyst, market underpricing the TAM or growth rate

TIER 4 — SPECULATIVE GROWTH (High risk, asymmetric upside)
  Profile: Small-to-mid cap ($1B–$3B), early revenue stage, proprietary 
  technology or dataset, long runway but unproven at scale

TIER 5 — DEEP VALUE / TURNAROUND (High risk, different return profile)
  Profile: Company being repriced by the market due to AI-driven competitive 
  disruption OR an incumbent being undervalued because the market doesn't yet 
  understand their AI infrastructure pivot

STEP 4 — Scoring
Score every company:
  — Moat Strength: 1–10
  — Revenue Growth: 1–10 (normalized within tier)
  — Valuation Attractiveness: 1–10 (relative to growth rate and tier)
  — Judge Resonance: 1–10 (fit with Laffont/Loeb/Hao's documented frameworks)
  — Data Advantage Score: 1–10 (how much does Perplexity's premium data 
    access enable unique insight vs. standard research?)
  — COMPOSITE CONVICTION SCORE: weighted average

Output:
1. "AI_Universe.xlsx" — full universe, sortable, with all fields and scores, 
   organized by Tier then Conviction Score descending
2. "universe_data.json" — same data structured for web app:
   { tier: 1-5, companies: [{ticker, name, category, metrics, scores, thesis_sentence}] }

Log: 7 parallel sub-agents, data sources per company, total companies evaluated.
```

---

## TASK 3 — Comparative Analysis: Select the Top Candidate Per Tier, Then the Winner
**Runtime estimate:** 1.5–2 hrs | **Output:** comparative_data.json + Task3_Comparative.pdf
**Story purpose:** Chapter 3. Here is how we narrowed the field — showing our work.
⚠️ CHECKPOINT before launching Task 4.

```
Using AI_Universe.xlsx from Task 2, run a two-stage comparative analysis.

STAGE 1 — Select the strongest candidate from each risk/reward tier (5 finalists)
For each tier, identify the single highest-conviction company. 
Write a 150-word profile for each finalist covering:
— Core thesis (the non-consensus insight in one sentence)
— Moat description (specific, not generic)
— Primary catalyst (specific event, not "continued growth")
— Key risk (the thing most likely to be wrong)
— Judge fit (one sentence per judge: Laffont / Loeb / Hao)
— Financial snapshot: Market Cap, Revenue Growth, Gross Margin, EV/Revenue vs. peers

The 5 finalists represent the full risk/reward spectrum:
  Finalist T1: The conservative anchor (sleep-well-at-night infrastructure)
  Finalist T2: The established grower (quality at a reasonable price)
  Finalist T3: The high-conviction pick (the differentiated thesis)
  Finalist T4: The speculative asymmetric bet
  Finalist T5: The deep value / turnaround

STAGE 2 — Head-to-head comparative analysis across all 5 finalists
Build a structured comparison matrix:

Dimension 1 — Moat Durability (5 years out): who is hardest to displace?
Dimension 2 — Growth Visibility: whose revenue growth is most predictable?
Dimension 3 — Valuation vs. Opportunity: who has the widest gap between 
  price and fair value?
Dimension 4 — Catalyst Specificity: whose near-term re-rating catalyst is 
  most concrete and time-bound?
Dimension 5 — Judge Resonance: which company speaks most directly to all 3 judges?
Dimension 6 — Non-Consensus Advantage: which thesis is the most differentiated 
  from what Coatue/Third Point/Silver Lake already know and own?
Dimension 7 — Data Advantage: which company benefits most from Perplexity's 
  premium data access for unique insight generation?

Score each finalist 1–10 on each dimension. Show the matrix. 
Explain the top scorer on each dimension in 2 sentences.

STAGE 3 — Final Recommendation
Select ONE company as the pitch. 
Write a 300-word justification that:
— States the thesis in a single non-obvious sentence
— Explains why this is the best pitch for THESE specific judges
— Acknowledges the strongest competing candidate and explains why it lost
— Names the primary risk and why it's acceptable
— States the specific catalyst that makes this timely

Output:
1. "Task3_Comparative.pdf" — full analysis readable by a human reviewer
2. "comparative_data.json" — structured for web app:
   { finalists: [{ tier, ticker, name, profile_150w, scores{} }],
     comparison_matrix: [{ dimension, scores{ticker: score}, leader, explanation }],
     winner: { ticker, thesis_sentence, justification, catalyst, primary_risk } }

Log: methodology, how many companies considered, scoring approach.
⚠️ REVIEW THIS OUTPUT before launching Task 4. Wrong stock = wrong everything.
```

---

## TASK 4 — Deep Dive: Full Research on the Selected Company
**Runtime estimate:** 3–5 hrs | **Input:** Winner from Task 3

```
Conduct a comprehensive investment research deep dive on [COMPANY NAME] ([TICKER]).

Run 4 parallel research sub-agents simultaneously:

SUB-AGENT A — Business & Competitive Intelligence
Sources: CB Insights, PitchBook, LinkedIn hiring data, patent databases, 
company website, industry analyst reports
— Full product/service breakdown with revenue attribution by segment
— Competitive moat: why can the hyperscalers (Google, Microsoft, Amazon) NOT 
  replicate this in 24 months? Cite specific technical, data, or structural barriers.
— Customer concentration, key contracts, churn/retention signals
— Hiring trends: job posting volume and category changes, last 12 months
— Patent landscape: key IP, filing velocity vs. top 3 competitors

SUB-AGENT B — Financial Analysis
Sources: SEC EDGAR 10-K/10-Q (3 years), FactSet, S&P Global, insider transaction data
— 5-year income statement, balance sheet, cash flow reconstruction
— Unit economics: CAC, LTV, gross margin by segment, R&D efficiency ratio
— Management guidance accuracy: beat/miss history and magnitude (last 8 quarters)
— Insider ownership % and recent Form 4 activity (buying/selling signal)
— Capital allocation history: buybacks, M&A, R&D ROI

SUB-AGENT C — Market Sizing
Sources: Statista, CB Insights, industry reports, company filings
— TAM per segment, methodology explicit
— SAM and SOM with realistic penetration assumptions
— Competitive market share evolution, last 3 years
— Market growth rate from 3 independent sources; flag where they diverge and why

SUB-AGENT D — Alternative & Sentiment Data
Sources: web traffic analytics, app store data, academic citation databases, 
patent registries, Polymarket (if applicable)
— Web traffic and app download trends vs. competitors
— Patent filing velocity: [TICKER] vs. top 3 competitors, by quarter
— Academic citation counts for company research publications
— Any prediction market signals on company events

Output:
1. "Research_Dossier.pdf" — structured dossier with Executive Summary front page
2. "research_data.json" — for web app:
   { exec_summary{}, business{ segments[], moat{}, customers{}, hiring{}, patents{} },
     financials{ income[], balance[], cashflow[], guidance_accuracy[], insiders{} },
     market{ tam{}, sam{}, som{}, share_evolution[], growth_projections[] },
     alt_data{ traffic{}, patents{}, citations{}, polymarket{} } }

Log: 4 parallel sub-agents, data sources per agent, runtime each.
```

---

## TASK 5 — Financial Model: DCF + Trading Comps
**Runtime estimate:** 2–3 hrs | **Input:** Task 4 financial data

```
Build a rigorous financial model for [COMPANY NAME] ([TICKER]).

COMPONENT 1 — TRADING COMPS
Using PitchBook and FactSet, identify the 6–8 closest public comparables.
For each: Market Cap, EV, Revenue TTM+NTM, EBITDA TTM+NTM, EV/Revenue, 
EV/EBITDA, P/E, Revenue Growth YoY, Gross Margin.
Flag [TICKER]'s premium/discount to peer median and explain in one sentence.

COMPONENT 2 — 5-YEAR DCF: 3 scenarios with GENUINELY DIFFERENT assumptions
(not just ±% on the same base — different structural stories)

BEAR: Hyperscaler competition accelerates. [TICKER]'s moat erodes faster than 
expected. Pricing pressure compresses gross margins. Customer churn increases.
→ State: Revenue CAGR, Gross Margin trajectory, EBITDA margin, WACC, 
  Terminal Growth Rate, Implied EV, Implied Share Price.

BASE: Management executes on current roadmap. Market share stable. Margins 
expand per guidance. No major competitive surprise.
→ Same fields.

BULL: Adjacent market expansion succeeds. Data network effects compound. 
A major enterprise contract or partnership accelerates the adoption curve. 
Gross margin re-rates toward software comps.
→ Same fields.

COMPONENT 3 — SENSITIVITY TABLE
Implied share price grid: CAGR (rows) × Exit EV/Revenue Multiple (columns).
Color coded: red (below current), yellow (0–30% upside), green (30%+ upside).

Output:
1. "Financial_Model.xlsx" — tabs: Comps, DCF_Bear, DCF_Base, DCF_Bull, Sensitivity, 
   Summary_Dashboard
2. "model_data.json" — for web app:
   { comps: [{ ticker, metrics{} }], ticker_vs_peers{ premium_discount, explanation },
     dcf: { bear{assumptions{}, outputs{}}, base{...}, bull{...} },
     sensitivity: { rows: cagr_values[], cols: multiple_values[], grid: [[price]] } }
```

---

## TASK 6 — Model Council: Multi-Model Thesis Stress Test
**Runtime estimate:** 1–1.5 hrs | [CAN RUN IN PARALLEL WITH TASK 5]
**This task IS a creative capability showcase — design it to feel like that.**

```
Invoke Model Council (GPT-5.4, Claude Opus 4.6, and Gemini 3.1 Pro in parallel) 
to independently stress-test the investment thesis for [COMPANY NAME] ([TICKER]).

Provide all 3 models with the winning thesis from Task 3 plus the financial 
summary from Task 5.

Each model independently answers:
Q1: What are the three weakest assumptions in this thesis?
Q2: What is the single most likely path to losing money on this investment?
Q3: What one piece of evidence, if found, would most strengthen the thesis?
Q4: Does this company have a durable moat in 5 years — yes or no, and exactly why?
Q5: If you were Dan Loeb on an earnings call with [TICKER]'s CEO, what is the 
    one question you'd ask to expose the thesis's vulnerability?

Synthesize across models:
— Where all 3 agree: high-confidence areas (lean into these in the pitch)
— Where they diverge: key uncertainties to address explicitly
— Unique flags per model: risks the other two missed
— Based on synthesis: 2–3 specific adjustments to make to the thesis or model

Output:
1. "Model_Council_Analysis.pdf" — full per-model responses + synthesis
2. "council_data.json" — for web app:
   { models: ["GPT-5.4", "Claude Opus 4.6", "Gemini 3.1 Pro"],
     questions: [{ id, text }],
     responses: [{ model, question_id, response, unique_flag: bool }],
     synthesis: { agreements[], divergences[], per_model_unique[], adjustments[] },
     loeb_question: { question, our_answer } }

Log: confirm Model Council invocation, orchestrator model, synthesis methodology.
```

---

## TASK 7 — BUILD THE SUBMISSION: The Investment Thesis Story Web App
**Runtime estimate:** 3–5 hrs | **THIS IS THE SUBMISSION ARTIFACT**
**Input:** All JSON outputs from Tasks 1–6

```
Build a professional, narrative-driven investment thesis web application for 
[COMPANY NAME] ([TICKER]) as the submission to the Perplexity Stock Pitch Competition.

This web app is simultaneously:
(a) A compelling investment pitch to sophisticated institutional investors
(b) A transparent, narrative story of how this analysis was built — the process 
    is part of the product, and the judges should feel the journey

CORE NARRATIVE PRINCIPLE:
The app tells a story in chapters. Every section answers "why did we look here 
next?" before revealing what we found. The reader moves from civilizational 
history → economic patterns → the AI paradigm → the candidate universe → 
the comparative analysis → the winner → the financial case → the stress test.
It does not open with the answer. It earns the answer.

---

DESIGN SYSTEM:
— Background: deep navy (#0A0E1A)
— Accent: electric blue (#2D6FFF) for data and interactive elements
— Highlight: gold (#C9A84C) for key conclusions and chapter markers
— Text: off-white (#F0F0F0)
— Typography: Space Grotesk for headers, Inter for body
— A persistent left sidebar showing chapter names; active chapter highlighted in gold
— Each chapter has a 2–3 sentence "chapter intro" card in italic — the "why we 
  looked here" framing — before the data appears
— Source chips on every data element: small tags showing "PitchBook" / "FactSet" / 
  "Statista" / "SEC EDGAR" / "CB Insights" etc.
— A persistent footer strip showing: Total sub-agents deployed | Data sources accessed | 
  Model Council invocations | Total async runtime

---

CHAPTER 1 — THE WORLD BEFORE THE ANSWER
"Every great investment thesis starts not with a stock, but with an observation 
about how the world is changing. We started here."

Subsection A: The Technology Stack of Civilization (paradigm_data.json, Sub-agent 1)
— Animated horizontal timeline: 1750 → 2026
— 6 eras marked: Industrial Revolution, Electrification, Digital Computing, 
  Internet, Mobile, AI
— Click each era: a card expands showing infrastructure phase duration, 
  key bottleneck solved, bottleneck solver company, 10-year return from inflection
— A connecting thread annotation across all eras: 
  "In every era, the infrastructure builders captured more durable value than 
  the application builders. Here's the data."

Subsection B: Economic Cycles and Capitalism's Technology Response (Sub-agent 2)
— Kondratiev wave visualization: ~50-year cycles overlaid on real GDP growth data
— Each wave labeled with its technology cluster
— Annotated: "Capital systematically underallocated to infrastructure at the 
  START of each wave, then overallocated. We believe AI is at the underallocation phase."
— P/E multiple expansion chart: what happened to market multiples in the 12 months 
  after each paradigm's infrastructure phase ended and applications went mainstream

Subsection C: AI's Civilizational Weight (Sub-agent 4)
— The cognitive labor map: animated visualization of which categories of human 
  cognitive work are automatable by AI (% of tasks, by sector)
— The lightbulb comparison: a side-by-side card showing: 
  "When Edison's lightbulb went commercial in 1882: [economic impact over 30 years]"
  "When GPT-4 went commercial in 2023: [current trajectory extrapolated]"
— The generality point: a single annotated chart showing why general-purpose 
  tools (steam engine, electricity, internet, AI) have fundamentally larger 
  economic impact than domain-specific tools

Chapter 1 closes with a gold-highlighted transition card:
"The historical pattern is consistent. A new general-purpose technology 
has arrived. The infrastructure phase is underway. The question is who's building it."

---

CHAPTER 2 — LOCATING THE OPPORTUNITY
"We mapped the full universe of public companies building this infrastructure. 
Here is the landscape — and how we narrowed it."

Subsection A: The AI Transformation Infrastructure Universe (universe_data.json)
Chapter intro: "Perplexity Computer deployed 7 parallel research sub-agents — 
one per structural AI flaw category — to map every qualifying public company."

— Interactive bubble chart: x = Revenue Growth, y = Gross Margin, 
  bubble size = Market Cap, color = category (7 colors for 7 structural flaw types)
— 7 category filter toggle buttons
— Click any bubble: company card appears (name, ticker, tier, one-line thesis, 
  conviction score)
— Stat strip: "N companies evaluated across 7 categories"

Subsection B: The Risk/Reward Spectrum
Chapter intro: "We organized the universe into 5 tiers — from conservative 
infrastructure anchors to speculative asymmetric bets — to understand the 
full range of available investment options."

— 5-column layout, one column per tier, labeled and color-graded 
  (dark blue → bright blue → gold for increasing risk/reward)
— Each column shows the tier's profile description and the 3 highest-conviction 
  companies within it (name, ticker, one-line thesis, conviction score)
— A risk/reward axis annotation runs across all 5 columns

Chapter 2 closes with a transition card:
"From this universe, we selected the strongest candidate from each tier 
to carry forward into a head-to-head comparison."

---

CHAPTER 3 — THE COMPARATIVE ANALYSIS
"Not all opportunities are equal. Here is how we evaluated the finalists."
Data source: comparative_data.json

Chapter intro: "Perplexity Computer ran a structured 7-dimension comparison 
across the 5 tier finalists. Here is the full analysis — not just the winner."

Subsection A: The Five Finalists
— 5 cards side by side (or stacked on mobile), one per finalist
— Each card: Company name, ticker, tier, 150-word profile, financial snapshot, 
  per-judge fit sentence (Laffont / Loeb / Hao)
— Cards are NOT yet revealing a winner — equal weight, honest presentation

Subsection B: The Comparison Matrix
— 7-dimension heatmap table: rows = dimensions, columns = 5 finalists
— Color coded by score: red (low) → yellow (mid) → green (high)
— Click any cell: 2-sentence explanation of that score appears
— A "Dimension Leader" chip on the highest scorer per row
— Animated: scores fill in sequentially (dimension by dimension) to create 
  a sense of the analysis unfolding

Subsection C: The Selection
— After the matrix fully loads, a gold divider line appears with text:
  "The analysis points to a winner. Here is the decision."
— The winning card pulses gold; the other 4 dim slightly
— A 300-word justification panel appears: thesis sentence, why these judges, 
  why now, strongest competing candidate and why it lost, primary risk accepted
— A final transition card: "This is the company. Now let's go deeper."

---

CHAPTER 4 — THE COMPANY
"Here is what we found when we looked closely."
Data source: research_data.json

Chapter intro: "Perplexity Computer deployed 4 simultaneous research sub-agents — 
Business Intelligence, Financial Analysis, Market Sizing, and Alternative Data — 
running in parallel to build the most complete picture possible."

— Executive Summary panel: one-page company profile with key metrics
— Animated segment breakdown donut chart (revenue by product line)
— Moat scorecard: 5-axis radar chart (Data Moat, Switching Costs, Network 
  Effects, Technical Barriers, Regulatory Position) scored 1–10
— Competitive positioning map: [TICKER] vs. top 5 competitors on 2 configurable axes
— Talent signal: job posting trend chart, 12-month history, by category
— Patent velocity chart: [TICKER] vs. top 3 competitors, quarterly filings
— Alternative data strip: web traffic trend, academic citation velocity
— Source chip on every element
— Sub-agent attribution line at bottom of each subsection

---

CHAPTER 5 — THE FINANCIAL CASE
"The thesis only works if the numbers work. Here is the model."
Data source: model_data.json

Chapter intro: "We built the financial model using SEC EDGAR filings, 
FactSet consensus estimates, and PitchBook comparable transactions."

— Trading Comps table: sortable columns, [TICKER] highlighted, 
  premium/discount to peers flagged in color
— Interactive DCF: scenario toggle (Bear / Base / Bull); sliders for 
  Revenue CAGR, Gross Margin, WACC, Exit Multiple; 
  real-time implied share price and upside/downside
— Scenario bar chart: Bear / Base / Bull vs. current price
— Sensitivity heat map: CAGR × Multiple grid, color coded
— Catalyst calendar: 24-month timeline of upcoming events (earnings, 
  product launches, contract renewals, regulatory decisions), each tagged 
  with probability and impact level

---

CHAPTER 6 — THE STRESS TEST
"Before we concluded, we challenged the thesis."
Data source: council_data.json

Chapter intro: "We invoked Perplexity's Model Council — running GPT-5.4, 
Claude Opus 4.6, and Gemini 3.1 Pro simultaneously — to independently 
challenge every assumption."

— Banner: "3 frontier AI models. 5 stress-test questions. Running in parallel."
— Three model cards side by side, each with its own color identity
— Question navigator: click any of the 5 Qs; all 3 model answers appear simultaneously
— Agreement / Divergence grid: 5×3 heatmap (questions × models), 
  green = agree / yellow = partial / red = diverge
— Synthesis panel: what the three models agreed on, where they diverged, 
  what was adjusted as a result
— "The Loeb Question" callout: 
  "If Dan Loeb sat across from [TICKER]'s CEO, the question would be: 
  [Q5]. Our answer: [answer]." — gold-bordered, largest text on the panel

---

CHAPTER 7 — THE RECOMMENDATION
"Here is the conclusion. Here is why we're confident."

— Full-bleed panel with company name, ticker, "LONG" badge in gold
— The thesis sentence: large, bold, center-aligned — the non-consensus insight
— Key metrics strip: Current Price | Base Case Target | Implied Upside | Market Cap
— Three conviction pillars (one per judge's primary lens):
    Pillar 1 (Laffont): historical infrastructure framing
    Pillar 2 (Loeb): catalyst and valuation discipline
    Pillar 3 (Hao): operational transformation and scale
— Risks & Mitigants: 3 expandable risk cards with traffic-light status and exit criteria
— A final line: "This thesis was built by a human with a vision and 
  Perplexity Computer with access to the data, models, and compute 
  to prove it. Here is how."

---

CHAPTER 8 — HOW THIS WAS BUILT
"The process is part of the evidence."
THIS SECTION IS EXPLICITLY FOR THE JUDGES — the creative use showcase.

Chapter intro: "Every insight in this pitch was generated by Perplexity Computer. 
This chapter shows exactly what ran, when, and why."

— Visual workflow diagram: all 7 Tasks mapped as nodes, with arrows showing 
  data flow from each task into the dashboard (the diagram's final node)
— Task cards (one per task): 
    What this task did | Which Perplexity capability | Which models/agents | 
    Data sources accessed | Estimated runtime
— Key stats panel (large, bold numbers displayed like a product dashboard):
    · Total parallel sub-agents deployed: [N]
    · Premium data sources accessed: [list with source chips]
    · Model Council sessions: [N]
    · Total companies evaluated: [N]
    · Total documents processed: [N]
    · Total async compute time: ~[Z] hours
— "Without Perplexity Computer" comparison:
    · Traditional analyst approach: ~[N] senior analyst-hours
    · Data subscription costs: ~$[X]/year for equivalent access
    · Time to completion: ~[Y] weeks
    · "Perplexity Computer completed this analysis in approximately [Z] hours."
— This section should make the scope feel real and impressive — 
  not a footnote but a demonstration

---

TECHNICAL REQUIREMENTS:
— Single-page app with smooth scroll and persistent left sidebar chapter navigation
— All data baked in from JSON outputs at build time (no external API calls at render)
— PDF export button on each chapter
— Mobile responsive
— Load time < 3 seconds
— The footer strip (sub-agents / sources / Model Council / runtime) is always visible

OUTPUT:
— Deployed live URL (this IS the submission — confirm publicly accessible)
— Source code zip: "[TICKER]_Story_App.zip"
— Confirm all 8 chapters are populated with real data from Tasks 1–6
```

---

## TASK 8 — Monitoring Setup (Bonus if credits allow)
**Runtime estimate:** 30 min

```
Set up a daily async monitoring workflow for [COMPANY NAME] ([TICKER]).
Run each morning; surface a report only when something material changes.

Monitor:
— SEC EDGAR: new 8-K, 10-Q, Form 4 insider trading filings
— News: press releases, analyst upgrades/downgrades > 10% price target change
— Competitors: product launches, funding, contracts among the 8 comps companies
— Hiring signals: surge or freeze in job postings at [TICKER]
— Patent activity: new filings by [TICKER] or top 3 competitors

Trigger a report when:
— Stock moves > 5% in one session
— New SEC filing submitted
— Competitor announces direct competing product
— Any catalyst from Chapter 5's catalyst calendar activates

Output: Confirm monitoring active. Show a sample triggered report.
```

---

## 📋 Execution Checklist & Critical Path

```
CRITICAL PATH:
Task 0 → [Tasks 1 + 2 in parallel] → Task 3 ⚠️ CHECKPOINT → Task 4 → 
[Tasks 5 + 6 in parallel] → Task 7 (SUBMISSION) → Task 8 (bonus)
```

| Task | Description | Runtime | Key Output | Status |
|---|---|---|---|---|
| 0 | Set persistent memory | 5 min | Memory set | ☐ |
| 1 | History: tech, economics, capitalism [‖ T2] | 2–3 hrs | paradigm_data.json | ☐ |
| 2 | Universe: risk/reward spectrum [‖ T1] | 2–3 hrs | universe_data.json | ☐ |
| 3 | Comparative analysis ⚠️ CHECKPOINT | 1.5–2 hrs | comparative_data.json | ☐ |
| 4 | Deep dive on winner | 3–5 hrs | research_data.json | ☐ |
| 5 | Financial model [‖ T6] | 2–3 hrs | model_data.json | ☐ |
| 6 | Model Council stress test [‖ T5] | 1–1.5 hrs | council_data.json | ☐ |
| 7 | BUILD SUBMISSION WEB APP | 3–5 hrs | Live URL (IS the submission) | ☐ |
| 8 | Monitoring setup (bonus) | 30 min | Monitoring active | ☐ |

**[‖] = run in parallel**
**Total estimated async runtime: 15–25 hours**

---

## ⚠️ Notes for Claude Code

**The JSON contract is load-bearing:**
Task 7's web app loads all data from the JSON files produced by Tasks 1–6.
Before execution begins, define the exact JSON schema each task must produce 
so that Task 7's app can ingest them without format mismatches.
Key schemas: paradigm_data, universe_data, comparative_data, research_data, 
model_data, council_data.

**After Task 3 checkpoint:**
Replace ALL `[TICKER]` and `[COMPANY NAME]` placeholders in Tasks 4–8 with 
the selected company before pasting into Perplexity Computer.

**Chapter intros are non-negotiable:**
The italic "why we looked here next" framing on each chapter is what makes 
this a story rather than a data dump. They must be written with the specific 
judges' voices in mind — analytical, precise, no hedging.

**Chapter 8 (How This Was Built) is a primary judging criterion:**
Populate it with real task log data, not estimates. If Perplexity provides 
runtime logs or source counts, use those exact numbers.

**Credit conservation priority if Pro limits bite:**
1. Task 0 (free)
2. Task 3 (comparative analysis — without this the story has no spine)
3. Task 4 (deep dive — the substance)
4. Task 6 (Model Council — the showcase)
5. Task 7 (the submission — required)
6. Tasks 1, 2 can be abbreviated but not skipped (Chapter 1 and 2 need data)
7. Task 5 can use simplified comps if needed
8. Task 8 is truly optional
