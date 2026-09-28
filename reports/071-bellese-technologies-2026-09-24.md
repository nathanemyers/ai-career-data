# Evaluation: Bellese Technologies — Senior Engineer, Full Stack

**Date:** 2026-09-24
**URL:** https://www.builtinchicago.org/job/senior-engineer-full-stack/11339272
**Via:** — (direct)
**Archetype:** Senior Full-Stack Engineer (Java/Spring Boot + TypeScript + Angular/React)
**Score:** 3.3/5
**Legitimacy:** High Confidence
**Work Auth:** ➖ Not needed
**Verification:** liveness uncertain in the bulk sweep (anti-bot); JD extracted via browser-extract.mjs (Playwright), and the page showed "Posted Yesterday" with an Apply path
**PDF:** output/cv-nathan-myers-bellese-2026-09-24.pdf

---

## Machine Summary

```yaml
company: "Bellese Technologies"
role: "Senior Engineer, Full Stack"
score: 3.3
legitimacy_tier: "High Confidence"
archetype: "Senior Full-Stack Engineer"
final_decision: "Consider"
hard_stops: []
soft_gaps:
  - "Java (Spring Boot) at advanced level: Java last used 2011-2012 (Cerner, Spring MVC)"
  - "Maven: Cerner only"
  - "Public Trust background investigation required (federal CMS contract)"
  - "Remote-only; no Chicago office"
top_strengths:
  - "TypeScript at advanced level (cv.md skills)"
  - "React (substitutable for Angular) at advanced level, plus real Angular exposure (Placester Angular 6, Strata AngularJS)"
  - "Test Driven Development (Fulton Works stack) matches the JD's TDD emphasis"
  - "APIs and data models integrating with frontends (Placester GraphQL)"
risk_level: "Medium"
confidence: "Medium"
next_action: "Consider applying. Be upfront that modern Spring Boot would need ramp-up, and lead with TS/React plus TDD."
work_auth: "not_needed"
discard_reasons:
  - "tech_stack_mismatch: advanced Java/Spring Boot backend"
  - "Remote-only (mild vs in-office preference)"
via: null
company_confidential: false
advertised_comp: "129K-153K Annually"
reports_to: null
requirement_importance:
  - requirement: "Java (Spring Boot), advanced"
    jd_signal: "Java (SpringBoot) (Advanced level)"
    evidence: "stated"
    importance: "critical"
    match: "partial"
  - requirement: "TypeScript, advanced"
    jd_signal: "Typescript (Advanced level)"
    evidence: "stated"
    importance: "critical"
    match: "strong"
  - requirement: "Angular (React may be substituted), advanced"
    jd_signal: "Angular (React may be substituted for Angular)(Advanced level)"
    evidence: "stated"
    importance: "critical"
    match: "strong"
  - requirement: "US Citizenship or Green Card; Public Trust eligibility"
    jd_signal: "US Citizenship or Green Card only - we do not offer Sponsorship"
    evidence: "stated"
    importance: "critical"
    match: "na"
  - requirement: "TDD for backend systems and UIs"
    jd_signal: "Leverage test-driven development to deliver backend systems and user interfaces"
    evidence: "structural"
    importance: "high"
    match: "strong"
  - requirement: "APIs, specifications, data models"
    jd_signal: "Contribute to the development of APIs, specifications, and data models"
    evidence: "structural"
    importance: "high"
    match: "strong"
  - requirement: "Scope/design/deliver medium-to-large features, reduce tech debt"
    jd_signal: "Reliably scope, estimate, design, and deliver medium-to-large features while reducing the technical debt"
    evidence: "structural"
    importance: "high"
    match: "strong"
  - requirement: "Data interactions: performance, integrity, security"
    jd_signal: "Design, implement, and maintain data interactions"
    evidence: "structural"
    importance: "high"
    match: "partial"
  - requirement: "Maven"
    jd_signal: "Tech used section"
    evidence: "structural"
    importance: "meaningful"
    match: "partial"
  - requirement: "PostgreSQL, AWS, Camunda, FHIR"
    jd_signal: "Nice to have section"
    evidence: "structural"
    importance: "preferred"
    match: "partial"
risk_summary:
  legitimacy: "high_confidence"
  classification: "clear"
  culture: "not_evaluated"
  interview_redflags: "not_evaluated"
  ai_infra: "not_evaluated"
  ai_screening_disclosure: "corroborating_only"
```

## A) Role Summary

| Field | Value |
|---|---|
| Archetype | Senior Full-Stack Engineer |
| Domain | Civic healthtech: CMS Unified Case Management (Medicare/Medicaid program integrity) |
| Function | Build Java/Spring Boot services, APIs, and Angular/React UIs with TDD; modernize to cloud |
| Seniority | Senior |
| Remote | Remote ("Remote First, Remote Only Culture"), hiring in the US |
| Team size | Not stated |
| Culture screen | No `culture_screen` in profile. Positives: mission-driven civic health work, four weeks PTO, flexible schedule, collaborative culture. Negative: remote-only, against his in-office preference. |
| TL;DR | A federal-contractor full-stack role where the TS and React parts fit well, but the Java/Spring Boot backend at "advanced level" is 14 years stale on his CV. Comp is on target. |

**Defense/DoD check (hard-exclude rule):** The client is CMS (HHS), a civilian health agency. A WebSearch of Bellese's contract history found CMS contracts (HQR, QMARS, MPSM pricing and coding) and no DoD contracts. The JD mentions no military, defense, or DoD work. The hard exclude does not apply.

**Geo-mismatch:** none. **Work authorization:** The candidate is US-authorized and needs no sponsorship → ➖ Not needed. The JD's status clause is covered in Block G.

## B) Match with CV

| Requirement | Importance | Match | JD signal | Evidence / gap |
|---|---|---|---|---|
| Java (Spring Boot), advanced | critical (stated) | ⚠️ Partial | "Java (SpringBoot) (Advanced level)" | Cerner: "Java 6, Mule ESB, Spring MVC, Maven, Jenkins" (2011-2012). Real, but dated and pre-Spring Boot. |
| Citizenship/Green Card; Public Trust | critical (stated) | ➖ N/A | "US Citizenship or Green Card only - we do not offer Sponsorship" | Candidate is US-authorized with no sponsorship needed. Public Trust eligibility was not assessed. |
| TypeScript, advanced | critical (stated) | ✅ Strong | "Typescript (Advanced level)" | cv.md Languages: TypeScript. |
| Angular or React, advanced | critical (stated) | ✅ Strong | "Angular (React may be substituted for Angular)(Advanced level)" | React/Redux at SteelSeries and Fulton Works; Angular 6 (Placester), AngularJS (Strata). |
| TDD for backend + UI | high (structural) | ✅ Strong | "Leverage test-driven development" | Fulton Works stack: "Test Driven Development"; Secondary skills: TDD. |
| APIs, specs, data models | high (structural) | ✅ Strong | "APIs, specifications, and data models" | Placester: "Built GraphQL APIs tying together disparate legacy services". |
| Scope/deliver features, reduce tech debt | high (structural) | ✅ Strong | "deliver medium-to-large features while reducing the technical debt" | SteelSeries "several large architectural projects"; Placester Backbone to Angular overhaul. |
| Data interactions (perf, integrity, security) | high (structural) | ⚠️ Partial | "Optimize data operations for performance and scalability" | SQL, MySQL (GlobalNOC). No deep DB-tuning evidence. |
| Maven | meaningful (structural) | ⚠️ Partial | Tech used | Cerner only. |
| Postgres/AWS/Camunda/FHIR | preferred (structural) | ⚠️ Partial | Nice to have | AWS Lambda only. |

### Gaps

1. **Java/Spring Boot advanced (critical, partial).** Interview risk: a Spring Boot coding or design round (dependency injection, JPA, REST controllers, testing). Mitigation: say plainly that his Java is from Cerner (Spring MVC, Maven) and he would need ramp-up on Spring Boot. Lean on TS/React depth and TDD, and consider a small Spring Boot practice project before interviewing. Never claim current Spring Boot fluency.
2. **Data-layer depth (high, partial).** Mitigation: the GlobalNOC MySQL work and the Placester API work show data modeling. Be honest about Postgres.

## C) Level and Strategy

1. **Level:** Senior, which matches.
2. **Sell senior without lying:** "15 years full-stack. I'm advanced in TypeScript and React, I practice TDD, and I've designed APIs and data models over legacy systems. My Java background (Spring, Maven at Cerner) gives me a foundation to ramp on Spring Boot quickly."
3. **If downleveled:** the band ($129K-$153K) is already near his target, so a downlevel would push below it. Negotiate for the top of the band instead.

## D) Comp and Demand

| Source | Range | Notes |
|---|---|---|
| Advertised (JD) | 129K-153K Annually | BuiltIn listing |

- **Advertised range:** $129K-$153K. **Likely guaranteed base:** stated as annual salary. **Variable:** none stated. **Expected stable cash:** $129K-$153K. **Non-cash:** 401(k) with 3% safe harbor, medical/dental/vision, four weeks PTO, 10 floating holidays.
- **Company type:** Government contractor / consulting vendor (a CMS digital-services firm founded in 2009, Baltimore metro). Medium confidence. **Reliability:** Medium (a clean base range; contractor pay tends to be stable but capped by contract rates).
- Comp meets his $131K target at the lower end and exceeds it at the top. Range width is $24K on a $129K floor, so the range-width signal does not fire.
- **HR verification questions:** Where in the band does a senior with limited recent Spring Boot land? Is the role tied to a specific contract period (UCM), and what happens at re-compete? Is the Public Trust investigation paid and pre-start?

Sources: [HigherGov contract 75FCMC21F0001](https://www.highergov.com/contract/75FCMC19A0007-75FCMC21F0001/), [OrangeSlices: QMARS task](https://orangeslices.ai/bellese-wins-48m-cms-quality-management-and-review-systems-qmars-support-task-on-acme-bpa/), [Nasdaq: CMS MPSM award](https://www.nasdaq.com/press-release/cms-awards-medicare-pricing-and-coding-services-contract-to-bellese-technologies-2021). Headcount was not found. The company appears mid-sized, which is an unconfirmed estimate.

## E) Customization Plan

| # | Section | Current status | Proposed change | Why |
|---|---|---|---|---|
| 1 | Summary | Frontend-first | "Full-stack: TypeScript and React UIs, APIs and data models, test-driven development; Java/Spring background" | JD's three advanced stacks |
| 2 | Competencies | — | TypeScript, React/Angular, TDD, API & Data Model Design, Legacy Modernization, Mentorship | JD language |
| 3 | Placester | Mid | Lead with the GraphQL APIs and the Angular 6 overhaul | Angular + API proof |
| 4 | Cerner | Low | Keep "Java 6, Mule ESB, Spring MVC, Maven" visible | Honest Java evidence |
| 5 | Fulton Works | Mid | Bold TDD | Their core practice |

LinkedIn: add "Test Driven Development" and "Angular" to skills (both backed by cv.md), and mention civic or healthcare interest only if it is genuine.

## F) Interview Plan

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|---|---|---|---|---|---|---|
| 1 | Modernization / tech debt | Placester Backbone to Angular 6 | Legacy Backbone apps | Help overhaul them | Assisted the Angular 6 migration | Modernized apps (cv.md) | Migrate incrementally behind stable interfaces |
| 2 | APIs & data models | Placester GraphQL | Disparate legacy services | Unify data access | GraphQL APIs | Unified interface (cv.md) | The schema is a contract; version it carefully |
| 3 | TDD | Fulton Works | Fast startup builds | Keep quality | TDD across ventures | Six shipped prototypes | Tests enable speed |
| 4 | Large features | SteelSeries architecture | Video editor, Electron app | Design and ship | Architecture + docs | Shipped (cv.md) | Scope in slices |
| 5 | Supporting teammates | SteelSeries mentorship | Juniors ramping | Raise the bar | PR review, pairing | Stronger team | Teach the why |
| 6 | Java backend | Cerner HA messaging | Message routing | HA SaaS | Java/Spring/Mule | HA in production | Foundation for Spring Boot |

**Red-flag questions:** "When did you last write Java?" Answer honestly (Cerner, 2011-2012), and describe his plan to ramp on Spring Boot. "Why remote civic work?" Mission and full-stack scope.

## G) Posting Legitimacy

**Assessment:** High Confidence

| Signal | Finding | Weight |
|---|---|---|
| Posting age | "Posted Yesterday" (scanner: 2026-09-23) | Positive |
| Apply path | Apply present on BuiltIn | Positive |
| Specificity | Specific system (CMS UCM), stack with proficiency levels | Positive |
| Salary | Stated | Positive |
| Hiring signals | Recent CMS contract wins ($47.8M QMARS task, HQR II) support real demand | Positive |

⚠️ **Immigration-status requirement signal:** This posting states "US Citizenship or Green Card only - we do not offer Sponsorship", which restricts eligibility to specific immigration statuses. Under 8 U.S.C. section 1324b (INA anti-discrimination provision; 28 C.F.R. Part 44), such restrictions are unlawful unless a listed exception applies: "a citizenship requirement is lawful when it is imposed by law, regulation, executive order, or a federal, state, or local government contract for the specific position." The posting names a plausible hook, a federal CMS contract that requires Public Trust eligibility and "US Residency for at least the past 3 years". Such requirements are lawful when the contract imposes them for the position, but the contract terms cannot be verified from the JD. Note: the "we do not offer Sponsorship" part is lawful on its own, and authorization or sponsorship questions are not what this flag is about. This does not affect the candidate, who is US-authorized. Informational only, not legal advice.

**Employment classification:** ✅ clear (full-time; benefits and 401(k) listed). **AI-screening disclosure (Illinois):** the posting is silent. The obligation attaches to the interview step. Informational only, not legal advice.

## Risk Summary

| Signal | Status |
|---|---|
| Posting legitimacy | ✅ High Confidence |
| Employment classification | ✅ clear |
| Culture screen | — not evaluated |
| Interview red flags | — no interview sessions yet |
| AI claims vs. infrastructure | — not evaluated |
| AI-screening disclosure | ℹ️ Illinois requires disclosure; posting is silent |

---

## Keywords extracted

Java, Spring Boot, TypeScript, Angular, React, Maven, JavaScript, test-driven development, APIs, specifications, data models, data integrity, security, UX, automated testing, PostgreSQL, AWS, Camunda, FHIR, CMS, case management, cloud migration, technical debt

## Job Description (archived verbatim)

Posted: Posted Yesterday (as shown on BuiltIn; scanner date 2026-09-23)

Bellese Technologies

 Jobs

 Senior Engineer, Full Stack

 Bellese Technologies

 Senior Engineer, Full Stack
 Job Posted Yesterday
 Posted Yesterday

 Remote
 Hiring Remotely in United States
 129K-153K Annually
 Senior level

 Remote
 Hiring Remotely in United States
 129K-153K Annually
 Senior level

 Develop and maintain full-stack features for CMS’s Unified Case Management system. Responsibilities include building Java and Spring Boot backend services, APIs, data models, Angular or React interfaces, database interactions, and automated tests using test-driven development. The engineer will optimize performance, scalability, security, and data integrity; collaborate on system design and integration; reduce technical debt; and support teammates in a remote-first environment.
 The summary above was generated by AIBellese is a mission-driven Digital Services Company committed to pioneering innovative technology solutions in civic healthcare. Our dedication lies in making a meaningful impact on public health outcomes. Driven by service design, we strive to know the “Why” to understand the healthcare journey for patients, caregivers, providers, payers, and policymakers. Our goal is to design and build solutions that reduce confusion, provide clarity, support decision making, and streamline the process so that we and our partners can focus on providing better health outcomes by improving patient care and reducing costs and burden.Team you will be joining:The Centers for Medicare & Medicaid Services (CMS) is enhancing program integrity efforts to combat fraud, waste, and abuse (FWA) within Medicare and Medicaid. The Unified Case Management (UCM) system serves as a centralized application for Program Integrity Contractors, facilitating case tracking, audits, investigations, and workload management. UCM supports coordinated efforts to prevent FWA and ensure compliance through efficient lead management, investigative actions, and reporting. As part of CMS’s modernization initiative, we are transforming UCM into a modern, scalable architecture that enhances performance, security, and usability. This effort includes migrating to cloud-based solutions, improving system interoperability, and adopting cutting-edge technologies to streamline workflows and improve data-driven decision-making. Our goal is to ensure a more robust, efficient, and future-ready platform for program integrity operations.As a Full Stack Engineer, you will: Influence: Make an impact on one or more projects or products.Technology: Highly proficient in one or more technologies within the Software Engineering discipline. Particularly skilled in one or more technologies.System: Reliably scope, estimate, design, and deliver medium-to-large features while reducing the technical debt of one or more projects or products.People: Proactively support other team members and help them to be successful.Process: Follow the team processes, delivering a consistent flow of features to production.These are the types of things you’ll be working on:Leverage test-driven development to deliver backend systems and user interfaces to ease development and integration between them.Contribute to the development of APIs, specifications, and data models, facilitating integration with frontend applications and third-party systems.Design, implement, and maintain data interactions. Optimize data operations for performance and scalability, and ensure data integrity and security.Design and develop user interfaces, informed by UX designs that meet customer needs.Understand and contribute to functional and non-functional automated testing suites.Tech used, but not limited to:Java (SpringBoot) (Advanced level)Typescript (Advanced level)Angular (React may be substituted for Angular)(Advanced level)MavenAngularJavascriptNice to have:Experience working on a large-scale system with over 100 usersPostgresSQLAWS knowledge & experienceCamundaAI/MLFHIRSecurity Clearance RequirementsUS Citizenship or Green Card only - we do not offer SponsorshipUS Residency for at least the past 3 yearsAble to meet the requirements to hold a position of Public Trust, including successful completion of a US Government background investigationDisclaimer: Medical or recreational marijuana use is considered illegal at the federal level, regardless of state laws allowing such, and may affect your ability to obtain Public Trust. See articleWork that matters, with perks that deliver. Discover how Bellese Technologies invests in you through a benefits suite that makes every day betterRemote First, Remote Only CultureFour weeks paid time off yearly (prorated based on start date for the first year)10 paid floating company holidaysFlexible scheduleWork from home setup including a Macbook Collaborative, learning environmentMedical, dental, and company-paid vision insuranceOptional HSA account with some medical plans and a company contributionCompany paid basic life and AD&D insurance coveragesCompany paid short and long term life insuranceOptional critical illness and accident insurance401K plan with 3% safe harbor contributionWellness resources and virtual carePerks Plus employee discountsYou will like it here if You foster a collaborative ethos, driven by the mission to deliver exceptional customer service to clients. You are passionate about Healthcare and changing the healthcare landscape. You’re an out of the box thinker, always striving to know the “why” when it comes to building solutions. You excel in a team-oriented, remote-first environment characterized by mutual respect and open communication. Your adaptability and ability to navigate challenges ensure your success in any situation.

## Cover Letter Draft

> Draft generated at evaluation time. Complete via `/career-ops cover bellese-technologies` to fill in angles, confirm research, and generate the PDF.
> Gaps flagged below. Address them during the cover flow.

---

**Opening** *(placeholder — refine with your "why this role" angle)*
Bellese is modernizing CMS's Unified Case Management system into a scalable, usable platform. That is legacy-to-modern full-stack work, and it is the kind I have done.

**Profile introduction**
I am a senior full-stack engineer with 15 years across startups and larger platforms. I work in TypeScript and React, with real Angular experience. I design APIs and data models over legacy systems and practice test-driven development. My backend background includes Java, Spring, and Maven at Cerner.

**Key achievements** *(selected from cv.md — exact wording preserved)*
- **Built GraphQL APIs** tying together disparate legacy services to provide a unified data interface.
- **Assisted in overhaul** of legacy Backbone.js apps to Angular 6.
- **Designed and maintained the internal UI component library.**
- **Developed highly available SaaS** for message processing and routing.

**Problems I will solve** *(placeholder — requires company research + your input)*
> To be completed: what challenges does the UCM modernization face that you'd address? How would you approach them?

**Closing**
I am happy to discuss further at your convenience.

---

**Gaps flagged:**
- Java/Spring Boot at advanced level: his Java is from 2011-2012 and would need ramp-up.
- Public Trust background investigation required.
- The role is remote-only.

**JD keywords to mirror** *(extracted for ATS + human read)*
test-driven development, APIs, specifications, and data models, TypeScript, Angular, React, Java Spring Boot, reducing technical debt, automated testing suites, modern scalable architecture

---
*Run `/career-ops cover bellese-technologies` to complete angles, confirm company research, and generate the PDF.*
