# AI Voice Operations — Sophie / TRJ Clean Service

## Overview

Sophie is an inbound AI voice receptionist built for a U.S. cleaning service. The system answers calls, understands the customer's request, collects the information needed for an estimate and sends a structured summary to the team through WhatsApp after the call.

## Problem

The business needed a way to answer inbound calls consistently without losing lead details when the team was unavailable. The solution had to sound natural, gather useful information and hand the result back to the human team in a format they could act on immediately.

## My role

I handled the technical setup and integration work, including:

- voice-agent configuration and conversation flow;
- prompt design for inbound customer calls;
- collection of name, phone, address, cleaning type, bedrooms, bathrooms, preferred date/time, pets and notes;
- post-call summary handling through webhooks;
- WhatsApp delivery of structured lead summaries;
- Docker/VPS infrastructure for the integration layer;
- Cloudflare Tunnel exposure for webhook delivery;
- iterative call testing and prompt/voice adjustments.

## Architecture

```mermaid
flowchart LR
    C[Customer call] --> V[Vapi voice agent]
    V --> Q[Qualification + data collection]
    Q --> S[Structured call result]
    S --> WH[Post-call webhook]
    WH --> API[Integration service on Docker / VPS]
    API --> WA[WhatsApp team handoff]
```

### Voice layer

- Vapi
- speech-to-text / LLM / voice pipeline
- structured conversation prompt

### Integration layer

- webhook endpoint
- Dockerized service on Linux/VPS
- Cloudflare Tunnel

### Team handoff

- WhatsApp integration
- structured post-call summary

## Core flow

1. A customer calls the business.
2. Sophie answers and identifies the service requested.
3. The agent asks the qualification questions required by the business.
4. Relevant information is structured after the call.
5. A webhook sends the call summary to the integration service.
6. The summary is delivered to the team through WhatsApp.

## Engineering focus

- Keep the conversation concise enough for a phone call while still capturing operationally useful data.
- Separate the voice-agent flow from the post-call integration so each part can evolve independently.
- Return a structured handoff instead of a raw transcript so the team can act on the lead quickly.
- Test with realistic call scenarios before considering the first version ready for validation.

## Stack

`Vapi` · `Webhooks` · `REST APIs` · `Docker` · `Linux/VPS` · `WhatsApp`

## Status

Working first version validated through real call scenarios, with further refinement focused on naturalness, prompt behavior and business-specific handling.

## Privacy

Client credentials, phone numbers and production infrastructure details are intentionally omitted.
