<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-2B2B2B?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-FF6A00?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software Systems & Automation" width="100%" />
</p>

## Desenvolvedor Full-Stack construindo software operacional

Transformo **processos manuais, ferramentas desconectadas e operações frágeis** em software que pode ser realmente operado: aplicações web e desktop, APIs, automações, integrações financeiras, fluxos com IA e produtos SaaS.

Meus trabalhos recentes não são centrados em projetos de tutorial. Incluem sistemas usados em **atribuição de leads, automação distribuída entre servidores, pagamentos de marketplace, atendimento por voz com IA e benchmarking de atendimento**.

**Foco atual:** Python · TypeScript · APIs · Automação · Integrações · Sistemas de negócio

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karlos-sanchez/)
[![Email](https://img.shields.io/badge/Email-Contato-2B2B2B?style=flat-square&logo=gmail&logoColor=white)](mailto:karloseduardosanchez51@gmail.com)
![Local](https://img.shields.io/badge/Brasil-Remoto-2B2B2B?style=flat-square)

---

## Sistemas selecionados

| Sistema | O que resolve | Foco de engenharia | Stack |
|---|---|---|---|
| **[UTMZAP — Lead Tracking & CRM](./case-studies/lead-tracking-crm.md)** | Rastreia origem de campanha/UTM antes do lead chegar ao WhatsApp e organiza o resultado em um mini-CRM. | Arquitetura desktop + web, endpoints públicos de tracking, dados de atribuição, autenticação/RLS e fluxo de leads. | Electron, React, TypeScript, Next.js, Supabase, PostgreSQL |
| **[AI Voice Operations — Sophie](./case-studies/ai-voice-operations.md)** | Atende chamadas, qualifica leads, coleta dados estruturados e envia o resultado para a equipe pelo WhatsApp. | Orquestração de voz com IA, webhooks, outputs estruturados, handoff operacional e deploy em VPS. | Vapi, APIs, Webhooks, Docker, Linux/VPS |
| **[Distributed Browser Automation](./case-studies/distributed-browser-automation.md)** | Executa coleta operacional em navegador entre agentes remotos com controle centralizado. | Concorrência, agendamento, recuperação de sessão, estado de execução, logs e confiabilidade de longa duração. | Python, Playwright, Django, PostgreSQL, Linux/Windows |
| **[Marketplace Payment Infrastructure](./case-studies/marketplace-payment-infrastructure.md)** | Implementa split multi-vendedor e regras financeiras dentro de um marketplace WooCommerce. | Idempotência, proteção contra duplicidade, refunds/reversals, limitações do provedor e testes automatizados. | PHP, WordPress, WooCommerce, Dokan, API Asaas |
| **[SaaS Benchmarking Platform](./case-studies/saas-benchmarking-platform.md)** | Transforma arquivos de atendimento em métricas persistidas, dashboards e análise por empresa. | Autenticação, roles, trial, processamento de CSV, rotas protegidas e persistência. | Next.js, TypeScript, Supabase, PostgreSQL |

> Repositórios comerciais permanecem privados quando contêm código específico de cliente ou detalhes operacionais. Os case studies documentam arquitetura, decisões de engenharia e responsabilidades sem expor código proprietário ou dados sensíveis.

---

## Onde atuo tecnicamente

<table>
<tr>
<td width="50%" valign="top">

### Backend & integrações

- APIs REST e consumidores de webhook
- Integrações com serviços externos
- Autenticação e limites de permissão
- Pagamentos e fluxos financeiros
- Validação server-side e processamento de dados

</td>
<td width="50%" valign="top">

### Automação & operação

- Automação de navegador com Playwright/Selenium
- Jobs agendados e processos de longa duração
- Agentes remotos e fluxo de controle central
- Recuperação de falhas e sessão
- Logs, alertas e visibilidade operacional

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Sistemas de produto

- SaaS e ferramentas internas
- Mini-CRMs e áreas administrativas
- Aplicações híbridas web + desktop
- Dashboards conectados a fluxos reais
- Ingestão de arquivos e pipelines de métricas

</td>
<td width="50%" valign="top">

### IA aplicada

- Agentes de voz em operações receptivas
- Qualificação e coleta estruturada de leads
- Handoff entre IA e equipe humana
- Entrega de resumos via WhatsApp
- IA como parte do sistema, não como produto inteiro

</td>
</tr>
</table>

---

## Preocupações de produção que levo a sério

A parte interessante do software normalmente começa depois que o caminho feliz funciona. Nos projetos recentes, precisei lidar com:

- **idempotência e proteção contra duplicidade** em fluxos financeiros e integrações;
- **concorrência e intervalos mínimos de execução** em automação distribuída;
- **recuperação de navegador e sessão** em agentes de longa duração;
- **autenticação, roles e limites de acesso por linha/empresa** em aplicações SaaS;
- **limitações de provedores e APIs externas** tratadas como parte do contrato do sistema;
- **deploy, logs e visibilidade operacional** para que falhas possam ser diagnosticadas depois da entrega;
- **testes em regras financeiras e de negócio** onde um erro silencioso custa caro.

É esse tipo de trabalho que quero que meu GitHub represente.

---

## Stack principal

| Área | Tecnologias |
|---|---|
| **Backend** | Python, FastAPI, Flask, Django, PHP |
| **Frontend** | TypeScript, React, Next.js, Electron |
| **Dados** | PostgreSQL, Supabase, SQL, ETL |
| **Automação** | Playwright, Selenium, jobs agendados, fluxos de navegador |
| **Infraestrutura** | Docker, Linux/VPS, Vercel, Cloudflare |
| **Integrações** | APIs REST, Webhooks, WhatsApp, Vapi, provedores de pagamento |

---

## Código público

Estes repositórios são públicos porque podem ser avaliados sem expor código de cliente:

| Repositório | O que pode ser analisado |
|---|---|
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Roteamento assíncrono no Telegram com Telethon, regras de origem/destino, tópicos e fluxos agendados. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Pequena camada Flask que recebe eventos e encaminha notificações estruturadas para o Telegram. |
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Coleta agendada, entrega no Telegram, integração com DeFiLlama, regras de alerta e fluxo de assinatura. |

Meus repositórios anteriores de Dados/BI continuam disponíveis como parte da trajetória, mas **não são o centro do meu posicionamento atual**.

---

## Como entrego

```text
Entender a operação
        ↓
Definir o menor escopo confiável
        ↓
Construir uma versão funcional
        ↓
Validar com uso real
        ↓
Endurecer os caminhos de falha
        ↓
Documentar e evoluir
```

Prefiro uma primeira versão que funciona, com limites claros, a uma especificação gigante que nunca chega em produção. A partir daí, evoluo o sistema com base em comportamento real, casos de borda e feedback de operação.

---

## O que estou aberto a fazer

- Projetos freelance de desenvolvimento
- Contratos remotos
- Automação e integrações
- Desenvolvimento de produto full-stack
- Apoio técnico para agências/software houses que precisam de capacidade de implementação

**Baseado no Brasil · disponível para trabalho remoto.**

---

## Contato

**LinkedIn:** [linkedin.com/in/karlos-sanchez](https://www.linkedin.com/in/karlos-sanchez/)  
**Email:** [karloseduardosanchez51@gmail.com](mailto:karloseduardosanchez51@gmail.com)

### Systems that work.
*De processo manual a software pronto para produção.*
