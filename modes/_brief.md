# Nathan Myers — Triage Brief

<!-- ============================================================
     THIS FILE IS YOURS. It is USER LAYER — never auto-updated by
     `node update-system.mjs`.
     ============================================================ -->

## Identity
Senior Frontend/Full-Stack Engineer — 15 yrs. Chicago, IL (local only, no relocation). US citizen, no sponsorship needed.

## Target Archetypes

| # | Archetype | What they buy (your proof) |
|---|-----------|----------------------------|
| 1 | **Senior/Staff Frontend Engineer** | Nearly 8 years at SteelSeries: Electron app + sandbox harness, video editing suite, internal UI component library, shared NPM libraries |
| 2 | **Senior Full-Stack Engineer** | NodeJS/GraphQL/AWS Lambda at Placester, Python/Django at Fulton Works, Java/Spring at Cerner |
| 3 | **Automation Engineer** | TD Ameritrade: cut deployment time from 8 hrs of engineer time to 15 min of QA time (Python/Fabric/Jenkins); Azure build automation pipelines + cross-team pain-point tooling at SteelSeries |

<!-- Analog titles: "Front-End Developer", "UI Engineer", "Web Engineer", "Developer Experience Engineer", "Platform Engineer" all count as direct hits on archetype 1 or 2. -->

**Not a target right now: AI/ML roles.** No professional AI/ML expertise yet — it's a topic he's actively learning, not a proof point. An AI/ML/GenAI-primary role (AI Research Engineer, Applied AI Engineer, ML/Agentic Systems Engineer, etc.) is an archetype MISMATCH (score 1-2 on archetype fit), not a hit, even though "AI" appears in the title/JD. Score it on whatever frontend/full-stack substance it has, if any.

## Proof Points (use exact metrics in matching)
- Automated build/deploy at TD Ameritrade — reduced deployment time from 8 hours of engineer time to 15 minutes of QA time
- Configured Azure build automation pipelines, and built cross-team tooling addressing other departments' pain points, at SteelSeries
- Designed and shipped an Electron application, sandbox harness, and video editing suite at SteelSeries (~7.5 years there)
- Statz on Statz — self-directed NBA data-viz project, running since Oct 2015

## Comp Strategy

| Target | Requirement |
|--------|-------------|
| $131K+ | Matches most recent SteelSeries base — target for any full-time offer |
| $110K  | Hard floor |

**Hard floor: $110K. Below that, FAIL regardless of other signals.**

## Location Scoring
- Chicago-based, hybrid or on-site (a real office to go to) → **5.0** — preferred, not just acceptable
- Fully remote / async-first → **4.0** — still fine, no DQ, but scores below an equivalent Chicago hybrid/on-site role
- On-site or hybrid requiring relocation outside Chicago with no remote option → **1.0** (Hard DQ)

## Hard DQ Criteria — instant FAIL (< 3.0)
- Stated comp ceiling below $110K
- Requires relocation outside Chicago with no remote option
- Primary hands-on skill outside JS/TS/frontend/full-stack AND outside CI/CD build/release automation or internal tooling (e.g. mobile-native iOS/Android, embedded/firmware roles, AI/ML research or applied-AI engineering roles) — a role whose primary work is automation/CI-CD tooling is a hit on archetype 3, not a DQ
- Defense contractor (primary business is defense/military contracting — prime contractors, weapons systems, military-only suppliers): score 1.0, DQ regardless of technical fit
- Gambling-affiliated company (casinos, sports betting, iGaming, core product is gambling): score 1.0, DQ regardless of technical fit

## Quick Scoring Guide

Bands are relative to `triage_threshold` (`config/profile.yml → pipeline.triage_threshold`,
default **3.5**), matching the verdict table in `modes/triage.md` — so a score at or
above the threshold is PASS, and only the band below it is MARGINAL.

| Score | Verdict | What it means |
|-------|---------|---------------|
| ≥ threshold (default 3.5) | **PASS** | Clears the bar — strong archetype + comp + location, gaps bridgeable |
| 3.0 – (threshold − 0.1) | **MARGINAL** | Borderline — shown to user as one line |
| < 3.0 | **FAIL** | Does not clear the bar — filtered |

## Soft Red Flags (−0.5 each, additive)
- Heavy backend-only role (Java/.NET/PHP-centric) with little to no frontend work — does not apply when the role is scored against archetype 3 (Automation Engineer), where backend/infra-only scope is expected, not a gap
- Stated primary frontend framework is Vue or Angular (not React) — deep expertise is React-specific; downrank, don't DQ. A role using both React and Vue/Angular, or where frontend is a minor component, is not flagged.
- Company headcount outside the 50-200 ideal range — mild tiebreaker only, prefer larger over smaller when it's the deciding factor between two similar roles; never a real penalty on its own

## Priority Override List — always return PASS regardless of score
<!-- none yet — add companies here as Nathan flags specific interest -->
