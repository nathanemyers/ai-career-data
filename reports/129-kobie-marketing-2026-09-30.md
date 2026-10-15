# Evaluation: Kobie Marketing — Software Engineer

**Date:** 2026-09-30
**URL:** https://www.builtinchicago.org/job/software-engineer/11420869
**Via:** — (direct)
**Archetype:** Senior Full-Stack Engineer (secondary fit — Java/Spring backend + Angular frontend; Angular is a soft downrank per `_profile.md`'s React-specific framework note)
**Score:** 3.1/5
**Legitimacy:** High Confidence
**Work Auth:** ➖ Not needed
**PDF:** output/cv-nathan-myers-kobie-marketing-2026-09-30.pdf

---

## Machine Summary

```yaml
report_num: 129
company: "Kobie Marketing"
role: "Software Engineer"
date: "2026-09-30"
url: "https://www.builtinchicago.org/job/software-engineer/11420869"
archetype: "Senior Full-Stack Engineer"
score: 3.1
legitimacy: "High Confidence"
work_auth: "not_needed"
advertised_comp: null
risk_summary:
  posting_legitimacy: "clear"
  employment_classification: "clear"
  culture_screen: "not_evaluated"
  interview_red_flags: "no_sessions"
  ai_infrastructure_mismatch: "not_evaluated"
requirement_importance:
  - requirement: "3+ yrs Java and Spring (Spring Boot)"
    evidence: "stated"
    importance: "critical"
    match: "partial"
  - requirement: "3+ yrs front-end web development; 1+ yr Angular"
    evidence: "stated"
    importance: "critical"
    match: "partial"
  - requirement: "1+ yr RESTful services (JSON)"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "Microservice cloud applications (Oracle/AWS/Azure)"
    evidence: "stated"
    importance: "high"
    match: "partial"
  - requirement: "SQL multi-table queries"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "Fully remote (travel as needed)"
    evidence: "structural"
    importance: "meaningful"
    match: "strong"
```

## A) Role Summary

| Field | Value |
|---|---|
| Archetype | Senior Full-Stack Engineer — Java/Spring backend + Angular frontend for a loyalty-platform product; Angular (not React) is the stated frontend framework, a soft downrank per `_profile.md` |
| Domain | Loyalty/marketing-tech SaaS (Kobie Marketing, "National Top Workplace") |
| Function | Build + maintain loyalty-platform integration points (APIs, batch, queue processing) |
| Seniority | "Mid level" tag, 3+ years required — below candidate's tenure |
| Remote | Fully remote, "remote-first" company (HQ St. Petersburg, FL), periodic travel for collaboration/training |
| Team size | Not stated |
| Culture screen | Not evaluated — no `culture_screen.require` in `config/profile.yml`; qualitatively, "everyone is a leader regardless of position," flexible time off, remote-first culture reads positively |
| TL;DR | A fully remote Java/Spring + Angular loyalty-platform role — solid backend/API/SQL overlap, but the frontend framework is Angular rather than React, and Java depth is dated relative to the candidate's recent stack. |

### Geo-mismatch check
No contradiction — "In-Office or Remote · Hiring Remotely in Chicago, IL, USA" matches JD body ("Kobie embraces a flexible work environment, offering teammates the freedom to work remotely... remote-first organization... periodic travel may be required").

### Work-authorization check
➖ **Not needed** — candidate authorized in the US; role is US-based; JD says nothing about sponsorship.

## B) Match with CV

| Requirement | Importance | Match | JD signal | Evidence / gap |
|---|---|---|---|---|
| 3+ yrs Java and Spring (Spring Boot) | critical (stated) | ⚠️ Partial | "3+ years of experience designing and developing applications and components using Java and Spring (Prefer JDK 11+ with Spring Boot)" | cv.md: "Java 6, Mule ESB, Spring MVC" (Cerner, 2011-2012) — real but 15 years old, and Spring MVC rather than Spring Boot |
| 3+ yrs front-end web development; 1+ yr Angular | critical (stated) | ⚠️ Partial | "3+ years of experience in front-end web application development... 1+ years of experience designing and developing applications using Angular (Prefer version 10+)" | cv.md: 15 years front-end (React-primary); Angular exposure is "Assisted in overhaul of legacy Backbone.js apps to Angular 6" (Placester) — real but secondary, and per `_profile.md`'s framework note this is a soft downrank since React is the deep expertise, not Angular |
| 1+ yr RESTful services (JSON) | high (stated) | ✅ Strong | "1+ years of experience developing RESTful services using JSON" | cv.md: GraphQL/REST API work (Placester), NodeJS Lambda services |
| Microservice cloud applications (Oracle/AWS/Azure) | high (stated) | ⚠️ Partial | "Experience developing microservice cloud applications (Oracle, AWS, or Azure)" | cv.md: AWS Lambda (Placester), Azure pipelines (SteelSeries) — real cloud experience, not framed as Oracle-cloud or classic microservices architecture |
| SQL multi-table queries | high (stated) | ✅ Strong | "1+ years of experience developing SQL multi-table queries, inserts, and updates" | cv.md Skills: SQL listed; NOC dashboard work used MySQL (GlobalNOC) |
| Fully remote | meaningful (structural) | ✅ Strong | JD body | `modes/_profile.md`: remote is fine, no disqualifier |

### Gaps

1. **Java/Spring currency (critical, Partial).** **Interview risk:** moderate — the Cerner experience is real but dated (2011-2012, Spring MVC not Spring Boot). **Mitigation:** be candid recent backend depth has shifted to NodeJS/Python/Go; emphasize transferable OOP/Spring fundamentals.
2. **Angular vs. React (critical, Partial).** **Mitigation:** per `_profile.md`, this is a soft downrank, not a disqualifier — frame the Backbone.js-to-Angular-6 migration at Placester honestly as real but secondary Angular exposure, with React as the deep specialty.

## C) Level and Strategy

1. **Level detected:** "Mid level" tag, 3+ years required — well below candidate's 15 years.
2. **"Sell senior without lying" plan:** Lead with REST/SQL/cloud backend experience and the Placester Angular migration; be candid about the Java/Spring currency gap and that React, not Angular, is the deep frontend specialty.
3. **"If they downlevel me" plan:** Not applicable — no advertised comp exists to negotiate against; would need a direct conversation on compensation regardless of level.

## D) Comp and Demand

**Company type:** Growth-stage / established SaaS vendor (Kobie Marketing — a national "Top Workplace," loyalty-technology partner to major brands) — **Medium** confidence per taxonomy default (no advertised figure to anchor reliability further).

- **Company type:** Growth-stage / established SaaS vendor — Medium confidence.
- **Compensation reliability:** Unknown — no advertised salary figure in this posting; skip component split and detailed market rows per the no-figure rule.

**Demand trend:** No repost/layoff signal found in this batch's bounded research.

## E) Customization Plan

| # | Section | Current status | Proposed change | Why |
|---|---------|---------------|------------------|---------|
| 1 | Experience (Cerner) | Java/Spring buried at bottom | Note explicitly, honestly flagged as dated | Directly answers the Java/Spring requirement |
| 2 | Experience (Placester) | Angular migration mentioned in passing | Expand slightly to name Angular 6 explicitly | Directly matches the Angular requirement |
| 3 | Skills | SQL listed without context | Add a line on multi-table query experience | Matches "SQL multi-table queries" |
| 4 | Summary | React-only framing | Note comfort across frontend frameworks (React-primary, Angular-exposed) | Honest framing for an Angular-primary JD |
| 5 | Summary | No remote framing | State comfort with fully remote, distributed work | Matches structural remote requirement |

**Top 5 LinkedIn changes:** headline adds "Full-Stack · Java/Spring · React/Angular," expand Cerner Java/Spring description, note Angular migration experience, add SQL as a named skill, note remote availability.

## F) Interview Plan

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|-----------------|-----------------|---|---|---|---|------------|
| 1 | Java/Spring backend | Cerner message processing/routing | Needed highly available SaaS for message routing | Build on Java/Spring MVC/Mule ESB | Developed highly available SaaS for message processing and routing | Delivered production-grade message routing | Would be candid this depth is 15 years old, though fundamentals transfer |
| 2 | Angular frontend | Placester Backbone-to-Angular migration | Legacy Backbone.js apps needed modernizing | Assist in the overhaul to Angular 6 | Assisted in overhaul of legacy Backbone.js apps to Angular 6 | Modernized the frontend stack | Would push for a more thorough migration plan/testing strategy now |
| 3 | REST/SQL APIs | Placester GraphQL/REST unification | Legacy services had no unified interface | Build a GraphQL/REST layer over them | Built GraphQL APIs tying together disparate legacy services | Unified interface for downstream consumers | Would add contract tests next time |
| 4 | Cloud/microservices | AWS Lambda + Azure pipelines | Needed scalable serverless routing and reliable CI/CD | Build on Lambda; configure Azure pipelines | Built NodeJS Lambda services; configured Azure build automation | Reliable, low-maintenance infra | Would benchmark against a more explicit microservices architecture now |

**Recommended case study:** the Placester Backbone-to-Angular-6 migration — most directly answers the Angular requirement with real, honest evidence.

**Red-flag questions:**
- *"How current is your Java/Spring experience?"* → Honest: dated (Cerner, 2011-2012); recent backend depth is NodeJS/Python/Go.
- *"Is React or Angular your strength?"* → Honest: React is the deep specialty; Angular exposure is real but secondary (one migration project).

## G) Posting Legitimacy

**Assessment: High Confidence**

| Signal | Finding | Weight |
|---|---|---|
| Posting Freshness | "Posted Yesterday," active Apply button | Positive |
| Description Quality | Specific stack (Java/Spring Boot, Angular 10+, RabbitMQ/ActiveMQ/Kafka, Docker/Kubernetes, Bitbucket/Gradle/Bamboo), named loyalty-platform domain, detailed remote-work/travel policy | Positive |
| Company Hiring Signals | No layoff/freeze signal found; Kobie is a named "Top Workplace in the USA and Top Remote Workplace" | Positive |
| Reposting Pattern | No repost match for this URL in `detect-reposts.mjs` | Neutral |
| Role Market Context | Mid-level full-stack roles at established SaaS vendors fill within normal timelines | Neutral |
| Employment Classification | No contractor-status language; standard FTE with stated benefits (Flexible Time Off, nine company-wide holidays) | Positive / clear |
| AI-buzzword vs. infrastructure mismatch | Not evaluated — no AI-transformation language in this JD at all | Not evaluated |
| Pay-transparency range width | No advertised range — signal does not apply | Not evaluated |

### Prior-contact FYI
No history: `company-history.mjs` shows `no-history` for Kobie Marketing.

## Risk Summary

| Signal | Status |
|--------|--------|
| Posting legitimacy | ✅ High Confidence |
| Employment classification | ✅ clear |
| Culture screen | — not evaluated |
| Interview red flags | — no interview sessions yet |
| AI claims vs. infrastructure | — not evaluated |

## Cover Letter Draft

> Draft generated at evaluation time. Complete via `/career-ops cover kobie-marketing` to fill in angles, confirm research, and generate the PDF.

---

**Opening**
Kobie's loyalty platform work — real-time integrations across APIs, batch, and queue processing — is exactly the kind of backend-plus-frontend systems work I enjoy.

**Profile introduction**
Senior full-stack engineer with 15 years across startups and larger platforms, with backend depth in Java/Spring and modern NodeJS/AWS services, and frontend experience spanning React and an Angular migration project.

**Key achievements**
- **Developed highly available SaaS for message processing and routing** (Java/Spring MVC/Mule ESB).
- **Assisted in overhaul of legacy Backbone.js apps to Angular 6.**
- **Built GraphQL APIs** tying together disparate legacy services into a unified data interface.
- **Built NodeJS backend services on AWS Lambda** to perform complex routing.

**Problems I will solve** *(placeholder — requires company research + your input)*
> To be completed: what does the current loyalty-platform integration architecture look like, and where's the biggest reliability or scale challenge?

**Closing**
I am happy to discuss further at your convenience.

---

**Gaps flagged:** Java/Spring depth is dated (Cerner, 2011-2012); Angular is a secondary framework relative to React. Be candid about both.

**JD keywords to mirror**
Java, Spring Boot, Angular, RESTful services, microservices, SQL, loyalty platform, Agile, mentoring

---

## Keywords extracted

Java, Spring, Spring Boot, Angular, RESTful services, JSON, microservices, SQL, Oracle, AWS, Azure, message queues, RabbitMQ, Kafka, Docker, Kubernetes, loyalty platform, Agile

## Job Description (archived verbatim)

Posted: Yesterday (as shown on posting page, 2026-09-30)

Software Engineer — Kobie Marketing

Join a National Top Workplace. Named a Top Workplace in the USA and Top Remote Workplace, Kobie is where the best minds in loyalty come together, driven by passion and innovation.

Join Us from Anywhere: While our headquarters are nestled in sunny St. Petersburg, Florida, Kobie embraces a flexible work environment, offering teammates the freedom to work remotely. Flexible Time Off; Nine Company-Wide Holidays; a diverse suite of benefits.

Travel Requirements: As a remote-first organization headquartered in St. Petersburg, Florida, Kobie values meaningful in-person connection and collaboration. While travel requirements vary by role, periodic travel may be required to support business objectives, team collaboration, customer engagements, training, and company events.

How you will make an impact:
- Participate in all phases of Agile methodology (planning, grooming, coding sprint items)
- Gain knowledge and control of our loyalty platform integration points (live APIs, Batch, Queue based processing).
- Participate in design sessions; work with product owners and team members to solve acceptance criteria
- Build and maintain all configuration and business logic rule documentation
- Assist other team members through coaching and mentoring
- Promote and demonstrate good coding practice and patterns for the team
- Set accurate time estimates and scope of work
- Develop simple solutions to complex problems
- Suggest innovative new ways to improve processes
- Effectively work with other groups and third parties

What you need to be successful:
- 3+ years of experience designing and developing applications and components using Java and Spring (Prefer JDK 11+ with Spring Boot)
- 3+ years of experience in front-end web application development
- 1+ years of experience designing and developing applications using Angular (Prefer version 10+)
- 1+ years of experience developing RESTful services using JSON
- Experience developing microservice cloud applications (Oracle, AWS, or Azure)
- 1+ years of experience developing SQL multi-table queries, inserts, and updates (Prefer Oracle / PostgreSQL)
- Experience tuning SQL statements with execution explain plans
- Familiarity with Agile (e.g., Scrum Process)
- Bachelor's Degree in Computer Science or related field is preferred
- Experience developing Loyalty, Accounting, or Banking applications
- Message Queues (RabbitMQ, ActiveMQ, Kafka Streams)
- Building Docker containers and configuring Kubernetes clusters (kubectl, Docker for Desktop)
- Build Management tools (Bitbucket/Git, Gradle, Bamboo)

Who we are: Kobie delivers market-leading, end-to-end loyalty solutions designed to enable customer experiences for the world's most successful brands, named a Top Workplaces in the USA.

A place for all: Kobie celebrates and embraces diversity, with employment based solely on merit and qualifications.
