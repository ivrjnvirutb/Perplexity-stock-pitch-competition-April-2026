# Stage 05 — Financial Model

**Perplexity Task:** Task 5  
**Purpose:** DCF valuation, trading comps, scenario analysis, and catalyst calendar for CRDO

---

## What This Stage Produced

A rigorous financial model covering three DCF scenarios, a trading comparable analysis, a sensitivity matrix, and a 24-month catalyst calendar. Designed to satisfy Loeb's demand for valuation discipline and Laffont's requirement for rigorous financial modeling.

### Model Components

| Component | Description |
|---|---|
| **DCF — Bull case** | Hyperscaler penetration accelerates; 2–3 new design win ramps; TAM expansion toward $20B |
| **DCF — Base case** | Current trajectory continues; existing design wins ramp per guidance |
| **DCF — Bear case** | Customer concentration risk materializes; one major hyperscaler delays or pauses |
| **Trading comps** | Peer group: Marvell, Broadcom (connectivity segment), Inphi legacy, selected fabless semis |
| **Sensitivity matrix** | Revenue growth rate vs. terminal multiple; shows where consensus is mispriced |
| **Catalyst calendar** | 24-month timeline of specific events that will force market repricing |

---

## Files

| File | Description |
|---|---|
| `CRDO_Financial_Model.xlsx` | Full financial model: DCF scenarios, comps, sensitivity, catalyst calendar |
| `model_data.json` | Structured data for web app charts (scenario outputs, comp table, catalyst dates) |

---

## Key Outputs

**Bull/Base/Bear scenario discipline:** Each scenario has genuinely different underlying assumptions — not just ±20% on the same base. The bull case assumes 5th hyperscaler full deployment and margin re-rate; the bear case assumes Marvell qualifies at a second hyperscaler and margins compress to 60%.

**The non-consensus argument:** Consensus models treat CRDO as a single-customer concentration risk. Our analysis shows that customer concentration at this stage of a design-win cycle is a *leading indicator of future revenue diversification*, not a terminal risk — and prices the stock as if the concentration never resolves.

**Price targets (from model_data.json):**
- Bear: $71 (−30%) — WACC 14%, 6x exit multiple, FY27 revenue $1.95B
- Base: $181 (+78%) — WACC 12%, 10x exit multiple, FY27 revenue $2.025B
- Bull: $358 (+253%) — WACC 11%, 14x exit multiple, FY27 revenue $2.1B

**Comp set (peer median EV/NTM Revenue: 14.7x vs. CRDO 8.6x):** ALAB 13.9x · MRVL 8.8x · MPWR 15.9x · AVGO 14.7x · MTSI 15.4x

**Key catalyst:** June 2, 2026 — Q4 FY2026 earnings. Options IV at 9.9% implied vs. 11.8% historical (33rd percentile). Options are historically cheap for the magnitude of the binary event.

---

## Perplexity Capabilities Used

- **FactSet** for financial data, consensus estimates, and historical trading multiples
- **S&P Global** for credit and capital structure analysis
- **PitchBook** for private market comparable transactions and revenue multiples
- Scenario modeling built inside Perplexity Computer's spreadsheet output capability

---

## Where This Feeds in the Final App

**Chapter 5: The Financial Case** — Interactive scenario toggle (Bull/Base/Bear), sensitivity heatmap, trading comp table, and the catalyst calendar timeline. Designed to let judges interrogate the assumptions directly.
