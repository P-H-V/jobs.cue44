# Resume & CV Parser Prompt (Extract Skills Without Hallucinating) (`jobs.44` // Prompt 2)

> **Part of the Cue44 `jobs.44` Career Search Architecture.**
> Read the full 44-module library free, or get the unified **Master System File** at **[cue44.com](https://www.cue44.com/jobs/prompts/prompt-2.html)**.

## Purpose

You have a CV as raw text and need the facts out of it without embellishment. Feed the parser your resume text and it returns a dated, verifiable profile — flagging anything ambiguous instead of guessing.

## Copy-Paste Prompt

```text
Parse [USER:CV_INPUT] and [AGENT:CANDIDATE_PROFILE] into [AGENT:CV_PROFILE]. Extract contact info, professional summary, work experience with dates and companies, education, skills, tools, certifications, languages, projects, achievements, and references. Normalize titles and dates. Extract ATS keywords. Flag ambiguous sections in [AGENT:ASSUMPTION_LOG]. Do not invent experience, skills, dates, or achievements. Do not inflate seniority. Do not rewrite the CV. Do not apply to jobs.
```

## Next Step in the Pipeline

- Continue through the full 44-prompt workflow at **[cue44.com](https://www.cue44.com/jobs/prompts/)** — every module has its own page, inputs, gates and expected deliverable.
