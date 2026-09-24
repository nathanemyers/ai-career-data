# Evaluation: Speechify — Software Engineer, Platform (Evanston, IL listing)

**Date:** 2026-09-22
**URL:** https://www.builtinchicago.org/job/software-engineer-platform-evanston-il-usa/9161876
**Via:** — (direct)
**Archetype:** Senior Full-Stack Engineer (secondary) — backend/platform-leaning
**Score:** 3.9/5
**Legitimacy:** High Confidence
**Work Auth:** ⚠️ Unstated
**PDF:** output/cv-nathan-myers-speechify-evanston-2026-09-22.pdf

---

## Note on the paired Chicago listing

This is one of two Built In listings for the identical "Software Engineer, Platform" role at Speechify — this one tagged "Evanston, IL, USA," the other (report 018) tagged "Chicago, IL, USA." Per the task scope, both are evaluated as distinct entries; see Block G for the location-tag anomaly this pairing reveals.

---

## Machine Summary

```yaml
company: "Speechify"
role: "Software Engineer, Platform"
score: 3.9
legitimacy_tier: "High Confidence"
archetype: "Senior Full-Stack Engineer (backend/platform-leaning)"
final_decision: "Consider"
hard_stops: []
soft_gaps:
  - "The posting is tagged 'In-Office or Remote' / 'Evanston, IL, USA,' but the JD body states Speechify is '100% distributed' with 'no office' anywhere -- there is no actual in-office option despite the city-specific tag, which changes this from the candidate's top-preference (hybrid/onsite) to a fully-remote role (still acceptable, scores slightly below)"
  - "GCP is the JD's named primary cloud ('Direct experience with GCP'); cv.md shows strong AWS (Lambda) experience but no GCP"
  - "Docker/containerized deployments and Kubernetes are both explicitly 'Preferred' and not documented in cv.md"
  - "The team is explicitly 'a flat organization... no separate ladder' -- growth here is scope-taking as a senior IC, not a people-management track, so it only partially maps to the candidate's stated growth-into-EM interest"
  - "Work authorization is entirely unstated in the JD -- neutral, not a blocker"
top_strengths:
  - "Proven TS/Node backend experience is a direct, required, and deeply-evidenced match (Placester: NodeJS/AWS Lambda/GraphQL)"
  - "AI-agent daily-workflow requirement is a direct, differentiated match: cv.md documents hands-on local LLM tooling and MCP server design"
  - "Company headcount (~160-200 per research) sits inside/near the candidate's ideal 50-200 range"
  - "Comp ($140K-$200K + Bonus + Stock) clears the $131K target with wide margin"
  - "Mission-driven accessibility product (50M+ users, Google Chrome Extension of the Year, Apple Design Award) with no confirmed layoff signal found"
risk_level: "Low"
confidence: "Medium"
next_action: "Consider applying -- strong backend/TS-Node match and comp, but confirm this is genuinely fully remote (no Evanston office exists) before assuming any onsite option, and be upfront about the GCP/Docker/Kubernetes gaps"
work_auth: "unstated"
discard_reasons: []
via: null
company_confidential: false
advertised_comp: "140,000-200,000 USD/Year + Bonus + Stock depending on experience"
reports_to: null
requirement_importance:
  - requirement: "Proven backend experience in TS/Node (required)"
    jd_signal: "Proven backend experience in TS/Node (required)"
    evidence: "stated"
    importance: "critical"
    match: "strong"
  - requirement: "Direct experience with GCP; working knowledge of AWS, Azure, or another cloud"
    jd_signal: "Direct experience with GCP; working knowledge of AWS, Azure, or another cloud"
    evidence: "stated"
    importance: "high"
    match: "partial"
  - requirement: "A daily working setup with AI agents you can describe in detail"
    jd_signal: "A daily working setup with AI agents you can describe in detail -- what runs unattended, what you review, and where you've decided it doesn't get to act alone"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "Own APIs behind payments, subscriptions, auth, consumption tracking, public TTS API"
    jd_signal: "Design, build, and own the APIs behind payments, subscriptions, auth, consumption tracking, and our public TTS API"
    evidence: "stated"
    importance: "critical"
    match: "partial"
  - requirement: "Instinct to check results against the system itself (logs, DB state, actual request)"
    jd_signal: "The instinct to check a result against the system itself -- logs, database state, the actual request -- rather than against a summary of it"
    evidence: "stated"
    importance: "meaningful"
    match: "strong"
  - requirement: "A habit of giving away work you used to own"
    jd_signal: "A habit of giving away work you used to own, and something to show for the room it created"
    evidence: "stated"
    importance: "meaningful"
    match: "strong"
  - requirement: "Design B2B and enterprise integrations"
    jd_signal: "Design B2B and enterprise integrations for customers building on top of us"
    evidence: "stated"
    importance: "meaningful"
    match: "strong"
  - requirement: "Docker and containerized deployments (preferred)"
    jd_signal: "Preferred: Docker and containerized deployments"
    evidence: "stated"
    importance: "preferred"
    match: "missing"
  - requirement: "Deploying high-availability applications on Kubernetes (preferred)"
    jd_signal: "Preferred: deploying high-availability applications on Kubernetes"
    evidence: "stated"
    importance: "preferred"
    match: "missing"
risk_summary:
  legitimacy: "high_confidence"
  classification: "clear"
  culture: "pass"
  interview_redflags: "not_evaluated"
  ai_infra: "consistent"
  ai_screening_disclosure: "no_match"
```

## A) Role Summary

| Field | Detail |
|---|---|
| Archetype | Senior Full-Stack Engineer (secondary), backend/platform-leaning — owns payments, subscriptions, auth, and a public API |
| Domain | Accessibility/ed-tech consumer product (text-to-speech), Platform team owns backend infrastructure serving 50M+ users |
| Function | Build + own end-to-end (APIs, billing correctness, B2B integrations) + reduce own future workload via automation and delegation |
| Seniority | JD tags "Mid level" but the actual scope described (owning payments/subscriptions/auth correctness at scale, B2B integrations, cross-team architecture influence) reads senior; candidate's 15 years comfortably covers either read |
| Remote | Tagged "In-Office or Remote" / "Hiring Remotely in Evanston, IL, USA," but the JD body states: "nearly 200 people around the globe work on Speechify in a 100% distributed setting -- Speechify has no office." This is a genuine contradiction — see Geo-mismatch check below |
| Team size | ~200 people company-wide; Platform team size not stated |
| Culture screen | No `culture_screen.require` configured — qualitative: mission-driven real product (50M+ users, Google/Apple recognition), explicit ownership-and-scope culture, "flat organization... no separate ladder," no confirmed layoff signal → **pass** |
| TL;DR | A fully-remote (despite the city-specific tag) senior backend/platform role at a real, well-funded accessibility-tech company, with a strong TS/Node/AI-agent-tooling match and comp well above target, tempered by a GCP/Docker/Kubernetes gap and a location tag that overstates the onsite option. |

### Geo-mismatch check
Structured location field: "In-Office or Remote," "Hiring Remotely in Evanston, IL, USA." JD body states: *"Today, nearly 200 people around the globe work on Speechify in a 100% distributed setting – Speechify has no office."* This is the reverse of the standard contradiction pattern (field implies an in-office option exists; the JD body says no office exists at all, anywhere, for anyone). This does not fit the standard flag wording (which covers "field says remote, JD requires onsite"), but it is a real, worth-surfacing mismatch in the opposite direction:

⚠️ **Location tag anomaly (non-standard direction):** location field/title says "In-Office or Remote" / "Evanston, IL, USA," but JD body says "Speechify has no office" — there is no actual in-office option anywhere, in any city. Treat this as a fully remote role, not hybrid/onsite, regardless of the city named in the listing title.

### Work-authorization check
JD is silent on sponsorship/work-authorization anywhere in the text. Role has no stated country restriction beyond "The United States Based Salary range..." implying a US-based hiring pool, but no sponsorship language either way. → **⚠️ Unstated.** This is neutral per policy, not a blocker. No flag (⚠️ Unstated does not require the flag line — only ⛔ No sponsorship does).

## B) Match with CV

| Requirement | Importance | Match | JD signal | Evidence / gap |
|---|---|---|---|---|
| Own APIs for payments, subscriptions, auth, consumption tracking, public TTS API | critical (stated) | ⚠️ Partial | "Design, build, and own the APIs behind payments, subscriptions, auth, consumption tracking, and our public TTS API" | cv.md — Placester GraphQL/Node API work is real and relevant, but no direct billing/subscription/payments-system experience is documented. |
| Proven backend experience in TS/Node | critical (stated) | ✅ Strong | "Proven backend experience in TS/Node (required)" | cv.md Languages/Platforms: "TypeScript," "NodeJS"; Placester: "Built NodeJS backend services on AWS Lambda," "NodeJS, GraphQL, Apollo Server, Serverless, AWS Lambda." |
| GCP direct / AWS-Azure working knowledge | high (stated) | ⚠️ Partial | "Direct experience with GCP; working knowledge of AWS, Azure, or another cloud" | cv.md shows strong, direct AWS Lambda experience (Placester) — satisfies the "working knowledge of AWS" fallback, but no GCP experience anywhere. |
| Daily AI-agent working setup | high (stated) | ✅ Strong | "A daily working setup with AI agents you can describe in detail" | cv.md Summary: "Recently active in local LLM tooling and MCP server design"; Skills: "Model Context Protocol," "Local LLM and MCP Server Design." |
| Check results against the system itself, not summaries | meaningful (stated) | ✅ Strong | "The instinct to check a result against the system itself" | cv.md — GlobalNOC: "Maintained an array of router diagnostic software," direct production-debugging instinct. |
| Give away work you used to own | meaningful (stated) | ✅ Strong | "A habit of giving away work you used to own" | cv.md — SteelSeries: proactive cross-team tool-building and mentorship, documentation-forward habits that hand off ownership. |
| Design B2B and enterprise integrations | meaningful (stated) | ✅ Strong | "Design B2B and enterprise integrations for customers building on top of us" | cv.md — Placester: "Built GraphQL APIs tying together disparate legacy services" for external-facing data consumption. |
| Docker / containerized deployments (preferred) | preferred (stated) | ❌ Missing | "Preferred: Docker and containerized deployments" | Not present anywhere in cv.md. |
| Kubernetes high-availability deployment (preferred) | preferred (stated) | ❌ Missing | "Preferred: deploying high-availability applications on Kubernetes" | Not present anywhere in cv.md. |

**Gaps**

1. **Own APIs for payments/subscriptions/billing correctness (critical, ⚠️ Partial).** *Interview risk:* the JD is explicit that "correctness compounds" here — a systems-design round would likely probe billing-state consistency across app stores, which is a genuinely specialized domain. *Mitigation:* bridge from the GraphQL/Node API-integration work honestly; be candid that payments/subscription-specific correctness patterns (idempotency, reconciliation across billing systems) are new territory, backed by strong general distributed-systems instincts.
2. **GCP direct experience (high, ⚠️ Partial).** *Interview risk:* GCP-specific tooling questions (Cloud Run, Pub/Sub, etc.) would expose the AWS-not-GCP gap. *Mitigation:* lead with AWS Lambda depth as the honest, adjacent answer; note cloud-platform concepts transfer readily.
3. **Docker/Kubernetes (preferred, ❌ Missing).** Lower risk since explicitly preferred, not required. *Mitigation:* be upfront; general infra/deployment-automation experience (TD Ameritrade CI/CD) is the honest bridge.

## C) Level and Strategy

1. **Level detected vs. candidate's natural level:** JD tags "Mid level," but the actual scope (owning payments/subscriptions correctness at 50M-user scale, B2B integrations, cross-team architecture influence, "people become leaders here by taking scope") reads senior. The candidate's 15 years and architecture-ownership track record likely exceed this role's baseline expectations.
2. **Sell senior without lying:** Lead with TS/Node backend depth and the AI-agent-tooling match directly; frame "designed and implemented major architectural features end to end" against the JD's "take on services you didn't write and make them faster, cheaper, and harder to break."
3. **If downleveled:** Unlikely to be an issue given the "Mid level" tag likely undersells the actual scope; if compensation landed toward the bottom of $140K-$200K, the range still clears target comfortably.

## D) Comp and Demand

**Company type:** Growth-stage, VC-backed startup — Speechify reached a $100M valuation (2024) with $17.6M ARR (2025) and approximately 160-200 employees (per WebSearch research) — **Medium** compensation reliability (funded startup with a clear, specific range, though startup bands can still move with negotiation/leveling).

| Source | Range | Notes |
|---|---|---|
| Advertised (JD) | $140,000-$200,000 USD/Year + Bonus + Stock depending on experience | JD |

**Compensation reliability:** Medium — a specific, credible range with bonus and equity disclosed separately (not folded into the base number), consistent with comparable senior roles on the same page (Webflow $187K-$278K, Trail of Bits $175K-$215K).

The advertised range clears the candidate's $131K target from the bottom of the band, a strong outcome.

**Company headcount note:** WebSearch estimates ~160-200 employees company-wide — sits inside or just above the candidate's ideal 50-200 range, a genuine positive per the company-size preference.

**HR verification questions:**
- Is there any in-office option anywhere, or is this role genuinely 100% remote regardless of the "Evanston, IL" tag?
- What does the equity grant/vesting look like at this funding stage?
- Which billing/subscription systems specifically (app-store APIs, payment processors) would this role own first?
- Is GCP a hard requirement for this specific team, or would strong AWS experience be an acceptable substitute in practice?

## E) Customization Plan

| # | Section | Current status | Proposed change | Why |
|---|---------|-----------------|------------------|-----|
| 1 | Summary | Generic architecture framing | Lead with TS/Node backend depth + AI-agent tooling line | Directly answers the JD's two most distinctive, named requirements |
| 2 | Placester bullet | GraphQL/Lambda framing | Add "API ownership" and "B2B integration" framing explicitly | Matches "own the APIs" and "B2B and enterprise integrations" language |
| 3 | Skills | AWS Lambda not framed as "cloud experience" | Add "AWS (Lambda, Serverless)" as an explicit cloud-platforms line | Honestly answers the "working knowledge of AWS" fallback without claiming GCP |
| 4 | Summary | No mention of local LLM/MCP work | Surface "hands-on local LLM tooling and MCP server design" prominently | Directly matches the JD's distinctive "daily working setup with AI agents" ask |

**LinkedIn:** Headline → "Senior Backend/Full-Stack Engineer — TypeScript, Node, API Ownership." About section should foreground the AWS/Node API work and the local-LLM/MCP tooling as differentiators.

## F) Interview Plan

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|---|---|---|---|---|---|---|
| 1 | TS/Node backend, API ownership | Placester GraphQL/Lambda API layer | Real-estate lead data was scattered across disparate legacy services | Build and own a unifying Node/GraphQL API layer | Built GraphQL APIs on AWS Lambda tying together the legacy services | Delivered a working, unified data interface | A unifying API layer is worth the upfront design cost when legacy systems disagree |
| 2 | Daily AI-agent workflow | Local LLM tooling and MCP server design | Wanted hands-on depth with local model tooling and agent-facing interfaces | Design and build MCP servers for local LLM workflows | Designed and implemented MCP server tooling, actively maintained | Working local-LLM tooling in daily use | Agent-facing tooling design rewards the same "interface for the next consumer" instinct as API design |
| 3 | Check results against the system, not summaries | GlobalNOC router diagnostics | Network outages needed real-time, ground-truth visibility | Build diagnostic tooling that surfaces raw system state | Built and maintained a NOC dashboard and router diagnostic software | Used in production by major university/state networks | Trusting raw system state over a summary is a habit worth deliberately building |
| 4 | Give away work you used to own | SteelSeries internal component library | Teammates needed to onboard onto a complex internal library quickly | Build and document the library for future ownership by others | Built and documented the internal UI component library | Reduced onboarding friction; the library became team-owned, not just mine | The real test of "giving away" work is whether it survives you leaving the room |
| 5 | B2B/enterprise integrations | Placester unified GraphQL layer for external consumption | Multiple internal and downstream consumers needed one consistent data interface | Design an integration layer usable by other teams/consumers | Built the GraphQL layer as the single integration point | Adopted as the standard interface | Designing for someone else's integration is a different discipline than designing for your own team |
| 6 | Automation reducing own future workload | TD Ameritrade deployment automation | Deployments consumed 8 hours of dedicated engineer time | Automate the pipeline so the role needed less manual effort | Automated the build/deploy pipeline end-to-end | Cut deployment time to 15 minutes, freeing the role for other work | "Make your own job smaller" is the same instinct as automating the manual steps — I'd already lived this once |

**Recommended case study:** Placester's GraphQL/AWS Lambda API layer — the most direct match to "own the APIs" and "B2B and enterprise integrations."

**Red-flag questions and answers:**
- *"This role is tagged Evanston/onsite-or-remote but you said Speechify has no office — is it really fully remote?"* → Ask directly and get written confirmation before assuming any onsite option exists.
- *"You don't have GCP or Kubernetes experience — how would you ramp?"* → Be honest; AWS/Lambda and general infra-automation experience are the honest bridge, and cloud/container concepts transfer quickly for someone with this background.

## G) Posting Legitimacy

**Assessment: High Confidence**

| Signal | Finding | Weight |
|---|---|---|
| Posting Freshness | "Job Posted 7 Hours Ago" / "Reposted 7 Hours Ago," "Be an Early Applicant," active Apply button | Positive |
| Description Quality | Unusually specific, well-written JD — names concrete technical concerns (billing-state consistency across five clients and two app-store systems, request-volume-aware metering), explicit interview process description (take-home + feedback loop), explicit comp with bonus/equity broken out separately. Very low boilerplate-to-specificity ratio | Positive |
| Company Hiring Signals | Speechify confirmed via WebSearch: $100M valuation (2024), $17.6M ARR (2025), ~160-200 employees, real 50M+-user product with Google/Apple industry recognition; no layoff signal found | Positive |
| Reposting Detection | This exact role/title also appears as a separate Chicago-tagged listing (evaluated separately as report 018) — same role posted under two different city tags for a company with no physical office anywhere, consistent with a fully-remote company casting a wide geographic net rather than a ghost-posting pattern | Neutral |
| Role Market Context | A senior backend/platform engineering req at a funded, actively-growing consumer product company is a common, legitimate, steadily-filling role type | Positive |

**Context Notes:** The Evanston/Chicago dual-city listing is explained plainly by the company having no physical office at all — this reads as normal remote-hiring practice (casting a wide net across a metro area) rather than a ghost-job or duplicate-posting concern, but it does mean the "Evanston" tag should not be read as implying any Evanston-specific office presence.

**AI claims vs. infrastructure:** This posting does not oversell AI/transformation ambitions against thin infrastructure — it's a concrete, scoped backend-ownership role at a real product company, with AI-agent-workflow fluency as one specific, well-defined expectation rather than a buzzword-heavy framing. **✅ Consistent.**

**AI-screening disclosure note:** This posting doesn't mention AI/automated screening in Speechify's own hiring process. No table row match was found for the candidate's jurisdiction against this specific check's conditions for this posting's context — informational only, no compliance verdict either way.

## Risk Summary

| Signal | Status |
|--------|--------|
| Posting legitimacy | ✅ High Confidence |
| Employment classification | ✅ clear |
| Culture screen | ✅ pass |
| Interview red flags | — no interview sessions yet |
| AI claims vs. infrastructure | ✅ consistent |
| AI-screening disclosure | — no jurisdiction match |

## Keywords extracted

TS/Node, backend, GCP, AWS, payments, subscriptions, authentication, consumption tracking, public TTS API, B2B integrations, AI agents, Docker, Kubernetes, high availability, text-to-speech, accessibility, distributed team, flat organization, automation

## Job Description (archived verbatim)

Posted: 7 Hours Ago (also displayed as "Reposted 7 Hours Ago")

The mission of Speechify is to make sure that reading is never a barrier to learning. Over 50 million people use Speechify's text-to-speech products to turn whatever they're reading – PDFs, books, Google Docs, news articles, websites – into audio, so they can read faster, read more, and remember more. Speechify's text-to-speech reading products include its iOS app, Android App, Mac App, Chrome Extension, and Web App. Google recently named Speechify the Chrome Extension of the Year and Apple named Speechify its 2025 Design Award winner for Inclusivity.

Today, nearly 200 people around the globe work on Speechify in a 100% distributed setting – Speechify has no office.

**Overview**
The Platform team owns the backend behind everything Speechify ships: the public TTS API, payments, subscriptions, auth, consumption tracking, and analytics — serving over 50 million users across iOS, Android, Mac, Chrome, and web.

These are systems where correctness compounds. Subscription state has to stay consistent across five clients and two app-store billing systems that each go quiet at the worst moment. Consumption metering has to be exact enough to bill on and cheap enough to run at our request volume. The public TTS API has external customers with their own products depending on our latency and uptime. None of this degrades gracefully — it is either right, or someone gets charged twice.

The job is to make your own job smaller. Every system you own here should need less of you a year from now than it did the day you took it, and the reward for that is a larger one. That is the entire growth path on this team — there is no separate ladder, and no ceiling except the one you stop raising. We are a flat organization: people become leaders here by taking scope and being right about it, fast.

**What You'll Do**
- Design, build, and own the APIs behind payments, subscriptions, auth, consumption tracking, and our public TTS API
- Take on services you didn't write and make them faster, cheaper, and harder to break
- Establish that a change is correct before it ships, and leave behind the checks that keep it correct after you've moved on
- Automate the parts of your role that shouldn't need a person, then go take on what that freed you up for
- Turn work you've done once into work the whole team can repeat
- Design B2B and enterprise integrations for customers building on top of us
- Work with product, mobile, and web to keep backend architecture ahead of where the product is going

**An Ideal Candidate Should Have**
- Proven backend experience in TS/Node (required)
- Direct experience with GCP; working knowledge of AWS, Azure, or another cloud
- A habit of giving away work you used to own, and something to show for the room it created
- A daily working setup with AI agents you can describe in detail — what runs unattended, what you review, and where you've decided it doesn't get to act alone
- The instinct to check a result against the system itself — logs, database state, the actual request — rather than against a summary of it
- Judgment about what not to build, and the ability to say plainly why you dropped it
- A preference for being corrected over being right
- Preferred: Docker and containerized deployments
- Preferred: deploying high-availability applications on Kubernetes

**Interview process:** Several technical interviews plus a take-home assessment on a real codebase. We aim to finish within a week. The assessment runs in two stages: you'll submit, get real feedback from an engineer on this team, and have time to act on it. Use the tools you use every day. You'll be asked to walk through your reasoning, so bring it.

**What We Offer:** A dynamic environment where your contributions shape the company and its products; a team that values innovation, intuition, and drive; autonomy; the opportunity to have significant impact in a revolutionary industry; competitive compensation; a welcoming atmosphere and asynchronous work culture; working on a product that changes lives, particularly for those with learning differences like dyslexia, ADD, and more; an active role at the intersection of artificial intelligence and audio.

**Salary:** The United States Based Salary range for this role is: 140,000-200,000 USD/Year + Bonus + Stock depending on experience

Speechify is committed to a diverse and inclusive workplace.

---

## Cover Letter Draft

> Draft generated at evaluation time. Complete via `/career-ops cover speechify-evanston` to fill in angles, confirm research, and generate the PDF.
> Gaps flagged below — address them during the cover flow.

---

**Opening** *(placeholder — refine with your "why this role" angle)*
Speechify's Platform team is asking for someone who treats API ownership and correctness as non-negotiable and works daily with AI-agent tooling — both describe how I've already been working, most recently hands-on with local LLM tooling and MCP server design.

**Profile introduction**
I'm a senior full-stack engineer with 15 years across startups and larger platforms (SteelSeries, Placester, TD Ameritrade, Cerner). My backend depth is TypeScript/Node on AWS, with a real track record of owning API layers end to end and, more recently, building hands-on with local LLM tooling and MCP server design.

**Key achievements** *(selected from cv.md — exact wording preserved)*
- **Built NodeJS backend services on AWS Lambda** to perform complex routing of real-estate leads to real-estate agents.
- **Built GraphQL APIs** tying together disparate legacy services to provide a unified data interface.
- **Designed and implemented major architectural features,** including a video editing suite, an Electron application and sandbox harness, and internal shared NPM libraries.
- **Automated build and deployment tasks,** reducing deployment time from 8 hours to 15 minutes.

**Problems I will solve** *(placeholder — requires company research + your input)*
> To be completed: which part of the Platform surface (payments, subscriptions, the public TTS API) is the most immediate priority right now?

**Closing**
I am happy to discuss further at your convenience.

---

**Gaps flagged:**
- GCP is the JD's named primary cloud; cv.md shows AWS depth, not GCP.
- Docker/Kubernetes are both preferred and undocumented in cv.md.
- Confirm the role is genuinely fully remote before assuming any in-office option — the JD body explicitly says Speechify has no office anywhere.

**JD keywords to mirror** *(extracted for ATS + human read)*
TS/Node, backend, API ownership, payments, subscriptions, consumption tracking, GCP, AWS, AI agents, B2B integrations, automation

---
*Run `/career-ops cover speechify-evanston` to complete angles, confirm company research, and generate the PDF.*
