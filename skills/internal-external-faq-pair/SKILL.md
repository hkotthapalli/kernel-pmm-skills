---
name: "internal-external-faq-pair"
description: "Build the internal FAQ and external FAQ plus the report: the internal FAQ judged by how hard its questions are, the external FAQ answer-first for sceptical buyers and AI assistants. Questions harvested from the buying committee, interviews, support, reviews and competitor FAQs, never invented; every answer has a state (Answerable, Blocked, Not yet answerable); the do-not-say list comes from the Claim check. Use when producing the FAQ output, writing launch or product FAQs, or preparing answers for the questions buyers actually ask."
---

# FAQ

Two documents, two audiences, two opposite jobs. Writing one and calling it both is the standard failure.

- **The internal FAQ** prepares whoever answers live. Its value is proportional to how hard its questions are — the discipline Amazon used to vet Kindle, Prime and AWS, where the FAQ exists to hold the hard questions, not to decorate the easy ones.
- **The external FAQ** answers the sceptical and the stuck, cuts support load, and is an AI answer surface: assistants quote answer-first, attributable text, and the FAQ page is one of the cheapest fixes to being absent from AI shortlists.

## The deliverables

Three: the internal FAQ file, the external FAQ file, and the report that judges them. On a real engagement all three ship; for demo or portfolio use, the report alone is enough.

## Harvest, never invent

Invented FAQs answer what the company wishes people asked. The system supplies the real ones:

1. **The buying committee output is the skeleton.** Each buying role's key questions at each buying stage are the FAQ, organised by buying role, per buying motion, never summed.
2. **The objection library** — the eight, restated as questions.
3. **Sales calls and win/loss** — the questions that stopped a conversation.
4. **The community and support channels** — the freshest confusion.
5. **"People also ask" and search queries** — for the external version this doubles as keyword research.
6. **Competitor FAQs** — what the category's buyers worry about. Unconfirmed until one of your own buyers asks it.
7. **Internal chat** — if employees keep asking it, customers will too.

**Rank by frequency × cost of a wrong answer.** A rare question whose wrong answer loses a deal outranks a common one about button placement.

## Answer states

| State | Means | Drawn as |
|---|---|---|
| Answerable | The honest answer exists today | Solid, green in the app |
| Blocked | The answer waits on another decision (a price, a legal call) | Dashed, with the blocker and owner named |
| Not yet answerable | Nobody knows, and pretending is worse | Outlined, with what would settle it |

A blocked question stays in the document with its blocker named. Removing it hides the gap; a rep meets it live anyway.

## The internal FAQ

Must include the hard questions — if it contains no awkward questions, it was not written honestly, and a rep gets caught out in front of a customer:

- Why is this more expensive than [competitor]?
- What's not ready yet? The known gaps, plainly.
- What do I say about [competitor]?
- What happens to the customer if we shut down?
- What can't I promise? The roadmap boundary, in writing.
- Who do I escalate to, and how fast do they answer? The escalation path, by role.

Plus a **known issues** section with current status, and the **do-not-say list, imported from the Claim check** in strikethrough form: the claims graded Contradicted or high-risk, each with the line to say instead. The FAQ is where those fixes reach the people who talk.

A rep who has read an honest internal FAQ handles a hostile question calmly. A rep who has read a sanitised one improvises, and improvised answers become commitments.

## The external FAQ

People read FAQs when they are sceptical or stuck. Both states are hostile to enthusiasm.

- **Answer in the first sentence.** Then elaborate. Never build up to the answer. Aim for 40 to 80 words.
- **Buyers' words for the question.** If customers say "does it work offline", the question is not "connectivity resilience".
- **No marketing language.** An FAQ that sells makes the reader distrust every answer.
- **Say no clearly.** "Does it do X?" gets "No. It does Y, which covers most of the same need." An evasive answer is worse than none: the reader concludes something is being hidden and stops trusting the rest.
- **One question, one answer.** Link deeper rather than expanding.
- **The limitations section is non-optional.** A product with no stated limits reads as dishonest or unconsidered, and technical buyers check for it specifically.
- **Built as an AI answer surface**: answer-first structure, attributable statements, FAQPage markup so assistants can quote it. State this purpose in the document. FAQPage markup is a supported type, but vendor claims that it raises AI citations are unverified, so never promise a lift.

## Guardrails

- Never invent a question to fill a section. A short honest FAQ beats a padded one.
- Never answer what cannot be answered truthfully. "We don't have a firm answer yet. Here is what we know" is an answer.
- No roadmap promises in either document. "Not currently supported" is safe; "coming in Q3" becomes a contractual expectation.
- Keep the two documents separate and labelled. Assume the external one will be forwarded and the internal one might be.
- Date both. FAQs rot faster than almost any other asset.

## Maintenance: the twice-asked rule

**When the same question is asked twice, it goes in the FAQ.** That single habit beats any quarterly review, and it means the FAQ grows from evidence. Pair with the freshness audit; update per release.

## The report's structure

Header: `FAQ · N questions · N answerable · <date>`.

**01 · Question sources** — sources drawn with counts, the buying committee skeleton visible, per buying motion.

**02 · Internal FAQ and external FAQ** — question rows with their answer states, side by side at count scale. The picture shows how much of what buyers ask has an answer today.

**03 · Hard questions** — five internal specimens with their real answers, including at least one honest "no" and one "we don't have a firm answer yet".

**04 · Do-not-say list** — strikethrough rows from the Claim check, each with the replacement line.

**05 · Key finding** — one sentence, black band.

**06 · Limitations** — standing limits, always including: the harvest covers the people who asked, not the ones who left silently; and a blocked answer is a decision owed elsewhere, not a writing task.

## Drawing rules

- Questions as rows with state marks. Fragments, not paragraphs, in the report (the full answers live in the files).
- The two FAQs drawn side by side so the reader sees internal hard questions next to external clarity.
- Do-not-say rows in strikethrough-to-replacement form.
- Counts per buying motion, never summed. No percentages under thirty.

## Language

Standard product marketing terms on every label and heading. Never a label built from "who, what, which, where" phrasing. External questions stay in buyers' words.

| Use | Instead of |
|---|---|
| Internal FAQ, External FAQ | (stays) |
| Question sources | Where the questions came from |
| Answer states: Answerable, Blocked, Not yet answerable | Blocked upstream, can't be answered honestly yet, pending dependency |
| Hard questions | The uncomfortable questions, sensitive topics, edge cases |
| Roadmap boundary | What am I not allowed to promise, roadmap governance |
| Do-not-say list | (stays, imported from Claim check) |
| Known issues, Escalation path | (stays) |
| FAQPage markup, AI answer surface | (stays) |
| Twice-asked rule | Feedback loop process |
| Say no clearly | Manage expectations |
| Key finding, Limitations | The finding, what can't be known |

## Standing rules for every output

- **Three deliverables: two FAQ files and the report.**
- **Harvest, never invent.** Every question traces to a source with a count.
- **Every answer carries a state.** Blocked stays in, with its blocker named.
- **The do-not-say list imports from the Claim check.** The FAQ never re-argues the grades.
- **Read the source, never the snippet.**
- **Name organisations, never individuals**, when the work is confidential.
- **Sentence case. British spelling. No em dashes. No balanced two-part lines.**
