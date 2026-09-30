# Evaluation: JPMorganChase — Lead Software Engineer

**Date:** 2026-09-29
**URL:** https://www.builtinchicago.org/job/lead-software-engineer/11380947
**Via:** — (direct)
**Archetype:** Off-target: Python Site Reliability Engineering (closest user archetype: Automation Engineer, partial)
**Score:** 2.4/5
**Legitimacy:** High Confidence
**Work Auth:** ➖ Not needed
**Verification:** JD extracted via browser-extract.mjs (Playwright CLI); the page showed "Job Posted 4 Days Ago" with an active Apply path
**PDF:** not generated — run /career-ops pdf jpmorganchase to create on demand

---

## Machine Summary

```yaml
company: "JPMorganChase"
role: "Lead Software Engineer"
score: 2.4
legitimacy_tier: "High Confidence"
archetype: "Python SRE / reliability engineering (off-target; partial Automation Engineer overlap)"
final_decision: "Skip"
hard_stops:
  - "SRE practice (SLIs/SLOs/error budgets, chaos engineering, incident response/RCA): none in cv.md"
  - "Performance testing with JMeter: none in cv.md"
soft_gaps:
  - "Python proficiency: used at TD Ameritrade (2016) and Fulton Works (2016-2017), not recent"
  - "MongoDB: none"
  - "AWS: Lambda only (Placester)"
  - "Professional AI experience: none (personal project only, not a claim per _profile.md)"
top_strengths:
  - "Chicago hybrid (preferred setup)"
  - "Automation focus: TD Ameritrade deploy automation, Azure build pipelines"
  - "15 years application development; maintainable, documented code"
risk_level: "High"
confidence: "Medium"
next_action: "Skip. The role is an SRE/reliability specialty with no SRE evidence in cv.md; the Lead title vs 'Software Engineer' body and 'Entry level' tag also make the level unclear."
work_auth: "not_needed"
discard_reasons:
  - "tech_stack_mismatch: Python SRE (SLOs, chaos engineering, JMeter, incident response), MongoDB"
via: null
company_confidential: false
advertised_comp: null
reports_to: null
requirement_importance:
  - requirement: "Python proficiency"
    jd_signal: "Proficient in coding in Python"
    evidence: "stated"
    importance: "critical"
    match: "partial"
  - requirement: "SRE principles: SLIs, SLOs, error budgets"
    jd_signal: "Understanding of SRE principles, including SLIs, SLOs, and error budgets"
    evidence: "stated"
    importance: "critical"
    match: "missing"
  - requirement: "Reliability engineering: monitoring, alerting, automated recovery, health checks"
    jd_signal: "Familiarity with reliability engineering concepts, including monitoring, alerting, and automated recovery"
    evidence: "stated"
    importance: "critical"
    match: "partial"
  - requirement: "Incident response and root cause analysis"
    jd_signal: "Experience with incident response and root cause analysis"
    evidence: "stated"
    importance: "high"
    match: "missing"
  - requirement: "Chaos engineering"
    jd_signal: "Experience with chaos engineering practices to test system resiliency"
    evidence: "stated"
    importance: "high"
    match: "missing"
  - requirement: "Performance testing with JMeter"
    jd_signal: "Proficiency in performance testing tools such as JMeter"
    evidence: "stated"
    importance: "high"
    match: "missing"
  - requirement: "System design, application development, testing, operational stability"
    jd_signal: "Hands-on practical experience in system design, application development, testing, and operational stability"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "Large corporate environment, modern languages and database querying"
    jd_signal: "Experience developing, debugging, and maintaining code in a large corporate environment with modern programming languages and database querying languages"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "SDLC, AWS exposure, automation focus"
    jd_signal: "Knowledge of the Software Development Life Cycle, AWS cloud exposure, troubleshooting abilities, resiliency, and automation focus"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "CI/CD, application resiliency, security"
    jd_signal: "Understanding of agile methodologies such as CI/CD, application resiliency, and security"
    evidence: "stated"
    importance: "high"
    match: "partial"
  - requirement: "AI experience and MongoDB"
    jd_signal: "Experience with AI and full understanding of the SDLC process, and MongoDB"
    evidence: "stated"
    importance: "high"
    match: "missing"
  - requirement: "Maintainable, testable, high-quality code"
    jd_signal: "Commitment to writing maintainable, testable, and high-quality code"
    evidence: "stated"
    importance: "high"
    match: "strong"
  - requirement: "Data visualizations and reporting for system improvement"
    jd_signal: "Gather, analyze, and synthesize data to develop visualizations and reporting"
    evidence: "structural"
    importance: "meaningful"
    match: "partial"
  - requirement: "Modern front-end technologies"
    jd_signal: "Familiarity with modern front-end technologies"
    evidence: "structural"
    importance: "preferred"
    match: "strong"
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
| Archetype | Off-target: Python SRE / software reliability. Closest user archetype: Automation Engineer (partial) |
| Domain | Banking, Corporate Functions (team not named beyond "Software Reliability in our product team") |
| Function | Build and harden Python systems; SLIs/SLOs, monitoring/alerting, chaos experiments, JMeter perf testing, incident RCA |
| Seniority | Unclear. BuiltIn title "Lead Software Engineer", but the body says "Software Engineer – Software Reliability" and BuiltIn tags it "Entry level"; no years-of-experience requirement stated |
| Remote | Hybrid, Chicago, IL |
| Team size | Not stated |
| Culture screen | No `culture_screen` in profile.yml, so no structural cap. Chicago hybrid matches his preference for a real office. Very large enterprise (well outside the 50-200 ideal, but larger is the preferred direction). Fintech: acceptable, mildly deprioritized per _profile.md |
| TL;DR | Right city and setup, but this is a Python SRE specialty role (SLOs, chaos engineering, JMeter, incident response) with no SRE evidence in cv.md. |

**Geo-mismatch:** none (location field and body both hybrid/Chicago). **Work authorization:** ➖ Not needed (US role, `needs_sponsorship: false`). **Deal-breakers:** no DoD, defense, or gambling reference in the JD.

## B) Match with CV

| Requirement | Importance | Match | JD signal | Evidence / gap |
|---|---|---|---|---|
| SRE principles (SLIs/SLOs/error budgets) | critical (stated) | ❌ Missing | "Understanding of SRE principles, including SLIs, SLOs, and error budgets" | Nothing in cv.md. |
| Python proficiency | critical (stated) | ⚠️ Partial | "Proficient in coding in Python" | TD Ameritrade "Stack: Python, Fabric, Jenkins" (2016); Fulton Works Django/Python (2016-2017). Not recent. |
| Monitoring, alerting, automated recovery | critical (stated) | ⚠️ Partial | "Familiarity with reliability engineering concepts, including monitoring, alerting, and automated recovery" | GlobalNOC: "Built a Network Operations Center (NOC) dashboard reporting live outages and network errors" (2012-2014). Adjacent, not SRE practice. |
| Incident response + RCA | high (stated) | ❌ Missing | "Experience with incident response and root cause analysis" | Not in cv.md. |
| Chaos engineering | high (stated) | ❌ Missing | "Experience with chaos engineering practices to test system resiliency" | Not in cv.md. |
| JMeter performance testing | high (stated) | ❌ Missing | "Proficiency in performance testing tools such as JMeter" | Not in cv.md. |
| AI experience + MongoDB | high (stated) | ❌ Missing | "Experience with AI and full understanding of the SDLC process, and MongoDB" | No MongoDB. AI is personal learning only; _profile.md forbids treating it as a professional claim. |
| CI/CD, resiliency, security | high (stated) | ⚠️ Partial | "Understanding of agile methodologies such as CI/CD, application resiliency, and security" | "Configured Azure build automation pipelines" (SteelSeries); CI/CD in Skills. No resiliency/security evidence. |
| System design, app dev, testing, stability | high (stated) | ✅ Strong | "Hands-on practical experience in system design, application development, testing, and operational stability" | "Designed and implemented major architectural features, including a video editing suite, an Electron application and sandbox harness..." |
| Large corporate environment + DB querying | high (stated) | ✅ Strong | "Experience developing, debugging, and maintaining code in a large corporate environment..." | Cerner, TD Ameritrade, SteelSeries; SQL/MySQL in Skills and GlobalNOC stack. |
| SDLC, AWS exposure, automation focus | high (stated) | ✅ Strong | "Knowledge of the Software Development Life Cycle, AWS cloud exposure, troubleshooting abilities, resiliency, and automation focus" | "Automated build and deployment tasks, reducing deployment time from 8 hours of dedicated engineer time to 15 minutes of QA time"; AWS Lambda at Placester. |
| Maintainable, testable code | high (stated) | ✅ Strong | "Commitment to writing maintainable, testable, and high-quality code" | TDD in Fulton Works stack and Skills; "Documentation Forward" strength. |
| Data visualization/reporting | meaningful (structural) | ⚠️ Partial | Job Responsibilities: "develop visualizations and reporting for software and system improvement" | NOC dashboard (GlobalNOC); Statz on Statz data viz project. Not system-metrics reporting. |
| Modern front-end | preferred (structural) | ✅ Strong | Preferred: "Familiarity with modern front-end technologies" | React, Redux, Electron (cv.md Skills). |

### Gaps

- **SRE core (SLOs/error budgets, incident response/RCA, chaos engineering, JMeter):** hard blocker. These are the role's identity, not add-ons. Interview risk: a reliability-focused loop will ask how he defined an SLO, ran a postmortem, or designed a chaos experiment, and he has no story for any of them. Mitigation: none honest beyond "fast learner" framing plus the GlobalNOC outage dashboard as adjacent exposure. Not enough.
- **Python proficiency:** real but dated (2016-2017). Interview risk: live Python coding at a bank. Mitigation: refresh; lead with TD Ameritrade Python/Fabric automation.
- **Monitoring/alerting/automated recovery:** partial via GlobalNOC. Mitigation: frame the NOC dashboard as operational-visibility work.
- **AI + MongoDB:** missing. Do not claim the personal Ollama project as professional AI experience.
- **CI/CD, resiliency, security:** CI/CD covered; mention Azure pipelines and Jenkins.

## C) Level and Strategy

Level is ambiguous: the listing title is Lead, while the body and BuiltIn tag read as a mid/entry Software Engineer role with no years requirement. His natural level is senior IC. Even at a lower level, the SRE specialty is the gap, not seniority. If pursued anyway, pitch as "automation engineer who removes manual toil" (TD Ameritrade deploy automation) and ask the recruiter which level the requisition actually is. Not recommended.

## D) Comp and Demand

- **Company type:** Public big tech / mature financial services (JPMorgan Chase & Co.). High confidence.
- **Compensation reliability:** Unknown. The JD states no salary figure, so the component split, market rows, and HR verification questions are skipped.

No new searches run; company context reused from reports 040 and 072 (no company-wide 2026 layoffs; tech budget growing; targeted AI-driven redeployments in some teams).

## E) Customization Plan

Not produced (role not recommended).

## F) Interview Plan

Not produced (role not recommended).

## G) Posting Legitimacy

**Assessment:** High Confidence

| Signal | Finding | Weight |
|---|---|---|
| Posting age | "Job Posted 4 Days Ago" (scanner posted date 2026-09-25) | Positive |
| Apply path | Apply button present on BuiltIn | Positive |
| Tech specificity | Specific: Python, SLIs/SLOs, error budgets, chaos engineering, JMeter, MongoDB, AWS | Positive |
| Requirements realism | Title "Lead Software Engineer" vs body "Software Engineer – Software Reliability" and BuiltIn "Entry level" tag; no years stated | Neutral (likely listing metadata inconsistency, not a ghost signal) |
| Reposting | First sighting of this URL in scan-history (2026-09-28); several other distinct JPMorganChase Chicago reqs seen, no same-title repost pattern | Neutral |
| Salary | Not stated | Neutral |

**Context notes:** The level inconsistency most likely comes from BuiltIn metadata or a JPMC template title; confirm the actual level with the recruiter if applying. **Employment classification:** ✅ clear (full-time employee language, benefits). **AI-screening disclosure (Illinois):** the posting is silent. Informational only, not legal advice. Prior-contact history: none.

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

Python, Site Reliability Engineering, SRE, SLIs, SLOs, error budgets, monitoring, alerting, automated recovery, chaos engineering, JMeter, performance testing, incident response, root cause analysis, post-incident reviews, AWS, MongoDB, CI/CD, application resiliency, SDLC, system health checks

## Job Description (archived verbatim)

Posted: Job Posted 4 Days Ago (as shown on BuiltIn; scanner date 2026-09-25)

JPMorganChase
 
 
 
 Jobs
 
 
 Lead Software Engineer
 
 
 
 
 

 
 JPMorganChase

 Lead Software Engineer
 Job Posted 4 Days Ago
 Posted 4 Days AgoBe an Early Applicant
 
 
 Hybrid
 Chicago, IL, USA
 Entry level

 Hybrid
 Chicago, IL, USA
 Entry level

 
 
 Design and develop scalable Python systems while applying SRE principles to improve reliability, security, and performance. Responsibilities include monitoring, alerting, automated recovery, SLI/SLO measurement, chaos engineering, performance testing with JMeter, incident response, root cause analysis, and production troubleshooting. The role collaborates with product teams, contributes to architecture and engineering practices, and maintains high-quality, resilient software.
 The summary above was generated by AI As a Software Engineer – Software Reliability in our product team, you will design and develop scalable, resilient systems using Python. You will apply SRE principles, drive operational excellence, and ensure our applications meet the highest standards of reliability and security. You’ll work closely with peers to troubleshoot, optimize, and maintain production code, while fostering a collaborative and inclusive environment. Your expertise will help us advance our software engineering practices and deliver impactful solutions.
 Job Responsibilities 
 Design and develop scalable and resilient systems using Python to support continuous improvement Apply Site Reliability Engineering (SRE) concepts to enhance system reliability and performance Execute software solutions, including design, development, and technical troubleshooting Create secure, high-quality production code and maintain algorithms that run synchronously with appropriate systems Produce or contribute to architecture and design artifacts, ensuring design constraints are met Gather, analyze, and synthesize data to develop visualizations and reporting for software and system improvement Identify hidden problems and patterns in data to drive improvements in coding hygiene and system architecture Implement reliability engineering practices such as monitoring, alerting, and automated recovery Define and measure Service Level Indicators (SLIs) and Service Level Objectives (SLOs) to track system health Conduct chaos engineering experiments to test system resiliency and identify weaknesses Perform performance testing using tools such as JMeter to ensure scalability and stability Collaborate with product teams to enhance system reliability, scalability, and performance Contribute to software engineering communities of practice and events exploring new and emerging technologies Foster a team culture of diversity, opportunity, inclusion, and respect Participate in post-incident reviews and drive root cause analysis for system failures Required qualifications, capabilities, and skills 
 Hands-on practical experience in system design, application development, testing, and operational stability Proficient in coding in Python Experience developing, debugging, and maintaining code in a large corporate environment with modern programming languages and database querying languages Knowledge of the Software Development Life Cycle, AWS cloud exposure, troubleshooting abilities, resiliency, and automation focus Understanding of agile methodologies such as CI/CD, application resiliency, and security Knowledge of software applications and technical processes within a technical discipline (e.g., cloud, artificial intelligence, machine learning, mobile, etc.) Experience with AI and full understanding of the SDLC process, and MongoDB Familiarity with reliability engineering concepts, including monitoring, alerting, and automated recovery Ability to implement and maintain system health checks and performance metrics Experience with incident response and root cause analysis Commitment to writing maintainable, testable, and high-quality code Understanding of SRE principles, including SLIs, SLOs, and error budgets Experience with chaos engineering practices to test system resiliency Proficiency in performance testing tools such as JMeter Preferred qualifications, capabilities, and skills 
 Familiarity with modern front-end technologies Exposure to cloud technologies About Us JPMorganChase, one of the oldest financial institutions, offers innovative financial solutions to millions of consumers, small businesses and many of the world’s most prominent corporate, institutional and government clients under the J.P. Morgan and Chase brands. Our history spans over 200 years and today we are a leader in investment banking, consumer and small business banking, commercial banking, financial transaction processing and asset management.
 
 We offer a competitive total rewards package including base salary determined based on the role, experience, skill set and location. Those in eligible roles may receive commission-based pay and/or discretionary incentive compensation, paid in the form of cash and/or forfeitable equity, awarded in recognition of individual achievements and contributions. We also offer a range of benefits and programs to meet employee needs, based on eligibility. These benefits include comprehensive health care coverage, on-site health and wellness centers, a retirement savings plan, backup childcare, tuition reimbursement, mental health support, financial coaching and more. Additional details about total compensation and benefits will be provided during the hiring process. We recognize that our people are our strength and the diverse talents they bring to our global workforce are directly linked to our success. We are an equal opportunity employer and place a high value on diversity and inclusion at our company. We do not discriminate on the basis of any protected attribute, including race, religion, color, national origin, gender, sexual orientation, gender identity, gender expression, age, marital or veteran status, pregnancy or disability, or any other basis protected under applicable law. We also make reasonable accommodations for applicants’ and employees’ religious practices and beliefs, as well as mental health or physical disability needs. Visit our FAQs for more information about requesting an accommodation. JPMorgan Chase & Co. is an Equal Opportunity Employer, including Disability/Veterans About the TeamOur professionals in our Corporate Functions cover a diverse range of areas from finance and risk to human resources and marketing. Our corporate teams are an essential part of our company, ensuring that we’re setting our businesses, clients, customers and employees up for success.
 Read Full Description
 

 JPMorganChase Chicago, Illinois, USA Office

 Chicago, IL, United States

## Cover Letter Draft

> Not recommended. Stub only.

**Gaps flagged:** SRE practice (SLIs/SLOs, error budgets, chaos engineering, incident response/RCA), JMeter, MongoDB, recent Python, professional AI experience; role level unclear (Lead title vs Entry level tag).

**JD keywords to mirror:** automation focus, maintainable, testable, and high-quality code, system design, CI/CD, monitoring and alerting
