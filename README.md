<!--
README Template for Product Manager Portfolio
Fill in each section as you build your repos, case studies, and demos.
-->

# 👋 Hi, I am Alisha — Senior Technical Product Manager
## I build SaaS platforms with AI-powered features that make complex decisions simple for enterprise clients across globe. 
Senior TPM with a track record of turning messy, ambiguous problems into production-ready platforms. From LLM-powered workflows to automated data pipelines, I have delivered B2B SaaS products across insurance and financial services markets that reduce manual effort, accelerate decisions, and drive measurable adoption.

---

## ⚡ What I Bring to a Senior PM Role
<div align="justify">
  
**AI Product Delivery — end to end** \
From LLM orchestration and agent architecture to user-facing chatbots — I have shipped AI features in regulated industries where accuracy, governance, and explainability are non-negotiable.

**Technical Depth Without Losing the Business** \
I work directly in Python notebooks, Azure environments, and API design sessions — not just in Jira. Engineering teams trust me because I understand the tradeoffs, not just the timelines.

**0→1 in Ambiguous Environments** \
I've built products from blank-page briefs in domains with no existing playbook — actuarial AI, model monitoring, automated data pipelines — and created the structure others now follow.

**Global Stakeholder Delivery** \
Shipped products across UK, US, and APAC markets, navigating regulatory constraints (GDPR, EU AI Act), legal reviews, and client-specific requirements simultaneously.

**Rapid Prototyping to Production** \
I use GitHub Copilot and Azure tooling to prototype fast, validate with users early, and reduce engineering rework — cutting the gap between idea and demo significantly.

---

## 🧩 Featured Portfolio Projects

<div align="justify">

### 🧠 AI-Powered Insight Translator — Visualise, Summarise, Decide
#### LLMs · Agent Orchestration · Azure OpenAI · EU AI Act · Conversational UX · Human-in-the-Loop

**The Problem Worth Solving**
Every week, actuarial teams produced sophisticated model outputs that told a clear story — to them. But portfolio managers, executives, and client-facing teams were receiving the same dense metrics with no translation layer. 
The result:

- Actuaries spent hours in meetings re-explaining the same outputs
- Business stakeholders made decisions on partial understanding
- Reporting workflows were fragmented across emails, spreadsheets, and ad-hoc summaries with no consistency

The real issue wasn't comprehension — it was that the organisation had built sophisticated AI it couldn't operationalise. The last mile between model output and business decision was entirely manual, inconsistent, and invisible to leadership.

**What Made This Hard**
Three constraints made this genuinely difficult to get right:

**1. Domain accuracy was non-negotiable**
Generic LLM summaries wouldn't work. Actuarial metrics carry regulatory weight — a misrepresented loss ratio or reserve movement could influence a business decision with real financial 
consequences. The AI had to be domain-aware, not just fluent.

**2. Multiple personas, one interface**
A portfolio manager, a CFO, and a claims analyst all needed different things from the same underlying data. I had to design a system that adapted outputs by persona without requiring separate models or manual reconfiguration.

**3. Regulated environment — EU AI Act compliance**
Deploying a generative AI tool in a financial services context meant governance wasn't optional. Human-in-the-loop validation, audit trails, and explainability requirements had to be architected in from day one — not retrofitted.

**What I Built**
An Agent-to-Agent orchestration system where:

- A **Coordinator Agent** receives the user query and routes it based on persona, metric type, and regulatory context
- **Specialist Agents** handle domain-specific summarisation — each grounded in actuarial knowledge and calibrated prompt templates I defined and iterated
- A **Validation Layer** surfaces AI-generated summaries for human review before downstream use, satisfying EU AI Act HITL requirements
- A **Feedback Loop** captures reviewer edits to continuously improve output quality over time

I designed the full agent architecture, defined the prompt framework for each specialist agent, and established the governance model with legal and compliance teams.

**My Specific Contribution**
- Ran discovery interviews with actuaries, portfolio managers, and CFOs to define the three core personas and their distinct summarisation needs
- Designed the agent orchestration architecture — documented routing logic, agent responsibilities, and fallback behaviour
- Wrote and iterated 40+ prompt templates across persona types, testing for accuracy, tone, and regulatory appropriateness
- Defined HITL controls and audit logging requirements in partnership with legal — directly mapped to EU AI Act obligations for high-risk AI systems
- Led usability testing across three user cohorts, iterating the interface in Figma before engineering implementation
- Owned the feedback loop design — defined what signals to capture, how corrections fed back into prompt refinement, and how quality was measured over time

**Impact**
- 📈 **50% increase in adoption** of complex analytics features among previously disengaged business user cohorts
- ⏱️ Reduced time to generate reporting summaries from **1 hour to under 60 seconds** per output
- ✅ First AI feature in the platform to achieve full EU AI Act governance sign-off before deployment
- 💬 Qualitative feedback: stakeholders described outputs as "the clearest explanation of our portfolio I have ever seen"

**Tech Stack**
Azure OpenAI (GPT-4) · Azure Functions · Azure App Service · Azure Key Vault · Cosmos DB · Python · REST API · Figma · MLOps · LangChain / Agent Orchestration Framework · EU AI Act Compliance · Human-in-the-Loop Architecture

<p align="left">
  <a href="https://github.com/users/AL-Product/projects/1" target="_blank">
  </a>
</p> 

### 🔧 Automated Data Ingestion API — Model Performance Monitoring
#### API Design · Azure Data Lake · Python · Databricks · GDPR · SaaS/Cloud

**The Problem Worth Solving**
Portfolio managers at insurance firms needed daily visibility into model performance across hundreds of models — but every morning, a data analyst was manually uploading files. One missed upload 
meant stale metrics reaching the C-suite. One schema error meant hours of debugging before anyone could make a decision. This wasn't a data problem. It was a product gap.

**What I Built — and Why It Was Hard**
I led the end-to-end design and delivery of an automated ingestion API that replaced manual uploads entirely. The complexity wasn't  the ingestion itself — it was the constraints:

- **Multi-client architecture** — each client had different schemas, data volumes, and security requirements
- **Regulated environment** — GDPR-compliant retention policies had to be baked into the pipeline design, not bolted on after
- **Zero trust security** — service-principal authentication with Azure AD, ensuring no human credentials ever touched production
- **Downstream compatibility** — seamless integration with Databricks and existing data platforms without requiring client-side changes

**The hardest tradeoff:** Balancing schema flexibility for new clients against strict validation rules needed for model reliability. 
I defined a tiered validation framework that flagged anomalies without blocking ingestion — preserving data flow while surfacing issues for review.

**My Specific Contribution**
- Defined the full API specification and ingestion workflow from scratch
- Shaped authentication architecture with engineering — chose service-principal over managed identity based on client infrastructure constraints
- Wrote and iterated the schema validation logic in Python notebooks before handing to engineering for productionisation
- Led client-facing PoC demos, translating technical architecture into business value for non-technical stakeholders
- Owned GDPR alignment — worked directly with legal to define retention schedules and audit logging requirements

**Impact**
- 🚀 Enabled onboarding of **3 new enterprise clients** within **6 months** of launch resulting in £7M increase in revenue.
- 🔒 **Zero** security incidents post-launch across all client environments
- 📐 Ingestion framework adopted as the **standard architecture** for all subsequent client onboardings

**Tech Stack**
Python · Azure Data Lake Gen2 · Azure Active Directory (Service Principal)· Databricks · Parquet · REST API · GDPR Retention Policies · Schema Validation Frameworks

</div>
---

## 🧭 Product Case Studies

## 📋 Case Study: Automated Alerts
### Real-Time Risk Detection for Actuarial Model Portfolios
#### 0→1 Feature · Statistical Alerting · Event-Driven Architecture · 
#### B2B SaaS · General Insurance

### The Context

Large insurance portfolios run on hundreds of predictive models evaluated daily against incoming claims and market data. When a model begins to drift — or a market event suddenly shifts loss 
patterns — the window to act is narrow.
The platform already gave teams visibility into model performance. But visibility isn't the same as awareness. A portfolio manager would have to log in, navigate to the right model, and know what to look for. At scale, across dozens of General Insurance sectors, that's not a workflow — it's a gamble.

### The Problem I Was Asked to Solve
> *"We have the data. We just don't know when something's wrong until it's already a problem."* — Portfolio Manager, discovery interview

Three failure modes were costing teams time and trust:

**1. Silent degradation**
Models underperforming by statistically significant margins went unnoticed for days because no one was watching the right metric at the right time.

**2. Alert fatigue risk**
Previous attempts at monitoring had produced too much noise — teams had learned to ignore flags. Any new alerting system had to earn trust by being precise, not just sensitive.

**3. No escalation path**
Even when issues were spotted manually, there was no structured workflow for routing the alert to the right person with the right context attached.

---

### Discovery — What I Did Before Writing a Single Requirement

Before defining any solution, I ran structured discovery across three stakeholder groups:

**Portfolio Managers** — What decisions do you make daily, and what information do you wish you had sooner?

**Actuarial Teams** — Which metric movements actually matter, and which are normal variance you'd want to ignore?

**Engineering & Data Science** — What's detectable reliably at the cadence we ingest data, and what would produce false positives at scale?

Key insight that changed the design: actuaries didn't want to be alerted to every threshold breach. They wanted to be alerted to *unexpected* breaches — movements that fell outside normal seasonal or portfolio variance. This shifted the alerting logic from static thresholds to **statistical significance relative to baseline behaviour.**

### The Hard Decisions

**Decision 1: Static thresholds vs. statistical baselines**
The simpler build was fixed thresholds — alert when metric X drops below value Y. Fast to build, easy to explain.
The right build was dynamic — alert when a metric moves beyond its own historical variance band, adjusted for portfolio type and data volume.

I pushed for the harder version. The reason: static thresholds would have produced the same alert fatigue that killed trust in previous attempts. The statistical baseline approach meant fewer alerts, higher signal quality, and a system actuaries would actually trust.

**Decision 2: How much to automate vs. keep human**
There was pressure to make alerts fully automated — fire and forget. I advocated for a human-in-the-loop review step for Severity 1 alerts before they escalated to stakeholders.

The tradeoff: slightly slower escalation in exchange for dramatically fewer false positives reaching clients. In a regulated industry where trust is the product, that tradeoff was correct.

**Decision 3: Alert routing logic**
Not all alerts should reach the same person. I designed a tiered routing framework:

- **Severity 1** — immediate escalation to portfolio lead with full metric context attached
- **Severity 2** — daily digest to actuarial team for review
- **Severity 3** — logged and surfaced in weekly performance summary only

This alone reduced perceived noise by eliminating the sense that everything was equally urgent.

### What I Delivered

- Full alerting framework specification including statistical threshold logic, severity tiers, and routing rules
- Partnered with data science to define and validate baseline variance models across 6 General Insurance portfolio types
- Designed the end-to-end event-driven workflow — from metric ingestion trigger to alert delivery and acknowledgement tracking
- Led simulation testing across historical data to validate signal quality before any live deployment
- Defined HITL governance controls for Severity 1 escalations in partnership with compliance
- Presented the feature in client-facing webinars, translating statistical logic into business value for non-technical audiences

### What I would do differently

The initial severity framework was defined largely by internal assumptions. In hindsight, I would have run a structured co-design session with two or three early clients before finalising the tier definitions — their mental model of "urgent" didn't always match ours, and we iterated post-launch to correct this.
This is now a standard step in my discovery process for any alerting or notification feature.

### Outcome

Launched within **two months** of the platform's initial release — one of the fastest 0→1 deliveries on the roadmap.

- 📣 Featured in client webinars within weeks of launch
- 📈 **~12% increase** in demo requests and trial conversions directly attributed to the alerts capability
- 🏆 Became one of the **top three most cited features** in sales conversations, repositioning the product from a monitoring tool to a proactive risk management platform
- 🔁 Alert routing framework adopted as the **standard template** for all subsequent notification features built on the platform


### What This Case Study Demonstrates

| PM Skill | Where It Shows |
|---|---|
| Structured discovery | Three stakeholder groups, insight that changed the design |
| Technical judgment | Statistical baselines over static thresholds — and why |
| Tradeoff reasoning | Automation vs HITL, speed vs trust |
| Governance thinking | EU AI Act aligned HITL controls |
| Business impact | 12% demo uplift, repositioned product narrative |
| Self-awareness | What I'd do differently section |

</div>

---

## 🛠️ Skills & Tooling

### Product & Strategy

| Skill | Proficiency |
|---|---|
| 0→1 Product Development | ████████████ Expert |
| AI/ML Product Strategy | ████████████ Expert |
| Roadmap Ownership & Prioritisation | ████████████ Expert |
| User Research & Persona Definition | ██████████░░ Advanced |
| Experimentation & Funnel Analytics | ██████████░░ Advanced |
| Workflow & API Design | ██████████░░ Advanced |
| Agile / SAFe Delivery | ██████████░░ Advanced |

---

### AI & Technical

| Skill | Proficiency |
|---|---|
| LLM APIs & Prompt Engineering | ████████████ Expert |
| Agent Architecture & Orchestration | ██████████░░ Advanced |
| API Architecture & Design | ██████████░░ Advanced |
| Azure (OpenAI, Functions, Data Lake, Key Vault, Cosmos DB) | ██████████░░ Advanced |
| Python (Prototyping & Notebooks) | ████████░░░░ Working |
| GitHub Copilot & Rapid Prototyping | ████████░░░░ Working |
| MLOps & Model Monitoring | ████████░░░░ Working |

---

### Governance & Compliance

| Skill | Proficiency |
|---|---|
| EU AI Act (High-Risk AI Systems) | ██████████░░ Advanced |
| GDPR & Data Retention Design | ██████████░░ Advanced |
| Human-in-the-Loop (HITL) Controls | ████████████ Expert |
| Regulated Industry Delivery (Insurance/Financial Services) | ████████████ Expert |

---

### Stakeholder & Commercial

| Skill | Proficiency |
|---|---|
| Executive & C-Suite Communication | ████████████ Expert |
| Cross-functional Leadership (Eng, Design, Data, Legal) | ████████████ Expert |
| Client-Facing Demos & Sales Enablement | ██████████░░ Advanced |
| Global Stakeholder Delivery (UK, US, APAC) | ██████████░░ Advanced |
---

## ✍️ Thought Leadership
<!-- Add links to articles, talks, templates, frameworks -->

- [Thought Leadership: Ever Wondered why SMEs currently have low Adoption?](https://www.linkedin.com/feed/update/urn:li:activity:7437069010518691840/?originTrackingId=ixmliYAIFe%2BYqKGD9dQ%2B%2FQ%3D%3D)
- [Thought Leadership: Insights I gained by rolling-up my sleeves ](https://www.linkedin.com/posts/alisha3094_product-productmanagement-mindsetshift-activity-7433984387391672320-eLAr?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)
- [Guest Speaker at Macquarie University, Sydney, sharing insights on data science and product innovation](https://www.linkedin.com/posts/alisha3094_gratitude-guestspeaker-education-activity-7204503119093780480-GWJY?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)

---
## 🥇 Product Achievements
- [Radar Vision - Product I worked on at WTW](https://www.linkedin.com/posts/wtw-ict_radarvision-modelmonitoring-portfoliomanagement-ugcPost-7315554290821918721--QOb?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)  

| Achievement | Impact | Year |
|---|---|---|
| Launched Automated Alerts 0→1 | 12% increase in demo requests | 2025 |
| AI Insight Translator | 50% adoption increase | 2025 |
| Data Ingestion API | 3 enterprise clients onboarded (£10M ARR)| 2024 |
| Complex Feature Delivery - Custom Loss Functionality| Activation ~2 clients (£4M ARR) | 2023 |
| Migration from Legacy to SaaS | Retention ~97% | 2022 |

## 🥇 Personal Achievements
| Achievement | Impact | Year |
|---|---|---|
| Guest Speaker — Macquarie University | Data Science & Product Innovation | 2023 |
| Promotion | 2 Promotions at WTW | 2023 & 2025 |
| SAFe PM/PO Certified | Scaled Agile Framework | 2022 |
| AI Fundamentals Certified | Generative AI & Responsible AI | 2024 |

- [Recognition at WTW](https://www.linkedin.com/posts/alisha3094_insuranceconsultingandtechnology-productgrowth-share-7284572680169627648-zgx7?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg) 
- [AI Fundamentals](https://www.linkedin.com/posts/alisha3094_ai-generativeai-responsibleai-activity-7432892188084043776-_aGa?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)
- [SAFe Product Owner/Manager](https://www.linkedin.com/posts/alisha3094_wtw-wtwcareers-insurancetechnology-activity-6990127285592887296-_WRQ?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)

---

## Want to know what others say about me?

- **Hear directly from the colleagues I've worked with** — real stories, real impact  
  👉 [Read their recommendations](https://www.linkedin.com/in/alisha3094/details/recommendations/?detailScreenTabIndex=0)

- **Curious what my professors thought of me during my Masters?**  
  👉 [See their words and recognition](https://www.linkedin.com/posts/alisha3094_macquarieuniversity-departmentofmathematicsandstatistics-activity-6835935151034396672-uMFe?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)

---

## 📫 Let's Talk
I'm currently open to Senior PM and Lead PM roles in AI, data platforms, and regulated B2B SaaS.

If you're building something ambitious and need a PM who can work at the intersection of engineering, data, and business strategy — let's connect.

**LinkedIn:** https://www.linkedin.com/in/alisha3094
**Email:** alishamehta3012@gmail.com
