# Evaluation: Aquatic Capital Management — Software Engineer, Production Platform

**Date:** 2026-09-24
**URL:** https://www.builtinchicago.org/job/software-engineer-production-platform/11320698
**Via:** — (direct)
**Archetype:** Automation Engineer (build/release tooling, deployment orchestration, toil elimination)
**Score:** 4.1/5
**Legitimacy:** High Confidence
**Work Auth:** ➖ Not needed
**Verification:** liveness confirmed (check-liveness.mjs); JD extracted via browser-extract.mjs (Playwright)
**PDF:** output/cv-nathan-myers-aquatic-2026-09-24.pdf

---

## Machine Summary

```yaml
company: "Aquatic Capital Management"
role: "Software Engineer, Production Platform"
score: 4.1
legitimacy_tier: "High Confidence"
archetype: "Automation Engineer"
final_decision: "Apply"
hard_stops: []
soft_gaps:
  - "Strong Python: real but secondary in cv.md (TD Ameritrade Fabric, Fulton Works Django)"
  - "Workload orchestration (Nomad/Kubernetes) and configuration management: not in cv.md"
  - "C++ familiarity: not in cv.md"
  - "Trading-systems domain (helpful, not required)"
top_strengths:
  - "Build/release and deployment automation: TD Ameritrade deploys cut from 8 hours to 15 minutes"
  - "Toil elimination by learning other teams' workflows (SteelSeries cross-team tools)"
  - "Documentation-forward: 'built to be supported by people who did not write it' is his stated strength"
  - "In-office Chicago and a 91-147-person firm, both his preferred setup"
risk_level: "Low"
confidence: "Medium"
next_action: "Apply with the automation-tailored CV, and brush up on Python and Nomad/Kubernetes basics before the technical screen."
work_auth: "not_needed"
discard_reasons: []
via: null
company_confidential: false
advertised_comp: "$150,000 and $300,000 (base salary); discretionary bonus"
reports_to: null
requirement_importance:
  - requirement: "Strong Python; production-grade systems"
    jd_signal: "Strong python and familiarity with Java and C++ and a track record of building production-grade systems."
    evidence: "structural"
    importance: "critical"
    match: "partial"
  - requirement: "Distributed systems, deployment pipelines, or internal developer platforms"
    jd_signal: "Experience building and operating distributed systems, deployment pipelines, or internal developer platforms."
    evidence: "structural"
    importance: "critical"
    match: "strong"
  - requirement: "4+ years professional development"
    jd_signal: "4+ years of professional software development experience."
    evidence: "structural"
    importance: "critical"
    match: "strong"
  - requirement: "Own build and release tooling, promotion, rollback"
    jd_signal: "Own build and release tooling, including build pinning and approval, promotion workflows, and rollback paths"
    evidence: "structural"
    importance: "high"
    match: "strong"
  - requirement: "Replace manual operational processes with automation"
    jd_signal: "replace manual operational processes with automation, eliminating toil at the source"
    evidence: "structural"
    importance: "high"
    match: "strong"
  - requirement: "CI/CD, config management, workload orchestration (Nomad/K8s)"
    jd_signal: "Familiarity with CI/CD, configuration generation and management, workload orchestration (Nomad, Kubernetes, or similar)"
    evidence: "structural"
    importance: "high"
    match: "partial"
  - requirement: "Production environments where uptime/latency/correctness matter"
    jd_signal: "Comfortable operating in production environments where uptime, latency, and correctness are of highest importance."
    evidence: "structural"
    importance: "high"
    match: "partial"
  - requirement: "Observability into deployments and services"
    jd_signal: "Build observability into deployments and production services"
    evidence: "structural"
    importance: "high"
    match: "partial"
  - requirement: "Clean, tested, documented Python supportable by others"
    jd_signal: "Clean, maintainable Python, tested and documented, built to be supported by people who did not write it."
    evidence: "structural"
    importance: "meaningful"
    match: "strong"
  - requirement: "Familiarity with Java and C++"
    jd_signal: "familiarity with Java and C++"
    evidence: "structural"
    importance: "meaningful"
    match: "partial"
  - requirement: "Trading systems / market data exposure"
    jd_signal: "Helpful but not required: exposure to trading systems, market data, or model lifecycle management in production."
    evidence: "structural"
    importance: "preferred"
    match: "partial"
risk_summary:
  legitimacy: "high_confidence"
  classification: "clear"
  culture: "pass"
  interview_redflags: "not_evaluated"
  ai_infra: "not_evaluated"
  ai_screening_disclosure: "corroborating_only"
```

## A) Role Summary

| Field | Value |
|---|---|
| Archetype | Automation Engineer |
| Domain | Quantitative investment management: the production platform that moves code, models, and data into live trading |
| Function | Build/release tooling, deployment orchestration, observability, reliability, toil automation |
| Seniority | Listed "Mid level", with 4+ years and "open to a range of experience levels" |
| Remote | In-office, Chicago, IL (HQ 60640) |
| Team size | Engineering team size not stated. The firm has about 91-147 employees (web estimates, see D). |
| Culture screen | No `culture_screen` in profile, so scored qualitatively as **pass**. It meets his in-office Chicago preference, sits in the 50-200 ideal size band, and is an early-stage firm with "collaboration, meritocracy" culture. The explicit "documented, built to be supported by people who did not write it" line matches his narrative. |
| TL;DR | This is close to the Automation Engineer archetype on paper: own the deploy/build/release platform and remove toil, in-office in Chicago at a firm in the ideal size range, paying $150K-$300K base. The gaps are Python depth and orchestration tooling. |

**Geo-mismatch:** none (in-office Chicago; the candidate is local). **Work authorization:** ➖ Not needed.

## B) Match with CV

| Requirement | Importance | Match | JD signal | Evidence / gap |
|---|---|---|---|---|
| Strong Python; production-grade systems | critical (structural) | ⚠️ Partial | "Strong python and familiarity with Java and C++" | TD Ameritrade: "Stack: Python, Fabric, Jenkins"; Fulton Works: "Django, Python". Real production Python, but not his most recent or primary language. |
| Distributed systems / deployment pipelines / internal dev platforms | critical (structural) | ✅ Strong | "deployment pipelines, or internal developer platforms" | "Automated build and deployment tasks, reducing deployment time from 8 hours of dedicated engineer time to 15 minutes of QA time"; "Configured Azure build automation pipelines"; "internal shared NPM libraries". |
| 4+ years | critical (structural) | ✅ Strong | "4+ years of professional software development experience." | 15 years. |
| Build/release tooling, promotion, rollback | high (structural) | ✅ Strong | "Own build and release tooling..." | TD Ameritrade deploy automation; Azure build pipelines. |
| Replace manual ops with automation | high (structural) | ✅ Strong | "replace manual operational processes with automation, eliminating toil at the source" | TD Ameritrade (8h to 15 min); "Proactively built tools for other departments after learning about their jobs and pain points." |
| CI/CD, config mgmt, Nomad/K8s | high (structural) | ⚠️ Partial | "workload orchestration (Nomad, Kubernetes, or similar)" | CI/CD yes (Jenkins, Azure). No Nomad or Kubernetes. |
| Uptime/latency/correctness in production | high (structural) | ⚠️ Partial | "uptime, latency, and correctness are of highest importance" | Cerner: "highly available SaaS for message processing and routing"; GlobalNOC live outage dashboard. |
| Observability into deployments | high (structural) | ⚠️ Partial | "Build observability into deployments and production services" | GlobalNOC: "NOC dashboard reporting live outages and network errors". No modern observability stack named. |
| Tested, documented, supportable Python | meaningful (structural) | ✅ Strong | "built to be supported by people who did not write it" | cv.md Strength: "designed with an eye toward how it will be encountered by someone coming to it fresh"; TDD. |
| Java and C++ familiarity | meaningful (structural) | ⚠️ Partial | "familiarity with Java and C++" | Java: Cerner (Java 6, Spring MVC). No C++. |
| Trading/market-data exposure | preferred (structural) | ⚠️ Partial | "Helpful but not required" | TD Ameritrade (brokerage), but the work was deploy automation. |

### Gaps

1. **Python depth (critical, partial).** Interview risk: a live Python coding round aimed at a Python-first platform engineer. Mitigation: refresh idiomatic Python (packaging, typing, pytest, subprocess and concurrency) before the screen, and lead with the fact that his TD Ameritrade automation was written in Python. The cover-letter line: "My deploy automation at TD Ameritrade was Python, and it took an 8-hour process to 15 minutes."
2. **Nomad/Kubernetes and config management (high, partial).** Interview risk: questions on scheduling across regions and regional parity. Mitigation: be honest that orchestration would be new. Study Nomad job specs and K8s deployment and rollback concepts, and connect them to the release-promotion and rollback thinking he already uses.
3. **Production uptime/latency (high, partial).** Mitigation: use the Cerner HA message-routing story and the GlobalNOC outage dashboard as reliability evidence.
4. **Observability (high, partial).** Mitigation: GlobalNOC NOC dashboard; show that he thinks in terms of "what is running, what changed, what broke".

## C) Level and Strategy

1. **Level detected:** Listed mid level, but "open to a range of experience levels", and the $150K-$300K band clearly spans mid to senior. His natural level is senior.
2. **Sell senior without lying:** "15 years. I've owned the part of the stack that everyone else ships through, including build pipelines, deployment automation, and shared libraries, and I write it so the next person can support it."
3. **If they downlevel:** The $150K floor is above his $131K target. Accept a mid-level title if base is at least around $160K, and negotiate a 6-month review with explicit promotion criteria.

## D) Comp and Demand

| Source | Range | Notes |
|---|---|---|
| Advertised (JD) | $150,000 and $300,000 (base salary); discretionary bonus | JD: "The base salary for this role is anticipated to be between $150,000 and $300,000" |
| Firm size | 91 employees (Form ADV data) vs 147 (other tracker) | Fintrx/Radient vs RocketReach. The two estimates disagree. |

- **Advertised range:** $150K-$300K base. **Likely guaranteed base:** stated as base. For a candidate new to trading, expect the lower third ($150K-$200K). **Variable:** "discretionary bonus can be a significant portion of total compensation". **Expected stable cash:** base only. **Non-cash:** fully paid medical/dental/vision for employee and dependents, 401(k), lunch, generous PTO.
- **Company type:** Growth-stage quant investment manager (RIA, about $5.4B AUM; founded by a former Citadel GQS lead, per web sources). Medium confidence.
- **Compensation reliability:** Medium. The base is stated, but the band is very wide and the bonus is discretionary.
- ⚠️ **Pay-transparency range-width signal:** The range is $150K wide on a $150K floor, far more than half the floor. It probably spans several levels. Ask the recruiter for the band for your level. This is a general heuristic applied to the posting's own numbers, not a legal threshold, and not legal advice.
- **HR verification questions:** What base band applies at the level you would hire me into? What is the typical bonus as a percentage of base for platform engineers, and how is it decided? Is any part of the bonus deferred? Are there in-office days or hours expectations beyond the stated in-office policy?
- **Company size note:** 91-147 employees sits inside the 50-200 ideal range (estimates). **Fintech note:** A quant fund is finance-adjacent. The profile accepts it but does not prefer it, so this is a mild trade-off and not a deduction. It is not gambling: systematic investment management is outside the hard exclude.

Sources: [Fintrx — Aquatic Capital Management](https://fintrx.com/firms/firm/aquatic-capital-management-llc-307291), [Radient Form ADV](https://radientanalytics.com/firm/adv/aquatic-capital-management-llc-307291), [RocketReach](https://rocketreach.co/aquatic-capital-management-profile_b47f00b6fc540505), [Quantt](https://www.quantt.co.uk/quant-firms/aquatic-capital-management).

## E) Customization Plan

| # | Section | Current status | Proposed change | Why |
|---|---|---|---|---|
| 1 | Summary | Frontend-first | "Automation engineer: build/release tooling, deploy automation, internal developer platforms; Python" | Mirrors "production platform" |
| 2 | Competencies | — | Build & Release Automation, Deployment Pipelines, Toil Elimination, Internal Developer Tooling, Python, Documentation for Supportability, Reliability & Monitoring, CI/CD | JD pillars, honest |
| 3 | TD Ameritrade | Low on the page | Put it first and bold the 8h to 15 min result | Top proof point |
| 4 | SteelSeries | Architecture-first | Lead with Azure pipelines and the cross-team tools; keep the sandbox harness | Platform framing |
| 5 | GlobalNOC / Cerner | Low | Keep the outage dashboard and HA routing bullets | Observability and uptime evidence |

LinkedIn: headline "Senior Engineer · Build/Release & Deploy Automation · Python/TypeScript". Pin the TD Ameritrade story. Add "Internal developer platforms" to About.

## F) Interview Plan

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|---|---|---|---|---|---|---|
| 1 | Replace manual ops with automation | TD Ameritrade deploys | Each deploy took 8 hours of a dedicated engineer | Automate release | Python/Fabric/Jenkins pipeline | 15 minutes of QA time | Once the toil was gone the role was done, so he left. Automating yourself out is the goal. |
| 2 | Build/release tooling | SteelSeries Azure pipelines | Builds needed automation | Configure CI | Azure build automation pipelines | Automated builds (cv.md) | Treat pipelines as product code |
| 3 | Partner with Research/Trading Ops | SteelSeries cross-team tools | Other departments had manual pain | Learn their jobs first | Built tools for them | Tools adopted (qualitative) | Sit with the user before designing |
| 4 | Supportable by others | Electron sandbox harness + shared NPM libraries | Many teams consuming shared code | Make it safe to depend on | Documented architecture, shared libraries | Shipped (cv.md) | Docs are part of the interface |
| 5 | Uptime/correctness | Cerner message routing | Healthcare messages had to flow | HA SaaS | Java/Mule/Spring | HA in production (cv.md) | Design the failure path first |
| 6 | Observability | GlobalNOC NOC dashboard | Universities and state networks needed outage visibility | Live dashboard | Built it | Used by several major universities (cv.md) | Observability is a product for operators |

**Case study:** TD Ameritrade deploy automation, extended with how he would add pinning, approvals, and rollback today.
**Red-flag questions:** "Your recent work is frontend. Why platform?" Answer: automation is the thread through his whole career (TD Ameritrade, Azure pipelines, cross-team tools), and this role is that thread full time. "Kubernetes/Nomad?" Not yet. He picked up Jenkins/Fabric and Azure pipelines on the job, and he would ramp the same way. "No trading background?" TD Ameritrade was brokerage infrastructure. He knows why correctness and uptime come first.

## G) Posting Legitimacy

**Assessment:** High Confidence

| Signal | Finding | Weight |
|---|---|---|
| Posting age | "Posted 2 Days Ago" (scanner: 2026-09-22) | Positive |
| Apply path | Apply button present on BuiltIn | Positive |
| Specificity | Very specific (build pinning, promotion workflows, Nomad, regional parity) | Positive |
| Requirements realism | Realistic; open to a range of levels | Positive |
| Salary | Stated (wide) | Neutral-positive |
| Hiring signals | Web sources report Chicago/NY/London openings (July 2026) and firm growth; no layoff news surfaced | Positive |

**Employment classification:** ✅ clear (full-time employee, benefits listed). **AI-screening disclosure (Illinois):** the posting is silent. The obligation attaches to the interview step. Informational only, not legal advice.

## Risk Summary

| Signal | Status |
|---|---|
| Posting legitimacy | ✅ High Confidence |
| Employment classification | ✅ clear |
| Culture screen | ✅ pass |
| Interview red flags | — no interview sessions yet |
| AI claims vs. infrastructure | — not evaluated |
| AI-screening disclosure | ℹ️ Illinois requires disclosure; posting is silent |

---

## Keywords extracted

production platform, build and release tooling, build pinning, promotion workflows, rollback, deployment orchestration, scheduling, observability, alerting, failure recovery, automation, toil elimination, Python, Java, C++, distributed systems, deployment pipelines, internal developer platforms, CI/CD, configuration management, Nomad, Kubernetes, live trading

## Job Description (archived verbatim)

Posted: Posted 2 Days Ago (as shown on BuiltIn; scanner date 2026-09-22)

Aquatic Capital Management

 Jobs

 Software Engineer, Production Platform

 Aquatic Capital Management

 Software Engineer, Production Platform
 Job Posted 2 Days Ago
 Posted 2 Days Ago

 In-Office
 Chicago, IL, USA
 150K-300K Annually
 Mid level

 In-Office
 Chicago, IL, USA
 150K-300K Annually
 Mid level

 Build and operate the production platform that deploys code, models, and data into global live trading systems. Own build and release tooling, deployment orchestration, observability, rollback, alerting, failure recovery, and automation. Partner with research, engineering, and trading operations teams to improve reliability, eliminate manual processes, and establish maintainable engineering standards using Python and distributed-systems technologies.
 The summary above was generated by AIAquatic was founded with a shared passion for tackling some of the most complex challenges in one of the world’s most competitive arenas—global financial markets. From the very beginning, we have been driven by a deep commitment to applying cutting-edge scientific research and technological innovation to deliver unparalleled performance. Our journey is one of continuous growth and exploration, marked by a spirit of curiosity and relentless drive for excellence. At Aquatic, we are actively recruiting for a Software Engineer to join our Engineering team in Chicago. We are investing in the production platform that carries our research and trading systems into live markets, and we are doing it while the firm expands globally. This role sits at the center of that effort: building the deployment, build, and observability systems the rest of the firm runs on, and owning how well they behave in production.You will collaborate with researchers and engineers across Research, Execution, and Trading Operations. The work is hands-on, high-leverage, and visible: when the platform is good, everyone at the firm ships faster and sleeps better.Role DetailsOwnership of the platform that moves code, models, and data from development into global live trading, with automated dependency resolution and safe, repeatable deployments.Own build and release tooling, including build pinning and approval, promotion workflows, and rollback paths that let engineers ship into production with confidence.Extend deployment orchestration and scheduling infrastructure across regions as we enter new markets, with regional parity as the default rather than the exception.Build observability into deployments and production services so engineers, researchers, and operations can see what is running, what changed, and what broke.Partner with Research and Trading Operations to replace manual operational processes with automation, eliminating toil at the source.Improve the reliability and operability of production systems: alerting, failure handling, fallback, and recovery.Set and hold engineering standards for the platform. Clean, maintainable Python, tested and documented, built to be supported by people who did not write it.Technical ExperienceBS/MS in Computer Science, Engineering, or a related technical field, or equivalent practical experience.4+ years of professional software development experience. We are open to a range of experience levels for the right engineer.Strong python and familiarity with Java and C++ and a track record of building production-grade systems.Experience building and operating distributed systems, deployment pipelines, or internal developer platforms.Familiarity with CI/CD, configuration generation and management, workload orchestration (Nomad, Kubernetes, or similar), and production debugging.Comfortable operating in production environments where uptime, latency, and correctness are of highest importance.Helpful but not required: exposure to trading systems, market data, or model lifecycle management in production.Candidate QualitiesStrong bias for actionDriven by accountability and internal urgencyA builder's instinct for automation and toil eliminationDesire to independently seek best solutionsPreference for working in a team that focuses on delivering results aligned with Research and Development goalsComfortable providing and receiving actionable feedback in a collaborative team settingMotivated by an ambitious environment and driven colleaguesCompensationThe base salary for this role is anticipated to be between $150,000 and $300,000, which is based on information at the time of posting. This position may also be eligible for additional forms of compensation, such as a discretionary bonus, and benefits. Discretionary bonus can be a significant portion of total compensation. Actual compensation for successful candidates will be carefully determined based on a number of factors, including their unique skills, qualifications and relevant experience.Benefits:Benefits: For full-time employees, fully paid medical, dental, and vision for employees and dependents, competitive 401k plan, employer-paid life & disability insurance Perks: Wellness programs, casual dress, snacks, lunch, game room, team and company eventsDevelopment: Open environment to maximize learning and knowledge sharingTime: Generous PTO, paid holidays, competitive paid caregiver leavesAquatic Capital This role represents a unique opportunity to join a quantitative investment manager in its early stage of growth. The firm’s culture will be shaped by collaboration, meritocracy, ambition, and calm determination.Aquatic is a proud equal opportunity workplace. We do not discriminate based upon race, religion, color, national origin, sex, sexual orientation, gender identity/expression, age, status as a protected veteran, status as an individual with a disability, or any other applicable legally protected characteristics.

## Cover Letter Draft

> Draft generated at evaluation time. Complete via `/career-ops cover aquatic-capital-management` to fill in angles, confirm research, and generate the PDF.
> Gaps flagged below. Address them during the cover flow.

---

**Opening** *(placeholder — refine with your "why this role" angle)*
Aquatic wants the platform that carries research into live markets to be something engineers ship through with confidence. Building that kind of layer, and removing manual toil from it, is the work I most want to do next, in person in Chicago.

**Profile introduction**
I am a senior engineer with 15 years across startups and larger platforms, including SteelSeries, TD Ameritrade, and Cerner. I automate build and release work, I build tools for the teams around me after learning how they actually work, and I document systems so people who did not write them can support them.

**Key achievements** *(selected from cv.md — exact wording preserved)*
- **Automated build and deployment tasks,** reducing deployment time from 8 hours of dedicated engineer time to 15 minutes of QA time.
- **Configured Azure build automation pipelines.**
- **Proactively built tools for other departments** after learning about their jobs and pain points.
- **Built a Network Operations Center (NOC) dashboard** reporting live outages and network errors, used by several major universities and US state networks.

**Problems I will solve** *(placeholder — requires company research + your input)*
> To be completed: what challenges does Aquatic's production platform face that you'd address? How would you approach them?

**Closing**
I am happy to discuss further at your convenience.

---

**Gaps flagged:**
- Python is real but secondary in cv.md, and the JD asks for "strong python".
- No Nomad, Kubernetes, or configuration-management tooling.
- No C++.

**JD keywords to mirror** *(extracted for ATS + human read)*
build and release tooling, deployment orchestration, observability, eliminate toil, replace manual operational processes with automation, tested and documented, supported by people who did not write it, CI/CD, Python

---
*Run `/career-ops cover aquatic-capital-management` to complete angles, confirm company research, and generate the PDF.*
