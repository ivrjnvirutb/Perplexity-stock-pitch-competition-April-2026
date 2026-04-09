# X Post (under 280 chars)

built a @perplexity_ai stock pitch in 1 day.

→ mapped the tool's capabilities first
→ grounded thesis in civilizational history
→ 59 companies, 7 AI categories
→ 7-dimension matrix → $CRDO

AI amplifies conviction. it can't manufacture it.

@askperplexity @PPLXFinance [link]

@askperplexity @PPLXFinance [link]

---

# X Thread (for later — if the single post gets traction)

1/

i designed a full AI research pipeline for a stock pitch competition judged by Philippe Laffont, Dan Loeb, and Ken Hao.

here's the technical breakdown — the architecture, the constraints, the pivots, and what i'd do differently.

@perplexity_ai @PPLXFinance 🧵

---

2/

the constraint that shaped everything:

@askperplexity Computer runs tasks asynchronously and unattended. you fire a task and walk away for hours.

that meant i couldn't iterate mid-run. i had to design the entire pipeline upfront — what each task produces, what the next task consumes, and exactly where every output lands in the final web app.

no planning = broken pipeline.

---

3/

the architecture: 8 tasks, parallelism built in where it mattered.

Task 0: persistent memory context (5 min, most leveraged thing i did — every subsequent task inherited this framing automatically)
Tasks 1 + 2: ran in parallel — civilizational history research + 59-company universe mapping
Task 3: comparative analysis ← hard checkpoint before committing to one stock
Tasks 4 + 5 + 6: deep dive + financial model + Model Council stress test (5 + 6 in parallel)
Task 7: web app built from all prior JSON outputs

---

4/

the JSON contract was the load-bearing piece of the entire system.

before writing a single task prompt, i defined the exact output schema every task had to produce.

Task 7 (the submission web app) was written to ingest those schemas at build time — specific field names, nested objects, array structures.

if any upstream task drifted from the schema: silent failure. the app just wouldn't populate.

lesson: design your output format before you design your prompts.

---

5/

the most important design decision: Task 3 as a hard checkpoint.

before going 5+ hours deep on one company, i forced a structured comparison across 5 finalists — one per risk/reward tier.

7 dimensions scored: moat durability, growth visibility, valuation vs. opportunity, catalyst specificity, judge resonance, non-consensus advantage, data advantage.

CRDO scored 59/70. NVDA scored 58. but NVDA lost — every judge in the room already owns it. the edge was in the non-consensus pick.

the checkpoint is what made that visible before i wasted compute on the wrong company.

---

6/

the prompt design rule that changed everything:

outcome-based only. never step-by-step.

"build X using Y sources, output as Z schema" — not "first research this, then analyze that, then format it."

step-by-step prompts collapse the moment the model hits an unexpected result mid-task and has to decide what to do next. outcome-based prompts let it navigate. it knows what done looks like.

this is the difference between a prompt that runs for 3 hours and succeeds, and one that runs for 3 hours and returns something unusable.

---

7/

the Model Council was the most technically interesting part.

3 frontier models — GPT-5.4, Claude Opus 4.6, Gemini 3.1 Pro — ran in parallel, each independently answering 5 stress-test questions about the thesis. zero coordination between models.

what they agreed on: customer concentration is the #1 near-term risk.

where they diverged: Gemini alone flagged optical substitution (LPO/CPO) as a category-level threat — not AEC competition, but AEC obsolescence. the other two models didn't raise it.

that divergence went directly into the risk section of the final pitch.

---

8/

what i'd do differently:

- define the JSON schemas first, before writing any prompts — i had to revise mid-pipeline when Task 7's app couldn't ingest Task 4's output format
- build the final app shell before running any research tasks — design the pipeline backward from the output, not forward from the data
- set the persistent memory context (Task 0) with even more specificity — the more precisely you define the audience and success criteria upfront, the less steering each downstream task needs

---

9/

the meta takeaway:

the skill isn't prompting.

it's systems design — knowing what needs to happen in what order, what each step's output contract is, and where every piece of data lands in the final deliverable.

that's just engineering. the language changed. the thinking didn't.

---

10/

full piece on the broader implications — for individuals, businesses, and what this shift actually means — on LinkedIn [link]

live submission: [link to web app]

@perplexity_ai @askperplexity @PPLXFinance
