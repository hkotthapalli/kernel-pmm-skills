---
name: "use-cases"
description: "Use case prioritisation from counted jobs to be done in customer interviews and win-loss, with a four-check build test, a page brief per page and the forces of progress; then a publish kit with each built page in full, ready for the site and owned channels. Use when producing the Use cases output, planning use case or solution pages, deciding what pages the site needs, or asking what jobs customers hire the product for."
---

# Use cases

**This output is a build list, then the pages themselves.**

It covers use case prioritisation (the pages the site needs, in order), a page brief per page, and a publish kit with each page in full so the client can publish it.

Jobs to be done are the input. The page plan and the publish kit are the output. If the document ends in an insight rather than a list of pages someone can start publishing on Monday, it has failed.

## Why it works this way

"Use cases" in practice is a website architecture decision. The industry standard is a page per job, and the standard rule for splitting is: **make a separate page only when the headline, the objection or the proof would materially change.** Everything else belongs on the page that already exists.

Most competitors publish how to *design* the page — layout, calls to action, load speed, word count. Almost nobody publishes how to decide *which pages deserve to exist*, from counted evidence. That decision is this output.

## Where jobs to be done come from

Customer interviews and win-loss transcripts. This is a second pass over transcripts that have already been read, not new research. In the app, the user can add more buyer words from a file (sales call notes, support tickets, survey exports). Call recorders and helpdesks connect later.

**Do not re-run the Voice of customer analysis here.** That output owns themes, verbatims and the language bank. This one takes the jobs to be done as given, states each in one line with a count, and moves straight to the decision. If section 01 of this output could be lifted into Voice of customer without anyone noticing, it is too long — cut it.

A job is what somebody was trying to get done, in their words, starting with a verb. "Tell me what the first step is" is a job. "Track your retirement savings" is a feature with a verb in front of it.

## The build test

Four checks per job. Each is yes or no, and each carries its evidence.

| Check | The question |
|---|---|
| **Different headline** | Would the headline change from the main page? |
| **Different objection** | Would a different objection need answering? |
| **Different proof** | Would you show a different customer, number or screenshot? |
| **Multiple sources** | Did more than one person in the research have this job? |

**The first three decide whether it is a separate page.** If the headline, the objection and the proof are all the same as the main page, it is the same page.

**The fourth decides whether you build it yet.** One source is not a page.

## Verdicts

| Verdict | Means | Drawn as |
|---|---|---|
| `BUILD` | Three or more checks yes, including multiple sources | Solid block, green in the app |
| `BUILD LATER` | Splits cleanly but only one source behind it so far | Block filled to half |
| `MERGE INTO EXISTING PAGE` | Does not split. Belongs as a section on an existing page | Outlined block |
| `DON'T BUILD` | No evidence anyone wants it, or it is a feature not a job | Outlined, struck through |

Same fill grammar as every other output. Build is green because it rests on counted evidence.

**Give the BUILD pages an order, and say why the first one is first.** An unordered list is not a decision. Order by count first, then by how close the proof already is.

**Expect to build fewer pages than the client expects.** Three real jobs with one of them carried by a single source is two pages, not four. Saying so plainly is more useful than a long list, and if every job comes back BUILD, re-read the transcripts — the split test was applied too loosely.

## The page brief

One per `BUILD` and `BUILD LATER` page. Five lines each, no more.

| | |
|---|---|
| **Headline** | Their words, lifted from the language bank, not written fresh |
| **Opens with** | The problem, as the buyer described it |
| **Promises** | The outcome, stated as what changes for them |
| **Proves it with** | The specific proof — and marked present or missing |
| **Key objection** | The one objection that kills this page if it is ignored |

**Mark missing proof as missing.** A page brief that quietly assumes a case study nobody has written is how these plans die. Missing proof is a finding, and it feeds the Customer case studies output.

## The publish kit

The second deliverable. For every `BUILD` page, the full page as it will read, so the client can publish it on their own site and reuse it on their owned channels.

The client provides two inputs for it: proof they are allowed to publish (each item with a permission tick), and where they publish (Webflow, Framer, WordPress, a site builder such as Lovable, or other).

Fixed structure, top to bottom:

| Section | Rule |
|---|---|
| **Hero** | The headline is a verbatim line from the language bank. If none fits, the headline stays unwritten and the kit says what Kernel needs to hear. The subhead names the target customer (from ICP and segments) and what the product does |
| **Opening answer** | One paragraph that answers the job directly, so search engines and AI assistants can quote it |
| **The problem** | In the buyer's words, with the count behind it |
| **How it works** | Two to four steps, in the buyer's order, each with the screenshot that shows that step |
| **Proof** | From a customer with the same job, with permission to publish ticked |
| **Key objection** | The objection from the page brief, answered in the client's words |
| **Next step** | One call to action. The form records the page in a hidden field so leads can be traced to it |

Beside each section, show its evidence source.

**A page does not publish without proof.** The kit holds any page whose proof is missing, says so, and adds the missing proof to the Customer case studies output. A short checklist sits above the exports: proof has permission, the headline comes from a buyer's words, the key objection has the client's answer, and the live URL is added.

Exports follow where the client publishes: Markdown for any site, a CSV with one column per section for a CMS collection (Webflow, Framer), or a single message for a site builder.

Each page also gets a short post and an email for the client's owned channels, drawn only from the same buyer words and product facts. Nothing in them that nobody said.

The output is proven when the first page is live, its proof is real, and the Landing page review gets past relevance on it.

## Forces of progress

The forces that move people or hold them in the status quo, and an honest split between the ones copy can move and the ones it cannot.

Four forces, from Bob Moesta and Chris Spiek's jobs-to-be-done work. People change when the first two together beat the second two.

| Force | What it is | Owner |
|---|---|---|
| **Push** | Frustration with the status quo | The page |
| **Pull** | The attraction of the new product | The page |
| **Anxiety** | Fear about the switch itself | The page, sometimes. Product, often |
| **Habit** | What they would have to stop doing, and the comfort of deciding nothing | Not the page |

Run this on the top job only.

**This section exists to stop someone writing copy at a problem copy cannot solve.** "Doing nothing is free and nothing bad happens today" is not a headline problem. Name it, count it, and name the owner — page, product, onboarding or pricing. Hand onboarding forces to the Onboarding journey output.

Score by how many people voiced it, never by how strong it feels.

## Output structure

Two deliverables: the report below, and the publish kit above.

Header: `Use cases · N jobs · N pages · <sources> · <date>`

**01 · Jobs to be done** — one line each with the count drawn as marks and one verbatim. Compressed. This is the input, not the deliverable.

**02 · Use case prioritisation** — the four checks per job as a grid, a verdict per job in fill, and the build order underneath.

**03 · Page briefs** — the brief per built page, five lines, missing proof marked.

**04 · Forces of progress** — the forces, with counts and owners.

**05 · Key finding** — one sentence, black band.

**06 · Limitations.**

Six sections in the report.

## Drawing rules

- Counts as marks, filled out of the total. The reader counts.
- The build test is a grid: jobs down, four checks across, filled or dashed.
- Verdicts in fill. Green only on Build, proof that is present, and pages ready to publish.
- Quote verbatim. Never tidy a job into marketing language — the moment you do, it becomes a feature again.

## Language

Standard product marketing terms on every label and heading. Never a label built from "who, what, which, where" phrasing. Jobs to be done themselves stay in buyers' words.

| Use | Instead of |
|---|---|
| Jobs to be done | The jobs, use case scenario, user story |
| Use case prioritisation | Which pages to build, content mapping |
| Build, Build later, Merge into existing page, Don't build | Fold in, consolidate, deprecate |
| Different headline, Different objection, Different proof, Multiple sources | Different first line, different worry, more than one voice |
| Page brief | What goes on each page, content brief |
| Key objection | Must answer, the question it must answer |
| Forces of progress: push, pull, anxiety, habit | What a page can't fix, friction |
| Publish kit | (stays) |
| Customer interviews | Calls |
| Evidence source | Where it came from |
| Key finding, Limitations | The finding, what can't be known |

## Voice

- Plain and direct. Their words in quotes, yours outside them.
- No slogans, no balanced two-part phrases, no line whose job is to sound clever. If a line has a rhythm, or a turn, or would work on a poster, cut it.
- The key finding is a fact, not a formulation. If the reader has to decode it, rewrite it.
- Sentence case. British spelling. No em dashes.
- No section subtitles unless they carry something the drawing does not.

## Rules

- **It ends in a build list and a publish kit.** An output with no page order is not finished.
- **A job with one source behind it is one person's job.** Mark it as one. It can be `BUILD LATER`, never `BUILD`.
- **Never a percentage on a base under thirty.** Four of five is four of five.
- **Headlines come from the language bank**, not from you. If there is no verbatim close enough to use, say the headline is not yet written and name what you would need to hear to write it.
- **Mark missing proof as missing.** No page brief or published page assumes evidence that does not exist.
- **No proof, no publish.**
- **No false zeroes.** State what exists, then why it falls short.
- **Read the source, never the snippet.** The transcript, not your notes on it. Any competitor page cited as a pattern gets fetched and read in full first.
- **Name organisations, never individuals**, when the work is confidential. Published proof names a person only with written permission.
