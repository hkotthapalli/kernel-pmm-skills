---
name: "message-drift"
description: "Run the Message drift check — compare every surface's copy against the approved messaging matrix cell by cell, draw the drift map in fill grammar, rank the damage by who sees it, let the field vote on lines the matrix got wrong, and write every fix as a strikethrough rewrite with a location and an owner. Use when producing the Message drift output, checking messaging consistency, or asking whether the surfaces still say the agreed thing."
---

# Message drift

Messaging decays without anyone deciding to change it. A page written before the last repositioning, a deck edited for one deal and reused, an ad running against a value line retired two quarters ago. Nobody is wrong at any single step, and the company ends up saying four different things about the same product.

This is the maintenance instrument for the Messaging framework, exactly as the Competitor monitor is for The Fifty. **A run, not a register.** Monthly on core surfaces; full sweep quarterly and immediately after any repositioning, rename or price change — the weeks after a matrix change are when drift is created fastest, because the matrix moved and forty surfaces didn't.

## What this is not

**Not the Claim check.** Drift compares the copy against the matrix: are we saying the agreed thing. The Claim check compares the claims against the evidence: is the agreed thing true. A company can be perfectly on-message and unable to back a word of it, or fully evidenced and saying it differently on every page. Sisters, never merged.

**Not an audit against vibes.** The reference document is the approved messaging matrix. If it does not exist, build it first. There is no drift without a thing to drift from.

## The map

The main visual is the drift map: matrix lines down (the elevator pitch, each pillar, one line per person in each route to purchase), surfaces across (homepage, product pages, deck, ads, emails, whatever ships). Every cell in fill grammar:

| Cell | Means |
|---|---|
| Solid | Says the agreed line, in the matrix's words |
| Half | Same idea, different words |
| Struck | Says something that disagrees with the line |
| Dashed | The surface doesn't carry the line at all |

Dashed is not automatically a fault — an ad is not supposed to read like a positioning statement, and not every surface owes every line. Judge against intent, not identity.

Count the cells and the lines, separately: "1 cell of 60 matches" and "5 of 12 lines appear nowhere". Counts, never a score, never a percentage under thirty.

## The six states, itemised

The map compresses to four marks; the fix list uses the full six, in plain names:

1. **Says it** — the matrix line in the matrix's vocabulary.
2. **Same idea, different words** — usually fine. If it reads better than the matrix, that is data, not drift.
3. **Says something else** — a different claim or emphasis where the line should be.
4. **Says something the matrix never said** — the orphan claims. Someone invented positioning on a landing page. Orphans get their own list.
5. **Two surfaces disagree** — the highest severity, and the only state that is a factual problem together with:
6. **Out of date** — a retired name, an old price, a churned customer's logo.

Only 5 and 6 are factual problems. The rest are alignment problems. Conflating them inflates severity and loses the team's trust.

## Severity

Three things multiplied, not averaged: **who sees it** (the homepage beats an archived PDF), **how deep in the funnel it sits** (a contradiction in a sales deck costs more than one in a blog post), and **whether it is factually wrong or merely off-tone**. A tonal variant on a five-year-old post is not worth anyone's Tuesday.

## The field gets a vote

Drift is not always the copy's fault. If the same "wrong" phrasing appears on several surfaces written by different people, the matrix language is unusable and the market has voted. Flag it as a **matrix revision candidate** instead of mass-correcting toward words nobody can say out loud. The same applies to an orphan claim that keeps appearing: if three surfaces keep saying something the matrix never said, the matrix may be missing a line. Where call recordings exist, what reps drop or rewrite mid-deal is the same vote in a different room.

This is the step that separates the run from a compliance exercise, and the one that earns the team's cooperation rather than their resentment.

## Fixes, not findings

Every flagged cell gets: the location, the current copy verbatim, the matrix line it should express, the rewrite in strikethrough-to-replacement form, and an owner. Twelve URLs with before-and-after copy generate a pull request. "The messaging is inconsistent" generates a meeting.

Rules for the rewrites: at least as readable as what they replace, never rewritten into corporate, and where a fix already exists in another output (the positioning report's homepage copy, the Claim check's shrunk claims), point at it rather than writing a rival version.

## The report's structure

Header: `Message drift · N lines × N surfaces · N cells aligned · <date>`, with the cadence line beneath.

**01 · The drift map** — the full grid, drawn, with stat rows beneath (cells matching, lines appearing nowhere, surfaces disagreeing).

**02 · Where it hurts** — the worst cells ranked, each row: rank, the cell named, a bar for who sees it, the mark.

**03 · What the surfaces say that the matrix doesn't** — the orphan list, and any matrix revision candidates with the count of surfaces that voted.

**04 · The fix** — strikethrough rewrites with locations and owners, worst first.

**05 · The finding** — one sentence, black band. About the copy or the matrix, not the method.

**06 · What can't be known** — the standing limits, always including: variants may be deliberate channel adaptation; surfaces not read are not judged; and a map drawn the week after the matrix shipped mostly measures the age of the site, not the discipline of the team.

## Drawing rules

- The map is cells, not a table of words. The reader should locate the fracture in one look.
- Stat rows in the fixed two-column form: large count left, full sentence right.
- Strikethrough form for every fix: struck old copy, arrow, replacement.
- No colour. Never a percentage under thirty.

## Language

| Use | Never |
|---|---|
| Says the agreed thing | On-message, aligned to the matrix |
| Same idea, different words | Variant, paraphrase drift |
| Says something the matrix never said | Orphan claim, rogue messaging |
| The field voted | Bottom-up feedback signal |
| Out of date | Stale asset, content debt |

## Standing rules for every output

- **A run, not a register.** State the cadence and the re-run triggers in the report.
- **Quote verbatim, both sides.** Paraphrase hides the drift being shown.
- **Read what renders, never the markup.** Every surface fetched and read in full.
- **Name the owner of each surface**, not just the fix.
- **No invented findings. No false zeroes.** An empty column on a surface that was never meant to carry the line is not a failure.
- **Name organisations, never individuals**, when the work is confidential.
- **Sentence case. British spelling. No em dashes. No balanced two-part lines.** If a line would work on a poster, cut it.
