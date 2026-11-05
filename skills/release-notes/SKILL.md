---
name: "release-notes"
description: "Produce the release drumbeat as a kit and a report: classify every ship, write each note as what changed, why it matters and what to do (saying \"nothing\" when it is nothing), segment ruthlessly, batch the small stuff into a monthly digest, and give breaking changes the full treatment with notice, migration guide first and a deprecation register. Chained to Launch tiers, and every claim traces to the matrix. Use when producing the Release notes output, writing a changelog, announcing product updates, or communicating a breaking change."
---

# Release notes

The drumbeat, not the launch. A launch is an event with a tier and a plan; release comms ship every week or two, forever. Done badly they are invisible or annoying. Done well they are one of the cheapest trust-builders in B2B: consistent, honest notes signal a company that ships and tells the truth about it, and almost nobody does them properly.

**Chained to Launch tiers both ways**: tier 3 releases feed this output's monthly digest, and a release that turns out to need a tier is not a release, it is a launch.

## The deliverables

**1. The kit**: the note template, the digest format, and the breaking-change pack (notice letter, migration guide skeleton, deprecation register). Working files on the client's own drive.

**2. The report**: the rules drawn, one real specimen written, and the finding.

On a real engagement both ship; for demo or portfolio use, the report alone is enough.

## Classify first — the class decides the treatment

| What shipped | Treatment |
|---|---|
| New capability | Announce |
| Improvement | Note; announce only if it changes someone's day |
| Fix | Note only — unless it fixes something complained about publicly, then say so by name |
| **Breaking change** | The full treatment |
| **Deprecation** | The full treatment |
| Security | The disclosure policy, different rules entirely |

## Every item gets three things

The third is always missing:

1. **What changed** — plainly, in the customer's vocabulary. An engineering ticket title is not a release note: "refactored the ingestion pipeline" becomes "positions now update in under two minutes, down from five."
2. **Why it matters** — the benefit, not the mechanism.
3. **What you need to do** — and when the answer is nothing, **say "nothing"**. "No action needed" is the most reassuring sentence in a release note and it is routinely omitted.

**Banned: "various bug fixes and improvements."** It tells the reader you either did not bother or do not want them to know.

The changelog canon agrees on the shape: date, the change, the benefit, the next step, and above all **consistency** — a monthly digest that always arrives beats sporadic announcements that arrive when someone remembers.

## Segment ruthlessly

**Only message people it affects.** Blanket release emails train the whole base to ignore all your email, including the one that matters — a cost that shows up months later as unread announcements you needed read.

- Affected by a breaking change → direct email, named sender, personal outreach for significant accounts
- Uses the thing that improved → targeted email or in-app
- Would benefit but does not use it → that is a lifecycle message, owned by the Onboarding journey, different channel and timing
- Unaffected → the changelog exists, and that is enough

## Batch the small stuff

Per-ship notifications for minor items exhaust attention. A **monthly digest** carries the tier 3 stream; significant items get their own moment. On a product with a community channel, the digest posts where the users already are.

## Breaking changes and deprecations — the rules

1. **Notice period**: whatever the contract says, plus more. 90 days minimum for anything requiring customer work.
2. **Contact the affected personally.** No customer discovers a breaking change from a changelog.
3. **The migration guide publishes before the announcement**, never after. An announcement without a path generates panic.
4. **The timeline publishes with dates**: announced, deprecated, removed.
5. **Never buried in a list.** A breaking change hidden among six improvements destroys trust with technical customers, and it will be quoted back.
6. **A deprecation register** keeps the timeline visible and enforceable internally.

## Guardrails

- Never announce before it is live for the people receiving the announcement.
- Never overstate: calling an improvement "a whole new way to work" trains readers to discount everything.
- **Every claim traces to the messaging matrix and its Claim check grade.** Release notes are a quiet source of drift, and this output is formally inside the drift run's surface list.
- Docs update before or with the note, never after. Docs contradicting the product generate tickets for months.
- Support hears everything before customers do.
- Do not announce what nobody asked for as though it is major; the reader can tell.

## The report's structure

Header: `Release notes · the drumbeat · <date>`.

**01 · What gets which treatment** — the classification table drawn as rows with treatment marks, the tier chain stated.

**02 · The anatomy of a note** — the three-part rule drawn, with a banned-phrase strikethrough.

**03 · One real specimen** — an actual shipped item written properly, and the same item written as the engineering ticket beside it, struck.

**04 · The digest and the breaking-change pack** — the monthly format and the six rules at count scale.

**05 · The finding** — one sentence, black band.

**06 · What can't be known** — always including: consistency is the entire trick, and it cannot be shown in a specimen, only kept.

## Drawing rules

- Classification as rows with treatment weight marks.
- The specimen as a miniature note artefact, ticket-version struck beside it.
- Fragments everywhere except inside the specimen itself.
- Counts, never percentages under thirty.

## Language

| Use | Never |
|---|---|
| What changed, why it matters, what to do | Feature summary, benefit statement, CTA |
| No action needed | N/A |
| The monthly digest | Release cadence communications |
| The full treatment | Enhanced comms protocol |

## Standing rules for every output

- **Two deliverables: the kit and the report.**
- **Classify before writing. The class decides the treatment.**
- **Say "nothing" when nothing is needed.**
- **Segment or stay silent.**
- **Claims trace to the matrix; the drift run reads this surface.**
- **Read the source, never the snippet.**
- **Name organisations, never individuals**, when the work is confidential.
- **Sentence case. British spelling. No em dashes. No balanced two-part lines.** Written for a cold reader.
