# Evaluation: Grainger — Senior Software Engineer, Backend

> **🤝 LinkedIn connections at Grainger:** Navin Reddy — Senior Software Engineering Manager (https://www.linkedin.com/in/navreddy)

**Date:** 2026-09-29
**URL:** https://www.builtinchicago.org/job/senior-software-engineer-backend/11386695
**Via:** — (direct)
**Archetype:** Backend engineer, customer order platform (cart, pricing, freight, tax, payments). Nearest target: Senior Full-Stack Engineer (backend half), with EM-growth mentoring duties.
**Score:** 1.0/5
**Legitimacy:** High Confidence
**Work Auth:** ➖ Not needed
**Verification:** liveness confirmed via browser-extract.mjs (Built In page shows "Posted 3 Days Ago" with full JD and apply path)
**PDF:** not generated — run /career-ops pdf grainger to create on demand

---

> ⛔ **Deal-breaker (DoD / military client list):** this is the same company-level finding as report 104. Grainger's own public-sector page, "Military Procurement and Supplies" (grainger.com/content/mc/product-collections/industries/public-sector/federal-government/military), says its military onsite teams "provide the Air Force, Army, Navy, and Marine Corps with onsite support" under GSA contracts. GSA also announced a March 2021 contract with W.W. Grainger to supply industrial goods to Navy customers worldwide. `modes/_profile.md` treats a company whose client list names "a defense/military branch" as a hard exclude "even when defense/military work is a minor line of business for an otherwise non-defense company." Score set to **1.0**. The JD itself says nothing about DoD or the military. The trigger is Grainger's customer list, not this team's work.
>
> **On the role's own merits this posting scores about 3.6/5, well above report 104's ~2.8.** It is a general backend seat (HTTP APIs, distributed systems, 3+ years) with no language lock-in and explicit mentoring duties, and it lines up with the NodeJS/GraphQL/Lambda and Cerner Java work in cv.md. The gaps are payments/pricing/tax domain experience and recent backend depth. If you decide Grainger's military MRO supply business is acceptable, tell me and I will re-score. This would then be the best Grainger posting evaluated so far.

## Machine Summary

```yaml
company: "Grainger"
role: "Senior Software Engineer, Backend"
score: 1.0
legitimacy_tier: "High Confidence"
archetype: "Backend engineer, customer order platform (nearest target: Senior Full-Stack Engineer)"
final_decision: "Skip"
hard_stops:
  - "Profile deal-breaker: Grainger's client list names U.S. military branches (Air Force, Army, Navy, Marine Corps) via its military procurement / GSA onsite program"
soft_gaps:
  - "No cart/checkout, pricing, tax, freight, payment or invoicing domain experience in cv.md"
  - "Most recent backend work is Placester (2017-2018); SteelSeries role is frontend"
  - "Order-platform scale (100,000s of orders/day) not evidenced; nearest is Cerner HA message routing and GlobalNOC dashboards"
  - "Backend language not named in the JD; Grainger sibling postings lean Java, where cv.md shows Java only in 2011-2012"
top_strengths:
  - "HTTP API building: 'Built GraphQL APIs tying together disparate legacy services to provide a unified data interface.'"
  - "Distributed backend: 'Built NodeJS backend services on AWS Lambda to perform complex routing of real-estate leads' and 'Developed highly available SaaS for message processing and routing.'"
  - "Mentoring match: 'Mentored junior developers via constructive PR reviews and pair programming sessions.'"
  - "CI/CD: TD Ameritrade deploy automation and SteelSeries Azure build pipelines"
  - "Chicago hybrid at theMART (preferred setup); base $112.9K-$188.1K + up to 10% incentive"
risk_level: "High"
confidence: "High"
next_action: "Skip because of the DoD/military client-list deal-breaker. If you waive it for Grainger, this is the Grainger posting to pursue: generate a full-stack/backend-framed CV and ask Navin Reddy for a warm intro."
work_auth: "not_needed"
discard_reasons:
  - "dod_client_list_dealbreaker"
via: null
company_confidential: false
advertised_comp: "113K-188K Annually"
reports_to: null
requirement_importance:
  - requirement: "3+ years designing, building and deploying scalable software"
    jd_signal: "3+ years experience with modern software engineering; designing, building, and deploying scalable software applications required"
    evidence: "explicit"
    importance: "critical"
    match: "strong"
  - requirement: "Bachelor's degree or equivalent"
    jd_signal: "Bachelor's Degree or equivalent experience required"
    evidence: "explicit"
    importance: "critical"
    match: "strong"
  - requirement: "Understanding of distributed system design"
    jd_signal: "Understanding of distributed system design"
    evidence: "structural"
    importance: "high"
    match: "partial"
  - requirement: "Building HTTP APIs"
    jd_signal: "Familiarity with building HTTP API"
    evidence: "structural"
    importance: "high"
    match: "strong"
  - requirement: "Scalable backend for cart, pricing, freight, tax, payment, invoicing"
    jd_signal: "The cart customers interact with ... calculate the cost of an Order ... Freight, Pricing and Tax ... payment and invoicing capabilities"
    evidence: "structural"
    importance: "high"
    match: "missing"
  - requirement: "Coach and mentor junior engineers"
    jd_signal: "Coach and mentor junior engineers"
    evidence: "structural"
    importance: "high"
    match: "strong"
  - requirement: "Implement CI/CD and drive engineering best practices"
    jd_signal: "Implement continuous delivery activities (CICD) and drive engineering best practices"
    evidence: "structural"
    importance: "meaningful"
    match: "strong"
  - requirement: "Agile/Scrum and DevOps familiarity"
    jd_signal: "Familiarity with Agile/Scrum methodologies and DevOps practices"
    evidence: "structural"
    importance: "meaningful"
    match: "partial"
  - requirement: "Analyzing and interpreting complex problems"
    jd_signal: "Experience analyzing and interpreting complex problems and processes"
    evidence: "structural"
    importance: "meaningful"
    match: "strong"
  - requirement: "Pairing with peers on stories"
    jd_signal: "Support team activities and pair with peers to work on stories"
    evidence: "structural"
    importance: "meaningful"
    match: "strong"
risk_summary:
  legitimacy: "high_confidence"
  classification: "clear"
  culture: "caution"
  interview_redflags: "not_evaluated"
  ai_infra: "not_applicable"
  ai_screening_disclosure: "corroborating_only"
```

## A) Role Summary

| Field | Value |
|---|---|
| Archetype | Backend engineer on Grainger's Customer Order team. Nearest target is Senior Full-Stack Engineer (backend half). The JD says "Utilize (Frontend/Backend/Full Stack) specialized skills", and the mentoring duty touches the EM-growth track. |
| Domain | E-commerce order platform: cart, order cost calculation (freight, pricing, tax), payments and invoicing |
| Function | Build + support + mentor ("full systems life cycle") |
| Seniority | Senior ("Senior Software Engineer (Software Engineer III)") |
| Remote | Hybrid, Chicago (theMART office; HQ in Lake Forest) |
| Team size | Not stated; Grainger ~25,000 employees (Revelio Labs estimate from report 104, unverified) |
| Culture screen | caution. Positive: mentoring, pairing and CI/CD are named duties. Caution: a ~25K-employee enterprise, far above the 50-200 ideal (mild tiebreaker only). No `culture_screen` config in profile, so this is a qualitative read. |
| TL;DR | A solid senior backend seat on a high-volume order platform (100,000s of orders/day), Chicago hybrid, pay above target. On merits it is a reasonable fit. Grainger's military customer list trips the profile's DoD deal-breaker. |

**Work authorization:** ➖ Not needed. The JD says "This position is not eligible for any form of sponsorship now or in the future". The candidate is US-authorized with `needs_sponsorship: false`, so this has no effect.

## B) Match with CV

| Requirement | Importance | Match | JD signal | Evidence / gap |
|---|---|---|---|---|
| 3+ years scalable software | critical (explicit) | ✅ Strong | "3+ years experience with modern software engineering ... required" | 15 years (Jan 2011 to Jul 2026). |
| Bachelor's or equivalent | critical (explicit) | ✅ Strong | "Bachelor's Degree or equivalent experience required" | B.S. Earlham 2008, M.S. Indiana 2010. |
| Distributed system design | high (structural) | ⚠️ Partial | "Understanding of distributed system design" | Placester: "Built NodeJS backend services on AWS Lambda to perform complex routing of real-estate leads to real-estate agents." Cerner: "Developed highly available SaaS for message processing and routing." Real but not recent, and not at 100K-orders/day scale. |
| HTTP APIs | high (structural) | ✅ Strong | "Familiarity with building HTTP API" | Placester: "Built GraphQL APIs tying together disparate legacy services to provide a unified data interface." |
| Order domain (cart, pricing, tax, freight, payments, invoicing) | high (structural) | ❌ Missing | "calculate the cost of an Order ... Freight, Pricing and Tax ... payment and invoicing" | Nothing in cv.md on commerce, checkout or payments. |
| Mentoring | high (structural) | ✅ Strong | "Coach and mentor junior engineers" | SteelSeries: "Mentored junior developers via constructive PR reviews and pair programming sessions." |
| CI/CD, best practices | meaningful (structural) | ✅ Strong | "Implement continuous delivery activities (CICD)" | TD Ameritrade: "reducing deployment time from 8 hours of dedicated engineer time to 15 minutes of QA time." SteelSeries: "Configured Azure build automation pipelines." |
| Agile/DevOps | meaningful (structural) | ⚠️ Partial | "Familiarity with Agile/Scrum methodologies and DevOps practices" | CI/CD and Jenkins across several roles; Agile/Scrum not named in cv.md. |
| Complex problem analysis | meaningful (structural) | ✅ Strong | "Experience analyzing and interpreting complex problems and processes" | Strength "Architecture Focused"; "Designed and implemented several large architectural projects." |
| Pairing on stories | meaningful (structural) | ✅ Strong | "pair with peers to work on stories" | SteelSeries pair programming. |

Note: the JD does not name a backend language. Grainger's sibling postings (Staff Tech Lead, Backend on the same team; product-data roles) list Java and React, so expect Java to come up. cv.md shows Java only at Cerner (2011-2012: "Java 6, Mule ESB, Spring MVC").

### Gaps

1. **Order/payments domain (high, missing).** *Interview risk:* questions on idempotent payment calls, tax/pricing calculation consistency, and cart state across channels. *Mitigation:* map the Placester lead-routing and GraphQL aggregation work to "resolving many inputs into one computed answer". Say plainly that commerce is a new domain.
2. **Recency of backend work (partial).** The most recent backend work is Placester (2017-2018). *Mitigation:* use the Full-Stack framing from `_profile.md` and point to the SteelSeries Electron sandbox harness and shared NPM libraries as systems-design evidence.
3. **Possible Java stack.** *Mitigation:* ask the recruiter for the team's stack up front. Cite Cerner Spring honestly as dated.

## C) Level and Strategy

1. **Level:** Software Engineer III (Senior). This matches the candidate's seniority. With 15 years he may be at or above the level; the Staff Tech Lead, Backend posting on the same team (134K-224K) is a stretch alternative.
2. **Sell senior without lying:** architecture ownership (Electron app + sandbox harness, shared libraries), backend API aggregation at Placester, HA routing at Cerner, deploy automation, and mentoring.
3. **If they downlevel:** unlikely below III. The band floor ($112.9K) is above the $110K minimum.

## D) Comp and Demand

| Item | Value | Source |
|---|---|---|
| Advertised (JD) | "The anticipated base pay compensation range for this position is $112,900.00 - $188,100.00"; "incentive target of up to 10%" | JD (Built In) |
| Grainger Software Engineer, Chicago | avg ~$155.5K (general SE, all levels) | [Glassdoor](https://www.glassdoor.com/Salary/Grainger-Software-Engineer-Chicago-Salaries-EJI_IE711.0,8_KO9,26_IL.27,34_IM167.htm) |
| Grainger SE II, Greater Chicago | $120K-$145K+ | [Levels.fyi](https://www.levels.fyi/companies/grainger/salaries/software-engineer/levels/software-engineer-ii/locations/greater-chicago-area) |
| Chicago market, SE III | avg ~$170.5K, typical $147K-$201K | [Glassdoor](https://www.glassdoor.com/Salaries/chicago-software-engineer-iii-salary-SRCH_IL.0,7_IM167_KO8,29.htm) |

- **Company type:** Enterprise / traditional corporate (NYSE-listed MRO distributor, $17.9B 2025 revenue).
- **Advertised range:** $112.9K-$188.1K base.
- **Likely guaranteed base:** stated explicitly as base; placement depends on "geographic work location and relevant experience and skills".
- **Variable / conditional cash:** incentive "up to 10%", tied to individual and company performance, program "subject to change".
- **Expected stable cash:** base only.
- **Non-cash benefits:** day-one medical/dental/vision/life, 23 PTO days + 6 holidays, 6% 401(k) company contribution with no employee contribution required, tuition reimbursement, parental leave.
- **Compensation reliability:** High (explicit base; public data consistent).
- **vs. targets:** floor $2.9K above the $110K minimum, $18.1K below the $131K target; midpoint (~$150.5K) is above target. Negotiate toward the upper half.

**HR verification questions:**
- Where in $112.9K-$188.1K do Software Engineer III offers land in Chicago for 15 years of experience?
- What backend language and platform does the Customer Order team use?
- What has the incentive paid out, as a percent of target, in recent years?
- How many in-office days per week, and at theMART or Lake Forest?
- Is there on-call for the order platform, and how often?

**Demand:** generalist senior backend roles in Chicago are plentiful. Grainger has several open engineering roles right now (see Block G).

## E) Customization Plan

No PDF generated (score below the 3.0 auto-PDF threshold because of the deal-breaker). If the deal-breaker is waived:

| # | Section | Current status | Proposed change | Why |
|---|---------|---------------|------------------|---------|
| 1 | Summary | Frontend-first | Lead with "frontend/full-stack engineer with backend services in NodeJS, GraphQL, Python and Java" | Backend-titled role |
| 2 | Placester | Mid-list | Move GraphQL API and Lambda routing bullets up | "HTTP API", "distributed system design" |
| 3 | Cerner | Last entry | Keep "highly available SaaS for message processing and routing" visible | HA / distributed |
| 4 | TD Ameritrade / SteelSeries | Automation bullets | Keep deploy automation and Azure pipelines | "CICD" |
| 5 | SteelSeries | Mentoring is last bullet | Move mentoring up | "Coach and mentor junior engineers" |
| 6 | Skills | No payments/commerce terms | Do not add commerce/payments terms | Never fabricate |

**LinkedIn:** no role-specific changes.

## F) Interview Plan

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|-----------------|-----------------|---|---|---|---|------------|
| 1 | HTTP APIs | Placester GraphQL | Disparate legacy services | One data interface | Built GraphQL APIs over them | Unified data interface | Schema design decides how easily clients evolve |
| 2 | Distributed systems | Placester Lambda lead routing | Leads needed complex routing to agents | Build it serverless | NodeJS on AWS Lambda | Routing in production | Serverless trades ops load for cold-start and observability tradeoffs |
| 3 | High availability | Cerner message routing | HA message processing needed | Build routing SaaS | Java/Mule ESB/Spring | Highly available SaaS | Reliability is a design input |
| 4 | CI/CD | TD Ameritrade deploy automation | Deploys took 8 hours of engineer time | Automate | Python/Fabric/Jenkins | 15 minutes of QA time | Automation's value is who it frees up |
| 5 | Mentoring | SteelSeries mentoring | Juniors ramping up | Raise quality | PR reviews, pairing | (use concrete examples you remember) | Review tone matters |
| 6 | Complex design | Electron app + sandbox harness | New app architecture | Design and ship | Designed and implemented | Shipped | What you'd document differently |

**Red-flag questions:** "How would you make a payment call idempotent / keep cart totals consistent with tax and pricing services?" Answer from first principles and say plainly you have not worked in payments.

## G) Posting Legitimacy

**Assessment:** High Confidence

| Signal | Finding | Weight |
|---|---|---|
| Freshness | "Posted 3 Days Ago" (scanner posted date 2026-09-26); apply path present | Positive |
| Description quality | Specific team scope (cart, freight, pricing, tax, payments, invoicing), scale stated ("100,000s orders per day"), req number 334425, base range stated | Positive |
| Company hiring signals | From report 104: no 2026 tech layoff announcement found; headcount -0.7% YoY, postings -4.6% in 2026 (estimates) | Neutral |
| Reposting | Single scan-history entry (first seen 2026-09-28); the sibling "Staff Tech Lead, Backend" for the same order platform is a different level, not a repost | Neutral |
| Role market context | Order platform is core to Grainger's e-commerce; hiring a senior plus a staff lead for the same team is consistent | Positive |

**Context:** Built In's "The summary above was generated by AI" refers to the board's own summary, not the employer's screening. No imperative or AI-directed text in the JD. The JD's "Utilize (Frontend/Backend/Full Stack)" line reads like a shared Grainger template, a mild generic-JD signal outweighed by the team-specific detail.
**Employment classification:** ✅ clear (W-2-style benefits, 401(k), PTO; no contractor language).
**AI claims vs. infrastructure:** ➖ not applicable (no AI claims in the role).
⚠️ **Pay-transparency range-width signal:** the advertised base range is $75.2K wide ($112.9K-$188.1K) on a $112.9K floor, more than half the floor ($56.5K). Wide ranges often span several locations or experience levels. Ask the recruiter for the actual band for this level in Chicago. This is a general heuristic, not a jurisdiction-specific legal threshold, and not legal advice.
**Minimum-wage lawyer question:** skipped (advertised comp is a range).
⚠️ **AI-screening disclosure note:** the posting doesn't mention AI or automated screening. Illinois's Artificial Intelligence Video Interview Act (820 ILCS 42) requires notice and consent when AI analyzes recorded video interviews. That duty applies at the interview step, so the posting's silence tells you nothing either way. Informational only, not legal advice.
**Prior contact:** report 104 (Grainger, Software Engineer IV - Search Platform) evaluated today, also 1.0 on the same deal-breaker. No applications.

## Risk Summary

| Signal | Status |
|--------|--------|
| Posting legitimacy | ✅ High Confidence |
| Employment classification | ✅ clear |
| Culture screen | ⚠️ caution — ~25K-employee enterprise (outside 50-200 ideal); mentoring and pairing are positives |
| Interview red flags | — no interview sessions yet |
| AI claims vs. infrastructure | ➖ not applicable |
| AI-screening disclosure | ℹ️ Illinois requires disclosure; posting is silent |

### Score breakdown

| Dimension | Score | Note |
|---|---|---|
| CV match | 3.5 | APIs, distributed routing, CI/CD, mentoring, years all match; commerce domain missing; backend work not recent |
| Archetype fit | 3.5 | Backend half of Senior Full-Stack; mentoring feeds the EM-growth track |
| Comp | 4.0 | $112.9K-$188.1K base + up to 10%; floor under target, midpoint above |
| Company / culture | 3.0 | Stable enterprise, strong benefits, mentoring culture; far above ideal headcount |
| Location | 5.0 | Chicago hybrid at theMART, the preferred setup |
| Growth / mentorship | 3.5 | Explicit mentoring; no EM path stated; staff lead role on the same team |
| Red flags | — | DoD/military client-list deal-breaker (profile hard exclude) |
| **On-merits (pre deal-breaker)** | **~3.6** | Decent; apply only with a reason |
| **Global** | **1.0** | Deal-breaker applied |

---

## Keywords extracted

backend, customer order platform, cart, pricing, freight, tax, payments, invoicing, distributed systems, HTTP API, scalable software, CI/CD, continuous delivery, Agile, Scrum, DevOps, mentoring, pair programming, full systems life cycle

## Cover Letter Draft

> Draft generated at evaluation time. Complete via `/career-ops cover grainger` to fill in angles, confirm research, and generate the PDF.
> Not recommended: this role hits a profile deal-breaker (military client list) and scores 1.0.

---

**Opening** *(placeholder; refine with your "why this role" angle)*
Your Customer Order team resolves carts, pricing, freight, tax and payments for hundreds of thousands of orders a day. I build backend services that pull many inputs into one reliable answer, and I mentor the engineers around me.

**Profile introduction**
I am a senior frontend and full-stack engineer with 15 years across startups and larger platforms, most recently nearly eight years at SteelSeries. I have built backend services in NodeJS, GraphQL, Python and Java, and I document as I go so the next engineer can ramp up quickly.

**Key achievements** *(selected from cv.md; exact wording preserved)*
- **Built GraphQL APIs** tying together disparate legacy services to provide a unified data interface (Placester).
- **Built NodeJS backend services on AWS Lambda** to perform complex routing of real-estate leads to real-estate agents (Placester).
- **Developed highly available SaaS** for message processing and routing (Cerner).
- **Automated build and deployment tasks,** reducing deployment time from 8 hours of dedicated engineer time to 15 minutes of QA time (TD Ameritrade).
- **Mentored junior developers** via constructive PR reviews and pair programming sessions (SteelSeries).

**Problems I will solve** *(placeholder; requires company research + your input)*
> To be completed: what challenges does the order platform face that you'd address?

**Closing**
I am happy to discuss further at your convenience.

---

**Gaps flagged:**
- Profile deal-breaker: Grainger lists U.S. military branches as customers.
- No commerce, checkout, tax or payments experience in cv.md.
- Most recent backend work is 2017-2018.

**JD keywords to mirror**
"customer order platform", "distributed system design", "HTTP API", "scalable software", "continuous delivery (CICD)", "Coach and mentor junior engineers", "pair with peers"

---
*Run `/career-ops cover grainger` to complete angles, confirm company research, and generate the PDF.*

## Job Description (archived verbatim)

Posted: Posted 3 Days Ago (Built In Chicago, viewed 2026-09-29; scanner posted date 2026-09-26)

# Grainger — Senior Software Engineer, Backend

Hybrid · Chicago, IL, USA
113K-188K Annually
Senior level

Design, build, test, deploy, and support scalable software for Grainger's customer order platform, including cart, pricing, freight, tax, payment, and invoicing capabilities. Partner with engineers, architects, analysts, stakeholders, and product managers to deliver maintainable solutions. Implement CI/CD and engineering best practices, participate in Agile development, solve complex technical problems, and mentor junior engineers.

The summary above was generated by AIWork Location Type: Hybrid Req Number 334425 About Grainger W.W. Grainger, Inc. is a leading broad line distributor with operations primarily in North America and Japan. At Grainger, We Keep the World Working® by serving more than 4.6 million customers worldwide with maintenance, repair and operating (MRO) products and value-added solutions delivered through innovative technology and deep customer expertise. Known for its commitment to service and purpose-driven culture, the Company reported 2025 revenue of $17.9 billion. For more information, visit www.grainger.com. Compensation The anticipated base pay compensation range for this position is $112,900.00 - $188,100.00. This role is eligible for an incentive target of up to 10% or $, based on the achievement of individual and company performance objectives in accordance with the current terms of the incentive program which are subject to change. This position is not eligible for any form of sponsorship now or in the future. Individuals requiring sponsorship (e.g. OPT or H1B visa status) should not apply. Only individuals authorized to work in the United States now and for the foreseeable future will be considered for this position. Rewards and Benefits With benefits starting on day one, our programs provide choice and flexibility to meet team members' individual needs, including: Medical, dental, vision, and life insurance plans with coverage starting on day one of employment and 6 free sessions each year with a licensed therapist to support your emotional wellbeing. 23 paid time off (PTO) days annually for full-time employees (accrual prorated based on employment start date) and 6 company holidays per year. 6% company contribution to a 401(k) Retirement Savings Plan each pay period, no employee contribution required. Employee discounts, tuition reimbursement, student loan refinancing and free access to financial counseling, education, and tools. Maternity support programs, nursing benefits, and up to 14 weeks paid leave for birth parents and up to 4 weeks paid leave for non-birth parents. For additional information and details regarding Grainger's benefits, please click on the link below: https://experience100.ehr.com/grainger/Home/Tools-Resources/Key-Resources/New-Hire Grainger Benefits The pay range provided above is not a guarantee of compensation. The range reflects the potential base pay for this role at the time of this posting based on the job grade for this position. Individual base pay compensation will depend, in part, on factors such as geographic work location and relevant experience and skills. The anticipated compensation range described above is subject to change and the compensation ultimately paid may be higher or lower than the range described above. Grainger reserves the right to amend, modify, or terminate its compensation and benefit programs in its sole discretion at any time, consistent with applicable law. This position is not eligible for any form of sponsorship now or in the future. Individuals requiring sponsorship (e.g. OPT or H1B visa status) should not apply. Only individuals authorized to work in the United States now and for the foreseeable future will be considered for this position. Position Details As a Senior Software Engineer (Software Engineer III) you will be involved in the full systems life cycle and responsible for designing, coding, configuring, testing, implementing and supporting application software and systems that are delivered on time and within budget. In addition to mentoring junior engineers, you will work closely with technical teams, stakeholders and product managers to understand the business requirements that drive the analysis and physical design of technical solutions You will work as a Senior Engineer on a Customer Order team. The team is responsible for largely three things: The cart customers interact with on, eventually, all channels at Grainger. Currently this is limited to our main Grainger.com experience. Provide internal capabilities to calculate the cost of an Order to a customer. This means resolving interesting Freight, Pricing and Tax considerations for our customers. Lastly, we manage the payment and invoicing capabilities to ensure people can securely access their payment information. To give you a picture of our scale, we can see 100,000s orders per day and each one of those has at least one cart, one payment method, and one order calculation. We are a critical component of the customer's experience and require a team that build solutions that scale. You Will Build applications and develop product design solutions in partnership with engineers, architects, and analysts leading to scalable and maintainable software solutions Utilize (Frontend/Backend/Full Stack) specialized skills based on specific platform or domain as required Implement continuous delivery activities (CICD) and drive engineering best practices Support team activities and pair with peers to work on stories Coach and mentor junior engineers Consistently practice sensible defaults You Have Bachelor's Degree or equivalent experience required 3+ years experience with modern software engineering; designing, building, and deploying scalable software applications required Understanding of distributed system design Experience analyzing and interpreting complex problems and processes Familiarity with Agile/Scrum methodologies and DevOps practices Familiarity with building HTTP API We are committed to equal employment opportunity regardless of race, color, ancestry, religion, sex (including pregnancy), national origin, sexual orientation, age, citizenship, marital status, disability, gender identity or expression, protected veteran status or any other protected characteristic under federal, state, or local law. We are proud to be an equal opportunity workplace. We are committed to fostering an inclusive, accessible work environment that includes both providing reasonable accommodations to individuals with disabilities during the application and hiring process as well as throughout the course of one's employment, should you need a reasonable accommodation during the application and selection process, including, but not limited to use of our website, any part of the application, interview or hiring process, please advise us so that we can provide appropriate assistance.

Offices: HQ Grainger Lake Forest, Illinois, USA Office — 100 Grainger Parkway, Lake Forest, IL, United States, 60045. Grainger Chicago, Illinois, USA Office — In the heart of Chicago's River North neighborhood, Grainger's offices at theMART are walking distance from many transit stations and moments from the expressway.
