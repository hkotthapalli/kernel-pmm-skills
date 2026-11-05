---
name: "launch-tiers"
description: "Assign every release a tier by five yes/no questions, never by feelings or scores, and let the tier fire a fixed activity checklist with owners and back-planned dates — shipped as two deliverables: the tier kit (the questions and the activity workbook) and the report. Use when producing the Launch tiers output, deciding how big a launch is, or asking what a release needs before it ships."
---

# Launch tiers

Most launch chaos comes from one unmade decision: **how big is this launch?** Without an explicit tier, every release gets negotiated from scratch, small features get press releases, and major launches ship with a Slack message.

This is deliberately the least creative output on the map. Tier in, checklist out. A launch process that varies by mood is not a process.

## Two deliverables

**1. The tier kit.** The five decision questions and the fixed activity matrix as a workbook on the client's own drive — one sheet for the questions, one for the checklist with owner, due date, status and dependency columns. This is the instrument the team runs on every release after handover, and the input to every launch retro.

**2. The report.** The client's actual release pipeline tiered, drawn, with the checklist each tier fires and the finding.

On a real engagement both ship; for demo or portfolio use, the report alone is enough.

## The tier is decided by questions, not feelings and not scores

The published rubrics score five dimensions 0 to 2 and add them up. Do not copy that: a score lets people average away a decisive answer, and a launch that "scores 7" invites negotiation. Five yes/no checks, drawn as marks:

| Question | A yes means |
|---|---|
| Does it need new positioning or messaging? | Tier 1 |
| Does it change what someone pays or how they buy? | Tier 1 |
| Does it win new customers, or only please existing ones? | New customers: tier 1. Existing only: tier 2 at most |
| Would a customer notice if you didn't announce it? | No: tier 3 |
| Does leadership call it a milestone? | An override candidate, not a tier by itself |

Either of the first two alone makes it a tier 1. **The requester never self-assigns** — everyone believes their launch is tier 1, and the disagreement the questions surface is a real difference of view about the release's ambition, far cheaper to have now than three weeks in.

## The three tiers

**Tier 1 — Major.** New product, new buyer, new revenue line, or a change to how the product is bought or priced. The market does not already understand it, so positioning work is required. Lead time: 8 to 12 weeks from feature complete. **One to three times a year at most.** More than that and either the product is exceptional or the tiers are broken.

**Tier 2 — Mid.** A significant improvement that matters to existing customers or one segment. Supports retention and expansion but does not change the pitch. Lead time: 3 to 4 weeks.

**Tier 3 — Minor.** An incremental change customers should hear about but that changes nothing commercially. No lead time. **Tier 3 has a communication role**: small releases aggregate into a monthly changelog digest instead of vanishing one by one.

## Tier at build start, not at feature complete

The tier is assigned when the feature enters build and revalidated at beta. By feature complete there is no time left to run a tier 1, so tiering late converts every major launch into a mid one by default. Practically: a launch tier field on the roadmap, required before anything moves from discovery to build.

## The checklist

The matrix is fixed. Tier 1 fires 28 required activities, tier 2 fires 8, tier 3 fires 4, across three categories: communication (emails, campaigns, pages, in-app, social, PPC, webinar), internal material (research, positioning, battlecard, Oracle doc, launch deck, pitch), resources (brochure, two-pager, case study, video). Each row carries a default owner and a lead time back-planned from launch day: research 45 days out, positioning 30, battlecard and video 21, pages and deck 14, blog and newsletter 5 to 7, social 3, in-app 1, the announcement on the day.

**Do not silently drop items.** A skipped activity is recorded as `Skipped — [reason]`. Skipped with a reason is a decision; missing is an accident, and only one of them is recoverable at the retro.

**Dependencies are explicit.** Positioning blocks everything containing copy. Research blocks positioning. The battlecard and pitch block sales training. Product pages block PPC. The Oracle doc blocks the launch deck. Twenty-eight parallel tasks with no order fail the same way every time.

## Overrides exist and get written down

**Up** (treat a tier 2 as tier 1): a competitor just shipped the same thing and the narrative needs neutralising, or the release is the proof point for entering a new market.

**Down** (treat a tier 2 as tier 3): the team is at capacity and a tier 2 run at 70% effort damages credibility more than a clean tier 3, or a bigger tier 1 lands within six weeks and needs the attention protected.

Every override carries one line of rationale in the workbook. Frequent overrides in one direction mean the questions need recalibrating, not bending.

## The report's structure

Header: `Launch tiers · N releases tiered · <date>`.

**01 · The five questions** — the client's next releases against the five checks, drawn as a grid of marks. The tier falls out of the picture.

**02 · What each tier fires** — the three checklists at count scale (28 / 8 / 4 drawn, not listed), with the categories and the lead-time ladder.

**03 · The releases, tiered** — each release: its tier, the question that decided it, the lead time it needs against the time it has. Where those disagree, that is the row the founder reads twice.

**04 · The finding** — one sentence, black band.

**05 · What can't be known** — the standing limits, including that a tier assigned before build is a bet revalidated at beta, and that the checklist counts assume a team exists to own the rows.

## Drawing rules

- The questions grid: releases down, five questions across, marks per cell. Solid yes, dashed no.
- Checklists drawn as mark blocks at count scale. The 28-versus-4 ratio is the argument; a table hides it.
- Lead time drawn as bars against the calendar where a launch date exists.
- No colour. No scores, no numbers out of ten.

## Language

| Use | Never |
|---|---|
| How big is this launch | Launch sizing, tier assessment |
| The question that decided it | Scoring rationale |
| Skipped, with the reason | Descoped, deprioritised |
| The monthly digest | Changelog aggregation strategy |

## Standing rules for every output

- **Two deliverables: the kit and the report.** The kit on real engagements always.
- **Tier in, checklist out.** The matrix does not flex by mood.
- **The requester never self-assigns.**
- **No invented findings. No false zeroes.** Where a release's launch date or team is unknown, say so.
- **Read the source, never the snippet.**
- **Name organisations, never individuals**, when the work is confidential.
- **Sentence case. British spelling. No em dashes. No balanced two-part lines.** Written for a cold reader: no method jargon in the deliverable.
