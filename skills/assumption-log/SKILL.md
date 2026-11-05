---
name: "assumption-log"
description: "Build the Assumption log as two deliverables: the living log the client updates as tests run, and the report that judges it — every assumption harvested from a real source and written as a testable claim, graded by impact if wrong (Critical, Costly) and evidence (Validated, Partly validated, Untested, Invalidated), with the riskiest assumptions given the cheapest assumption test and pass criteria set before it runs. Use when producing the Assumption log output, auditing what a plan rests on, or finding the riskiest assumptions."
---

# Assumption log

The register of what the plan takes as true. Not a list of worries. Every line is a claim somebody already made, graded by how much evidence sits behind it.

## Two deliverables

**1. The log.** A living sheet on the client's own drive — one row per assumption: the claim, the source, the assumption type, the impact if wrong, the evidence as a plain word, the assumption test and its pass criteria where one exists. It is a register by definition: evidence changes as results arrive, invalidated lines accumulate, and the client updates it after handover. Plain format (Google Sheets, xlsx, docx or markdown), no analysis, no drawing.

**2. The report.** The snapshot that judges the log at a moment in time — the log drawn, the invalidated lines, the riskiest assumptions with tests, the key finding. The report is the showable artefact; the log is the one that stays alive.

A report alone freezes a document whose whole point is that it moves. On a real engagement both ship; for demo or portfolio use, the report alone is enough.

## What this is not

**Not the Pre-mortem.** The Pre-mortem imagines the launch failed and asks why. It is a one-off, run before a launch, and it produces failure modes. The Assumption log is a standing register of claims and evidence that gets updated as results arrive. If a line reads "the integration might break", it is a pre-mortem line, not an assumption. Move it.

**Not a risk register.** Risks are things that might happen to you. Assumptions are things you have decided are true and acted on.

**Not brainstormed.** See the harvest rule. Workshop templates (Miro, FigJam, ClickUp) sort sticky notes on a 2x2 once; this log traces every line to a source, fixes the pass criteria in advance and records results.

## The harvest rule

Every assumption must trace to a sentence somebody already wrote or said. Sources, in order of yield:

- The deck — every market number, every "the problem is X"
- The homepage and pricing page — every claim about who it's for and what they'll pay
- The plan or roadmap — every "then we will"
- Sales calls and internal notes — every "they'll obviously"
- In the Kernel app, every other output that marks something untested: differentiator candidates not yet validated (Table-stakes read), unknown grades and the validation test (Positioning), the value metric and price point (Packaging and pricing), unvalidated objections (Sales enablement), and buyer's stated reasons that test old beliefs (Win / loss)

If you cannot point at the source, it is not an assumption, it is your invention. Cut it.

Record the source on every line. Two words is enough: "Deck, slide 4."

## Writing an assumption

**A testable claim, in the present tense. Never a question.**

Right: "Gulf expats will pay monthly for a retirement plan."
Wrong: "Will Gulf expats pay monthly?"

A question cannot be marked true or false, so it cannot be tested, so it cannot leave the log.

Strip hedges. "We think people might prefer" becomes "People prefer". The plan is behaving as though this is settled.

Tag each with an assumption type: desirability (buyers want it), viability (it works as a business) or feasibility (it can be built and run).

## The two axes

**Impact if wrong** — does the plan survive? Two levels only:
- *Critical* — the plan does not work
- *Costly* — the plan works, something has to change

**Evidence** — four states, drawn with the standard fill grammar:
- **Validated** (solid) — evidence exists, from the right people, in enough numbers.
- **Partly validated** (half) — evidence exists but it is thin, second-hand, or from the wrong people. Say which.
- **Untested** (dashed) — nobody has checked. The honest default, and most lines start here.
- **Invalidated** (struck through) — tested, and it was false. The most valuable lines in the log.

Never add a fifth state.

## The ranking rule

Only one group gets a test: **the riskiest assumptions — critical and untested.** Everything else is recorded and left alone.

This keeps the log short and actionable. Three to five riskiest assumptions is right. If you have twelve, your critical bar is too low — a critical assumption kills the plan, not the quarter.

## The assumption test and pass criteria

Each riskiest assumption gets three things:

1. **The cheapest assumption test that could disprove it.** Cheapest, not most rigorous. A landing page, ten interviews, one manual concierge run. Not a build.
2. **Pass criteria, written before the test runs.** "At least 4 of 10 will do X." Not "we'll see what happens." In the app, Kernel locks the pass criteria when the test starts.
3. **A decision rule, both branches.** What you do if it passes and if it fails. If the answer changes nothing, do not run the test.

The pre-written pass criteria are the whole discipline. Without them the team reads the result to fit what they already wanted.

## The report's structure

Header carries the count and the date: `Assumption log · N assumptions · M untested · <month year>`. That is enough — do not add a paragraph explaining the method.

**01 · Assumption log** — the whole register, drawn. One mark per assumption, grouped by evidence, with counts by type and impact.

**02 · Invalidated assumptions** — the struck lines, with what actually happened. Put these before the untested ones. They are the evidence the log works.

**03 · Riskiest assumptions** — critical and untested, ordered by impact. Each with its source, assumption test, pass criteria drawn as a bar with the threshold line, and decision rule.

**04 · Key finding** — one sentence, black band. Usually about the shape of the ignorance, not about any one assumption. "Nobody has tested the three things that decide whether this works" is a key finding. "We have twelve assumptions" is not.

**05 · Limitations** — the standing limits.

## Drawing rules

- Draw the register. One mark per assumption, grouped by evidence, so the reader sees the proportion before reading a word.
- Draw the untested group. The dashed marks are the point of the output.
- Draw the pass criteria. Show the bar and the line it has to clear.
- Fill grammar first. Green only on validated assumptions and on the pass criteria line.
- No tables of prose where marks would do.

## Language

Standard product marketing and product discovery terms on every label and heading. Never a label built from "who, what, which, where" phrasing.

| Use | Instead of |
|---|---|
| Assumption log | What the plan takes as true, assumption set |
| Assumption types: desirability, viability, feasibility | (new) |
| Impact if wrong: Critical, Costly | Fatal, risk exposure |
| Evidence: Validated, Partly validated, Untested, Invalidated | Nobody has checked, tested and it was false, unknown-unknown |
| Riskiest assumptions | What nobody has checked, leap-of-faith assumptions |
| Assumption test | The cheapest test, MVP, RAT |
| Pass criteria | The number that decides it, threshold metric |
| Decision rule | What we do either way |
| Source | (stays) |
| Key finding, Limitations | The finding, what can't be known |

## Standing rules for every output

- **Two deliverables: the living log and the report.** The log on real engagements always.
- **No invented findings.** If it was not observed, said or published, it does not appear.
- **No false zeroes.** Before writing that something does not exist, check what exists in its place.
- **No competitor prices as structural facts.** A competitor's price is a competitor's choice, not a fact about the market.
- **Name organisations, never individuals**, when the work is confidential.
- **"Not measured" is not an answer.** If a number is missing, find the path to it or state exactly which public source would have to exist.
- **Read the source, never the snippet.** Assumptions are harvested from the actual deck, page and notes, read in full. Any evidence that marks a line validated or invalidated gets opened and read. A line marked validated on the strength of a snippet is worse than a line left untested.

## Where the method comes from

Assumptions mapping and the desirability, viability and feasibility split come from David Bland's work with Strategyzer. The pre-written pass criteria come from Teresa Torres's assumption tests in continuous discovery. The cheapest-test-first principle is the riskiest assumption test, argued as an alternative to building an MVP. None of this needs to appear in the output.
