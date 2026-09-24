# Evaluation: Northern Trust — Sr Associate Software Engineer, AI Security

**Date:** 2026-09-22
**URL:** https://www.builtinchicago.org/job/sr-associate-software-engineer-ai-security/11306603
**Via:** — (direct)
**Archetype:** Senior Full-Stack Engineer (secondary) — the "AI Security" framing is not scored as an archetype match per modes/_profile.md; evaluated on its non-AI full-stack/backend merits
**Score:** 3.2/5
**Legitimacy:** High Confidence
**Work Auth:** ➖ Not needed
**PDF:** output/cv-nathan-myers-northern-trust-2026-09-22.pdf

---

## DoD / defense-related content check (explicit, per user request)

The full JD was read line by line specifically for any Department of Defense, military, or defense-contract mention. **None found.** The platform being built is an internal AI-powered code security scanner for Northern Trust's own enterprise codebases; the company's own description is wealth management, asset servicing, asset management, and banking services (Nasdaq: NTRS) — a financial-services company, not a defense contractor, with no client list, program name, or team description anywhere in the JD referencing DoD, a military branch, or a defense contract. The `modes/_profile.md` DoD/defense hard-exclude does **not** apply here; the standing **fintech/financial-services soft-deprioritize** applies instead (see Block G and the Machine Summary).

---

## Machine Summary

```yaml
company: "Northern Trust"
role: "Sr Associate Software Engineer, AI Security"
score: 3.2
legitimacy_tier: "High Confidence"
archetype: "Senior Full-Stack Engineer (secondary, non-AI merits only per modes/_profile.md)"
final_decision: "Consider"
hard_stops: []
soft_gaps:
  - "Application security and vulnerability management is the core subject-matter of this role (an AI-powered security scanner) and cv.md has zero evidence of appsec/vulnerability-management background"
  - "REST APIs and authentication/authorization integrations are stated requirements; cv.md's API depth is GraphQL-specific (Placester), not REST+auth-specific"
  - "Automation and orchestration frameworks (workflow/pipeline orchestration, not just CI/CD automation) are only partially evidenced -- TD Ameritrade's deployment automation is adjacent, not the same category"
  - "Agent-based workflows and automation frameworks -- cv.md's MCP/local-LLM work is agent-adjacent but not explicitly proven in a production agent-workflow context"
  - "Financial services / banking: soft-deprioritized per modes/_profile.md, not a penalty"
  - "Large company (24,000+ partners) sits well outside the candidate's ideal 50-200 headcount range -- soft tiebreaker only, not a penalty (larger preferred over smaller outside the ideal band)"
top_strengths:
  - "Chicago Loop hybrid location (50 S. La Salle) is exactly the candidate's stated preferred setup"
  - "Expert-level Python and mid-level-or-above React are both direct, deep, named matches in cv.md"
  - "Experience integrating Large Language Models (LLMs) is a direct match: cv.md Summary states 'Recently active in local LLM tooling and MCP server design'"
  - "No sponsorship needed -- JD states no sponsorship available, candidate doesn't require it, non-issue"
  - "Comprehensive, transparent comp/benefits disclosure from a large, publicly traded, 135-year-old company"
risk_level: "Medium"
confidence: "Medium"
next_action: "Consider applying -- strong engineering fundamentals match, but be candid in the process that application-security/vulnerability-management domain depth is a genuine gap, not a stretch; ask directly how much of the role is security-domain-specific vs. general platform engineering"
work_auth: "not_needed"
discard_reasons:
  - "domain_expertise_gap (application security)"
via: null
company_confidential: false
advertised_comp: "$88,900 - 151,100 USD"
reports_to: null
requirement_importance:
  - requirement: "5+ years of professional software engineering experience"
    jd_signal: "5+ years of professional software engineering experience"
    evidence: "stated"
    importance: "critical"
    match: "strong"
  - requirement: "Expert-level Python development"
    jd_signal: "Expert-level Python development"
    evidence: "stated"
    importance: "critical"
    match: "strong"
  - requirement: "Experience integrating Large Language Models (LLMs)"
    jd_signal: "Experience integrating Large Language Models (LLMs)"
    evidence: "stated"
    importance: "critical"
    match: "strong"
  - requirement: "Application security and vulnerability management"
    jd_signal: "Application security and vulnerability management"
    evidence: "stated"
    importance: "critical"
    match: "missing"
  - requirement: "Mid-level React development"
    jd_signal: "Mid-level React development"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "REST APIs and authentication integrations"
    jd_signal: "REST APIs and authentication integrations"
    evidence: "stated"
    importance: "high"
    match: "partial"
  - requirement: "API design and integration"
    jd_signal: "API design and integration"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "Automation and orchestration frameworks"
    jd_signal: "Automation and orchestration frameworks"
    evidence: "stated"
    importance: "high"
    match: "partial"
  - requirement: "Agent-based workflows and automation frameworks"
    jd_signal: "Agent-based workflows and automation frameworks"
    evidence: "stated"
    importance: "high"
    match: "partial"
  - requirement: "Modern SPA architecture"
    jd_signal: "Modern SPA architecture"
    evidence: "stated"
    importance: "meaningful"
    match: "strong"
  - requirement: "Test automation and quality engineering"
    jd_signal: "Test automation and quality engineering"
    evidence: "stated"
    importance: "meaningful"
    match: "strong"
risk_summary:
  legitimacy: "high_confidence"
  classification: "clear"
  culture: "caution"
  interview_redflags: "not_evaluated"
  ai_infra: "consistent"
  ai_screening_disclosure: "corroborating_only"
```

## A) Role Summary

| Field | Detail |
|---|---|
| Archetype | Senior Full-Stack Engineer (secondary) — React frontend + Python backend, with LLM integration as a product feature. Per `modes/_profile.md`, the "AI Security" framing is not scored as an archetype match; the role is evaluated on its full-stack engineering substance |
| Domain | Enterprise internal tooling — an AI-powered code security scanner used across Northern Trust's own enterprise codebases (wealth management / asset servicing / banking company) |
| Function | Build (React dashboards, Python backend/orchestration services, LLM integration, auth, vulnerability detection/verification automation) |
| Seniority | Senior Associate — 5+ years stated floor; candidate's 15 years comfortably clears it |
| Remote | Hybrid — Chicago, IL (50 S. La Salle, the Loop); JD also lists Naperville and North Chicago offices |
| Team size | Not stated |
| Culture screen | No `culture_screen.require` configured — qualitative: 135-year-old public company, "flexible and collaborative work culture... strong history of financial strength and stability," accessible senior leadership, philanthropy culture — positives — tempered by a confirmed January 2026 layoff of ~200 employees (Bengaluru, India office, not confirmed Chicago/engineering-specific) and Glassdoor-sourced employee reports describing "layoffs every 1-2 years" as a recurring pattern → **caution** |
| TL;DR | A Chicago Loop hybrid senior engineering role with strong Python/React/LLM-integration overlap, undercut by a real, critical-importance gap in the role's actual subject matter — application security and vulnerability management. |

### Geo-mismatch check
Structured location field: "Hybrid," "Chicago, IL, USA." JD lists three Illinois office locations (Chicago Loop, Naperville, North Chicago) with no remote-only framing and no contradicting language in the JD body. No contradiction — no flag. This is the candidate's explicitly preferred setup.

### Work-authorization check
JD states explicitly: *"Applicants must be authorized to work in the U.S. without the need for employment-based visa sponsorship now or in the future. Northern Trust will not sponsor applicants for U.S. work visa status for this opportunity (no sponsorship is available for H-1B, L-1, TN, O-1, E-3, H-1B1, F-1, J-1, OPT, CPT or any other employment-based visa)."* Candidate is authorized to work in the United States and does not need sponsorship. → **➖ Not needed.** No flag — this is informational for the candidate, not a blocker.

## B) Match with CV

| Requirement | Importance | Match | JD signal | Evidence / gap |
|---|---|---|---|---|
| 5+ years professional software engineering | critical (stated) | ✅ Strong | "5+ years of professional software engineering experience" | cv.md — 15 years across SteelSeries, Placester, Fulton Works, TD Ameritrade, GlobalNOC, Cerner. |
| Expert-level Python development | critical (stated) | ✅ Strong | "Expert-level Python development" | cv.md Languages: "Python"; Fulton Works (Django/Python across six client products), TD Ameritrade (Python/Fabric automation). |
| Experience integrating Large Language Models (LLMs) | critical (stated) | ✅ Strong | "Experience integrating Large Language Models (LLMs)" | cv.md Summary: "Recently active in local LLM tooling and MCP server design"; Skills: "Model Context Protocol," "Local LLM and MCP Server Design." |
| Application security and vulnerability management | critical (stated) | ❌ Missing | "Application security and vulnerability management" | No appsec, vulnerability-scanning, or security-tooling experience anywhere in cv.md. |
| Mid-level React development | high (stated) | ✅ Strong | "Mid-level React development" | cv.md Frameworks: "React, Redux" — deep, senior-level depth across SteelSeries, Placester, Fulton Works, well above the stated "mid-level" bar. |
| REST APIs and authentication integrations | high (stated) | ⚠️ Partial | "REST APIs and authentication integrations" | cv.md — Placester "Built GraphQL APIs tying together disparate legacy services"; no explicit REST-specific or authentication/authorization work named. |
| API design and integration | high (stated) | ✅ Strong | "API design and integration" | cv.md — Placester GraphQL API layer; SteelSeries shared NPM libraries designed for consumption by other teams. |
| Automation and orchestration frameworks | high (stated) | ⚠️ Partial | "Automation and orchestration frameworks" | cv.md — TD Ameritrade: "Automated build and deployment tasks, reducing deployment time from 8 hours... to 15 minutes" (CI/CD automation); no named workflow/orchestration framework (e.g. Airflow, Temporal, Celery). |
| Agent-based workflows and automation frameworks | high (stated) | ⚠️ Partial | "Agent-based workflows and automation frameworks" | cv.md's MCP/local-LLM work (Secondary skills) is agent-adjacent but not explicitly demonstrated in a production agent-workflow-automation context. |
| Modern SPA architecture | meaningful (stated) | ✅ Strong | "Modern SPA architecture" | cv.md — React/Redux SPA work across multiple roles; Electron application architecture at SteelSeries. |
| Test automation and quality engineering | meaningful (stated) | ✅ Strong | "Test automation and quality engineering" | cv.md Skills: "Jest," "Test Driven Development (TDD)"; Fulton Works stack explicitly lists TDD. |

**Gaps**

1. **Application security and vulnerability management (critical, ❌ Missing).** *Interview risk:* this is the actual subject matter the platform addresses — a technical screen would almost certainly probe SAST/DAST concepts, CVE/vulnerability triage, or OWASP-adjacent knowledge, and there is no honest way to claim depth here. *Mitigation:* be candid that general software-engineering rigor and quality-automation habits transfer, but security-domain-specific expertise does not exist yet; ask directly in the process how much of day-to-day work is security-domain judgment vs. general platform engineering (dashboards, orchestration, LLM integration) — the JD's own responsibilities lean heavily toward the latter.
2. **REST APIs and authentication integrations (high, ⚠️ Partial).** *Interview risk:* a systems-design question probing OAuth/JWT/session-auth specifics could expose thinner depth than the GraphQL work suggests. *Mitigation:* bridge honestly from GraphQL API-integration experience; note REST and auth patterns are a fast, adjacent ramp for someone with this API background.
3. **Automation and orchestration frameworks (high, ⚠️ Partial).** *Interview risk:* naming a specific orchestration framework (Airflow, Temporal, Celery, etc.) the candidate hasn't used could expose a gap. *Mitigation:* bridge from CI/CD build-automation work; be upfront that framework-specific orchestration experience is thinner.
4. **Agent-based workflows and automation frameworks (high, ⚠️ Partial).** *Interview risk:* deeper questions on production agent-orchestration patterns beyond MCP server design. *Mitigation:* lead with the honest, real MCP/local-LLM work as the closest evidence available.

## C) Level and Strategy

1. **Level detected vs. candidate's natural level:** The JD's 5+ year floor is comfortably cleared by 15 years, and the engineering scope (own frontend + backend + AI integration + automation for an internal platform) matches the candidate's natural senior IC level well. The gap is domain-specific (security), not seniority-specific.
2. **Sell senior without lying:** Lead with the Python/React/LLM-integration triad directly, and frame architecture-ownership experience (SteelSeries) against the JD's "architectural evolution, and long-term enhancement of the platform" language. Do not claim application-security expertise that isn't there — name it as an area to grow into, backed by genuine engineering rigor (TDD, quality automation) as the honest bridge.
3. **If downleveled:** Unlikely on seniority grounds; if comp landed toward the bottom of the range due to the security-domain gap, negotiate toward the top using the Python/React/LLM match, or accept with a clear ramp-up plan on the security-domain side.

## D) Comp and Demand

**Company type:** Public big tech / mature tech-adjacent — Northern Trust (Nasdaq: NTRS), a 135-year-old, 24,000+-partner global wealth management, asset servicing, and banking institution — **High** compensation reliability (explicit numeric range, comprehensive disclosed benefits, discretionary bonus program with possible equity component, formal HR process).

| Source | Range | Notes |
|---|---|---|
| Advertised (JD) | $88,900 - $151,100 USD | JD |

**Compensation reliability:** High — a specific, formally-disclosed range from a large public financial institution, with a clearly stated benefits package (401k + pension, medical/dental/vision, spending accounts, disability, PTO, parental/caregiver leave, life & accident insurance) and a disclosed discretionary bonus program.

The floor of the range sits below the candidate's $110K minimum; the ceiling clears the $131K target with meaningful margin. Given "Senior Associate" banking-style titling tends to run conservative relative to tech-company leveling for comparable seniority, and the role explicitly requires only a 5+ year floor (well below the candidate's 15 years), the realistic landing point is uncertain — likely mid-to-upper band, but not guaranteed to clear target.

**HR verification questions:**
- Where within the $88,900-$151,100 band would 15 years of experience typically land for this title?
- What percentage of day-to-day work is security-domain judgment (vulnerability triage, threat modeling) vs. general platform/full-stack engineering?
- Is the discretionary bonus program's equity component available at this level, and what's the typical target percentage?
- What does "architectural evolution... of the platform" mean concretely — greenfield expansion or largely maintenance of an existing system?

## E) Customization Plan

| # | Section | Current status | Proposed change | Why |
|---|---------|-----------------|------------------|-----|
| 1 | Summary | Generic architecture framing | Add explicit line on Python + React + LLM integration together | Directly mirrors the JD's three critical, stated requirements |
| 2 | Placester bullet | GraphQL-only framing | Add "API design and integration" framing explicitly, note auth/authz honestly as a growth area if asked | Matches "API design and integration" strongly without overclaiming REST/auth depth |
| 3 | TD Ameritrade bullet | Deployment automation as-is | Frame explicitly as "automation" evidence, without claiming orchestration-framework depth | Honest bridge toward "automation and orchestration frameworks" |
| 4 | Skills | MCP/Local LLM buried in Secondary | Surface "Model Context Protocol" and "Local LLM and MCP Server Design" higher, near Python/React | Directly answers the LLM-integration requirement, the strongest differentiator for this JD |
| 5 | Summary | No security framing | Do not add — no appsec evidence exists in cv.md; omit rather than overclaim | No-fabrication rule — this is a genuine gap, not one to paper over |

**LinkedIn:** Headline → "Senior Full-Stack Engineer — Python, React, LLM Integration." About section should lead with the Python/React/LLM triad, since that is the strongest, most honest overlap with this specific JD.

## F) Interview Plan

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|---|---|---|---|---|---|---|
| 1 | Expert-level Python | Fulton Works — Django/Python across six client products | Founders needed working backend services fast, repeatedly | Build reliable Python/Django backends under time pressure | Delivered Django/Python backends for six concurrent products | All six shipped and iterated with founders | Python depth compounds when you're forced to reuse patterns quickly across many small projects |
| 2 | Mid-level React / Modern SPA architecture | SteelSeries Electron app + component library | Needed a maintainable desktop SPA architecture and reusable UI layer | Own the frontend architecture end to end | Designed and implemented the Electron app and internal component library | Shipped and maintained as a major feature for years | SPA architecture decisions compound the same way backend architecture ones do — worth the same rigor |
| 3 | LLM integration | Local LLM tooling and MCP server design | Wanted hands-on production-adjacent depth with local model tooling | Build and design MCP servers for local LLM workflows | Designed and implemented MCP server tooling | Working, actively maintained local-LLM tooling | Agent-facing tooling design rewards the same "interface for the next consumer" instinct as any API |
| 4 | API design and integration | Placester unified GraphQL layer | Real-estate lead data was scattered across disparate legacy services | Build a unifying API layer | Built GraphQL APIs tying together the legacy services | Delivered a working, unified data interface | A unifying API layer pays for its upfront design cost when legacy systems disagree |
| 5 | Test automation and quality engineering | Fulton Works TDD practice | Rapid prototyping risked quality regressions across six products | Bake TDD into the delivery process | Practiced Test Driven Development across client engagements | Delivered working, tested products under time pressure | Testing discipline is what makes "move fast" sustainable, not contradictory to it |
| 6 | Automation (CI/CD) | TD Ameritrade deployment automation | Deployments consumed 8 hours of dedicated engineer time | Automate the build/deploy pipeline | Automated the pipeline end-to-end | Cut deployment time to 15 minutes of QA time | Automation done right eliminates the manual role, not just the manual steps |

**Recommended case study:** Local LLM tooling / MCP server design — the most directly-matching, differentiated proof point for this JD's core LLM-integration requirement.

**Red-flag questions and answers:**
- *"This is a security-focused role — what's your application-security background?"* → Honest answer: limited/none directly; pivot immediately to the engineering-rigor evidence (TDD, quality automation, architecture ownership) as the transferable foundation, and express genuine interest in growing into the security domain specifically because of the strong Python/React/LLM overlap elsewhere in the role.
- *"Why banking/financial services, coming from consumer tooling?"* → Be honest the domain is new; pivot to the platform-engineering substance (React dashboards, Python backend, LLM integration) that transfers regardless of industry.

## G) Posting Legitimacy

**Assessment: High Confidence**

| Signal | Finding | Weight |
|---|---|---|
| Posting Freshness | "Job Posted An Hour Ago," "Be an Early Applicant," active Apply button | Positive |
| Description Quality | Names specific real technologies (React, Python, LLMs, REST, orchestration frameworks); explicit, formally-disclosed comp and benefits; realistic, well-scoped requirements. Minor quality note: the Technical Skills list repeats four bullets verbatim ("Expert-level Python development," "API design and integration," "Automation and orchestration frameworks," "Test automation and quality engineering" each appear twice) — reads as a copy-paste formatting artifact in the posting itself, not a fabrication or ghost-job signal | Positive, with a minor neutral formatting note |
| Company Hiring Signals | Northern Trust confirmed as a large, stable, publicly traded institution; WebSearch found a confirmed ~200-employee layoff in January 2026, but at the Bengaluru, India office — not confirmed as Chicago-based or engineering-specific; multiple Glassdoor/Fishbowl sources describe a recurring "layoffs every 1-2 years" pattern at the company broadly | Neutral, with a stability caveat |
| Reposting Detection | First appearance in `scan-history.tsv` (added 2026-09-22) | Neutral |
| Role Market Context | A senior engineering req blending platform engineering with LLM integration is an increasingly common, legitimate role type at large financial institutions building internal AI tooling | Positive |

**Context Notes:** The recurring-layoffs pattern found in research is a general company-level signal, not specific to this posting, this department, or this location — worth factoring into how much stability to expect, but not itself a reason to doubt this specific posting is real and active.

**AI claims vs. infrastructure:** This posting does not oversell AI/transformation ambitions against thin infrastructure — Northern Trust is a large, mature institution building a concrete, scoped internal tool (a code security scanner with LLM-based analysis), with specific, credible technical requirements throughout. **✅ Consistent.**

**AI-screening disclosure note:** This posting doesn't mention AI/automated screening in its own hiring process. Illinois' Artificial Intelligence Video Interview Act (820 ILCS 42, effective 2020-01-01) requires employers to notify and obtain consent before using AI to analyze a recorded video interview — this obligation attaches to the interview step itself, not the job ad, so the posting's silence here doesn't indicate anything about whether disclosure happens before an interview. Informational only, not legal advice.

## Risk Summary

| Signal | Status |
|--------|--------|
| Posting legitimacy | ✅ High Confidence |
| Employment classification | ✅ clear |
| Culture screen | ⚠️ caution — large public company, stable overall, but a confirmed ~200-employee layoff (Bengaluru, Jan 2026) and reported recurring layoff pattern |
| Interview red flags | — no interview sessions yet |
| AI claims vs. infrastructure | ✅ consistent |
| AI-screening disclosure | ℹ️ Illinois requires disclosure before an AI video interview; posting is silent (not a compliance verdict — this obligation attaches to the interview step, not the ad) |

## Keywords extracted

AI-powered code security scanner, React dashboards, Python backend, LLM integration, agent-based workflows, orchestration frameworks, REST APIs, authentication, authorization, vulnerability detection, application security, test automation, enterprise codebases, hybrid, Chicago Loop, wealth management, asset servicing, banking

## Job Description (archived verbatim)

Posted: An Hour Ago

**About Northern Trust**
As a global leader in innovative wealth management, asset servicing, asset management and banking services, Northern Trust (Nasdaq: NTRS) is proud to guide the world's most successful individuals, families, corporations and institutions. Since 1889, we have aligned our efforts with our three guiding Principles That Endure: Service, Expertise, and Integrity. With more than 135 years of financial experience and over 24,000 partners, we serve the world's most sophisticated clients using leading technology and exceptional service.

We are seeking a Senior Associate Software Engineer to support technical development of our AI-powered Code Security Scanner platform. This platform leverages frontier AI models and advanced security automation to identify, validate, and report software vulnerabilities across enterprise codebases.

This role will be responsible for ongoing development, architectural evolution, and long-term enhancement of the platform. The successful candidate must be equally comfortable designing user-facing applications, building automation, integrating AI services, and securing cloud-native solutions.

**Platform Support**
- Serve as a developer for the AI Code Scanner platform
- Implement modernization, enhancements, and scalability initiatives

**Front-End Development**
- Improve user experience, reporting dashboards, workflow management, and administrative capabilities
- Implement secure authentication and authorization patterns

**Backend & AI Engineering**
- Maintain and extend orchestration and scanning services
- Expand and manage integrations with LLM-based security analysis capabilities
- Enhance automated vulnerability analysis, reporting, and verification workflows

**Experience**
- 5+ years of professional software engineering experience

**Technical Skills**
- Mid-level React development
- Modern SPA architecture
- REST APIs and authentication integrations
- Expert-level Python development
- API design and integration
- Automation and orchestration frameworks
- Test automation and quality engineering
- (duplicated in source) Expert-level Python development
- (duplicated in source) API design and integration
- (duplicated in source) Automation and orchestration frameworks
- (duplicated in source) Test automation and quality engineering
- Experience integrating Large Language Models (LLMs)
- Agent-based workflows and automation frameworks
- Application security and vulnerability management

**Salary Range:** $88,900 - $151,100 USD

Salary range is a good faith estimate of base pay. Northern Trust provides a comprehensive benefits package including retirement benefits (401k and pension), health and welfare benefits (medical, dental, vision, spending accounts and disability), paid time off, parental and caregiver leave, life & accident insurance, and other voluntary and well-being benefits. Northern Trust also provides a discretionary bonus program that may include an equity component.

**Work Authorization**
Applicants must be authorized to work in the U.S. without the need for employment-based visa sponsorship now or in the future. Northern Trust will not sponsor applicants for U.S. work visa status for this opportunity (no sponsorship is available for H-1B, L-1, TN, O-1, E-3, H-1B1, F-1, J-1, OPT, CPT or any other employment-based visa).

**Working with Us**
As a Northern Trust partner, you will be part of a flexible and collaborative work culture, which has a strong history of financial strength and stability. Movement within the organization is encouraged, senior leaders are accessible, and you can take pride in working for a company committed to an inclusive workplace and assisting the communities we serve. Philanthropy is deeply rooted in Northern Trust's history and is an essential element of our culture.

**Reasonable Accommodation**
Northern Trust is committed to working with and providing adjustments to individuals with health conditions and disabilities.

Location: 50 S. La Salle, Chicago, IL, 60603 (also lists Naperville, IL and North Chicago, IL offices)

---

## Cover Letter Draft

> Draft generated at evaluation time. Complete via `/career-ops cover northern-trust` to fill in angles, confirm research, and generate the PDF.
> Gaps flagged below — address them during the cover flow.

---

**Opening** *(placeholder — refine with your "why this role" angle)*
Northern Trust's Code Security Scanner platform needs someone equally comfortable across React dashboards, Python backend services, and LLM integration — that combination is close to how I've already been working, most recently hands-on with local LLM tooling and MCP server design.

**Profile introduction**
I'm a senior full-stack engineer with 15 years across startups and larger platforms (SteelSeries, TD Ameritrade, Cerner). My depth is in Python and React, with production API-integration experience (GraphQL) and, more recently, hands-on local LLM tooling and MCP server design.

**Key achievements** *(selected from cv.md — exact wording preserved)*
- **Designed and implemented major architectural features,** including a video editing suite, an Electron application and sandbox harness, and internal shared NPM libraries.
- **Built GraphQL APIs** tying together disparate legacy services to provide a unified data interface.
- **Quickly prototyped several web-based startups,** working closely with founders across six concurrent early-stage products (React, Django, Python).
- **Automated build and deployment tasks,** reducing deployment time from 8 hours to 15 minutes.

**Problems I will solve** *(placeholder — requires company research + your input)*
> To be completed: what stage is the Code Security Scanner platform at (early build vs. established), and what's the split between platform engineering and security-domain-specific work day to day?

**Closing**
I am happy to discuss further at your convenience.

---

**Gaps flagged:**
- Application security / vulnerability management is a genuine, undocumented gap — the core subject matter of this role. Do not overclaim; be candid and pivot to transferable engineering rigor.
- REST/auth-specific API depth and named orchestration-framework experience are both thinner than the GraphQL/CI-CD-automation evidence in cv.md.

**JD keywords to mirror** *(extracted for ATS + human read)*
Python, React, LLM integration, API design, orchestration, automation, application security, vulnerability management, SPA architecture, test automation

---
*Run `/career-ops cover northern-trust` to complete angles, confirm company research, and generate the PDF.*
