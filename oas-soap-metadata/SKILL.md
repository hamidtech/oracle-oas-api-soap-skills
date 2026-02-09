---
name: oas-soap-metadata
description: Oracle OAS SOAP MetadataService Service methods. Trigger when requests map to this service domain and operations.
---

# MetadataService Service Skill

## Scope

- Use for subject area, table, and column metadata discovery and metadata reload/cache actions.
- Source: `Oracle docs\MetadataService Service.mhtml`

## Methods

- `clearQueryCache()`
- `describeColumn()`
- `describeSubjectArea()`
- `describeSubjectAreaWithSort()`
- `describeTable()`
- `describeTableWithSort()`
- `getSubjectAreas()`
- `getSubjectAreasWithSort()`
- `reloadLogConfiguration()`
- `reloadMetadata()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
