# Kernel PMM skills

A full product marketing function, written as 34 Claude skills.

34 outputs. 6 stages. One product marketing function.

I'm Harsha Kotthapalli, a 3× founding product marketing leader. I built PMM functions from zero at LINAGORA, MarineTraffic and Food Vessel. These skills are the method I use for clients at [Kernel](https://kernelpmm.com), my fractional product marketing practice for Seed to Series B startups. Research and competition run as AI workflows. I do positioning and messaging by hand, and I check every number against its source before a human reads it.

Each skill tells Claude how to produce one output: what goes in, what comes out, the evidence it needs, and the rules that stop it from making things up.

## The 34 outputs

| # | Stage | Output | What it gives you |
|---|---|---|---|
| 01 | Research | [Voice of customer](skills/voice-of-customer/SKILL.md) | Sales calls and reviews mined first, then six switch interviews, coded into a language bank |
| 02 | Research | [Win/loss](skills/win-loss/SKILL.md) | Why deals were really won and lost, from the buyer, with the recorded reasons sealed before the calls |
| 03 | Research | [Market report](skills/market-report/SKILL.md) | A sizing model where every assumption is a cell with a source, plus a bottom-up and top-down check |
| 04 | Research | [Why now](skills/why-now/SKILL.md) | Every timing claim dated to a real external catalyst, then one chosen |
| 05 | Research | [Assumption log](skills/assumption-log/SKILL.md) | What the plan rests on, graded by impact and evidence, with the cheapest test for the riskiest ones |
| 06 | Research | [Pre-mortem](skills/pre-mortem/SKILL.md) | How a launch fails, ranked by how late you would notice, with a tripwire per critical cause |
| 07 | Competition | [The Fifty](skills/the-fifty/SKILL.md) | Fifty questions across six categories for every real competitor, each cell sourced and dated |
| 08 | Competition | [Table-stakes read](skills/table-stakes-read/SKILL.md) | Which attributes every rival has, and which are differentiator candidates worth testing |
| 09 | Competition | [AI visibility](skills/ai-visibility/SKILL.md) | What ChatGPT, Perplexity and others say when buyers ask, scored for mentions, share of voice and accuracy. No API keys |
| 10 | Competition | [Competitor monitor](skills/competitor-monitor/SKILL.md) | A weekly watch that reports only what changed and names the document each change makes stale |
| 11 | Position | [ICP and segments](skills/icp-and-segments/SKILL.md) | Scored segments, a disqualification sheet, and the beachhead to start with |
| 12 | Position | [Use cases](skills/use-cases/SKILL.md) | Jobs to be done counted from interviews and win/loss, with a build test and a page brief per use case |
| 13 | Position | [Buying committee](skills/buying-committee/SKILL.md) | The roles that must agree, the questions each asks, and the ones you cannot answer yet |
| 14 | Position | [Positioning](skills/positioning/SKILL.md) | Two or three positioning options, evidence grades, and a test that would prove the choice wrong |
| 15 | Position | [Packaging and pricing](skills/packaging-and-pricing/SKILL.md) | Value metric first, then packaging, then the price point, with a test kit for willingness to pay |
| 16 | Position | [Deck spine](skills/deck-spine/SKILL.md) | The argument an investor deck rests on, with every claim graded and the empty slides named |
| 17 | Message | [Messaging framework](skills/messaging-matrix/SKILL.md) | A one-page messaging sheet per buying role, passed through a competitor swap test |
| 18 | Message | [Claim check](skills/claim-check/SKILL.md) | Every public claim graded against its evidence, with a fix for each high-risk one |
| 19 | Message | [Landing page review](skills/landing-page-review/SKILL.md) | Clarity, relevance, value and differentiation, checked in order, stopping at the first failure |
| 20 | Message | [Message drift](skills/message-drift/SKILL.md) | Every surface compared with the approved messaging, cell by cell |
| 21 | Launch | [Launch tiers](skills/launch-tiers/SKILL.md) | Five yes/no questions decide the tier, and the tier decides the checklist |
| 22 | Launch | [Launch brief](skills/launch-brief/SKILL.md) | One page that runs a launch, with one pass number agreed before ship |
| 23 | Launch | [Channel and funnel](skills/channel-and-funnel/SKILL.md) | The channels you can afford at your price, tested with pass numbers set in advance |
| 24 | Launch | [Product Oracle](skills/product-oracle/SKILL.md) | The two-page source of truth every other document is built from |
| 25 | Launch | [Sales enablement](skills/sales-enablement/SKILL.md) | Battlecards, objection library, demo script and playbook, with a usage log |
| 26 | Launch | [FAQ](skills/internal-external-faq-pair/SKILL.md) | An internal and an external FAQ harvested from real questions, never invented |
| 27 | Launch | [Onboarding journey](skills/onboarding-journey/SKILL.md) | One activation moment, a journey map, and early warnings for accounts that stall |
| 28 | Launch | [Release notes](skills/release-notes/SKILL.md) | Every ship classified, then written as what changed, why it matters and what to do |
| 29 | Measure | [Funnel metrics](skills/product-funnel-metrics/SKILL.md) | A monthly reading of the funnels the other outputs define |
| 30 | Measure | [Launch post-mortem](skills/launch-post-mortem/SKILL.md) | A blameless review against the number agreed before launch |
| 31 | Measure | [Trust metrics](skills/trust-metrics/SKILL.md) | Trust in three layers: what people do, what they say when asked, and what others lend you |
| 32 | Measure | [Case studies](skills/case-studies/SKILL.md) | A scored pipeline, an interview guide, a ladder for getting a real number, and a permission record |
| 33 | Measure | [Half-Life Map](skills/half-life-map/SKILL.md) | Every asset with an owner and a half-life, so stale material gets fixed or retired |
| 34 | Measure | [Six-stage readout](skills/six-stage-readout/SKILL.md) | A quarterly grade of all 34 outputs, rolled up to the one constraint to fix next |

Skills refer to each other by these numbers. For example, Messaging framework (17) uses Positioning (14) and the language bank from Voice of customer (01).

## How the skills work

**Two deliverables per output.** Most skills produce a working file the team keeps using (a sheet, a log, a kit) and a report that judges it.

**Evidence or nothing.** Every claim carries a source and a date. A cell nobody can fill stays empty and says so. A missing count is shown as unknown, never as zero.

**The fill grammar.** Reports use one visual language for evidence:

| Mark | Meaning |
|---|---|
| Solid | Proven, counted, exists |
| Half-filled | Partial, or exists but thin |
| Dashed outline | Unchecked or missing. The honest default |
| Struck | Tested and false, or retired |
| Outlined empty | Nobody knows yet |
| Hatched | Made stale by an event |
| Heavy border | Start here |

If most marks come back solid, the standard was too soft.

## Install

**Claude Code**

```
/plugin marketplace add hkotthapalli/kernel-pmm-skills
/plugin install kernel-pmm-skills@kernel-pmm-skills
```

**Claude.ai and the Claude desktop app**

Zip any folder under `skills/` and upload it in Settings, Capabilities, Skills. Then ask for the output by name, for example "run the claim check on our homepage" or "build the buying committee for our mid-market motion".

## Related

- [gtm-map-agents](https://github.com/hkotthapalli/gtm-map-agents): the free diagnostic that maps a company's public surfaces against these 34 outputs, built by one agent and re-checked by a second agent that never sees the first one's notes.
- [kernelpmm.com/work](https://kernelpmm.com/work): case studies from the companies where this method was built.

## Licence

MIT. Use it, change it, ship it. A link back is appreciated.
