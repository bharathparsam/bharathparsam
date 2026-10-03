# Hey, I'm Bharath 👋

### I like problems that don't arrive as Jira tickets.

They usually sound more like:

> “Why are pickups being missed?”  
> “Why did sales suddenly drop?”  
> “Why are our teams still doing this manually?”  
> “Can AI actually help here — or are we forcing it?”

That's the kind of work I enjoy.

I'm a **Forward Deployed Engineering-focused Technical Lead** with **8+ years of experience** building software at the intersection of **business problems, engineering, enterprise systems, and AI**.

My work usually starts before the solution is obvious:

**understand the problem → talk to users → inspect the system → prototype → validate → build → ship → observe → improve**

Currently, I'm a **Senior Consultant / Managed Service Engineer III at Deloitte Consulting India (USI)** and pursuing the **Advanced Certification in Forward Deployed Engineering from IIT Roorkee & FDE Academy**.

---

## What I actually do

I enjoy working in the space between:

```text
Business Problem
      ↓
Problem Discovery
      ↓
System / Data Understanding
      ↓
Solution Design
      ↓
Rapid Prototype
      ↓
Production Engineering
      ↓
Measure → Learn → Improve
```

Sometimes the answer is **AI**.

Sometimes it is a **deterministic workflow**.

Sometimes it is simply removing a process that should never have existed in the first place.

The goal isn't to add more technology.

**The goal is to make the system work better.**

---

## A few problems I've worked on

### 🚛 When operations break, routes shouldn't

A recurring missed-pickup problem was being caused by driver cancellations and operational changes.

I proposed and designed a **smart routing workflow** that could:

- dynamically assign drivers
- automatically reschedule affected pickups
- identify the next feasible pickup slot
- introduce AI-assisted recommendations when disruptions occur

The interesting part wasn't the routing logic itself.

It was designing a system that could respond when **real-world operations stopped following the happy path**.

---

### 🎯 Which lead should a team work on first?

Support and sales teams had plenty of leads.

The harder problem was knowing **which ones deserved attention first**.

I worked on an AI-assisted prioritisation approach combining signals from:

- Salesforce order history
- LogRocket behaviour
- Adobe Analytics
- rule-based scoring
- LLM-generated summaries

Instead of asking someone to manually inspect multiple systems, the system brings the useful context closer to the decision.

---

### 🧠 Making enterprise knowledge actually useful

Built and iterated on a **RAG-based support assistant using Amazon Bedrock and enterprise knowledge**.

The focus wasn't simply:

> “Can the model answer a question?”

The real questions were:

- Did we retrieve the right information?
- Can users trust the answer?
- What happens when retrieval fails?
- How do we use feedback to improve the system?
- When should the assistant say *I don't know*?

Iterations based on user feedback helped reduce dependency on support agents by approximately **25–30%**.

---

### ⚙️ Automating the boring parts

Business pricing data required significant manual transformation before it could be loaded into Salesforce.

I built a **Python-based transformation workflow** that converts raw business pricing data into Salesforce-ready datasets and automates ingestion through Bulk APIs.

**Result:** around **70% improvement in processing efficiency**.

This is one of the things I enjoy most:

> finding repetitive human work hiding inside a technical process and eliminating it.

---

## Selected builds

### 🍕 SliceMatic — AI Operations Platform

An experiment around a simple question:

> What if a small business had an AI COO looking at operations every day?

Built a **0→1 order and operations platform** replacing workflows spread across Google Forms and spreadsheets.

The AI layer analyses daily operations to:

- surface important patterns
- highlight areas requiring attention
- summarise operational performance
- help owners understand what happened without digging through raw data

`AI + Operations + Product Engineering`

---

### 🎙 Context-Aware Meeting Intelligence

Most meeting assistants understand **one meeting**.

I wanted to explore what happens when the system understands the **relationship between meetings**.

Built a local-first meeting assistant that:

- transcribes meetings
- generates structured summaries
- remembers recurring context
- tracks unresolved topics
- connects discussions across sessions
- generates relevant follow-ups

The interesting problem here is not transcription.

It's **context continuity**.

`Local AI + Memory + Retrieval + Structured Outputs`

---

## Enterprise engineering

Over the years I've worked across large enterprise systems involving:

**Commerce · Payments · Authentication · Customer Verification · APIs · Automation · Production Support**

Some of the platforms I've integrated or engineered around include:

`Salesforce B2B Commerce`  
`CyberSource`  
`Paymentus`  
`Okta`  
`Azure AD B2C`  
`SheerID`

I also worked on transitioning enterprise commerce toward a **headless architecture**, connecting React applications with Salesforce APIs while progressively modernising legacy Backbone.js and Handlebars.js components.

---

## My engineering toolbox

### Core

```text
Python        JavaScript        Node.js
FastAPI       React             REST APIs
```

### AI Engineering

```text
Amazon Bedrock
RAG
LLM Orchestration
Tool Calling
Structured Outputs
Agentic Workflows
Human-in-the-Loop Systems
```

### Cloud & Infrastructure

```text
AWS
├── ECS
├── ECR
├── EC2
├── Lambda
├── CloudWatch
└── API Gateway

Azure DevOps
GitHub Actions
CI/CD
Git
```

### Enterprise & Automation

```text
Salesforce B2B Commerce
Salesforce Bulk APIs
Workflow Automation
API Integrations
Data Transformation
n8n
```

### Frontend

```text
React
JavaScript ES6+
HTML5
CSS3
Tailwind CSS
Backbone.js
Handlebars.js
```

---

## How I think about AI

I'm interested in AI systems that can survive outside demos.

That means thinking beyond prompts and models:

```text
                 ┌─────────────────┐
                 │   User Problem  │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  Context / Data │
                 └────────┬────────┘
                          │
                          ▼
              ┌───────────────────────┐
              │ Workflow / Reasoning  │
              └───────────┬───────────┘
                          │
             ┌────────────┼────────────┐
             ▼            ▼            ▼
          Tools       Retrieval      APIs
             │            │            │
             └────────────┼────────────┘
                          ▼
                 ┌─────────────────┐
                 │    Guardrails   │
                 └────────┬────────┘
                          ▼
                 ┌─────────────────┐
                 │ Human / System  │
                 │    Feedback     │
                 └────────┬────────┘
                          │
                          ▼
                     Improve
```

I'm especially interested in:

- **Forward Deployed Engineering**
- production-grade AI systems
- agentic workflows
- enterprise RAG
- evaluation and observability
- human-in-the-loop systems
- AI + operational workflows
- systems that combine deterministic software with probabilistic models

---

## Experience

### Deloitte Consulting India Private Limited · USI

**Managed Service Engineer III / Senior Consultant**  
`Feb 2021 → Present`

**Client:** WM  
**Industry:** Energy, Resources & Industrials · United States

My role gradually evolved from implementing features to working much closer to:

- product owners
- business stakeholders
- architects
- operational teams
- engineering teams

Today, a large part of my work involves **understanding why a problem exists before deciding what should be built**.

Along the way I've worked on:

- AI-assisted routing workflows
- lead prioritisation
- enterprise RAG
- sales process automation
- pricing transformation
- payment integrations
- identity systems
- headless commerce
- production incident ownership
- architecture and rapid POCs

---

### Wipro Limited

**Software Engineer**  
`Jul 2018 → Jan 2021`

This is where I built much of my engineering foundation.

I worked on:

- production web applications
- Vue / JavaScript-based frontend development
- Azure AD B2C authentication
- AMCharts dashboards
- Azure DevOps CI/CD pipelines
- production troubleshooting
- Agile delivery

It taught me something I still value today:

**shipping software is very different from writing software.**

---

## Currently learning deeper

```python
current_focus = [
    "Forward Deployed Engineering",
    "Production AI systems",
    "Agent architecture",
    "RAG & retrieval",
    "Evaluation",
    "Observability",
    "AI system design",
    "Python backend engineering"
]
```

I'm deliberately moving deeper into roles where engineering sits closer to the customer and the actual business problem.

That is the direction I'm building toward:

# Forward Deployed Engineer

---

## Certifications & learning

- 🎓 **Advanced Certification in Forward Deployed Engineering**  
  IIT Roorkee & FDE Academy — *In Progress*

- 🏭 **Industry Proficiency Foundation**  
  Energy, Resources & Industrials

- ☁️ **Microsoft Certified: DevOps Engineer Expert**

- ☁️ **Salesforce Certified JavaScript Developer**

- 🤖 **Claude Certified Developer Foundations**

---

## Education

**Master of Technology — Software Engineering (Integrated)**  
Vellore Institute of Technology, Vellore

---

## A principle I try to follow

```text
Don't start with:
"What can we build with AI?"

Start with:
"What is making this person's job harder than it needs to be?"
```

Then decide whether the answer is:

**AI, software, automation, better data, better UX — or simply a simpler process.**

---

## What you'll find in my GitHub

This GitHub is where I'm documenting that journey.

Expect repositories around:

```text
AI Engineering
├── RAG
├── Agents
├── Tool Calling
├── Evaluations
└── Production AI Patterns

Forward Deployed Engineering
├── Problem Discovery
├── Rapid Prototyping
├── Business → Technical Translation
└── Real-world case studies

Engineering
├── Python
├── FastAPI
├── React
├── Node.js
└── System Design

Experiments
└── Ideas that may or may not work :)
```

Not everything here will be perfect.

Some repositories are experiments.

Some are learning notes.

Some are things I built because I couldn't stop thinking:

> **“There has to be a better way to do this.”**

---

## Let's connect

I'm always interested in conversations around:

**Forward Deployed Engineering · AI Engineering · Enterprise AI · Product Engineering · Agentic Systems · RAG · Interesting business problems**

If you're building something difficult, operating at the intersection of **customers + engineering + AI**, or just want to exchange ideas—

**I'd probably enjoy that conversation.**

---

<p align="center">
  <b>Understand the problem deeply. Build the simplest thing that actually changes the outcome.</b>
</p>
