---
name: oas-soap-analysis-export-views
description: Oracle OAS SOAP AnalysisExportViewsService Service methods. Trigger when requests map to this service domain and operations.
---

# AnalysisExportViewsService Service Skill

## Scope

- Use for exporting analysis outputs (PDF, MHTML, Excel, CSV) via export jobs.
- Source: `Oracle docs\AnalysisExportViewsService Service.mhtml`

## Methods

- `completeAnalysisExport()`
- `initiateAnalysisExport()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
