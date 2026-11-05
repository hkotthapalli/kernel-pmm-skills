---
name: "ai-visibility"
description: "Run the AI visibility (GEO) output with no API keys: you ask the assistants buyer prompts in your own browser and paste the answers, and Kernel measures mention rate, share of voice against the competitor set, an accuracy check against approved positioning, messaging and price, and the cited sources, then ranks off-site and on-site fixes. A free baseline audit plus a monthly re-ask. Use when producing the AI visibility output, running a GEO or AEO audit, or asking what AI says about us."
---

---
name: "ai-visibility"
description: "Run the AI visibility (GEO) output with no API keys: you ask the assistants buyer prompts in your own browser and paste the answers, and Kernel measures mention rate, share of voice against the competitor set, an accuracy check against approved positioning, messaging and price, and the cited sources, then ranks off-site and on-site fixes. A free baseline audit plus a monthly re-ask. Use when producing the AI visibility output, running a GEO or AEO audit, or asking what AI says about us."
---

# AI visibility

What an assistant says when a buyer asks the category question, before that buyer has heard of the company. GEO, short for generative engine optimisation, means getting named, and described correctly, in those answers.

## Two modes

- **Baseline audit.** Free and standalone. Needs only the website. Feeds the GTM Map.
- **Monthly re-ask.** The same prompt set, re-asked on the first Monday of each month and compared with the baseline.

## How answers get collected: no API keys

Kernel makes no calls to any assistant. You ask each buyer prompt in your own browser and paste the full answer, links included. Kernel records the date and assistant with each answer.

- Ask in a private window while signed out, so your history doesn't shape the answer.
- Start a new chat for each run.
- Default: 3 prompts x the assistants your buyers use (ChatGPT and Perplexity by default) x 3 runs. Two assistants gives 18 answers, about 20 minutes.
- Kernel can read the answers with slots still empty, and says so in Limitations.

When producing this output outside the app (a demo or a GTM Map), run the same protocol yourself in a browser and record every answer verbatim. Never paraphrase an answer you did not receive.

## Buyer prompts

**Ask the buyer's question, never the brand name.** "What is WealthKarma?" always returns something and proves nothing.

Kernel drafts the prompts from 11 purchase triggers and the 01 language bank. Three types:
- **Category:** "Best financial planning app for expats leaving the UAE"
- **Comparison:** "Cheapest way to manage investments across two countries"
- **Status quo:** "How should an expat in Dubai plan their money before moving". Buyers start here.

Reject any prompt that contains a brand name.

## Runs and spread

Answers are not stable. The same prompt can return different shortlists. Report the spread, never a single answer. Named in 2 of 3 is the finding. A single answer is a sample of one.

States per run, in fill grammar:
| State | Means | Drawn |
|---|---|---|
| **Named** | The company appears | solid |
| **Named wrong** | Appears, described incorrectly | struck |
| **Not named** | Absent | dashed |

## Metrics

Define each on screen.
- **Mention rate:** runs that name you over all runs.
- **Share of voice:** your mentions over all mentions of the competitor set from 07. Count the status quo (spreadsheet, local bank, do nothing) apart.
- **Accuracy:** mentions that match your approved versions over all mentions.
- **Citation sources:** links in the pasted answers. Some assistants answer without links. List sources only where the answer shows them.

## Accuracy check

Quote each mention verbatim against the approved versions: category and target customer from 14, message pillars and proof points from 17, price point from 15, facts from 24 Product Oracle (or the website until 24 exists). Each mention gets one result:
- **Accurate**
- **Wrong category:** the assistant files you in the wrong category
- **Wrong facts:** countries, features, team
- **Outdated:** true once, no longer true

Trace each wrong answer to the cited page that carries it, where the answer shows one. Named wrong is worse than absent and gets the first fixes.

## Citation sources

Open every cited link. Group by source type: listicles and best-of pages, competitor websites, Reddit threads, editorial media, YouTube, review sites, your website. List the most cited pages with run counts and whether you're on each one. Those pages are the fix.

## What the evidence says moves visibility

All of this is correlation. Say so.
- **Ahrefs, 75,000 brands, AI Overviews (May 2025):** branded web mentions correlate 0.664 with AI Overview mentions, backlinks 0.218, ad spend 0.215. The top quartile of web mentions averages 169 AI Overview mentions against 14 for the next.
- **Seer Interactive, 10,000 GPT-4o API answers (Jan 2025):** page-one Google rankings correlate about 0.65 with brand mentions. Backlinks weak.
- **Kumar, arXiv 2606.20065 (June 2026):** niche and small brands appear in 11% of first runs, household names 73%. Ranked best-of listicles are the most-cited format, about 21% of citations. Sentiment flips far more often than mentions.
- **Aggarwal et al., GEO, KDD 2024:** on your own pages, verifiable statistics, quotations and cited sources gave 30 to 40% gains. Keyword stuffing and an authoritative tone did not help.

So: **off-site fixes first, on-site second.**

## Fixes, ranked

Rank by runs at stake: how many runs the source appears in.
- **Off-site fixes:** get added to a cited listicle with the 14 category line, correct an outdated fact at the publisher, answer a cited Reddit thread as the company, build review profiles where the category's buyers read them.
- **On-site fixes:** publish an **AI fact sheet** with dated, checkable numbers and real citations, built from 24, and no instructions to assistants. Add statistics and named sources to the pages the prompts should reach.

Every fix that adds a claim goes through 18 Claim check first. Each fix carries an owner.

**Do not recommend instruction pages.** Some companies publish /llm-info pages that tell assistants what to say. Reputable assistants treat retrieved content as data, the research finds an authoritative tone does not help, and attacks on named competitors carry legal exposure.

## Report structure

1. **Metrics:** mention rate, share of voice, accuracy, citation sources
2. **Runs:** a grid of prompts by assistant, one mark per run
3. **Share of voice** against 07, status quo apart
4. **Accuracy check:** verbatim mention, approved version, result
5. **Citation sources:** by type, most cited pages
6. **Fixes, ranked:** off-site, then on-site, each with source, runs at stake, Claim check state, owner
7. **Key finding:** a fact, in a black band. "Named in 4 of 18 runs, and 3 of those got you wrong" is a finding. "You are invisible" is a slogan.
8. **Most representative answer**, verbatim, wrong part struck
9. **Limitations**, always including: answers vary between runs and this is a sample; answers depend on account, region and model version; no assistant publishes how it picks brands; the next model release can change everything.

## Language

Matches Kernel's PMM glossary.

| Use | Instead of |
|---|---|
| AI visibility, GEO (generative engine optimisation) | What AI says about us |
| Baseline audit, Monthly re-ask | (new) |
| Buyer prompts, prompt set | The buyer's question |
| Runs | (stays) |
| Named, Not named, Named wrong | (stays) |
| Mention rate | Named in 2 of 5 runs |
| Share of voice | (new) |
| Accuracy check: Accurate, Wrong category, Wrong facts, Outdated | Described incorrectly |
| Citation sources, cited pages | The pages it cited |
| Off-site fixes, On-site fixes | Get into these pages |
| AI fact sheet | llm-info page |
| Key finding, Limitations | The finding, what this can't tell you |

GEO and AEO are recognised market terms now. Use GEO with its plain definition beside it.

## What the competition does (checked October 2026)

- **GEO tools** (GTM 8020 comparison, 18 Oct 2026, a vendor-sponsored list): Otterly from $29/mo, Peec $95/mo, Evertune $60/mo with 100 samples per prompt, Ahrefs Brand Radar from EUR 47/mo, AthenaHQ, Scrunch, Goodie, Mentionova, Profound and Bluefish at enterprise pricing. All track prompts by API across assistants, with share of voice, sentiment and cited sources. More of them now draft fixes with agents.
- **SEO agencies** (WebFX, Seer, SEO.co, PBJ) sell AI visibility audits.
- **PMM firms:** none found checking AI answers against approved positioning. PitchKitchen markets copy "that AI engines cite". Octave sells context for AI agents, not visibility.
- Kernel's difference: the accuracy check against 14, 17, 15 and 24, and fixes routed through 18. Do not claim more coverage or more runs than the tools. They have both.

## Standing rules for every output

- No invented findings. Never paraphrase an answer you did not receive.
- No false zeroes. Absent from one assistant is not absent from all.
- Name organisations, never individuals, when the work is confidential.
- Read the source, never the snippet. Open every cited page.
- Record the date and assistant on every run. An undated report is worthless within weeks.
