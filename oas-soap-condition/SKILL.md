---
name: oas-soap-condition
description: Oracle OAS SOAP ConditionService Service methods. Trigger when requests map to this service domain and operations.
---

# ConditionService Service Skill

## Scope

- Use for evaluating saved/inline conditions and fetching condition-customizable elements.
- Source: `Oracle docs\ConditionService Service.mhtml`

## Methods

- `evaluateCondition()`
- `evaluateInlineCondition()`
- `getConditionCustomizableReportElements()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
