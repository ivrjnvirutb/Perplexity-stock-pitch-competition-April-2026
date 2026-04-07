# CRDO Submission Thread — 3 Prompts to Paste into Perplexity Computer
> Paste in order into ONE new Perplexity Computer Task. This thread IS the submission.
> Do not start a new task between prompts. Wait for each output before pasting the next.

---

## PROMPT 1 OF 3 — Full Investment Thesis Web App

Paste this as the **first message** in a new Perplexity Computer Task.

---

```
You are building the final submission for the Perplexity Stock Pitch Competition (judges: Philippe Laffont / Coatue, Dan Loeb / Third Point, Ken Hao / Silver Lake). The submission is a long investment thesis on Credo Technology Group (NASDAQ: CRDO).

Build a single-file interactive web app (index.html) — a dark, premium, scroll-based investment presentation with 8 chapters. All data is provided below. Do not invent numbers. Build the full app in one pass.

---

## DESIGN SPEC

- Dark navy background (#0A0E1A), gold accent (#C9A84C), blue accent (#2D6FFF)
- Font: Space Grotesk (headings, display numbers), Inter (body)
- Full-screen chapter panels, scroll-triggered animations (Intersection Observer)
- Persistent left-side chapter navigation sidebar (Ch1–Ch8)
- Mobile responsive
- PDF export button (fixed bottom-right, window.print())
- Source chips (pill badges) on every chapter citing the data sources used
- Every chapter has an animated entrance (opacity 0 → 1, translateY 28px → 0)

---

## CHAPTER STRUCTURE + CONTENT

### Chapter 1 — The World Before the Answer
**Title:** "Infrastructure always wins first."
**Subtitle:** "We are in 1996."

Left side: Animated horizontal bar chart — 6 technology eras, bar width = relative investor return. Click each bar to expand detail card.

| Era | Bottleneck Solver | Peak 10yr Return | Key Insight |
|---|---|---|---|
| Industrial Revolution (1760–1850) | Boulton & Watt | Foundational (~15% IRR) | Steam patent = rent on all industrial output |
| Electrification (1880–1930) | General Electric | Foundational | Paul David (1990): 25-year lag before productivity gain |
| Computing (1950–1990) | IBM | Foundational | Platform era required infrastructure stability first |
| Internet (1993–2003) | Cisco | +118,741% | $1B → $550B cap following TCP/IP buildout |
| Mobile (2003–2013) | Qualcomm | +3,000% | CDMA patents = toll road for smartphone era |
| AI (Now) | ? | ? | "We are here." Pulsing gold bar. |

Right side: Animated ratio counter.
- AI CapEx 2025: $443B (animates up from $0)
- AI Application Revenue 2025: ~$49B (animates up from $0)
- "9:1 ratio — identical to 1997 internet"
- Quote: "The market is pricing AI infrastructure like it priced the internet in 1996. That window closes."

Source chips: Goldman Sachs, McKinsey Global Institute, NBER, Statista, Epoch AI, CB Insights

Process note (small text below source chips): "4 parallel sub-agents | 118 primary sources | SA1: Technology Paradigm Shifts (26 sources, 50KB output) · SA2: Economic Cycles (42 sources, 40KB output) · SA3: AI Historical Arc (30 sources, 27KB output) · SA4: Civilizational Impact (20 sources, 34KB output)"

---

### Chapter 2 — Locating the Opportunity
**Title:** "59 companies. 7 AI transformation categories. 5 tiers of risk and reward."
**Subtitle:** "The market offered a spectrum. We mapped it."

Interactive bubble chart: X-axis = NTM Revenue Growth %, Y-axis = Gross Margin %, bubble size = market cap. CRDO bubble highlighted gold. Other bubbles muted. Hover to see ticker + metrics.

Plot these companies (use approximate coordinates):
- NVDA: growth 65%, GM 71%, large bubble
- PLTR: growth 56%, GM 82%, medium bubble
- CRDO: growth 90%, GM 68%, medium bubble — GOLD, pulsing
- AVGO: growth 53%, GM 67%, very large bubble
- MRVL: growth 32%, GM 50%, large bubble
- ALAB: growth 58%, GM 76%, small bubble
- ZETA: growth 30%, GM 61%, small bubble
- BOX: growth 8%, GM 79%, small bubble

Below chart: 5-tier framework table.

| Tier | Label | Risk Profile | Winner |
|---|---|---|---|
| 1 | Conservative Anchor | Proven platform, premium multiple | NVDA |
| 2 | Established Grower | High growth, execution premium | PLTR |
| 3 | High Conviction Growth | Mispriced, moat-gated | **CRDO ★** |
| 4 | Speculative Asymmetric | Cookie-deprecation catalyst | ZETA |
| 5 | Deep Value / Turnaround | FCF machine, compliance moat | BOX |

Source chips: PitchBook, CB Insights, FactSet, SEC EDGAR, Goldman Sachs

Process note: "7 parallel sub-agents — one per AI transformation category — mapped every qualifying NYSE/NASDAQ company with market cap >$1B. 59 companies evaluated. Each sub-agent scored independently on: AI infrastructure criticality, moat durability, growth visibility, valuation vs. opportunity."

---

### Chapter 3 — The Comparative Analysis
**Title:** "Five finalists. Seven dimensions. One winner."

7-dimension comparison matrix table. Color code each cell: dark green = leader, light green = strong, yellow = average, orange = weak.

| Dimension | NVDA | PLTR | CRDO | ZETA | BOX |
|---|---|---|---|---|---|
| Moat Durability (5yr) | 10 | 9 | **8** | 7 | 6 |
| Growth Visibility | 9 | 8 | **8** | 6 | 7 |
| Valuation vs. Opportunity | 8 | 5 | **9** | 9 | 8 |
| Catalyst Specificity | 8 | 9 | **8** | 7 | 7 |
| Judge Resonance | 10 | 9 | **8** | 7 | 7 |
| Non-Consensus Advantage | 6 | 7 | **9** | 8 | 8 |
| Data Advantage | 7 | 9 | **9** | 9 | 7 |
| **Total** | **58** | **56** | **59 ★** | **53** | **50** |

Below table: expandable finalist cards. Each card shows ticker, tier label, profile (150 words), key risk, judge fit.

Winner callout box (gold border):
**CRDO wins.** Not because it is the highest-conviction company — NVDA is. But because every judge in this room already owns NVDA and knows its thesis better than any presentation can explain. CRDO is the non-consensus insight: the mandatory IP tollgate for NVL72-class AI factory interconnect, trading at a 41.5% discount to peers, with 96% consensus upside and a binary catalyst on June 2, 2026.

Source chips: PitchBook, CB Insights, FactSet, Bloomberg

---

### Chapter 4 — The Company
**Title:** "Credo Technology Group (NASDAQ: CRDO)"
**Subtitle:** "The only commercially validated 224G SerDes AEC stack at hyperscale."

Left column:
- 3-pillar moat diagram (animated, staggered reveal):
  1. Proprietary 224G PAM4 SerDes IP on TSMC N3 — 40-50 dB channel loss handled by embedded DSP. Patent portfolio: 100+ issued US patents. ITC 337-TA-1446 enforced. Key patent US11032111 expires 2039.
  2. ZeroFlap Zero-Link-Flap Reliability — 1,000x better uptime than optical modules (no laser components). Critical for hyperscaler SLAs.
  3. HiWire System-Level Integration — chip + cable assembly designed with hyperscalers since 2019–2021. Co-design = 4+ year qualification head start.

- Qualification timeline visual (horizontal pipeline stages):
  Phase 1 Design Win (12–18mo) → Phase 2 Engineering Validation (6–12mo) → Phase 3 Production Validation (3–6mo) → Phase 4 Volume Ramp
  Milestone markers: Microsoft 2021 · Amazon 2022–23 · xAI 2024 · Google 2025–26 · Meta 2025–26

Right column:
- 5 hyperscaler customer logos / badges (animated staggered reveal):
  AWS (~39% revenue) · Microsoft (~17%) · xAI (~32% combined top-3) · Google (10%+) · Meta (initial Q3 FY2026)
  Label: "All 5 major AI hyperscalers. Qualified. Ramping."

- Competitive landscape table:

| Competitor | Status | Threat Timeline |
|---|---|---|
| Marvell | Sampling only — 'Golden Cable' Dec 2025; no hyperscaler volume | Best case 2027–2028 |
| Broadcom | Announced 800G AEC retimer (Sian3 3nm), no hyperscaler AEC wins | No confirmed volume |
| Astera Labs | PCIe/CXL retimers — not direct AEC competitor | Different market |
| Hyperscaler Internal | No confirmed custom AEC silicon program | CPO is longer-term play |

- Hiring signal box: "29 open roles as of April 2026: 9 optical engineering (Ottawa) → ZeroFlap optics ramp is real. 7 ASIC/SerDes roles. 2 new Sales Directors: Neocloud/Enterprise AI + Enterprise OEM (HPE/Dell/Lenovo) — expanding beyond hyperscalers."

Source chips: SEC EDGAR, IEEE Patents, DesignCon 2026, LinkedIn, SemiAnalysis

Process note: "4 simultaneous sub-agents: Business Intelligence (technical moat, patent analysis) · Financial Analysis (12-quarter model) · Market Sizing (bottom-up TAM) · Alternative Data (hiring, short interest, options IV)"

---

### Chapter 5 — The Financial Case
**Title:** "Bear / Base / Bull — and a catalyst the options market hasn't priced."

Left side:

Revenue trajectory bar chart (12 quarters Q4 FY2023 → Q3 FY2026):
Q4 FY23: $32M | Q1 FY24: $35M | Q2 FY24: $44M | Q3 FY24: $53M | Q4 FY24: $61M
Q1 FY25: $60M | Q2 FY25: $72M | Q3 FY25: $135M | Q4 FY25: $170M
Q1 FY26: $223M | Q2 FY26: $268M | Q3 FY26: $407M ← gold bar, annotation "↑ $407M / quarter"
Growth label: "+1,169% in 9 quarters"
Gross margin trend line overlay: 57.9% → 68.5%

Guidance accuracy strip (11 quarters):
Show BEAT/MISS badge per quarter. 10 of 11 beats. Q1 FY25 was the only miss (guided $64M, actual $59.7M).
Label: "Guides conservatively. Beats consistently. 83% beat rate."

Key metrics pills (click to expand):
- Gross Margin: 68.5% (record high — hardware with software economics)
- Net Cash: $1.29B (no debt, no dilution risk in any scenario)
- Guidance Beats: 10/11 (83% beat rate since IPO)

Right side:

EV/NTM Revenue comparison:
Peers median: 14.7x | CRDO: 8.6x
Peers used: ALAB 13.9x (+58% NTM growth) · MRVL 8.8x (+32%) · MPWR 15.9x (+21%) · AVGO 14.7x (+53%) · MTSI 15.4x (+15%)
Callout: "CRDO at 8.6x with +90% NTM growth. Peers at 14.7x with +32% median growth. −41.5% discount despite +57pp growth advantage."
Click table to expand full comps view.

DCF scenario bars (clickable, expand to show assumptions):
- Bear $71 (−30%): Marvell qualifies at 2nd hyperscaler, margins compress to 60%, 6x exit · WACC 14% · FY27 rev $1.95B
- Base $181 (+78%): Management executes roadmap, market share stable, 10x exit · WACC 12% · FY27 rev $2.025B ← current baseline
- Bull $358 (+253%): 5th hyperscaler full deployment, margin re-rates toward software, 14x exit · WACC 11% · FY27 rev $2.1B

Interactive DCF slider: "Adjust exit multiple" range 6x–16x, real-time price output. Base case at 10x = $181. At 8x = $145. At 14x = $254.

Sensitivity heatmap (5×5 grid):
Rows: FY2028 growth 20% / 30% / 40% / 50% / 60%
Cols: Exit multiple 6x / 8x / 10x / 12x / 14x
Color code: red <$101, yellow $101–150, light green $150–200, dark green >$200
Values: [[127,142,156,171,186],[137,153,169,184,200],[147,164,181,198,215],[156,175,193,211,229],[166,186,205,225,244]]
Current price line at $101.45.

Catalyst box (gold border, animated pulse):
📅 June 2, 2026 — Q4 FY2026 Earnings
- Consensus: $428M | Mgmt Implied: ~$430–440M | Bull case: $455M
- Beat probability: 83% historical rate (10 of 12 quarters)
- Options IV: 9.9% implied vs. 11.8% historical realized → 33rd percentile
- "Options are historically cheap. The binary event is underpriced."

Source chips: FactSet, SEC EDGAR, S&P Global, PitchBook

---

### Chapter 6 — The Stress Test
**Title:** "We asked the hardest questions before you could."
**Subtitle:** "Perplexity Model Council — GPT-5.4, Claude Opus 4.6, Gemini 3.1 Pro — ran in parallel. Zero coordination between models."

Three model cards (side by side, hover to reveal unique insight):
- GPT-5.4 (green border): "Primary source analysis · Most granular swim-lane breakdown" → hover: "Credo's S-1 discloses a 2–3 year design cycle — shorter than the thesis's 36–48 month framing. Separately, S-1 confirms competitors, weakening 'mandatory toll gate' language."
- Claude Opus 4.6 (orange border): "Competitive re-rating · Quantified bear scenarios" → hover: "Re-rates to $55–70 even with continued revenue growth if multiple compresses from ~10x to 5–6x on Marvell hyperscaler entry. That's the real bear case."
- Gemini 3.1 Pro (blue border): "Category-level risk · Optical substitution threat" → hover: "LPO and CPO optical solutions could bypass AECs entirely — not Marvell competition but AEC category obsolescence. Gemini was the only model to raise this."

5-question navigator (button row Q1–Q5, click to show all 3 model responses side-by-side):

Q1: "What are the three weakest assumptions in this thesis?"
Q2: "What is the single most likely path to losing money on this investment over 24 months?"
Q3: "What one piece of evidence, if confirmed, would most strengthen conviction?"
Q4: "Does Credo have a durable competitive moat in 5 years — yes or no, and exactly why? (Consider 448G transition, hyperscaler internal silicon, ITC patent position.)"
Q5 (Dan Loeb Question): "Bill, you've described full swim-lane penetration at your largest hyperscaler and engagement with five of the top seven. Marvell demonstrated a working 224G 1.6T AEC at DesignCon in February with 10^-10 pre-FEC BER over 3 meters on their Alaska A DSP. My question is specific: Of your top three hyperscaler customers, how many have formally indicated they will NOT qualify a second AEC source for their next-generation 1.6T rack architecture — and for those that are evaluating alternatives, at what stage of qualification is the competing solution today? Because if every major customer is actively qualifying Marvell's AEC alongside yours, then the right valuation framework is a competitive-market multiple, not a sole-source monopoly premium."

"Our Answer" reveal button for Q5:
"Hyperscalers dual-source every critical component — we've never claimed otherwise. The premium reflects a 24–30 month revenue visibility advantage, not a monopoly. Marvell's DesignCon demo requires 2–3 years of swim-lane qualification across five distinct deployment categories. We are three years into that process. The fifth hyperscaler win and Microsoft design win extension are evidence of deepening alignment, not displacement. We do not build our business plan around permanent sole-source status. We build it around compounding qualification advantages, rising ASPs at each speed node, and expanding swim-lane coverage per customer."

Model Council consensus / divergence chips (animated staggered reveal):
✓ All 3 models agree: Customer concentration is the #1 near-term risk
✓ All 3 models agree: A second hyperscaler achieving broad production deployment = strongest conviction signal
✓ All 3 models agree: Qualification lead-time is real but not insurmountable for incumbents like Marvell
△ Divergence: Optical substitution risk (LPO/CPO) flagged by Gemini 3.1 Pro only — the only model to raise category obsolescence rather than AEC competition
△ Divergence: Moat durability at 5 years — GPT-5.4: YES (narrower but real) | Opus 4.6: NO (vulnerable at 448G) | Gemini: NO (hyperscalers will fund alternatives)
△ Divergence: What changed the thesis — GPT-5.4 corrected the qualification timeline (2–3yr not 3–4yr per S-1). Opus quantified the bear case as $55–70. Gemini introduced the optical substitution risk.

Source chips: GPT-5.4, Claude Opus 4.6, Gemini 3.1 Pro, Perplexity Model Council, SEC EDGAR, DesignCon 2026

---

### Chapter 7 — The Recommendation
**Title:** "Long CRDO. $181 base case. +78% upside. June 2 is the test."

Three conviction pillars (one per judge, gold/blue/navy card):

**Philippe Laffont (Coatue):** IP moat in a capacity-constrained, qualification-cycle-gated market. CUDA compounding is the framework — Credo's AEC qualification cycles create the same sticky platform dynamic at the hardware interconnect layer. Every NVL72-class rack is a recurring revenue event.

**Dan Loeb (Third Point):** 16 analysts, median $200 target, stock at $101. 96% consensus upside at a profitable semiconductor company growing revenue +400% YoY. The mispricing is measurable, the catalyst is June 2, and the options market is pricing in less uncertainty than history warrants.

**Ken Hao (Silver Lake):** AEC and 224G SerDes IP requires understanding physics that standard institutional research cannot quantify. Perplexity's access to IEEE patents, hyperscaler procurement data, and DesignCon technical filings enabled unique non-consensus insight. This is a Silver Lake-style technical complexity discount that data-driven research resolves.

Three risks (expandable cards):
1. Customer Concentration (top 3 = 88% revenue) — Mitigant: 4+ year qualification timeline before replacement reaches production. Microsoft and Amazon extended design wins, not pulled them. Exit signal: formal qualification initiation by Marvell at a top-2 hyperscaler confirmed by channel check.
2. Margin Compression (ZeroFlap optical ramp diluting GM to 64–66%) — Mitigant: optical mix shift is temporary; ZeroFlap ultimately supports margin re-rate toward 70%+ as scale reaches. Exit signal: two consecutive quarters of GM below 63%.
3. 448G Speed Node Transition — Mitigant: Blue Heron 224G multiprotocol retimer sampling now; 1.6T ZeroFlap AECs sampling for H2 CY2026. Credo moving faster than the transition. Exit signal: Marvell announces confirmed production volume at any hyperscaler.

Source chips: Goldman Sachs, SEC EDGAR, FactSet, Perplexity Model Council

---

### Chapter 8 — How This Was Built
**Title:** "The methodology is the edge."
**Subtitle:** "Built with Perplexity Computer. This is what parallel multi-model research looks like."

SVG workflow diagram: 8 task nodes in a DAG layout, showing parallel execution and dependencies.
- Tasks 1–6 ran first (Tasks 1, 2, 3, 4, 5, 6 with parallel sub-agents per task)
- Task 7 (Model Council) ran after Tasks 3–5 synthesized
- Task 8 (this app) built from all prior task outputs

Task log table:

| Task | Description | Agents | Sources | Output |
|---|---|---|---|---|
| 1 | Technology History & Economic Foundations | 4 parallel | 118 sources | 151KB |
| 2 | AI Universe Mapping | 7 parallel (1 per AI category) | 59 companies | Universe spreadsheet |
| 3 | Comparative Analysis — 5 Finalists | 5 parallel | 7 dimensions | Selection matrix |
| 4 | CRDO Deep Dive | 4 parallel | SEC EDGAR, IEEE, LinkedIn, FactSet | Research dossier |
| 5 | Financial Model | 1 specialist | FactSet, S&P Global, PitchBook | DCF + sensitivity |
| 6 | Model Council Stress Test | 3 frontier models × 5 questions | — | 15 independent responses |
| 7 | Synthesis & Recommendation | Orchestrator | All prior outputs | Judge-specific conviction pillars |
| 8 | Submission Web App (this) | GPT-5.3-Codex | All JSON outputs | Single-file interactive app |

3 discoveries that changed the pitch (animated reveal):
1. **The 41.5% discount** — discovered by simultaneously cross-referencing FactSet NTM multiples, PitchBook peer set, and CB Insights category mapping. No single source contained all three inputs. Parallel compute surfaced the anomaly in hours, not days.
2. **The qualification timeline correction** — GPT-5.4 retrieved Credo's own S-1 disclosing a 2–3 year design cycle, not the 36–48 month framing in the draft thesis. This tightened the moat language from "insurmountable" to "substantial 24–30 month head start."
3. **The optical substitution risk** — Gemini 3.1 Pro alone raised LPO/CPO as a category-obsolescence threat. The other two models focused on AEC competition. This introduced a new bear case (AEC replacement) that was not in the original thesis and is now reflected in the risk section.

Comparison table: "Without Perplexity" vs. "With Perplexity Computer"

| | Manual Research | Perplexity Computer |
|---|---|---|
| Companies evaluated | ~15 (typical coverage) | 59 (7 parallel sub-agents) |
| Time to comparable set | 3–5 days | ~4 hours |
| Data sources synthesized | Public sources only | IEEE patents, DesignCon filings, hyperscaler procurement data, PitchBook, FactSet |
| Bear case quality | Single analyst view | 3 frontier models × 5 questions = 15 independent stress tests |
| Unique insight generated | Consensus view | 41.5% mispricing, S-1 timeline correction, optical substitution risk |

Closing line (large, gold, centered): "19 sub-agents · 3 frontier models · 6 premium data sources · 59 companies evaluated · ~20 hours of async compute"

---

## TECHNICAL REQUIREMENTS

- All charts built with vanilla JS (no external chart libraries) or CSS-only
- All data hardcoded from the values above — no API calls
- Intersection Observer for all section entrance animations
- Single index.html file, no external dependencies except Google Fonts
- Include a PDF export button (window.print() with @media print styles)
- Chapter navigation sidebar: clicking a chapter name smooth-scrolls to that section
- All source chip badges visible on every chapter
- Output: single deployable index.html file
```

---

## PROMPT 2 OF 3 — Concise 2-Minute Video Companion App

Paste this as the **second message** in the same thread, after the full thesis app is complete.

---

```
Now build a second web app in the same thread — a concise 2-minute video companion to the full thesis above.

This is a separate file (concise.html). It is designed to be screen-recorded as a 2-minute walk-through video. Six full-screen panels, each readable in ~20 seconds. Same dark design system as the full thesis. All data is the same.

The critical difference from a typical executive brief: Panel 6 must visually showcase the Perplexity Computer methodology — this is the 30-point judging criterion and must be as prominent as the financial case.

---

## DESIGN SPEC
- Same dark navy/gold/blue design system as the full thesis
- Each panel = full viewport height (100vh), centered content
- Smooth scroll between panels via keyboard arrow or scroll
- Scroll progress indicator (thin gold bar at top, fills left to right as user scrolls through all 6 panels)
- Animated number count-ups on Panel 1 stat cards (trigger on scroll into view)
- Panel transition: scroll-snap or Intersection Observer reveals

---

## PANEL STRUCTURE

### Panel 1 — The Call (15 seconds)
Center layout, hero style.

Badge: "LONG" (gold pill, pulsing dot)
Company: "Credo Technology Group"
Ticker: "NASDAQ: CRDO" (blue)
Thesis: "The dominant qualified incumbent at 224G SerDes — every NVL72-class AI factory rack must use Credo's technology — trading at a 41.5% discount to peers with a binary catalyst on June 2, 2026."

4 animated stat cards (count up from zero on load):
- $101.45 — Current Price
- $181 — Base Case Target
- +78% — Upside
- $1.29B — Net Cash

Source chips: PitchBook · FactSet · SEC EDGAR · CB Insights

---

### Panel 2 — Why Now (20 seconds)
Title: "The infrastructure phase is the entry point."
Subtitle: "We are in 1996."

Left: Animated horizontal bar chart (6 eras, same as Chapter 1 above — Industrial Revolution through AI Now, gold pulsing bar for AI).

Right: Animated ratio counter
- AI CapEx: $443B (animates up)
- App Revenue: ~$49B (animates up)
- Label: "9:1 ratio — identical to 1997"
- Quote: "The market is pricing AI infrastructure like it priced the internet in 1996. That window closes."

Source chips: Goldman Sachs · Statista · NBER · Epoch AI

---

### Panel 3 — Why Credo (20 seconds)
Title: "1,169% revenue growth. 41.5% discount to peers. One reason."

Left: Revenue bar chart (9 quarters, Q3 FY2024 → Q3 FY2026):
Q3 FY24: $53M | Q4 FY24: $61M | Q1 FY25: $60M | Q2 FY25: $72M | Q3 FY25: $135M | Q4 FY25: $170M | Q1 FY26: $223M | Q2 FY26: $268M | Q3 FY26: $407M (gold, annotated "↑ $407M/quarter")
Gross margin overlay: rising from 61% → 68.5%

3 metric pills (click to expand):
- Gross Margin: 68.5%
- Net Cash: $1.29B
- Guidance Beats: 10/11

Right: Valuation disconnect (click to expand comp table):
- Peers: 14.7x NTM EV/Revenue
- CRDO: 8.6x NTM EV/Revenue
- "−41.5% discount despite +57pp growth advantage"
- "Implied price at peer median: ~$168 (+65.6%)"
- Comp table: ALAB 13.9x (+58%) · MRVL 8.8x (+32%) · MPWR 15.9x (+21%) · AVGO 14.7x (+53%) · MTSI 15.4x (+15%) | Peer median 14.7x | CRDO 8.6x ★

Moat text (typewriter animation): "Credo owns the only commercially validated Active Electrical Cable IP at 224G SerDes. Every NVL72 rack, every TPU pod, every Trainium cluster at 800G or above. 100+ patents. ITC enforced. 4-year hyperscaler qualification head start. No competitor is in production."

Source chips: FactSet · PitchBook · S&P Global · SEC EDGAR

---

### Panel 4 — The Numbers (25 seconds)
Title: "Bear / Base / Bull — and a catalyst the options market hasn't priced."

Scenario bars (click to expand detail card):
- Bear $71 (−30%): Marvell qualifies at 2nd hyperscaler · margins compress to 60% · 6x exit multiple applied
- Base $181 (+78%): Management executes roadmap · market share stable · 10x exit on $2.025B FY27 revenue
- Bull $358 (+253%): 5th hyperscaler ramps to full deployment · margin re-rates toward software · 14x exit multiple

DCF slider: "Adjust exit multiple" (6x–16x range), real-time output showing price and upside. Base = 10x = $181 (+78%).

Catalyst box (gold border, pulsing):
📅 June 2, 2026 — Q4 FY2026 Earnings
- Consensus: $428M | Mgmt Implied: $430–440M | Bull: $455M
- Beat rate: 83% (10 of 12 quarters)
- Options IV: 9.9% implied vs. 11.8% historical → 33rd percentile
- Click to reveal: "Options are historically cheap. The binary event is underpriced. Breakeven long call: $111.50."

Source chips: FactSet · SEC EDGAR · S&P Global

---

### Panel 5 — The Stress Test (20 seconds)
Title: "We asked the hardest questions before you could."

Intro: "Perplexity Model Council — GPT-5.4, Claude Opus 4.6, Gemini 3.1 Pro — ran in parallel to challenge every assumption. Zero coordination between models."

3 model cards (hover reveals unique insight):
- GPT-5.4 (green): "Primary source analysis · Swim-lane breakdown" → hover: "S-1 discloses 2–3yr design cycle, shorter than thesis's framing. Qualification head start is real but narrower."
- Claude Opus 4.6 (orange): "Competitive re-rating · Quantified bear" → hover: "Re-rates to $55–70 if Marvell qualifies at a second hyperscaler at scale. Multiple compression from ~10x to 5–6x."
- Gemini 3.1 Pro (blue): "Category-level risk · Optical substitution" → hover: "LPO/CPO optical solutions could bypass AECs entirely — not competition within AECs but AEC category obsolescence."

Dan Loeb question box (gold border, typewriter animation):
"Bill, of your top three hyperscaler customers, how many have formally indicated they will NOT qualify a second AEC source for their next-generation 1.6T rack architecture — and for those evaluating alternatives, at what stage of qualification is the competing solution today?"
[Click "Our Answer"] → reveals: "Hyperscalers dual-source every critical component — we've never claimed otherwise. The premium reflects a 24–30 month revenue visibility advantage, not a monopoly. Marvell's demo requires 2–3 years of swim-lane qualification Credo already completed. The fifth hyperscaler win and Microsoft design win extension are evidence of deepening alignment, not displacement."

Consensus chips (staggered animated reveal):
✓ All 3 models: Customer concentration is the #1 risk
✓ All 3 models: Second hyperscaler win = strongest conviction signal
△ Divergence: Optical risk (LPO/CPO) flagged by Gemini 3.1 Pro only
△ Divergence: 5-year moat — GPT-5.4: YES · Opus 4.6: NO · Gemini: NO

Source chips: Perplexity Model Council · GPT-5.4 · Claude Opus 4.6 · Gemini 3.1 Pro

---

### Panel 6 — How This Was Built (20 seconds)
Title: "The methodology is the edge."
Subtitle: "Every number in this pitch was surfaced by Perplexity Computer's parallel multi-agent research."

Left: Mini SVG workflow diagram — 6 task nodes arranged in a pipeline with parallel branches:
- Task 1: History (4 sub-agents) → Task 2: Universe (7 sub-agents) → Task 3: Comparison (5 parallel) → Task 4: Deep Dive (4 sub-agents) → Task 5: Financials → Task 6: Model Council (3 models × 5 Qs) → This App

Stats (large, animated count-up):
- 19 parallel sub-agents
- 3 frontier models
- 118 primary sources (Task 1 alone)
- 59 companies evaluated
- ~20 hours async compute

3 discoveries (animated reveal, staggered):
1. "41.5% discount — surfaced by simultaneously cross-referencing FactSet, PitchBook, and CB Insights. No single source contained all inputs."
2. "Qualification timeline — GPT-5.4 corrected the thesis by retrieving Credo's S-1 directly: 2–3yr, not 3–4yr."
3. "Optical risk — Gemini 3.1 Pro alone raised LPO/CPO as a category-obsolescence threat. Now in the risk section."

Comparison table:
| | Manual Research | Perplexity Computer |
|---|---|---|
| Companies evaluated | ~15 | 59 (7 parallel sub-agents) |
| Bear cases generated | 1 analyst view | 15 responses (3 models × 5 questions) |
| Unique insight | Consensus view | Mispricing · S-1 correction · Optical risk |

Closing line (large, centered, gold):
"Built with Perplexity Computer · 19 sub-agents · 3 frontier models · 6 premium data sources · 59 companies · ~20 hours of async compute"

---

## TECHNICAL REQUIREMENTS
- Single concise.html file
- Same design tokens as full thesis (same fonts, colors, CSS variables)
- All 6 panels are full viewport height with scroll-snap or smooth scroll
- Gold scroll progress bar at top
- All charts/animations in vanilla JS
- PDF export button
- No external dependencies except Google Fonts
- Output: single deployable concise.html file
```

---

## PROMPT 3 OF 3 — Polish Pass (send only if needed)

Only paste this if either output has obvious issues (broken charts, missing sections, placeholder content).

---

```
Please review both files (index.html and concise.html) and fix the following:

1. Ensure every chapter/panel has working source chip badges visible
2. Confirm the DCF slider in both files recalculates correctly at 6x, 10x, and 16x exit multiples against $2.025B FY27 revenue
3. Confirm the sensitivity heatmap color coding shows red below $101.45, yellow $101–150, light green $150–200, dark green above $200
4. Confirm the Model Council Q5 "Our Answer" button reveals the full management response text
5. Confirm the Chapter 8 / Panel 6 process notes, task log, and 3 discoveries are all present and not truncated
6. Confirm the scroll progress indicator in concise.html fills correctly across all 6 panels
7. Fix any mobile layout issues in either file

Output the corrected files.
```
