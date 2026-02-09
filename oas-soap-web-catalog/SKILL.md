---
name: oas-soap-web-catalog
description: Oracle OAS SOAP WebCatalogService Service methods. Trigger when requests map to this service domain and operations.
---

# WebCatalogService Service Skill

## Scope

- Use for catalog object and folder CRUD, ACL/ownership, properties, and object read/write.
- Source: `Oracle docs\WebCatalogService Service.mhtml`

## Methods

- `copyItem()`
- `copyItem2()`
- `createFolder()`
- `createLink()`
- `deleteItem()`
- `getItemInfo()`
- `getMaintenanceMode()`
- `getObjectCategories()`
- `getObjectCreateList()`
- `getObjectTypes()`
- `getSubItems()`
- `getUserHomeDirPath()`
- `maintenanceMode()`
- `moveItem()`
- `pasteItem2()`
- `readObjects()`
- `removeFolder()`
- `setItemAttributes()`
- `setItemProperty()`
- `setOwnership()`
- `updateCatalogItemACL()`
- `writeObjects()`

## Enumerations

- `ErrorDetailsLevel`
- `ReadObjectsReturnOptions`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
