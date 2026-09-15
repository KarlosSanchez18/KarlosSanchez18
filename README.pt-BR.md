<p align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-2B2B2B?style=for-the-badge" alt="English" /></a>
  <a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-FF6A00?style=for-the-badge" alt="Português" /></a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg" alt="Karlos Sanchez — Software para operações reais" width="100%" />
</p>

<p align="center">
  <strong>Eu construo software para operações que ainda dependem de abas, planilhas, WhatsApp e verificações manuais.</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LinkedIn-Karlos%20Sanchez-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/Email-karloseduardosanchez%40hotmail.com-2B2B2B?style=flat-square" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Bauru%2C%20Brasil-Remoto-FF6A00?style=flat-square" alt="Bauru Brasil Remoto" />
</p>

<br />

## O que eu realmente faço

Boa parte do meu trabalho começa antes de existir uma especificação bonita de software.

Normalmente já existe um processo. Alguém abre alguns sistemas, copia uma informação, confere outra, manda uma mensagem, espera, precisa lembrar de voltar depois — e tudo funciona porque aquela pessoa sabe onde estão todas as pontas soltas.

É justamente essa parte que eu gosto de transformar em software.

Trabalho com **aplicações web e desktop, APIs, automação de navegador, fluxos com WhatsApp, pagamentos e operações assistidas por IA**. A stack muda. O padrão não: tirar trabalho repetitivo, conectar o que está separado e deixar o resultado confiável o bastante para ser usado todos os dias.

---

## Dois projetos explicam melhor do que uma lista de tecnologias

### UTMZAP — a origem do lead não deveria sumir quando o WhatsApp abre

<p align="center">
  <a href="./case-studies/lead-tracking-crm.md"><img src="./assets/case-utmzap.webp" width="96%" alt="UTMZAP — Lead Tracking e CRM" /></a>
</p>

Uma agência precisava saber de onde o lead veio **antes** de a conversa ir para o WhatsApp. Eu construí o fluxo em volta desse problema: links rastreáveis de campanha, captura de UTMs/identificadores de anúncio, eventos de clique e lead, portal do cliente e um mini-CRM para acompanhar o que aconteceu depois.

<sub>Electron · React · TypeScript · Next.js · Supabase · PostgreSQL</sub>

**[Abrir o case →](./case-studies/lead-tracking-crm.md)**

<br />

### Sophie — o telefone toca, a equipe recebe só a parte útil

<p align="center">
  <a href="./case-studies/ai-voice-operations.md"><img src="./assets/case-ai-voice.webp" width="96%" alt="Sophie — AI Voice Operations" /></a>
</p>

Para uma empresa de limpeza nos EUA, desenvolvi uma assistente de voz receptiva que atende a chamada, pergunta o que a empresa realmente precisa saber e envia um resumo estruturado para o WhatsApp da equipe depois da conversa.

O objetivo nunca foi só “fazer uma IA falar”. A parte útil está no que acontece em volta da chamada: qualificação, captura estruturada, webhooks, processamento pós-ligação, entrega e a infraestrutura mantendo o fluxo de pé.

<sub>Vapi · Webhooks · APIs · Docker · Linux/VPS · WhatsApp</sub>

**[Abrir o case →](./case-studies/ai-voice-operations.md)**

---

## O trabalho menos fotogênico

Nem tudo que eu construo vira um screenshot bonito. Parte do trabalho em que mais consigo ajudar fica por trás da tela:

- **[Distributed Browser Automation](./case-studies/distributed-browser-automation.md)** — agentes remotos, execuções agendadas, recuperação de sessão e controle centralizado para automações longas de navegador.
- **[Marketplace Payment Infrastructure](./case-studies/marketplace-payment-infrastructure.md)** — split WooCommerce/Dokan/Asaas, proteção contra duplicidade, refunds/reversals e regras financeiras.
- **[SaaS Benchmarking Platform](./case-studies/saas-benchmarking-platform.md)** — autenticação, limites por empresa/usuário, processamento de CSV, métricas, dashboards e área administrativa protegida.

---

## O tipo de frase que normalmente chega para mim

> “A gente faz isso manualmente todo dia.”  
> “Esses dois sistemas não conversam.”  
> “A automação funciona… até travar.”  
> “O lead chegou, mas a gente perdeu de onde ele veio.”  
> “Na prática esse provedor não se comporta igual à documentação.”

Isso me interessa bem mais do que construir mais uma demo que só funciona no caminho feliz.

---

<details>
<summary><strong>Por baixo do capô — ferramentas e parte técnica</strong></summary>
<br />

**Ferramentas principais:** Python, FastAPI, Flask, Django, TypeScript, React, Next.js, Electron, PostgreSQL, Supabase, Docker, Playwright/Selenium e Linux/VPS.

**Coisas com que lido com frequência:**

- recuperação de sessões longas de navegador;
- retries, idempotência e proteção contra duplicidade;
- autenticação, roles e limites de dados;
- webhooks e tratamento de falhas em APIs externas;
- logs e visibilidade suficiente para diagnosticar falhas depois da entrega;
- casos chatos de pagamento e marketplace;
- primeiras versões úteis antes de especificações gigantes.

</details>

<details>
<summary><strong>Código público</strong></summary>
<br />

| Repositório | O que pode ser analisado |
|---|---|
| **[defi-alert-bot](https://github.com/KarlosSanchez18/defi-alert-bot)** | Coleta agendada, integração DeFiLlama, entrega via Telegram, regras de alerta e fluxo de assinatura. |
| **[telegram-message-router](https://github.com/KarlosSanchez18/telegram-message-router)** | Roteamento assíncrono no Telegram com Telethon, regras de origem/destino, tópicos e fluxos agendados. |
| **[automation-bot](https://github.com/KarlosSanchez18/automation-bot)** | Camada Flask que recebe eventos e encaminha notificações estruturadas para o Telegram. |

Repositórios comerciais/de clientes continuam privados quando possuem código proprietário ou detalhes operacionais sensíveis.

</details>

---

<h2 align="center">Tem um processo que já não deveria ser manual?</h2>

<p align="center">
  Me manda a versão bagunçada. A gente descobre o que realmente vale transformar em software.
</p>

<p align="center">
  <a href="mailto:karloseduardosanchez@hotmail.com"><img src="https://img.shields.io/badge/ME%20MANDA%20UM%20EMAIL-FF6A00?style=for-the-badge" alt="Me manda um email" /></a>
  <a href="https://www.linkedin.com/in/karlos-sanchez/"><img src="https://img.shields.io/badge/LINKEDIN-242424?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center"><sub>Systems that work. Não só screenshots que parecem prontos.</sub></p>