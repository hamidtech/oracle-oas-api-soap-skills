---
name: oas-soap-session
description: Oracle OAS SOAP SAWSessionService Service methods. Trigger when requests map to this service domain and operations.
---

# SAWSessionService Service Skill

## Scope

- Use for session login, keep-alive, impersonation, and session variable/context access.
- Source: `Oracle docs\SAWSessionService Service.mhtml`

## Methods

- `getCurUser()`
- `GetSessionEnvironment()`
- `getSessionVariable()`
- `impersonate()`
- `impersonateex()`
- `keepAlive()`
- `logoff()`
- `logon()`
- `logonex()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
