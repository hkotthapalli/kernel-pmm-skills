---
name: "pre-mortem"
description: "Run a pre-mortem on a Tier 1 or Tier 2 launch as two deliverables: the tripwire checklist with a go/no-go checklist someone actually watches, and the report. Declare the launch already failed, collect failure causes silently with three prompts (tigers, elephants, paper tigers), check coverage across nine launch risk areas, rank by time to detection, and give each critical cause one action (Fix before launch, Tripwire or Track) with an owner and a date. Use when producing the Pre-mortem output, before a launch ships, or when asking what will kill this launch."
---

---
name: "pre-mortem"
description: "Run a pre-mortem on a Tier 1 or Tier 2 launch as two deliverables: the tripwire checklist with a go/no-go checklist someone actually watches, and the report. Declare the launch already failed, collect failure causes silently with three prompts (tigers, elephants, paper tigers), check coverage across nine launch risk areas, rank by time to detection, and give each critical cause one action (Fix before launch, Tripwire or Track) with an owner and a date. Use when producing the Pre-mortem output, before a launch ships, or when asking what will kill this launch."
---

# Pre-mortem

The launch has already failed. It is six weeks after ship. What happened?

That shift in tense is the method. Asking "what might go wrong" produces the list everybody already agrees on. Telling people it has gone wrong and asking them to explain it produces the list people privately suspected and would not say.

## Two deliverables

**1. The tripwire checklist.** A one-page working file on your own drive, with two parts:
- **Go/no-go checklist:** every Fix before launch action, its owner and its date, ending at the go/no-go date.
- **Tripwires:** each late critical cause, its leading indicator, the trigger level, the tripwire owner and the check cadence.

A tripwire inside a report fires for nobody. This file is what makes the exercise change anything after the meeting. Plain format, no analysis.

**2. The report.** The failure scenario, the causes on the timeline, the coverage check, elephants, actions, ruled-out paper tigers, the key finding and limitations.

## When to run it

- Tier 1 and Tier 2 launches only, as set by 21 Launch tiers. Tier 3 launches skip it.
- 2 to 6 weeks before ship. Late enough that the plan is real, early enough to act.
- The go/no-go date sits about 2 weeks before ship. The failure date sits about 6 weeks after ship.

## What this is not

**Not the Assumption log.** The Assumption log is a standing register of claims the plan treats as true, graded by evidence. The Pre-mortem is a dated, one-off exercise tied to one launch, about what people already believe and are not saying.
- "We believe expats will pay monthly" goes in the Assumption log.
- "Nobody funded their account and we never noticed" goes in the Pre-mortem.
- An elephant found here goes back into 05 as a critical assumption.

**Not a risk register.** A risk register assigns probabilities nobody can estimate. This produces named failure causes with an owner and a date.

**Not the Launch post-mortem.** That runs after. 30 compares its findings with this pre-mortem.

## How to run it

**1. Brief the plan, then write the failure scenario.** "It is [specific date]. The launch failed badly enough that we are meeting about it." Use a real date. Specificity is what makes prospective hindsight work.

**2. Three prompts, answered alone.** Each person writes one line per reason:
1. Why did it fail? (finds **tigers**, real threats)
2. What is nobody saying about this launch? (finds **elephants**)
3. What are we worrying about that won't matter? (finds **paper tigers**)

Nobody sees anyone else's answers until everyone submits. If one person speaks first, the room converges on their answer.

**3. The plan owner writes separately.** Seniority collapses candour. This is the most common way the exercise fails.

**4. Merge and count independent mentions.** A cause three people wrote alone is real. A cause one person wrote is worth keeping and is one person's view.

**5. Coverage check.** Map every cause to nine launch risk areas:
demand, positioning and messaging, channels, sales readiness, pricing, onboarding and product, support and operations, legal and regulatory, competitor response.

An area nobody raised shows as empty. Do not fill it with invented causes. Send the team one follow-up question per empty area, answered alone, and add whatever comes back with its source. An area still empty goes in Limitations.

## Ranking by time to detection

Do not rank by likelihood. Rank by **time to detection**: when the evidence would actually reach you. A failure visible in week one is cheap. A failure that shows at month six has already spent the money.

Two axes:
- **Time to detection:** week 1 to month 6
- **Impact:** Critical or Costly

## One action per critical cause

Every critical cause gets exactly one action, with an owner and a date:

| Action | When |
|---|---|
| **Fix before launch** | Evidence exists today (an earlier output already found it), or there is no early signal at all |
| **Tripwire** | You would only find out late, and a leading indicator moves first |
| **Track** | Costly causes, watched after launch |

**The tripwire** is a leading indicator plus a trigger level. It is not the failure. It precedes the failure and shows sooner. Year-two churn is invisible for a year; the second monthly payment shows in eight weeks. Set the trigger level before launch and name the tripwire owner and check cadence.

If no early signal exists, say so and make it Fix before launch. That is a real finding.

**Paper tigers** go under Ruled out, each with the evidence that rules it out. A paper tiger without evidence stays a cause.

## Go/no-go

The go/no-go date holds the decision. The checklist lists every Fix before launch action plus "every tripwire has an owner". It reads Not ready until all are done. The same checklist becomes the launch gates in 22 Launch brief.

## Every cause needs a source

A cause is either something a person wrote, or something an earlier output already found. Name the source: "05, critical untested", "19, relevance fail". Do not add plausible failures nobody raised and no research supports. Inventing a risk is the same as inventing a finding.

Pull causes from earlier outputs if done: 05 (critical untested assumptions), 13 (unanswered questions), 15 (unpriced commitments), 18 (high-risk claims still live), 19 (failed message layers), 26 (blocked answers).

## Working alone

If you run it without a team, Kernel builds causes from earlier outputs only, labels the result "solo", and says so in Limitations. Do not invent a workshop.

## The report's structure

1. **Failure scenario**, dated, past tense, with the target missed.
2. **Failure causes by time to detection.** The timeline is the main visual: launch on the left, month 6 on the right, causes placed where the evidence arrives. Each cause tagged Tiger or Elephant, with one mark per independent mention and its source.
3. **Coverage check.** Nine risk areas, mention marks, empty areas dashed.
4. **Elephants**, quoted, with independent mention counts.
5. **Actions.** One per critical cause: action, detail, owner, date. Tripwires drawn as a trigger level line.
6. **Track** and **Ruled out**.
7. **Key finding**, one sentence, black band.
8. **Go/no-go**, hand-offs, Limitations (who took part, empty areas, "a tripwire only works if its owner checks it").

## Drawing rules

- The timeline is the output. The cluster on the right is the argument.
- Independent mentions as marks, not numbers in brackets.
- Tripwires as a trigger level line, as the Assumption log draws pass criteria.
- Fill grammar: solid critical, half costly, dashed no signal or nobody raised, struck ruled out.
- Fix before launch in black, Tripwire outlined, Track dashed.

## Language

Matches Kernel's PMM glossary.

| Use | Instead of |
|---|---|
| Pre-mortem | (stays) |
| Failure scenario (dated) | It failed, here is what happened |
| Failure causes | (stays) |
| Independent mentions | Raised by more than one person |
| Time to detection | How late you'd find out, detection latency |
| Impact: Critical, Costly | Fatal |
| Late critical causes | The ones you'd find out too late |
| Tripwire (leading indicator) | The thing that moves first |
| Trigger level | Fires at, threshold breach |
| Tripwire owner, check cadence | Who watches it |
| No early signal | Nobody would have seen this coming |
| Risk types: Tiger, Paper tiger, Elephant | (new) |
| Action: Fix before launch, Tripwire, Track | Launch-blocking, fast-follow |
| Risk areas (the nine) | (new) |
| Coverage check | (new) |
| Go/no-go date | (new) |
| Tripwire checklist | (stays) |
| Key finding, Limitations, Evidence source | The finding, what can't be known |

## Standing rules for every output

- Two deliverables: the tripwire checklist and the report.
- No invented findings and no invented risks.
- No false zeroes. Check what exists before writing that nothing does.
- No competitor prices as structural facts.
- Name organisations, never individuals, when the work is confidential.
- "Not measured" is not an answer.
- Read the source, never the snippet. Open the earlier output and read the finding. For external facts, fetch and read the actual source.

## Where the method comes from

Gary Klein formalised the pre-mortem in Harvard Business Review in 2007. It rests on prospective hindsight, which Mitchell, Russo and Pennington found in 1989 improves people's ability to identify reasons for an outcome by around 30 percent. Tigers, paper tigers and elephants come from launch-readiness practice at Atlassian and Shreyas Doshi's pre-mortem format. None of this belongs in the output.
