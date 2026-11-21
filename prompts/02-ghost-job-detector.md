# Fake & Ghost Job Posting Detector Prompt (`jobs.44` // Prompt 10)

> **Part of the Cue44 `jobs.44` Career Search Architecture.**
> Read the full 44-module library free, or get the unified **Master System File** at **[cue44.com](https://www.cue44.com/jobs/prompts/prompt-10.html)**.

## Purpose

You found a promising listing and want to know if it is real before applying. Feed the prompt the posting and it checks freshness, company and recruiter evidence for ghost-job and harvesting signals.

## Copy-Paste Prompt

```text
For each vacancy in [AGENT:VACANCY_MATCH_SCORES] and [AGENT:VACANCY_LIST_RAW], check posting freshness, company existence, recruiter identity, and application requirements. Re-open each shortlisted posting URL and its direct-application end-link in-session where possible. Run the link-specificity check on every link: the URL must be a deep link that resolves to a unique posting page for this role at this company — root domains, bare hosts, homepages, category pages, and board or Google search URLs with query params are auto-rejected and logged, never presented as results. A posting or apply link that cannot be re-opened is unverifiable, and the posting is excluded from the strong tier until confirmed. Confirm the final page shows this role at this company before trusting the link. Flag scam signals, ghost jobs, duplicates, unrealistic salaries, and vague or unpaid roles. Use [AGENT:SOURCE_LOG] and [AGENT:ATS_MAP]. State confidence levels and unresolved risks as [AGENT:VACANCY_VERIFICATION]. Present every verified vacancy with its posting URL and apply end-link inline; never describe a verified or rejected vacancy without its links. Record contradictions in [AGENT:CONTRADICTION_LOG]. Do not rubber-stamp. Do not ignore red flags. Do not verify from memory or plausibility; only from retrieved evidence. Do not give legal or immigration advice.
```

## Next Step in the Pipeline

- Continue through the full 44-prompt workflow at **[cue44.com](https://www.cue44.com/jobs/prompts/)** — every module has its own page, inputs, gates and expected deliverable.
