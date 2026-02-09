---
name: oas-soap-report-editing
description: Oracle OAS SOAP ReportEditingService Service methods. Trigger when requests map to this service domain and operations.
---

# ReportEditingService Service Skill

## Scope

- Use for report edit-time operations: defaults, params, prompt elements, columns, and SQL generation.
- Source: `Oracle docs\ReportEditingService Service.mhtml`

## Methods

- `applyReportDefaults()`
- `applyReportParams()`
- `getPromptElements()`
- `generateReportSQL()`
- `getReportColumns()`
- `getReportElements()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
