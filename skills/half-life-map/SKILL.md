---
name: "half-life-map"
description: "Build the Half-Life Map — every asset with an owner, a destination, and a half-life by type, staleness scored as age over half-life under a fixed risk ceiling, event triggers that beat dates, three verdicts (refresh, retire, leave), and a queue of the next ten with owners, never a report of everything. Two deliverables: the living map sheet and the report. Use when producing the Half-Life Map output, auditing asset freshness, or asking what is out of date and which of it matters."
---

# Half-Life Map

Marketing assets do not fail loudly. A battlecard does not break; it quietly starts losing deals eighteen months after the competitor repriced. The map finds decay before a prospect does, and answers the one question nobody can answer from memory: **what is out of date, and which of it matters?**

The name is earned: facts decay at measurable, predictable rates (the half-life of knowledge is a studied quantity — decades in some fields, days for a price). Every asset is a bundle of facts, and each bundle has a knowable half-life. Content itself decays too: after its growth and plateau, a page loses one to two percent of its traffic per week untouched — while refreshing old assets is the cheapest work in marketing (updating old posts produced a documented 106% average traffic lift, and updaters are twice as likely to report strong results).

## Two deliverables

**1. The map.** The living sheet on the client's own drive: asset · type · owner · destination · last updated · half-life · staleness ratio · risk band · blast radius. This is the standing instrument; the weekly run updates it, and it is the maintenance retainer's heartbeat.

**2. The report.** The library judged: the decay picture, the queue, the retirements, the finding.

On a real engagement both ship; for demo or portfolio use, the report alone is enough.

## Every asset gets a half-life by type

| Asset | Half-life | Risk ceiling |
|---|---|---|
| Battlecards, competitive grids | Quarterly | **Critical** — wrong words reach prospects |
| Product Oracle | Per release + quarterly | **Critical** — everything downstream quotes it |
| Pricing collateral | On change | **Critical** — a wrong price is a trust and legal problem |
| Messaging matrix | Monthly | High — drift propagates everywhere |
| Playbooks, factsheets, decks | Quarterly to annually | High |
| Release notes and docs | Per release | High |
| Personas, use cases, FAQs | Quarterly | Medium |
| Case studies | Quarterly | Medium — named customers churn |
| Product videos | Monthly review | Medium — UI drift is visible |
| Blogs, reports, webinars | Monthly review | Low |

The client's own cadence document beats this default where one exists.

**Staleness = age ÷ half-life.** Above 1.0 is overdue. Drawn as decay bars.

## The scoring rules

- **Risk ceiling is a property of the asset type. Staleness moves an asset within its band and never above it.** Without the ceiling, everything overdue screams critical and triage dies.
- **Blast radius**: does anything quote this? An Oracle feeding twelve assets outranks a blog at the same staleness.
- **Exposure**: customer-facing now outranks a file in a folder.
- **Volatility**: a battlecard for a just-acquired competitor is urgent regardless of its date.

## Triggers beat dates

Some staleness no date can show. The map **subscribes to the Competitor monitor's feed**, and an event puts the affected assets at their ceiling instantly:

- Competitor acquired, repriced or repositioned → every battlecard and comparison
- Your own price or packaging changed → all pricing collateral, decks, pages, FAQs
- A rename or rebrand → everything
- A named case-study customer churned → that study, the same day
- A repositioning → the narrative, the decks, the homepage

**And dates lie.** A file touched for a typo reads fresh. Where the facts are visibly old under a recent date, the date is unverified.

## Three verdicts, and retirement gets equal billing

Per overdue asset: **refresh, retire, or leave.**

- Stale is not wrong until verified — some assets age well, and the honest label is "overdue for review".
- **Retire is a first-class verdict.** The governance canon's biggest documented cleanup removed 80% of an institution's content as redundant, outdated or trivial. A battlecard against an acquired competitor gets deleted, not updated. News-pegged content past its news is retired, not refreshed.
- Missing assets are findings too: a product with no battlecard scores worse than a stale one.

## The queue, never the report

The deliverable is **the next ten things someone should do**, each with an owner and an estimate, ranked by risk not by staleness. "Update all 47 assets" means the audit failed — it moved the paralysis into a different document. Unowned queue items do not happen.

## Cadence

Weekly: the what-went-stale check, five minutes, run from the map. Quarterly: the full library audit. The weekly run is where the map earns its place — it converts a decaying library into a standing work queue, which is the difference between a library someone maintains and one everyone quietly stops trusting.

## The report's structure

Header: `Half-Life Map · N assets · N overdue · <date>`.

**01 · The library, decaying** — every asset as a decay bar (age against half-life), grouped by risk band, overdue bars crossing a marked line. The picture answers: how much of what we made is still true.

**02 · The triggers that fired** — events from the monitor and elsewhere, each with the assets it staled regardless of date.

**03 · The queue** — the next ten, each with verdict (refresh / retire / leave), owner and estimate. The retirement list called out.

**04 · The finding** — one sentence, black band.

**05 · What can't be known** — always including: a date proves nothing about content; half-lives are defaults until the client's own decay history calibrates them; and the map is as alive as its weekly run.

## Drawing rules

- Decay bars: a horizontal bar per asset filled to its staleness ratio, the 1.0 line marked, overdue portions crossing it. Grouped by ceiling band.
- Verdicts in plain marks: refresh solid, retire struck, leave dashed-light.
- The queue as ten rows, never more at the top.
- Counts, never percentages under thirty.

## Language

| Use | Never |
|---|---|
| Half-life | Refresh cadence, update SLA |
| Overdue for review | Incorrect, broken |
| Retire | Sunset, deprecate, archive |
| The queue | Backlog, work items |
| What went stale this week | Freshness delta report |

## Standing rules for every output

- **Two deliverables: the map and the report.**
- **Staleness never exceeds the type's ceiling.**
- **Triggers beat dates, and dates lie.**
- **Retire is a verdict, not a failure.**
- **Ten items at the top of the queue, each owned.**
- **No invented findings. No false zeroes.**
- **Read the source, never the snippet.**
- **Name organisations, never individuals**, when the work is confidential.
- **Sentence case. British spelling. No em dashes. No balanced two-part lines.** Written for a cold reader.
