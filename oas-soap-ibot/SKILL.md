---
name: oas-soap-ibot
description: Oracle OAS SOAP iBotService Service methods. Trigger when requests map to this service domain and operations.
---

# iBotService Service Skill

## Scope

- Use for agent (iBot) lifecycle, execution, subscriptions, and alert/message operations.
- Source: `Oracle docs\iBotService Service.mhtml`

## Methods

- `deleteIBot()`
- `enableIBot()`
- `executeIBotNow()`
- `getAgentPaths()`
- `getAgents()`
- `moveIBot()`
- `purgeAlerts()`
- `getIBotStatus()`
- `sendMessage()`
- `subscribe()`
- `unsubscribe()`
- `writeIBot()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
