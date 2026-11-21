# jobs.cue44 — Honesty-Gated AI Prompts for Job Seekers (Core Starter Kit)

> **AI answers are free. Questions are the asset.**

Generic AI resume prompts fail in predictable ways: they invent metrics you never had, fabricate skills that fall apart in the first screening call, and wrap real achievements in robotic clichés recruiters recognize instantly. `jobs.44` takes the opposite approach — every module runs on machine-checkable contracts (`[USER:…]` inputs, `[AGENT:…]` outputs) and per-prompt quality gates, so the assistant can only work with facts you actually provided, across ChatGPT, Claude, DeepSeek, Gemini, and Perplexity. This starter kit contains the six highest-impact modules of the system; the complete 44-module architecture lives on [cue44.com](https://www.cue44.com/jobs/).

## The Starter Pipeline Inside the Full 44-Module System

```text
              THE jobs.44 CAREER SEARCH ARCHITECTURE (44 MODULES)

   +------------------------------------------------------------------+
   |  CV INTAKE & HONESTY GATE                                        |
   |  facts in, everything ambiguous flagged - never guessed          |
   +------------------------------------------------------------------+
                                    |
                                    v
   [starter ★ 02] GHOST-JOB & SCAM AUDIT
   real postings only - or an honest empty result
                                    |
                                    v
   [starter ★ 03] ATS GAP ANALYSIS
   your verified CV vs the post: keywords, fit, red flags
                                    |
                                    v
   [starter ★ 04] ANTI-CLICHE ASSET GENERATION
   resume, cover letter, LinkedIn - your voice, human phrasing
                                    |
                                    v
   [starter ★ 05] STAR INTERVIEW PREP
   real projects -> structured behavioral answers
                                    |
                                    v
   [starter ★ 06] OFFER NEGOTIATION
   evaluation beyond base pay -> professional counter-offer

        ★ = included in this starter kit (6 of 44 modules)
        the CV parser (prompt-01) feeds everything: run it first
        full library: cue44.com/jobs
```

## The 6 Core Modules

| Phase | File | What It Solves | Full Web Version |
|:------|:-----|:---------------|:-----------------|
| 1 · Parse | [`01-cv-parser.md`](prompts/01-cv-parser.md) | Pulls real dates, hard skills and verifiable metrics out of any raw resume into clean, checkable data — and refuses to invent experience. | [Prompt 2 on cue44.com](https://www.cue44.com/jobs/prompts/prompt-2.html) |
| 2 · Verify | [`02-ghost-job-detector.md`](prompts/02-ghost-job-detector.md) | Flags ghost postings, evergreen resume-harvesting traps and outdated vacancies before you invest hours in an application. | [Prompt 10 on cue44.com](https://www.cue44.com/jobs/prompts/prompt-10.html) |
| 3 · Analyze | [`03-ats-keyword-gap-analyzer.md`](prompts/03-ats-keyword-gap-analyzer.md) | Compares your CV against the job post side by side and lists the missing ATS keywords and skill gaps honestly. | [Prompt 27 on cue44.com](https://www.cue44.com/jobs/prompts/prompt-27.html) |
| 4 · Humanize | [`04-anti-ai-cliche-editor.md`](prompts/04-anti-ai-cliche-editor.md) | Strips robotic AI phrasing from your resume, cover letter and LinkedIn copy so you read like a real human candidate. | [Prompt 25 on cue44.com](https://www.cue44.com/jobs/prompts/prompt-25.html) |
| 5 · Prepare | [`05-star-story-bank-builder.md`](prompts/05-star-story-bank-builder.md) | Turns your real project history into structured Situation–Task–Action–Result answers for behavioral questions. | [Prompt 33 on cue44.com](https://www.cue44.com/jobs/prompts/prompt-33.html) |
| 6 · Negotiate | [`06-salary-negotiation-plan.md`](prompts/06-salary-negotiation-plan.md) | Evaluates the offer beyond base pay and drafts a professional counter-offer email backed by market benchmarks. | [Prompt 36 on cue44.com](https://www.cue44.com/jobs/prompts/prompt-36.html) |

## Get the Full System

- **Read all 44 prompts free** — every module on its own page with inputs, quality gates and expected deliverables: [cue44.com/jobs/prompts](https://www.cue44.com/jobs/prompts/)
- **Master System File** — the unified single-file architecture with cross-step state persistence, vacancy archive tracking and an interactive setup wizard: one-time purchase on [cue44.com/jobs](https://www.cue44.com/jobs/) ($24.99 lifetime access)

## Quickstart

1. **Open** any `.md` prompt file in this repo and copy the prompt text.
2. **Fill the bracketed fields** (`[USER:…]`, `[AGENT:…]`) with your real data — the quality gates check honesty, so use facts you can prove.
3. **Paste** into ChatGPT, Claude, DeepSeek, Gemini, or Perplexity and follow the module's checkpoints.

---

<em>Part of [Cue44](https://www.cue44.com/) — Prompt Blueprints. `jobs.44` // for job seekers.</em>
