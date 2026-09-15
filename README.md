<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-FF6A00?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-2B2B2B?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software Systems & Automation" width="100%" />
</p>

## Full-Stack Developer building operational software

I turn **manual workflows, disconnected tools and fragile processes** into software that can actually be operated: web and desktop applications, APIs, automation, payment integrations, AI-assisted workflows and SaaS products.

My recent work is not centered on tutorial projects. It includes systems used for **lead attribution, multi-server browser automation, marketplace payments, AI voice operations and service benchmarking**.

**Current focus:** Python · TypeScript · APIs · Automation · Integrations · Business Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karlos-sanchez/)
[![Email](https://img.shields.io/badge/Email-Contact-2B2B2B?style=flat-square&logo=gmail&logoColor=white)](mailto:karloseduardosanchez@hotmail.com)
![Location](https://img.shields.io/badge/Brazil-Remote-2B2B2B?style=flat-square)

---

## Selected systems

| System | What it solves | Engineering focus | Stack |
|---|---|---|---|
| **[UTMZAP — Lead Tracking & CRM](./case-studies/lead-tracking-crm.md)** | Tracks campaign/UTM origin before a lead reaches WhatsApp and organizes the result in a mini-CRM. | Desktop + web architecture, public tracking endpoints, attribution data, auth/RLS, lead workflow. | Electron, React, TypeScript, Next.js, Supabase, PostgreSQL |
| **[AI Voice Operations — Sophie](./case-studies/ai-voice-operations.md)** | Handles inbound calls, qualifies leads, collects structured information and sends the result to the team on WhatsApp. | Voice AI orchestration, webhooks, structured outputs, operational handoff, VPS deployment. | Vapi, APIs, Webhooks, Docker, Linux/VPS |
| **[Distributed Browser Automation](./case-studies/distributed-browser-automation.md)** | Runs operational browser collection across remote agents with centralized control. | Concurrency, scheduling, session recovery, run state, logging and long-running reliability. | Python, Playwright, Django, PostgreSQL, Linux/Windows |
| **[Marketplace Payment Infrastructure](./case-studies/marketplace-payment-infrastructure.md)** | Implements multi-vendor payment splitting and financial workflow rules inside a WooCommerce marketplace. | Idempotency, duplicate protection, refunds/reversals, provider constraints and automated tests. | PHP, WordPress, WooCommerce, Dokan, Asaas API |
| **[SaaS Benchmarking Platform](./case-studies/saas-benchmarking-platform.md)** | Converts uploaded service data into persisted metrics, dashboards and company-scoped analysis. | Authentication, roles, trial rules, CSV processing, protected routes and persistence. | Next.js, TypeScript, Supabase, PostgreSQL |

> Commercial repositories remain private when they contain client-specific code or operational details. The case studies document the architecture, engineering decisions and responsibilities without exposing proprietary source code or sensitive data.

---

## The engineering surface I work on

<table>
<tr>
<td width="50%" valign="top">

### Backend & integrations

- REST APIs and webhook consumers
- External service integrations
- Authentication and permission boundaries
- Payment and financial workflows
- Server-side validation and data processing

</td>
<td width="50%" valign="top">

### Automation & operations

- Browser automation with Playwright/Selenium
- Scheduled and long-running jobs
- Remote agents and control-plane workflows
- Failure recovery and session handling
- Logs, alerts and operational visibility

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Product systems

- SaaS products and internal tools
- Mini-CRMs and admin surfaces
- Web + desktop hybrid applications
- Dashboards backed by real workflows
- File ingestion and metric pipelines

</td>
<td width="50%" valign="top">

### Applied AI

- Voice agents for inbound operations
- Lead qualification and structured capture
- AI-to-human handoff workflows
- WhatsApp delivery and operational summaries
- AI as part of a system, not the whole product

</td>
</tr>
</table>

---

## Production concerns I take seriously

The interesting part of software usually starts after the happy path works. Across recent projects, I have had to deal with:

- **Idempotency and duplicate protection** in payment/integration flows;
- **concurrency and minimum-interval rules** in distributed automation;
- **session and browser recovery** for long-running agents;
- **authentication, roles and row-level access boundaries** in SaaS applications;
- **provider/API limitations** that must be treated as part of the system contract;
- **deploy, logs and operational visibility** so failures can be diagnosed after delivery;
- **tests around financial and business rules** where a silent mistake is expensive.

That is the kind of work I want my GitHub to represent.

---

## Core stack

| Area | Technologies |
|---|---|
| **Backend** | Python, FastAPI, Flask, Django, PHP |
| **Frontend** | TypeScript, React, Next.js, Electron |
| **Data** | PostgreSQL, Supabase, SQL, ETL |
| **Automation** | Playwright, Selenium, scheduled jobs, browser workflows |
| **Infrastructure** | Docker, Linux/VPS, Vercel, Cloudflare |
| **Integrations** | REST APIs, Webhooks, WhatsApp, Vapi, payment providers |

---

## Public code

These repositories are intentionally public because they can be reviewed without exposing client code:

| Repository | What you can inspect |
|---|---|
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Async Telegram routing with Telethon, source/target rules, topics and scheduled workflows. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Small Flask integration layer that receives events and forwards structured Telegram notifications. |
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Scheduled data collection, Telegram delivery, DeFiLlama integration, alert rules and subscription flow. |

My earlier Data/BI repositories remain available as part of my background, but they are **not the center of my current positioning**.

---

## How I deliver

```text
Understand the operation
        ↓
Define the smallest reliable scope
        ↓
Build a functional version
        ↓
Validate with real usage
        ↓
Harden the failure paths
        ↓
Document and iterate
```

I prefer a working first version with clear boundaries over an oversized specification that never reaches production. From there, I improve the system based on real behavior, edge cases and operating feedback.

---

## What I am open to

- Freelance development projects
- Remote contracts
- Automation and integration work
- Full-stack product development
- Technical support for agencies/software teams that need implementation capacity

**Based in Brazil · available for remote work.**

---

## Contact

**LinkedIn:** [linkedin.com/in/karlos-sanchez](https://www.linkedin.com/in/karlos-sanchez/)  
**Email:** [karloseduardosanchez@hotmail.com](mailto:karloseduardosanchez@hotmail.com)

### Systems that work.
*From manual process to production-ready software.*
