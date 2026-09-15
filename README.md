<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-FF6A00?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-2B2B2B?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software for real operations" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2200&pause=750&color=FF6A00&center=true&vCenter=true&repeat=true&width=900&height=42&lines=%3E+tracing+a+lost+UTM+before+WhatsApp+opens...;%3E+recovering+a+browser+worker+after+failure...;%3E+making+payment+webhooks+idempotent...;%3E+turning+a+manual+handoff+into+software..." alt="Animated terminal showing real engineering problems" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/Email-karloseduardosanchez%40hotmail.com-2B2B2B?style=flat-square" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Bauru%2C%20Brazil-Remote-FF6A00?style=flat-square" alt="Bauru Brazil Remote" />
</p>

<br />

## I like the part before the software looks obvious

A lot of the work I take on starts as a messy routine instead of a clean specification: someone opens three systems, copies a value, checks a spreadsheet, sends a WhatsApp message and remembers to come back later.

That is usually the useful part to automate.

I build **web and desktop systems, APIs, browser automations, payment flows and AI-assisted operations**. The stack changes from project to project; the goal does not: fewer fragile handoffs, less repetitive work and something people can actually operate every day.

---

## Selected work

### UTMZAP — keeping attribution alive when the lead moves to WhatsApp

<p align="center">
  <a href="./case-studies/lead-tracking-crm.md"><img src="./assets/case-utmzap.webp" width="96%" alt="UTMZAP — Lead Tracking and CRM" /></a>
</p>

An agency needed campaign context to survive the jump into WhatsApp. I built the flow around that gap: trackable links, UTM/ad capture, click and lead events, a client portal and a mini-CRM for the team to work from afterwards.

`Electron` `React` `TypeScript` `Next.js` `Supabase` `PostgreSQL`

**[Open the case study →](./case-studies/lead-tracking-crm.md)**

<br />

### Sophie — the phone rings, the team receives the useful part

<p align="center">
  <a href="./case-studies/ai-voice-operations.md"><img src="./assets/case-ai-voice.webp" width="96%" alt="Sophie — AI Voice Operations" /></a>
</p>

For a U.S. cleaning business, I built an inbound voice assistant that qualifies the caller, captures the information the operation needs and sends a structured WhatsApp summary to the team after the call.

The interesting work is around the conversation: structured capture, webhooks, post-call processing, delivery and the infrastructure keeping the handoff alive.

`Vapi` `Webhooks` `APIs` `Docker` `Linux/VPS` `WhatsApp`

**[Open the case study →](./case-studies/ai-voice-operations.md)**

---

## Not every useful system has a pretty screenshot

| | System | The part that mattered |
|---|---|---|
| ⚙️ | **[Distributed Browser Automation](./case-studies/distributed-browser-automation.md)** | Remote agents, scheduled runs, concurrency rules, session recovery and centralized control for long-running browser work. |
| ↔️ | **[Marketplace Payment Infrastructure](./case-studies/marketplace-payment-infrastructure.md)** | WooCommerce/Dokan/Asaas split rules, duplicate protection, refunds/reversals and financial edge cases. |
| ◫ | **[SaaS Benchmarking Platform](./case-studies/saas-benchmarking-platform.md)** | Authentication, company/user boundaries, CSV ingestion, persisted metrics, dashboards and protected admin flows. |

---

## The kind of message that usually becomes a project

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=2600&pause=1000&color=D6D0C8&center=true&vCenter=true&repeat=true&width=900&height=42&lines=%22We+do+this+manually+every+day.%22;%22These+two+systems+do+not+talk+to+each+other.%22;%22The+automation+works...+until+it+gets+stuck.%22;%22The+lead+arrived%2C+but+we+lost+where+it+came+from.%22" alt="Animated examples of problems that become software projects" />
</p>

<details>
<summary><strong>Under the hood — tools, public code and technical depth</strong></summary>
<br />

**Main tools:** Python, FastAPI, Flask, Django, TypeScript, React, Next.js, Electron, PostgreSQL, Supabase, Docker, Playwright/Selenium and Linux/VPS.

**Things I regularly care about:** recovery for long-running browser sessions, retries and idempotency, authentication and data boundaries, webhook failure handling, logs, payment edge cases and keeping the first useful version small enough to actually ship.

### Public code

| Repository | What you can inspect |
|---|---|
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Scheduled data collection, DeFiLlama integration, Telegram delivery, alert rules and subscription flow. |
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Async Telegram routing with Telethon, source/target rules, topics and scheduled workflows. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Flask integration layer receiving events and forwarding structured Telegram notifications. |

Commercial/client repositories stay private when they contain proprietary code or sensitive operational details.

</details>

<br />

<p align="center"><sub>the orange pixel is eating my contribution graph ↓</sub></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KarlosSanchez18/KarlosSanchez18/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KarlosSanchez18/KarlosSanchez18/output/github-snake.svg" />
  <img alt="Animated orange snake moving through Karlos Sanchez's contribution graph" src="https://raw.githubusercontent.com/KarlosSanchez18/KarlosSanchez18/output/github-snake-dark.svg" width="100%" />
</picture>

---

<h2 align="center">Have a process that should not still be manual?</h2>

<p align="center">Send me the messy version. We can figure out what is actually worth turning into software.</p>

<p align="center">
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/EMAIL%20ME-FF6A00?style=for-the-badge" alt="Email me" /></a>
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LINKEDIN-242424?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center"><sub>Systems that work. Not just screenshots that look finished.</sub></p>