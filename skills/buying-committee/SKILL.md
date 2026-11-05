---
name: "buying-committee"
description: "Map the buying roles that have to agree before a purchase happens, the questions each role asks at the consideration and decision stages, and which of those questions you cannot answer, ranked into gaps with fixes and one enablement asset per role. Use when producing the Buying committee output, mapping buying roles, or asking why deals stall with no competitor involved."
---

# Buying committee

**A buying committee is every buying role that has to agree.**

A buying role is anyone who can stop the purchase, delay it, or undo it afterwards. It is defined by the job that person does in this one decision, never by a name. That definition works for enterprise software, for a clinical device, and for one person deciding whether to open an app — because in all three somebody else gets asked first.

The output is a question map: buying roles down the side, two buying stages across, and in every cell the question that role asks and whether you can answer it. **The unanswered cells are the output.**

## What this is not

There is a well-known artefact with the same name that belongs to revenue operations: a per-account map of named individuals with influence scores and last touch dates, built from a CRM with account hierarchy, a target account list, intent data and a contact database. Tools such as 6sense and Demandbase sell it.

**Do not build that one.** An early-stage company has no such list. A B2C company has no accounts at all. A thin imitation of a sales operations tool is worse than nothing.

This output works one level up: the buying roles, what each needs to hear, and which of those things you cannot currently say.

## Why a question map

Buyers spend a small share of their buying time with suppliers. The widely quoted Gartner figure is about 17%, split across every supplier being considered, though the survey date behind it is disputed (2017 to 2020), so cite it as widely quoted, not as current fact. Either way, any one seller gets a sliver of the committee's attention, and most buying roles never meet you.

That decides what counts as an answer. An answer is something that exists without you in the room: a page, a number, a document the champion can forward, a line in the pricing table. "The rep explains it on the call" is not an answer, because most of the committee is not on the call.

Apply this test to every cell. If the only way the role gets the answer is by talking to you, the cell is not answered.

## A buying role is not a persona

A persona describes a kind of person. A buying role describes the job that person does in one particular decision. The same finance lead is the economic buyer for one purchase and a blocker for the next. Roles are defined by their deal risk, never by who they are. Personas, where needed, are written per role.

## The role checklist

Run this **after** you have found the real roles, to see what you missed. Never as the starting list.

| Buying role | Deal risk |
|---|---|
| **End user** | Makes the purchase pointless by not using it |
| **Economic buyer** | Refuses on cost |
| **Champion** | Carries the case internally, and stalls if they have nothing to forward |
| **Influencer** | Kills it in a sentence, and is never marketed to |
| **Technical, security or legal reviewer** | Delays indefinitely on risk, data, legal or compliance |
| **Implementer** | Quietly deprioritises the rollout |
| **Blocker** | Loses budget, headcount or territory if you win |
| **Incumbent owner** | Chose the current solution and would have to admit it was wrong |
| **Approver** | Decides it is not this quarter |
| **Regulator** | Sets what everyone else may agree to, and never appears |

The last three are the ones most teams miss. The incumbent owner has an ego stake in your failure, and no framework lists them.

For B2C, the same checklist reads: end user and economic buyer (often one person), co-decision maker (a partner or spouse), influencer (the friend, colleague or adviser they ask), incumbent owner (whoever holds the current product, such as a bank adviser), regulator.

## Identifying buying roles

Roles come from evidence. Grade every role by its evidence source.

| Evidence source | What it means | Drawn as |
|---|---|---|
| **Customer interviews or lost deals** | A buyer named the role, or a loss record shows it | Solid, green in the app |
| **Structural or regulatory requirement** | Org chart, regulation, budget ownership, contract signatory | Half |
| **Inferred** | Inferred from what your own content never addresses | Dashed, and every cell for that role is unconfirmed |

**You do not need interviews to name a role. You need them to fill one.** Most roles are deducible. What each role actually asks is not, and a question invented and put in a role's mouth is the worst thing this output can contain.

### Where to look without interviews

- **Lost deals and the loss reason field.** Any external role named in a loss is a buying role.
- **Job ads at target companies.** A posted role tells you it exists and what it is measured on.
- **Review sites.** Complaints after purchase reveal which role was unhappy and was never sold to.
- **Support tickets and onboarding drop-off.** These expose the implementer who had to do work and didn't.
- **Competitors' own sites.** The roles they create content for are roles they have already met. A competitor with a security page has met a security reviewer.
- **The regulation and the standard contract for the category.** These name roles nobody mentions.
- **Community threads where buyers ask peers.** The reply is the influencer talking.

### What deduction always misses

Roles with no job title. An org chart gives you finance, legal and IT. It will never give you the colleague asked over lunch, the spouse, the consultant on retainer, or the peer in a community thread. Those influencers appear only in loss records and interviews, and they frequently decide it.

If the map contains only roles from an org chart, it was deduced, not researched. Say so in the limitations.

## How many roles

Benchmarks vary because definitions vary. Survey work puts a typical buying group between six and ten people, more on complex purchases, and other studies give five or thirteen. Cite the range, never one number as fact.

- **Fewer than three roles** — you probably have not looked. Check the checklist before accepting it.
- **More than eight** — you are listing people, not roles. Merge any that ask the same question.
- **Exactly one** — possible for self-serve, low price, low risk. **Do not manufacture a committee that isn't there.**

Role count scales with the risk of being wrong, not with the size of the company.

## One map per buying motion

Draw a separate map whenever **the same product is bought through a different buying motion**, because the roles change entirely:

- Self-serve alongside sales-led
- Direct alongside partner, reseller or marketplace
- Bought by the end user alongside purchased on behalf (an employer, a parent)
- New business alongside renewal, where the roles include whoever has to defend the original decision

Separate maps, never one merged. A merged map lets a gap in one motion hide behind an answer in the other. Say which roles appear in both.

## The two buying stages

| Stage | What the role is deciding | Shape of the question |
|---|---|---|
| **Consideration** | Is this worth shortlisting | Does it solve it, does it fit, roughly what does it cost |
| **Decision** | Is this the one, and is it safe | Prove it, who supports it, is it compliant, will you last |

Research on B2B buyers puts most of the process in consideration, where the shortlist forms and a favourite emerges, and the rest in decision, where the choice already made gets checked. The questions in each barely overlap.

Name the stages for the category: "before the shortlist" and "before signing" for software, "before download" and "before first deposit" for a considered consumer purchase. **Two stages always. A third is a project plan, not a question map.**

## Filling the cells

One question per cell, in the buyer's own words where an interview supplied it. Mark where each question came from: a buyer's words (in quotes) or Kernel's question (in italics, unconfirmed until a buyer raises it). Then give the cell a state.

| State | Means | Drawn as |
|---|---|---|
| `Answered` | There is an answer, with proof, and it exists without you in the room | Solid, green in the app |
| `Partly answered` | An answer exists but the proof is thin, borrowed, or from another market | Half |
| `Unanswered` | Nothing a buyer can find answers it | Dashed outline |
| `Contradicted` | You answer it and something of your own disagrees | Outlined, struck through |

**`Contradicted` is the state worth hunting for.** Two pages that disagree, a promise the small print takes back, a claim with no evidence behind it. These cost more than a gap, because the role finds them without your help and they raise the question of what else is wrong.

A map with no answered cells is usually the author showing off. Look properly for what does work and mark it.

## Gaps, ranked

The unanswered and contradicted cells, ranked by two things in this order:

1. **Veto power.** A gap in front of a role that can stop the purchase alone outranks a gap in front of an opinion.
2. **Buying stage.** A question that only lands at the decision stage has already cost the whole cycle.

For each gap, name the one fix — a number, a page, a document, a conversation — and the owner output (FAQ, Claim check, Sales enablement, Messaging framework). One line each. This is the part the reader acts on.

## Hand-offs

The point of naming roles is that other work gets built per role:

- **One message per buying role** in the Messaging framework
- **One enablement asset per role** — the champion needs something to forward, the reviewer needs a document, the economic buyer needs a number. This is the digital sales room idea without the sales room: something that reaches roles you never speak to
- Contradictions go to the Claim check
- Recurring objections from one role become that role's section in Sales enablement

If nothing downstream changes because of this output, it was a diagram.

## Output structure

Header: `Buying committee · N roles · N unanswered · <sources> · <date>`

**01 · Buying roles** — each with deal risk, evidence source with a count, and veto power. One verbatim where there is one.

**02 · Questions by buying stage** — the map or maps. Roles down, two stages across, every cell in its state.

**03 · Gaps, ranked** — each with its fix and owner output.

**04 · Key finding** — one sentence, black band, naming the role nobody answers.

**05 · Limitations** — always names the roles nobody interviewed, and whether the map was researched or deduced.

Five sections. The deliverable adds the enablement asset per role, with its status.

## Adapting by category

The method does not change. The roles do.

- **Enterprise software** — champion, economic buyer, security reviewer, implementer (the admin who runs it), procurement as approver.
- **Developer tools** — the engineer as end user and champion, the platform team as approver, security reviewer, whoever owns the cloud bill as economic buyer.
- **Health** — the clinician as end user, the administrator as economic buyer, whoever reimburses it, the patient who has to comply with it.
- **Consumer money** — end user and economic buyer, co-decision maker, influencer, incumbent owner, regulator.
- **Anything regulated or public** — end user, economic buyer, procurement as a role with its own rules, and the regulator.

If the category has a status quo option — the buyer can decide to do nothing — that is not a role, but it changes every cell, because each question competes with "or we just don't". Note it once and leave it to the Win / loss and competitive work.

## Drawing rules

- Counts as marks, filled out of the total. The reader counts.
- The question map is the centre of the document. Give it room.
- States in fill. Green only on answered cells, roles from interviews, and live assets.
- Buyer questions in quotes, Kernel's questions in italics.

## Language

Standard product marketing terms on every label and heading. Never a label built from "who, what, which, where" phrasing.

| Use | Instead of |
|---|---|
| Buying committee, buying roles | Seats, stakeholder map, DMU |
| End user, Economic buyer, Champion, Influencer, Co-decision maker | The one who uses it, the one who pays, the one who is asked |
| Technical, security or legal reviewer | The one who reviews it, gatekeeper |
| Implementer, Blocker, Incumbent owner, Approver, Regulator | The one who does the work, loses something, chose the old product, signs, never appears |
| Veto power | Can say no alone |
| Deal risk | What it can do to the decision |
| Evidence source | How you know |
| Buying motion: self-serve, sales-led, partner, purchased on behalf, renewal | Routes to purchase, how people buy |
| Consideration stage, Decision stage | Getting on the list, getting chosen, gates |
| Answered, Partly answered, Unanswered, Contradicted | Solid, half, dashed (as labels) |
| Gaps, ranked | Where it breaks |
| Enablement asset | One thing to send |
| Key finding, Limitations | The finding, what can't be known |

No influence scores, ever. Write "buying committee" once outside the title and say "buying roles" after that.

## Voice

- Plain and direct. Their words in quotes, yours outside them.
- No slogans, no balanced two-part phrases, no line whose job is to sound clever. If a line has a rhythm, a turn, or would work on a poster, cut it.
- The key finding is a fact, not a formulation.
- Sentence case. British spelling. No em dashes.

## Rules

- **Every role needs an evidence source, graded.** Interviews or lost deals, structural, or inferred. Inferred roles are always dashed.
- **You don't need interviews to name a role. You need them to fill one.**
- **An answer has to work without you.** If the role only gets it from you in a meeting, the cell is not answered.
- **The gaps are the output.** A map where everything is answered was filled in from imagination.
- **Never a named individual.** Roles only. This is not an account plan.
- **No influence scores.** Veto power is yes or no, in a sentence.
- **Never a percentage under thirty.** Four of twelve is four of twelve.
- **Two stages, never three.**
- **One map per buying motion.**
- **The key finding names the role nobody answers**, not how many roles there are.
- **Read the source, never the snippet.** Any page cited as evidence that a role is or is not addressed gets opened and read in full.
- **Name organisations, never individuals**, when the work is confidential.
