---
name: oas-soap-xml-view
description: Oracle OAS SOAP XMLViewService Service methods. Trigger when requests map to this service domain and operations.
---

# XMLViewService Service Skill

## Scope

- Use for executing logical SQL/XML queries, pagination (`fetchNext`), and prompted filters.
- Source: `Oracle docs\XMLViewService Service.mhtml`

## Methods

- `cancelQuery()`
- `executeSQLQuery()`
- `executeXMLQuery()`
- `fetchNext()`
- `getPromptedFilters()`

## Enumerations

- `XMLQueryOutputFormat`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
