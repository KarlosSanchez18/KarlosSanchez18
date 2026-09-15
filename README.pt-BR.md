<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-2B2B2B?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-FF6A00?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software Systems & Automation" width="100%" />
</p>

<h2 align="center">Desenvolvedor Full-Stack focado em automação, integrações e software operacional</h2>

<p align="center">
  Python · TypeScript · APIs · Web/Desktop · Automação de navegador · SaaS · IA aplicada
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/Email-karloseduardosanchez%40hotmail.com-2B2B2B?style=flat-square" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Brasil-Remoto-FF6A00?style=flat-square" alt="Brasil Remoto" />
</p>

---

## O tipo de problema que eu gosto de resolver

Boa parte dos meus projetos começa com uma operação que já funciona **manualmente**, mas mal: abas demais abertas, copiar e colar, planilhas, mensagens no WhatsApp, verificações repetitivas ou dois sistemas que simplesmente não conversam entre si.

Eu mapeio esse fluxo, substituo a parte frágil por software e depois cuido do que normalmente some das demos: tentativas novamente, permissões, eventos duplicados, limitações de provedores, recuperação, logs e aqueles casos estranhos que só aparecem depois que o sistema fica rodando por um tempo.

Nos trabalhos recentes, isso virou **rastreamento de origem antes do WhatsApp**, **atendimento de voz com IA**, **automação distribuída entre servidores**, **regras de pagamento em marketplace** e **sistemas internos SaaS**.

> Tenho muito mais interesse em software que tira trabalho de uma operação do que em colocar tecnologia só porque ela parece interessante.

---

## Projetos selecionados

### 01 — UTMZAP / Lead Tracking & CRM

<p align="center">
  <a href="./case-studies/lead-tracking-crm.md"><img src="./assets/case-utmzap.webp" width="88%" alt="UTMZAP — Lead Tracking & CRM" /></a>
</p>

Uma agência precisava saber **de onde o lead veio antes da conversa ir para o WhatsApp**. Eu construí um fluxo desktop + web que cria links rastreáveis de campanha, captura UTMs e identificadores de anúncio, registra eventos de clique/lead e entrega para a equipe um mini-CRM para acompanhar o que aconteceu depois.

**O que ficou comigo:** arquitetura, app desktop em Electron, fluxo público de tracking, autenticação/RLS no Supabase, modelo de dados, endpoints da API, fluxo de leads e documentação de deploy.

**Stack:** Electron · React · TypeScript · Next.js · Supabase · PostgreSQL · APIs REST

[Ver o case do UTMZAP →](./case-studies/lead-tracking-crm.md)

---

### 02 — Sophie / AI Voice Operations

<p align="center">
  <a href="./case-studies/ai-voice-operations.md"><img src="./assets/case-ai-voice.webp" width="88%" alt="AI Voice Operations — Sophie" /></a>
</p>

Para uma empresa de limpeza nos EUA, desenvolvi uma assistente de voz receptiva que atende chamadas, faz as perguntas que a equipe realmente precisa, organiza as respostas e envia um resumo da ligação para o WhatsApp depois da conversa.

A parte interessante não foi só fazer o modelo falar. Foi fazer o handoff inteiro funcionar: **comportamento do prompt, captura estruturada, webhooks, processamento pós-ligação, entrega no WhatsApp, infraestrutura em VPS/Docker e tratamento de falhas**.

**Stack:** Vapi · Webhooks · APIs · Docker · Linux/VPS · WhatsApp

[Ver o case de AI Voice →](./case-studies/ai-voice-operations.md)

---

## Outros sistemas em que trabalhei

**Distributed Browser Automation** — agentes remotos coletando dados operacionais em máquinas diferentes, com controle centralizado de runs, agendamento, regras de intervalo mínimo, recuperação de sessão, logs e tratamento de falhas.  
[Ver case →](./case-studies/distributed-browser-automation.md)

**Marketplace Payment Infrastructure** — integração customizada WooCommerce/Dokan/Asaas para split multi-vendedor, validações, idempotência, refunds/reversals e regras financeiras fora do caminho feliz.  
[Ver case →](./case-studies/marketplace-payment-infrastructure.md)

**SaaS Benchmarking Platform** — autenticação, acesso por empresa/usuário, ingestão de CSV, métricas persistidas, dashboards, regras de trial e área administrativa protegida.  
[Ver case →](./case-studies/saas-benchmarking-platform.md)

---

## Ferramentas que uso com frequência

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

Não escolho stack porque fica bonita no diagrama. Normalmente escolho o menor conjunto de ferramentas que deixe o sistema mais simples de entregar, operar e alterar depois.

---

## Coisas que passam a importar quando o caminho feliz já funciona

- **Idempotência e proteção contra duplicidade** quando existe dinheiro ou evento externo envolvido.
- **Recuperação** em sessões longas de navegador e agentes remotos.
- **Permissões e limites de dados** em produtos SaaS com múltiplos usuários.
- **Limitações de provedores** tratadas como parte do desenho do sistema, e não como surpresa no final.
- **Logs e visibilidade operacional** para que uma falha consiga ser diagnosticada de verdade.
- **Primeiras versões pequenas** que possam ser usadas antes do projeto virar uma especificação de seis meses.

<details>
<summary><strong>Mais detalhes técnicos</strong></summary>
<br />

### Automação & operação
- Fluxos de navegador com Playwright/Selenium
- Agendamento, controle de estado e concorrência
- Recuperação de navegador/sessão
- Agentes remotos e controle centralizado
- Deploy em VPS/Linux e serviços com Docker

### APIs & integrações
- APIs REST e consumidores de webhook
- Handoffs com WhatsApp e agentes de voz
- Integrações com provedores de pagamento
- Validação server-side e segurança de redirects
- Tratamento de falhas em APIs externas

### Produto & dados
- Autenticação e acesso por função
- Supabase RLS / dados isolados por empresa
- Mini-CRMs e áreas administrativas
- Ingestão de CSV/arquivos e métricas persistidas
- Sistemas híbridos web + desktop

</details>

<details>
<summary><strong>Repositórios públicos</strong></summary>
<br />

| Repositório | O que pode ser analisado |
|---|---|
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Coleta agendada, integração DeFiLlama, entrega via Telegram, regras de alerta e fluxo de assinatura. |
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Roteamento assíncrono no Telegram com Telethon, regras de origem/destino, tópicos e fluxos agendados. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Camada Flask que recebe eventos e encaminha notificações estruturadas para o Telegram. |

Repositórios comerciais/de clientes permanecem privados quando contêm código proprietário ou detalhes operacionais sensíveis.

</details>

---

## Se isso parece familiar

Se hoje o processo é algo como **“abre algumas abas, copia daqui, cola ali, manda no WhatsApp e lembra de conferir de novo depois”**, esse é exatamente o tipo de problema que eu gosto de transformar em software.

**Disponível para:** projetos freelance, contratos remotos, automação/integrações e desenvolvimento Full-Stack de produto.

<p align="center">
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/FALE%20COMIGO-FF6A00?style=for-the-badge" alt="Fale comigo" /></a>
</p>

<p align="center"><strong>Systems that work.</strong><br /><em>De processo manual a software pronto para produção.</em></p>