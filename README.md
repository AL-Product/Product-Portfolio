# 👋 Hi, I am Alisha — Senior Product Manager

## I build AI-powered products that create measurable impact for real people — not just enterprise dashboards.

Senior PM with 5+ years shipping ML-based SaaS products from zero to enterprise scale. My background spans AI/ML product development, data-driven roadmap execution, and translating complex model capabilities into experiences that real users trust and adopt. I bring a rare combination: a Master's in Applied Statistics, EU AI Act certification, and hands-on experience leading cross-functional teams of 30+ across engineering, design, and data science.

📍 Based in Barcelona | 🌍 Open to remote (European timezone)

---

## ⚡ What I Bring to a Senior PM Role

**AI Product Delivery — end to end**
From LLM orchestration and agent architecture to user-facing conversational tools — I have shipped AI features in regulated industries where accuracy, governance, and explainability are non-negotiable. I understand what it takes to make AI trustworthy for real users, not just technically impressive.

**Technical Depth Without Losing the Human**
I work directly in Python notebooks, Azure environments, and API design sessions — not just in Jira. Engineering teams trust me because I understand the tradeoffs. But I never lose sight of the user on the other end.

**0→1 in Ambiguous Environments**
I have built products from blank-page briefs in domains with no existing playbook — AI model monitoring, automated data pipelines, LLM-powered summarisation — and created the structure others now follow.

**B2B2C Product Thinking**
I sell to enterprises but design for the humans inside them. Whether it is an actuary interpreting model outputs, an employee accessing their benefits, or a learner navigating a platform — the end user experience is where the product lives or dies.

**Governance and Responsible AI**
EU AI Act certified. I have shipped AI features with full HITL controls, audit trails, and explainability requirements built in from day one — not retrofitted. This is increasingly critical for any company deploying AI in Europe.

---

## 🧩 Featured Portfolio Projects

---

### 🧠 AI-Powered Insight Translator — Visualise, Summarise, Decide

#### LLMs · Agent Orchestration · Azure OpenAI · EU AI Act · Conversational UX · Human-in-the-Loop

**The Problem Worth Solving**

Every week, analytical teams produced sophisticated model outputs that told a clear story — to them. But managers, executives, and client-facing teams received the same dense metrics with no translation layer. Actuaries spent hours re-explaining outputs. Business stakeholders made decisions on partial understanding. Reporting was fragmented across emails and spreadsheets with no consistency.

The real issue was not comprehension — it was that the organisation had built sophisticated AI it could not operationalise. The last mile between model output and business decision was entirely manual, inconsistent, and invisible to leadership.

**What Made This Hard**

Three constraints made this genuinely difficult:

1. **Domain accuracy was non-negotiable** — generic LLM summaries would not work. Metrics carry regulatory weight. A misrepresented figure could influence a decision with real financial consequences. The AI had to be domain-aware, not just fluent.

2. **Multiple personas, one interface** — a portfolio manager, a CFO, and an analyst all needed different things from the same underlying data. I had to design a system that adapted outputs by persona without requiring separate models or manual reconfiguration.

3. **Regulated environment — EU AI Act compliance** — deploying a generative AI tool in a financial context meant governance was not optional. Human-in-the-loop validation, audit trails, and explainability had to be architected in from day one.

**What I Built**

An Agent-to-Agent orchestration system where:

- A **Coordinator Agent** receives the user query and routes it based on persona, metric type, and regulatory context
- **Specialist Agents** handle domain-specific summarisation, each grounded in calibrated prompt templates I defined and iterated
- A **Validation Layer** surfaces AI-generated summaries for human review before downstream use, satisfying EU AI Act HITL requirements
- A **Feedback Loop** captures reviewer edits to continuously improve output quality over time

**My Specific Contribution**

- Ran discovery interviews with three distinct user cohorts to define personas and their distinct summarisation needs
- Designed the full agent orchestration architecture — documented routing logic, agent responsibilities, and fallback behaviour
- Wrote and iterated 40+ prompt templates across persona types, testing for accuracy, tone, and regulatory appropriateness
- Defined HITL controls and audit logging requirements in partnership with legal — directly mapped to EU AI Act obligations
- Led usability testing across three user cohorts, iterating the interface in Figma before engineering implementation
- Owned the feedback loop design — defined what signals to capture and how corrections fed back into prompt refinement

**Impact**

- 📈 **50% increase in adoption** of complex analytics features among previously disengaged user cohorts
- ⏱️ Reduced reporting summary generation from **1 hour to under 60 seconds** per output
- ✅ First AI feature on the platform to achieve full EU AI Act governance sign-off before deployment
- 💬 User feedback: described outputs as "the clearest explanation of our portfolio I have ever seen"

**Tech Stack**
`Azure OpenAI (GPT-4)` `Azure Functions` `Azure App Service` `Cosmos DB` `Python` `LangChain` `Agent Orchestration` `EU AI Act Compliance` `Human-in-the-Loop Architecture` `Figma`

---

### 🔧 Automated Data Ingestion API — Model Performance Monitoring

#### API Design · Azure Data Lake · Python · Databricks · GDPR · SaaS/Cloud

**The Problem Worth Solving**

Portfolio managers needed daily visibility into model performance across hundreds of models — but every morning, a data analyst was manually uploading files. One missed upload meant stale metrics reaching the C-suite. One schema error meant hours of debugging before anyone could make a decision. This was not a data problem. It was a product gap.

**What Made This Hard**

- **Multi-client architecture** — each client had different schemas, data volumes, and security requirements
- **Regulated environment** — GDPR-compliant retention policies had to be baked into the pipeline design, not added after
- **Zero trust security** — service-principal authentication with Azure AD, ensuring no human credentials ever touched production
- **Downstream compatibility** — seamless integration with Databricks and existing data platforms without requiring client-side changes

The hardest tradeoff: balancing schema flexibility for new clients against strict validation rules needed for model reliability. I defined a tiered validation framework that flagged anomalies without blocking ingestion — preserving data flow while surfacing issues for review.

**My Specific Contribution**

- Defined the full API specification and ingestion workflow from scratch
- Shaped authentication architecture with engineering — chose service-principal over managed identity based on client infrastructure constraints
- Wrote and iterated schema validation logic in Python notebooks before handing to engineering for productionisation
- Led client-facing PoC demos, translating technical architecture into business value for non-technical stakeholders
- Owned GDPR alignment — worked directly with legal to define retention schedules and audit logging requirements

**Impact**

- 🚀 Enabled onboarding of **3 new enterprise clients within 6 months** of launch — contributing to **£7M increase in revenue**
- 🔒 **Zero** security incidents post-launch across all client environments
- 📐 Ingestion framework adopted as the **standard architecture** for all subsequent client onboardings

**Tech Stack**
`Python` `Azure Data Lake Gen2` `Azure Active Directory` `Databricks` `Parquet` `REST API` `GDPR Retention Policies` `Schema Validation`

---

## 🧭 Product Case Studies

---

### 📋 Case Study: Automated Alerts — Real-Time Risk Detection

#### 0→1 Feature · Statistical Alerting · Event-Driven Architecture · B2B2C · General Insurance

**The Context**

Large portfolios run on hundreds of predictive models evaluated daily. When a model begins to drift — or a market event shifts patterns — the window to act is narrow. The platform gave teams visibility into model performance. But visibility is not the same as awareness. A user would have to log in, navigate to the right model, and know what to look for. At scale, that is not a workflow — it is a gamble.

**The Problem**

> *"We have the data. We just do not know when something is wrong until it is already a problem."* — Portfolio Manager, discovery interview

Three failure modes were costing teams time and trust:

1. **Silent degradation** — models underperforming by statistically significant margins went unnoticed for days
2. **Alert fatigue risk** — previous monitoring attempts produced too much noise, teams had learned to ignore flags
3. **No escalation path** — even when issues were spotted, there was no structured workflow for routing the alert to the right person with the right context

**Discovery — Before Writing a Single Requirement**

I ran structured discovery across three stakeholder groups:

- **Portfolio Managers** — What decisions do you make daily, and what information do you wish you had sooner?
- **Actuarial Teams** — Which metric movements actually matter, and which are normal variance you would want to ignore?
- **Engineering and Data Science** — What is reliably detectable at the cadence we ingest data, and what would produce false positives at scale?

Key insight that changed the design: users did not want to be alerted to every threshold breach. They wanted to be alerted to *unexpected* breaches — movements outside normal seasonal or portfolio variance. This shifted the alerting logic from static thresholds to **statistical significance relative to baseline behaviour.**

**The Hard Decisions**

| Decision | Options Considered | Choice Made | Reasoning |
|---|---|---|---|
| Alerting logic | Static thresholds vs statistical baselines | Statistical baselines | Static thresholds would have reproduced the alert fatigue that killed trust in previous attempts |
| Automation level | Fully automated vs human-in-the-loop | HITL for Severity 1 | Slower escalation in exchange for dramatically fewer false positives reaching clients |
| Routing logic | All alerts to all users | Tiered routing by severity | Eliminated the sense that everything was equally urgent |

**Alert Severity Framework**

- **Severity 1** — immediate escalation to portfolio lead with full metric context attached
- **Severity 2** — daily digest to actuarial team for review
- **Severity 3** — logged and surfaced in weekly performance summary only

**What I Delivered**

- Full alerting framework specification including statistical threshold logic, severity tiers, and routing rules
- Partnered with data science to define and validate baseline variance models across 6 portfolio types
- Designed the end-to-end event-driven workflow — from metric ingestion trigger to alert delivery and acknowledgement tracking
- Led simulation testing across historical data to validate signal quality before any live deployment
- Defined HITL governance controls for Severity 1 escalations in partnership with compliance
- Presented the feature in client-facing webinars, translating statistical logic into business value for non-technical audiences

**What I Would Do Differently**

The initial severity framework was defined largely by internal assumptions. In hindsight, I would have run a structured co-design session with two or three early clients before finalising the tier definitions — their mental model of "urgent" did not always match ours, and we iterated post-launch to correct this. This is now a standard step in my discovery process for any alerting or notification feature.

**Outcome**

- 📣 Featured in client webinars within weeks of launch
- 📈 **~12% increase** in demo requests and trial conversions directly attributed to alerts capability
- 🏆 Became one of the **top three most cited features** in sales conversations — repositioning the product from a monitoring tool to a proactive risk management platform
- 🔁 Alert routing framework adopted as the **standard template** for all subsequent notification features

| PM Skill | Where It Shows |
|---|---|
| Structured discovery | Three stakeholder groups, insight that changed the design |
| Technical judgment | Statistical baselines over static thresholds — and why |
| Tradeoff reasoning | Automation vs HITL, speed vs trust |
| Governance thinking | EU AI Act aligned HITL controls |
| Business impact | 12% demo uplift, repositioned product narrative |
| Self-awareness | What I would do differently section |

---

## 🎯 EdTech & Fintech/Insurtech — Why I Am Moving Here

My next chapter is in products where I can feel the human on the other side.

The work I have done in B2B SaaS has given me deep technical and enterprise delivery credibility. But what drives me is the intersection of AI and real human outcomes — how people learn, how they manage money, how they make better decisions in their lives.

**In EdTech**, I see a space where AI is transforming how people access knowledge — but where most products still struggle to make that intelligence feel personal, trustworthy, and genuinely useful for learners. My experience designing AI features that adapt to different personas, explain complex outputs clearly, and maintain user trust through HITL governance is directly transferable to this challenge.

**In Fintech and Insurtech**, I bring something rare: actuarial depth combined with consumer product thinking. I understand risk models, regulatory constraints, and enterprise buyers — but I also know that the product lives or dies in the moment a real person tries to use it.

I am looking for roles where both of those things matter.

---

## 🏆 Product Achievements

| Achievement | Impact | Year |
|---|---|---|
| AI Insight Translator | 50% adoption increase among business users | 2025 |
| Automated Alerts 0→1 | 12% increase in demo requests | 2025 |
| Data Ingestion API | 3 enterprise clients onboarded — £7M ARR | 2024 |
| Complex Feature Delivery — Custom Loss Functionality | Activated 2 enterprise clients — £4M ARR | 2023 |
| Migration from Legacy to SaaS | 97% customer retention | 2022 |

---

## 🛠️ Skills & Tooling

### Product & Strategy

| Skill | Proficiency |
|---|---|
| 0→1 Product Development | ████████████ Expert |
| AI/ML Product Strategy | ████████████ Expert |
| Roadmap Ownership and Prioritisation | ████████████ Expert |
| User Research and Persona Definition | ██████████░░ Advanced |
| B2B2C Product Design | ██████████░░ Advanced |
| Experimentation and Funnel Analytics | ██████████░░ Advanced |
| Agile / SAFe Delivery | ██████████░░ Advanced |

### AI & Technical

| Skill | Proficiency |
|---|---|
| LLM APIs and Prompt Engineering | ████████████ Expert |
| Agent Architecture and Orchestration | ██████████░░ Advanced |
| API Architecture and Design | ██████████░░ Advanced |
| Azure (OpenAI, Functions, Data Lake, Key Vault, Cosmos DB) | ██████████░░ Advanced |
| Python (Prototyping and Notebooks) | ████████░░░░ Working |
| MLOps and Model Monitoring | ████████░░░░ Working |

### Governance & Compliance

| Skill | Proficiency |
|---|---|
| EU AI Act (High-Risk AI Systems) | ██████████░░ Advanced |
| GDPR and Data Retention Design | ██████████░░ Advanced |
| Human-in-the-Loop (HITL) Controls | ████████████ Expert |
| Regulated Industry Delivery | ████████████ Expert |

### Stakeholder & Commercial

| Skill | Proficiency |
|---|---|
| Executive and C-Suite Communication | ████████████ Expert |
| Cross-functional Leadership (Eng, Design, Data, Legal) | ████████████ Expert |
| Client-Facing Demos and Sales Enablement | ██████████░░ Advanced |
| Global Stakeholder Delivery (UK, US, APAC) | ██████████░░ Advanced |

---

## ✍️ Thought Leadership

- [Why SMEs currently have low AI adoption — and what product teams can do about it](https://www.linkedin.com/feed/update/urn:li:activity:7437069010518691840/?originTrackingId=ixmliYAIFe%2BYqKGD9dQ%2B%2FQ%3D%3D)
- [What I learned by rolling up my sleeves as a PM — beyond the roadmap](https://www.linkedin.com/posts/alisha3094_product-productmanagement-mindsetshift-activity-7433984387391672320-eLAr?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)
- [Guest Speaker at Macquarie University, Sydney — Data Science and Product Innovation](https://www.linkedin.com/posts/alisha3094_gratitude-guestspeaker-education-activity-7204503119093780480-GWJY?utm_source=share&utm_medium=member_desktop&rcm=ACoAABWSa2YBbR_efFQcUG5n8UBXSMZA6WxJ0Hg)

> *Note: LinkedIn links require login to view. Happy to share full post content on request.*

---

## 📫 Let's Talk

I am currently open to **Senior PM and Lead PM roles in EdTech and Fintech/Insurtech** — particularly B2B2C products where AI is central to the user experience.

If you are building something where intelligent technology meets real human outcomes — and you need a PM who can work at the intersection of engineering, data, and business strategy — let us connect.

**LinkedIn:** [linkedin.com/in/alisha3094](https://www.linkedin.com/in/alisha3094)
**Email:** alishamehta3012@gmail.com
**Portfolio:** [github.com/AL-Product/Product-Portfolio](https://github.com/AL-Product/Product-Portfolio)
