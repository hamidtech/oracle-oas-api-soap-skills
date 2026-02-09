---
name: oas-soap-html-view
description: Oracle OAS SOAP HtmlViewService Service methods. Trigger when requests map to this service domain and operations.
---

# HtmlViewService Service Skill

## Scope

- Use for HTML rendering or page composition of analyses/reports.
- Source: `Oracle docs\HtmlViewService Service.mhtml`

## Methods

- `addReportToPage()`
- `endPage()`
- `getCommonBodyHTML()`
- `getHeadersHTML()`
- `getHtmlforPageWithOneReport()`
- `getHTMLForReport()`
- `setBridge()`
- `startPage()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
