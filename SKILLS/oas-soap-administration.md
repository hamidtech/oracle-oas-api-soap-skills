---
name: oas-soap-administration
description: Oracle OAS SOAP AdministrationService Service methods. Trigger when requests map to this service domain and operations.
---

# AdministrationService Service Skill

## Scope

- Use for CSP whitelist management and runtime admin reload actions.
- Source: `Oracle docs\AdministrationService Service.mhtml`

## Methods

- `deleteCSPWhitelist()`
- `getCSPDefaultAllowList()`
- `getCSPWhitelist()`
- `reloadLogConfiguration()`
- `updateCSPWhitelist()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
