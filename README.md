<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-FF6A00?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-2B2B2B?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software Systems & Automation" width="100%" />
</p>

<h2 align="center">Full-Stack Developer focused on automation, integrations and operational software</h2>

<p align="center">
  Python · TypeScript · APIs · Web/Desktop · Browser Automation · SaaS · Applied AI
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/Email-karloseduardosanchez%40hotmail.com-2B2B2B?style=flat-square" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Brazil-Remote-FF6A00?style=flat-square" alt="Brazil Remote" />
</p>

---

## The kind of work I do

Most of my projects start with an operation that already works **manually**, but badly: too many browser tabs, copy/paste, spreadsheets, WhatsApp messages, repeated checks, or two systems that simply do not talk to each other.

I map that flow, replace the fragile part with software, and then deal with the part that usually gets ignored in demos: retries, permissions, duplicate events, provider limitations, recovery, logs and the odd edge case that only appears after the system has been running for a while.

Recent work has included **lead attribution before WhatsApp**, **AI phone intake**, **multi-server browser automation**, **marketplace payment rules** and **SaaS back-office systems**.

> I am much more interested in software that removes work from an operation than in adding technology for its own sake.

---

## Selected work

### 01 — UTMZAP / Lead Tracking & CRM

<p align="center">
  <a href="./case-studies/lead-tracking-crm.md"><img src="./assets/case-utmzap.webp" width="88%" alt="UTMZAP — Lead Tracking & CRM" /></a>
</p>

An agency needed to know **where a lead came from before the conversation moved to WhatsApp**. I built a desktop + web flow that creates trackable campaign links, captures UTMs/ad identifiers, records click and lead events, and gives the team a small CRM to follow what happened next.

**What I owned:** architecture, Electron desktop app, public tracking flow, Supabase auth/RLS, data model, API endpoints, lead workflow and deployment documentation.

**Stack:** Electron · React · TypeScript · Next.js · Supabase · PostgreSQL · REST APIs

[Read the UTMZAP case study →](./case-studies/lead-tracking-crm.md)

---

### 02 — Sophie / AI Voice Operations

<p align="center">
  <a href="./case-studies/ai-voice-operations.md"><img src="./assets/case-ai-voice.webp" width="88%" alt="AI Voice Operations — Sophie" /></a>
</p>

For a U.S. cleaning business, I built an inbound voice assistant that answers calls, asks the questions the team actually needs, structures the answers and sends a call summary to WhatsApp after the conversation.

The interesting part was not just making the model speak. It was making the whole handoff useful: **prompt behavior, structured capture, webhooks, post-call processing, WhatsApp delivery, VPS/Docker infrastructure and failure handling**.

**Stack:** Vapi · Webhooks · APIs · Docker · Linux/VPS · WhatsApp

[Read the AI Voice case study →](./case-studies/ai-voice-operations.md)

---

## Other systems I have worked on

**Distributed Browser Automation** — remote agents collecting operational data across machines, with centralized run control, scheduling, minimum-interval rules, session recovery, logs and failure recovery.  
[Case study →](./case-studies/distributed-browser-automation.md)

**Marketplace Payment Infrastructure** — custom WooCommerce/Dokan/Asaas integration for multi-vendor splits, validations, idempotency, refunds/reversals and financial edge cases.  
[Case study →](./case-studies/marketplace-payment-infrastructure.md)

**SaaS Benchmarking Platform** — authentication, company/user access, CSV ingestion, persisted metrics, dashboards, trial rules and protected admin flows.  
[Case study →](./case-studies/saas-benchmarking-platform.md)

---

## Tools I use often

<p align="center">
  <img src="https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-111111?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/TypeScript-111111?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-111111?style=for-the-badge&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-111111?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-111111?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Docker-111111?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Playwright-111111?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
</p>

I do not pick a stack because it looks good on a diagram. I usually pick the smallest set of tools that makes the system easier to ship, operate and change later.

---

## Things I care about once the happy path works

- **Idempotency and duplicate protection** when money or external events are involved.
- **Recovery** for long-running browser sessions and remote agents.
- **Permissions and data boundaries** in multi-user SaaS products.
- **Provider limitations** as part of the design, not as an afterthought.
- **Logs and operational visibility** so a failure can actually be diagnosed.
- **Small first versions** that can be used before the project turns into a six-month specification.

<details>
<summary><strong>More technical detail</strong></summary>
<br />

### Automation & operations
- Playwright/Selenium browser workflows
- Scheduling, run-state tracking and concurrency control
- Session/browser recovery
- Remote agents and centralized control
- VPS/Linux deployment and Dockerized services

### APIs & integrations
- REST APIs and webhook consumers
- WhatsApp and voice-agent handoffs
- Payment-provider integrations
- Server-side validation and redirect safety
- External API failure handling

### Product & data
- Authentication and role-aware access
- Supabase RLS / company-scoped data
- Mini-CRMs and admin surfaces
- CSV/file ingestion and persisted metrics
- Web + desktop hybrid systems

</details>

<details>
<summary><strong>Public repositories</strong></summary>
<br />

| Repository | What you can inspect |
|---|---|
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Scheduled data collection, DeFiLlama integration, Telegram delivery, alert rules and subscription flow. |
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Async Telegram routing with Telethon, source/target rules, topics and scheduled workflows. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Flask integration layer receiving events and forwarding structured Telegram notifications. |

Commercial/client repositories stay private when they contain proprietary code or sensitive operational details.

</details>

---

## If this sounds familiar

If your workflow is currently something like **“open a few tabs, copy this, paste it there, send it on WhatsApp and remember to check again later”**, that is exactly the kind of problem I like turning into software.

**Open to:** freelance projects, remote contracts, automation/integration work and full-stack product development.

<p align="center">
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/CONTACT%20ME-FF6A00?style=for-the-badge" alt="Contact me" /></a>
</p>

<p align="center"><strong>Systems that work.</strong><br /><em>From manual process to production-ready software.</em></p>