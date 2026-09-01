# FDE Best Practice

## A Practical Framework for Forward Deployed Engineering

Forward Deployed Engineers operate where **business problems, data, AI, software engineering, and production reality meet**.

The role is broader than building a prototype and narrower than “owning everything.” A strong FDE must be able to understand how a customer actually works, identify the right problem, choose the simplest viable technical approach, validate it with evidence, and help turn a successful experiment into a system that can be safely operated, supported, and improved.

**FDE Best Practice** is a practical framework for doing that work well.

> **Full framework, playbooks, templates, and casebook:**
> https://fde.datacream.ai/

---

## Why This Project Exists

AI has made it dramatically easier to build software and prototypes.

It has not made it easier to answer the harder questions:

* Are we solving the right business problem?
* Do we understand how users really make decisions today?
* Should this problem use rules, analytics, ML, an LLM, RAG, an agent, or no AI at all?
* What does a successful POC actually prove?
* When is AI-generated code safe to promote into production engineering?
* What evidence is sufficient for quality, security, privacy, reliability, and customer acceptance?
* How should FDEs work with Product Owners, Business Analysts, SDEs, QA, Security, SRE, and AI/Data Operations?
* How do we know when to continue, reframe, stop, release, scale, hand over, or retire a solution?
* How do we turn one customer engagement into reusable organizational knowledge without leaking customer-specific information?

Without a shared practice, FDE work can easily degrade into one of several failure modes:

**demo engineering, endless customer customization, over-agentization, hidden manual work, POC code pushed directly to production, unclear ownership, or impressive AI metrics with little business value.**

This project is designed to prevent those outcomes.

---

# 1STEP FORWARD

The framework uses **FORWARD** as the end-to-end operating model for FDE delivery.

| Stage                               | Purpose                    | Key Question                                                                           |
| ----------------------------------- | -------------------------- | -------------------------------------------------------------------------------------- |
| **F — Frame Outcomes**              | Define the business result | What outcome is actually worth improving?                                              |
| **O — Observe Work**                | Understand real work       | How do users work, decide, and handle exceptions today?                                |
| **R — Represent Data & Knowledge**  | Structure the problem      | What data, business concepts, rules, relationships, and system boundaries matter?      |
| **W — Work Through Evidence**       | Reduce uncertainty         | What is the smallest credible experiment that can answer the important questions?      |
| **A — Assure Enterprise Readiness** | Prepare for production     | Is the solution secure, reliable, testable, maintainable, compliant, and supportable?  |
| **R — Release & Run**               | Operate safely             | How do we release, observe, support, improve, and recover the system?                  |
| **D — Distill & Diffuse**           | Compound learning          | What should become reusable knowledge, a pattern, a playbook, or a product capability? |

FORWARD is **not a waterfall process**. Teams can iterate between stages. The important principle is that progression should be based on **evidence, risk, ownership, and business value**, not on how impressive a demo looks.

---

## What an FDE Is Responsible For

An FDE is typically responsible for connecting:

**Business Context → Technical Approach → Validation Evidence → Production Reality**

That includes work such as:

* technical and business discovery;
* problem framing and success criteria;
* data and system readiness assessment;
* AI and non-AI solution selection;
* architecture and integration design;
* prototype, POC, and pilot design;
* evaluation and failure analysis;
* controlled AI-assisted / vibe coding;
* engineering promotion into production development;
* production-readiness evidence;
* rollout, observability, and operational feedback;
* handoff to long-term engineering and service owners;
* reusable patterns and field learning.

An FDE should **not automatically become** the final owner of:

* business priorities;
* customer business rules;
* residual enterprise risk;
* independent security or quality approval;
* permanent production support;
* every customization requested by a customer.

Clear responsibility boundaries are part of good FDE practice.

---

## Core Principles

### 1. Start with the outcome, not the model

“Build an agent” is not a business outcome.

A good engagement starts with a measurable change in a workflow, decision, risk, cost, revenue, quality, or user experience.

### 2. Observe real work before designing the solution

Requirements are not always the same as reality.

FDEs should understand actual workflows, exceptions, workarounds, decision rules, data limitations, and operational constraints.

### 3. Use the lowest necessary technical complexity

Rules, SQL, analytics, conventional software, or traditional ML may be better than an LLM.

A workflow may be better than an agent.

A single bounded agent may be better than a multi-agent system.

Complexity must earn its place.

### 4. A demo is not evidence

A successful demo proves that something can look convincing once.

A credible POC or pilot must define:

* the hypothesis;
* representative data;
* baseline or comparator;
* success thresholds;
* critical failure conditions;
* known limitations;
* manual intervention;
* evidence needed for the next decision.

### 5. AI-generated code still needs engineering

The method used to generate code does not define its quality.

AI-assisted coding must still meet the engineering, testing, security, maintainability, and operational standards required by the target environment.

### 6. Production readiness is release-specific

“Production ready” is not a permanent label.

It depends on the specific:

**release + environment + users + data + permissions + model + workflow + risk level + operational owner.**

### 7. Human oversight must be meaningful

Adding an “Approve” button does not create meaningful human control.

Reviewers need the right evidence, time, authority, capability, and escalation path to disagree with the system.

### 8. Evidence beats confidence

Important claims should be traceable to:

* business evidence;
* data;
* experiments;
* tests;
* operational signals;
* authoritative external sources;
* explicit owner decisions.

### 9. Customer knowledge has boundaries

Customer-specific data, workflow knowledge, rules, and lessons must not automatically become reusable organizational assets.

Reuse requires authorization, abstraction, and revalidation.

### 10. The goal is sustainable ownership

An FDE engagement is not complete because the demo worked.

It is complete when the capability can be **understood, operated, supported, measured, changed, and eventually retired without depending on a single FDE.**

---

## What the Full Framework Covers

The detailed FDE Best Practice includes guidance for:

### Customer & Business

* FDE role and responsibility boundaries
* engagement qualification
* outcome definition
* stakeholder discovery
* workflow observation
* business knowledge management

### Data & AI

* data and system readiness
* domain and semantic modeling
* analytics and AI applicability
* RAG, models, agents, and tools
* evaluation, Golden Sets, and production quality
* human-AI collaboration
* AI/Data Operations

### Engineering

* controlled AI-assisted coding
* agile delivery and engineering promotion
* architecture and maintainability
* APIs and integration
* CI/CD and release management
* observability
* performance, reliability, and disaster recovery

### Enterprise Assurance

* non-functional requirements
* security
* privacy
* AI governance
* open-source and software supply chain
* production readiness
* customer acceptance

### Operations & Learning

* rollout and adoption
* incident and problem management
* handoff and FDE exit
* documentation and traceability
* technical decision making
* reusable assets
* measurement
* community learning
* anti-patterns and failure casebook

---

## DataCREAM and Other FDE Skills

This framework is **tool-neutral**.

FDEs may use different methods and technologies depending on the problem, including:

* business analysis;
* statistics;
* SQL and BI;
* conventional software engineering;
* DataCREAM;
* machine learning;
* LLMs;
* RAG;
* agents;
* workflow automation;
* AI-assisted coding.

**DataCREAM is one optional data-analysis capability in the FDE toolbox. It is not a mandatory foundation of the FDE Best Practice.**

The framework focuses on **how to make good decisions and deliver trustworthy outcomes**, regardless of the specific tool selected.

---

## How to Use This Repository

This Git repository is intentionally a **concise entry point** to the framework.

Use it to understand the philosophy, lifecycle, and core principles.

For detailed standards, playbooks, templates, role definitions, evaluation guidance, reference frameworks, checklists, and case studies, use the full portal:

### 👉 https://fde.datacream.ai/

The portal is designed to help an FDE answer practical questions such as:

> What should I do next?

> What evidence do I need?

> Who should own this decision?

> Is this still a POC, or is it ready for engineering?

> What must be true before production?

> What can be simplified for a low-risk engagement?

> When should we stop instead of adding more AI?

---

## Project Status

The framework is under active development and field validation.

The current focus is not to create more process. It is to make the practice:

* easier to use in real engagements;
* more evidence-driven;
* easier to tailor by risk;
* more consistent across business, AI, and engineering;
* more useful for onboarding and coaching FDEs;
* more effective at preventing common delivery failures.

The framework does **not** currently provide an individual certification program.

---

## Design Philosophy

A Best Practice should not make an FDE slower.

It should help an FDE make **better decisions faster**.

The framework is successful only if it helps practitioners answer four questions clearly:

1. **What matters?**
2. **What should we do next?**
3. **What evidence is enough?**
4. **When should we stop, release, scale, hand over, or walk away?**

---

## Explore the Full FDE Best Practice

### https://fde.datacream.ai/

**1STEP FORWARD — Forward Deployed Engineering Framework**

From customer problem to sustainable production outcome.
