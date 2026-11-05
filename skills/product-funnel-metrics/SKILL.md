---
name: "product-funnel-metrics"
description: "Run the Product funnel metrics as the monthly reading of the funnels other outputs define, in two deliverables: the reading sheet the founder fills on the first Monday of each month — inputs separated from outputs, counts beside last month and the baseline, one chosen number per quarter, anomalies get sentences and normal numbers get silence — and the report judging the reading. The first run names the missing instruments. Use when producing the Product funnel metrics output, setting up a monthly metrics reading, or asking how the funnel is doing."
---

# Product funnel metrics

This output does not define a funnel. The funnels already exist: Channel and funnel drew one per
route, the Onboarding journey owns the activation moment. This output is the discipline of
**reading them monthly** — the thing that turns funnels from diagrams into instruments.

The only proven recurring-reading discipline in industry is Amazon's weekly business review.
Nobody on the competitive list sells it at founder scale; it lives inside operating cadences that
assume a data team. This output is the WBR stripped to what one founder can run: one page, one
funnel per route, monthly not weekly.

## The three rules, all borrowed from originals

1. **Inputs separated from outputs** (Amazon). Inputs are what you did and can act on: posts
   shipped, conversations held, emails sent. Outputs are what happened and can only be watched:
   started, kept going, paid. A reading that mixes them tells the founder nothing to do
   tomorrow. The safety net comes with it: if moving an input never moves its output across three
   readings, that input metric dies.
2. **One chosen number per quarter** (Lean Analytics). Chosen, not discovered; the stage this
   quarter's work must move; re-chosen when the stage changes. It must be a leading indicator of
   value delivered — signups and time-in-app are named bad choices (Amplitude's own playbook says
   so). For most products the right first choice is activation.
3. **Anomalies get sentences, normal gets silence** (WBR). Every count sits beside last month and
   the baseline. A number in line with its trail needs no words. A number off its trail gets one
   sentence: what happened, or "cause unknown, watching".

## Two deliverables

1. **The reading sheet** — the template the founder fills on the first Monday of each month, per
   route to purchase: stages in plain words (found you · started · kept going · brought someone ·
   paid) · this month, last month, baseline side by side · inputs column with the same trails ·
   the chosen number marked · a sentence slot only where a trail broke.
2. **The report** — the reading judged. On a first run this is mostly the instrument list: what
   cannot be counted yet, and which output owes the fix.

For demo use, the report carries a miniature of the sheet.

## The first reading

The first reading's job is not to read the funnel; it is to name the counts that must exist
before month two. Every dashed cell is traced to its owner: an undefined activation moment
belongs to the Onboarding journey; an impossible paid stage belongs to Packaging and pricing; an
uncounted kept-going belongs to whatever analytics the product ships. **A dashed cell without a
named owner will still be dashed in month six.** Each owed count carries a due reading (R2, R3).

## Guardrails

- **Counts, never percentages under thirty.** At founder scale a conversion rate on 60 people is
  noise wearing a suit.
- **Baselines beside every number.** A number without its trail is decoration.
- **One page per route, never summed across routes.** Consumer and employer funnels are different
  machines; adding their stages produces a number that describes neither.
- **Monthly means monthly.** The value of the reading is the unbroken series; a skipped month
  costs more than a thin one. Same day, same sheet.
- **The reading never renegotiates definitions mid-series.** If activation gets redefined, the
  series restarts and says so; otherwise the trail lies.
- **No dashboard.** A dashboard is looked at; a reading is written. The sentence a founder writes
  about a broken trail is the analysis; software drawing the chart would skip it.
- **A missing count is a "can't", never a zero.** Paid with no price is struck, not 0; writing 0
  poisons the trail.

## The report

Header bar (inverted): `Product funnel metrics · <route> · reading N of 12 · <month>`.

**01 · The reading at a glance** — four stat tiles, big mono numerals: the one counted output ·
stages countable of total · inputs countable of total · counts owed by next reading (this tile
gets the heavy border).

**02 · The stages** — one bar row per stage: plain-word label, proportional bar (solid counted,
dashed uncounted, struck impossible), the numeral, the instrument name or "none · owed RN". Under
them the coverage meter (solid vs faint segments) and the chosen number in a heavy-bordered chip
with the bet named.

**03 · Did against happened** — two scored tiles, x/y numerals with segment bars; the testable
input-output pair count stated.

**04 · The finding** — the numbered black band, 25px.

**05 · The owed counts** (first readings) or **the anomaly sentences** (later) — numbered rows:
count · owner output · due reading.

**06 · What can't be known** — always including: one reading is a point, three make the first
trail; the chosen number is a bet that can be wrong; under thirty a rate is noise.

## Drawing rules

- The document shell: 1px black frame, inverted mono header bar, mono note row, numbered
  eyebrows, hairline section rules, finding at 25px in the band.
- Big mono numerals carry the page; prose only where a number needs a sentence.
- Solid = counted · dashed = uncounted · struck = impossible. The chosen number boxed 1.5px.
- Fragments in drawings. Counts, never percentages under thirty.

## Language

| Use | Never |
|---|---|
| Found you, started, kept going, brought someone, paid | Acquisition, activation, retention, referral, revenue (in the sheet) |
| What you did / what happened | Input KPIs, output KPIs |
| The chosen number | North star metric, OMTM |
| A can't, not a zero | 0 (for an unmeasurable stage) |
| Cause unknown, watching | Under investigation |

## Standing rules for every output

- **The reading reads; other outputs define.** Funnel shape changes go back to their owners.
- **One route per page. Counts never summed across routes.**
- **No invented findings. No false zeroes. Baselines beside every number.**
- **Name organisations, never individuals**, when the work is confidential.
- **Sentence case. British spelling. No em dashes. No balanced two-part lines.** Written for a
  cold reader.
