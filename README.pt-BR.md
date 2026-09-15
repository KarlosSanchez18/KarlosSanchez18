<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-2B2B2B?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-FF6A00?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software Systems & Automation" width="100%" />
</p>

## Desenvolvedor Full-Stack focado em automação, integrações e sistemas de negócio

Construo software em cima de **problemas operacionais reais**: processos manuais, ferramentas desconectadas, fluxos frágeis e sistemas que precisam continuar funcionando depois da primeira demo.

Costumo assumir projetos desde a **definição técnica e modelagem de dados até implementação, deploy, validação e evolução**. Meus trabalhos recentes incluem atribuição de leads, automação distribuída entre servidores, pagamentos de marketplace, atendimento por voz com IA e benchmarking SaaS.

**Foco atual:** Python · TypeScript · APIs · Automação · Integrações · Sistemas de negócio

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karlos-sanchez/)
[![Email](https://img.shields.io/badge/Email-Contato-2B2B2B?style=flat-square)](mailto:karloseduardosanchez@hotmail.com)
![Local](https://img.shields.io/badge/Brasil-Remoto-2B2B2B?style=flat-square)

---

## Provas de trabalho

Estes são os projetos que melhor representam como eu trabalho hoje.

| Sistema | Entrega / validação | Trabalho de engenharia | Stack |
|---|---|---|---|
| **[UTMZAP — Lead Tracking & CRM](./case-studies/lead-tracking-crm.md)** | MVP funcional entregue | Rotas públicas de tracking, captura de UTM/`gclid`/`fbclid`, validação de redirecionamento, persistência de cliques/leads, mini-CRM, Supabase Auth + RLS | Electron, React, TypeScript, Next.js, Supabase, PostgreSQL |
| **[AI Voice Operations — Sophie](./case-studies/ai-voice-operations.md)** | Primeira versão funcional validada com cenários realistas de chamada | Fluxo de voz receptivo, qualificação, outputs estruturados, webhook pós-ligação, handoff no WhatsApp e camada de integração em Docker/VPS | Vapi, Webhooks, APIs, Docker, Linux/VPS, WhatsApp |
| **[Distributed Browser Automation](./case-studies/distributed-browser-automation.md)** | Execuções remotas completas validadas | Agentes Windows remotos, servidor Ubuntu de coordenação, regras de concorrência, agendamento, recuperação de sessão, estado de execução, logs e persistência PostgreSQL | Python, Playwright, Django, PostgreSQL, Linux/Windows |
| **[Marketplace Payment Infrastructure](./case-studies/marketplace-payment-infrastructure.md)** | Fluxo de split e núcleo do plugin implementados e testados | Regras financeiras multi-vendedor, validação, idempotência, proteção contra duplicidade, refunds/reversals, compatibilidade HPOS e testes automatizados | PHP, WordPress, WooCommerce, Dokan, API Asaas |
| **[SaaS Benchmarking Platform](./case-studies/saas-benchmarking-platform.md)** | Primeira fase do produto entregue | Autenticação, escopo empresa/usuário, roles, trial de 7 dias, ingestão de CSV, persistência de métricas, dashboards e rotas administrativas protegidas | Next.js, TypeScript, Supabase, PostgreSQL |

> Repositórios de clientes e projetos comerciais permanecem privados quando contêm código proprietário, credenciais, regras de negócio ou detalhes operacionais. Os case studies documentam arquitetura, responsabilidades e decisões técnicas sem expor material sensível.

---

## Profundidade de engenharia

<table>
<tr>
<td width="50%" valign="top">

### Confiabilidade & automação

- Recuperação de navegador/sessão em agentes de longa duração
- Regras de concorrência e intervalo mínimo
- Execuções agendadas e controle de estado
- Logs e visibilidade operacional
- Agentes remotos com controle centralizado

</td>
<td width="50%" valign="top">

### APIs & integrações

- APIs REST e consumidores de webhook
- Handoff entre WhatsApp e agentes de voz
- Tratamento de limitações e falhas de provedores
- Validação server-side e segurança de redirecionamentos
- Integrações financeiras e de marketplace

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Produto & limites de dados

- Autenticação e acesso baseado em roles
- Supabase RLS / dados isolados por empresa
- Mini-CRMs e áreas administrativas
- Ingestão de CSV/arquivos e métricas persistidas
- Sistemas híbridos web + desktop

</td>
<td width="50%" valign="top">

### Correção financeira

- Processamento idempotente
- Proteção contra processamento duplicado
- Fluxos de refund/reversal
- Regras de alocação multi-vendedor
- Testes automatizados para lógica crítica de negócio

</td>
</tr>
</table>

---

## Como construo

**1. Entender a operação** — mapear o fluxo real, restrições e pontos de falha.  
**2. Definir o menor escopo confiável** — evitar especificação gigante antes de provar o fluxo principal.  
**3. Entregar uma versão funcional** — algo que possa ser testado no contexto real de operação.  
**4. Validar comportamento real** — usar logs, casos de borda e feedback em vez de assumir que o caminho feliz basta.  
**5. Endurecer o sistema** — recuperação, validação, permissões, proteção contra duplicidade e visibilidade operacional.  
**6. Documentar e evoluir** — deixar a próxima mudança mais fácil que a anterior.

Essa abordagem aparece nos case studies acima: o trabalho não é só implementar funcionalidades, mas deixar o sistema **operável, diagnosticável e sustentável**.

---

## Stack principal

| Área | Tecnologias |
|---|---|
| **Backend** | Python, FastAPI, Flask, Django, PHP |
| **Frontend / Desktop** | TypeScript, React, Next.js, Electron |
| **Dados** | PostgreSQL, Supabase, SQL, ETL |
| **Automação** | Playwright, Selenium, jobs agendados, fluxos de navegador |
| **Infraestrutura** | Docker, Linux/VPS, Vercel, Cloudflare |
| **Integrações** | APIs REST, Webhooks, WhatsApp, Vapi, provedores de pagamento |

---

## Código público

Meus trabalhos comerciais mais fortes estão representados pelos case studies acima. Estes repositórios são públicos porque o código pode ser analisado sem expor projetos de cliente:

| Repositório | O que pode ser analisado |
|---|---|
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Coleta agendada, integração com DeFiLlama, entrega no Telegram, regras de alerta e fluxo de assinatura. |
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Roteamento assíncrono com Telethon, regras de origem/destino, tópicos e fluxos agendados. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Camada Flask que recebe eventos e encaminha notificações estruturadas ao Telegram. |

<details>
<summary><strong>Trabalhos anteriores em Dados / BI</strong></summary>
<br />
Minha trajetória também inclui SQL, ETL, Excel e Power BI. Esses repositórios continuam públicos como parte do histórico, mas meu posicionamento atual está centrado em sistemas de software, automação e integrações.
</details>

---

## Disponível para

- Projetos freelance de desenvolvimento
- Contratos remotos
- Automação e integrações
- Implementação de produtos / MVPs full-stack
- Apoio técnico de implementação para agências e software houses

**Baseado no Brasil · disponível para trabalho remoto.**

---

## Contato

**LinkedIn:** [linkedin.com/in/karlos-sanchez](https://www.linkedin.com/in/karlos-sanchez/)  
**Email:** [karloseduardosanchez@hotmail.com](mailto:karloseduardosanchez@hotmail.com)

### Systems that work.
*De processo manual a software pronto para produção.*
