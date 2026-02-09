---
name: oas-soap-user-personalization
description: Oracle OAS SOAP UserPersonalizationService Service methods. Trigger when requests map to this service domain and operations.
---

# UserPersonalizationService Service Skill

## Scope

- Use for user favorites, favorite categories, and most-recent artifacts.
- Source: `Oracle docs\UserPersonalizationService Service.mhtml`

## Methods

- `addFavorite()`
- `addFavoriteCategory()`
- `deleteFavorite()`
- `deleteFavoriteCategory()`
- `getFavorites()`
- `updateFavorites()`
- `getMostRecents()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
