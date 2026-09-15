<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-2B2B2B?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-FF6A00?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software para operações reais" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2200&pause=750&color=FF6A00&center=true&vCenter=true&repeat=true&width=900&height=42&lines=%3E+rastreando+uma+UTM+antes+do+WhatsApp+abrir...;%3E+recuperando+um+worker+de+navegador+ap%C3%B3s+falha...;%3E+deixando+webhooks+de+pagamento+idempotentes...;%3E+transformando+um+handoff+manual+em+software..." alt="Terminal animado mostrando problemas reais de engenharia" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/Email-karloseduardosanchez%40hotmail.com-2B2B2B?style=flat-square" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Bauru%2C%20Brasil-Remoto-FF6A00?style=flat-square" alt="Bauru Brasil Remoto" />
</p>

<br />

## Eu gosto da parte antes de o software parecer óbvio

Boa parte do trabalho que pego começa como uma rotina bagunçada, não como uma especificação perfeita: alguém abre três sistemas, copia um valor, confere uma planilha, manda uma mensagem no WhatsApp e precisa lembrar de voltar depois.

Normalmente é aí que existe algo útil para automatizar.

Construo **sistemas web e desktop, APIs, automações de navegador, fluxos de pagamento e operações assistidas por IA**. A stack muda de projeto para projeto; o objetivo não: menos handoffs frágeis, menos trabalho repetitivo e algo que realmente possa ser operado todos os dias.

---

## Trabalhos selecionados

### UTMZAP — mantendo a atribuição viva quando o lead vai para o WhatsApp

<p align="center">
  <a href="./case-studies/lead-tracking-crm.md"><img src="./assets/case-utmzap.webp" width="96%" alt="UTMZAP — Lead Tracking e CRM" /></a>
</p>

Uma agência precisava que o contexto da campanha sobrevivesse à ida para o WhatsApp. Construí o fluxo em volta desse ponto: links rastreáveis, captura de UTM/identificadores de anúncio, eventos de clique e lead, portal do cliente e um mini-CRM para a equipe trabalhar depois.

`Electron` `React` `TypeScript` `Next.js` `Supabase` `PostgreSQL`

**[Abrir o case →](./case-studies/lead-tracking-crm.md)**

<br />

### Sophie — o telefone toca, a equipe recebe a parte útil

<p align="center">
  <a href="./case-studies/ai-voice-operations.md"><img src="./assets/case-ai-voice.webp" width="96%" alt="Sophie — AI Voice Operations" /></a>
</p>

Para uma empresa de limpeza nos EUA, desenvolvi uma assistente de voz receptiva que qualifica o cliente, captura as informações que a operação precisa e envia um resumo estruturado no WhatsApp da equipe depois da ligação.

A parte interessante está em volta da conversa: captura estruturada, webhooks, processamento pós-ligação, entrega e a infraestrutura mantendo o handoff funcionando.

`Vapi` `Webhooks` `APIs` `Docker` `Linux/VPS` `WhatsApp`

**[Abrir o case →](./case-studies/ai-voice-operations.md)**

---

## Nem todo sistema útil rende um screenshot bonito

| | Sistema | A parte que realmente importava |
|---|---|---|
| ⚙️ | **[Distributed Browser Automation](./case-studies/distributed-browser-automation.md)** | Agentes remotos, execuções agendadas, regras de concorrência, recuperação de sessão e controle central para automações longas. |
| ↔️ | **[Marketplace Payment Infrastructure](./case-studies/marketplace-payment-infrastructure.md)** | Split WooCommerce/Dokan/Asaas, proteção contra duplicidade, refunds/reversals e casos financeiros chatos. |
| ◫ | **[SaaS Benchmarking Platform](./case-studies/saas-benchmarking-platform.md)** | Autenticação, limites por empresa/usuário, ingestão de CSV, métricas persistidas, dashboards e fluxos administrativos protegidos. |

---

## O tipo de mensagem que costuma virar projeto

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=2600&pause=1000&color=D6D0C8&center=true&vCenter=true&repeat=true&width=900&height=42&lines=%22A+gente+faz+isso+manualmente+todo+dia.%22;%22Esses+dois+sistemas+n%C3%A3o+conversam.%22;%22A+automa%C3%A7%C3%A3o+funciona...+at%C3%A9+travar.%22;%22O+lead+chegou%2C+mas+a+gente+perdeu+de+onde+veio.%22" alt="Exemplos animados de problemas que viram projetos de software" />
</p>

<details>
<summary><strong>Por baixo do capô — ferramentas, código público e parte técnica</strong></summary>
<br />

**Ferramentas principais:** Python, FastAPI, Flask, Django, TypeScript, React, Next.js, Electron, PostgreSQL, Supabase, Docker, Playwright/Selenium e Linux/VPS.

**Coisas com que lido com frequência:** recuperação de sessões longas de navegador, retries e idempotência, autenticação e limites de dados, falhas em webhooks/APIs, logs, casos de pagamento e manter a primeira versão útil pequena o bastante para realmente chegar em produção.

### Código público

| Repositório | O que pode ser analisado |
|---|---|
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Coleta agendada, integração DeFiLlama, entrega via Telegram, regras de alerta e fluxo de assinatura. |
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Roteamento assíncrono no Telegram com Telethon, regras de origem/destino, tópicos e fluxos agendados. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Camada Flask que recebe eventos e encaminha notificações estruturadas para o Telegram. |

Repositórios comerciais/de clientes continuam privados quando possuem código proprietário ou detalhes operacionais sensíveis.

</details>

<br />

<p align="center"><sub>o pixel laranja está comendo meu gráfico de contribuições ↓</sub></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KarlosSanchez18/KarlosSanchez18/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KarlosSanchez18/KarlosSanchez18/output/github-snake.svg" />
  <img alt="Snake laranja animada passando pelo gráfico de contribuições de Karlos Sanchez" src="https://raw.githubusercontent.com/KarlosSanchez18/KarlosSanchez18/output/github-snake-dark.svg" width="100%" />
</picture>

---

<h2 align="center">Tem um processo que já não deveria ser manual?</h2>

<p align="center">Me manda a versão bagunçada. A gente descobre o que realmente vale transformar em software.</p>

<p align="center">
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/ME%20MANDA%20UM%20EMAIL-FF6A00?style=for-the-badge" alt="Me manda um email" /></a>
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LINKEDIN-242424?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center"><sub>Systems that work. Não só screenshots que parecem prontos.</sub></p>