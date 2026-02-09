---
name: oas-soap-security
description: Oracle OAS SOAP SecurityService Service methods. Trigger when requests map to this service domain and operations.
---

# SecurityService Service Skill

## Scope

- Use for account/group membership, global privileges, and permission/ACL operations.
- Source: `Oracle docs\SecurityService Service.mhtml`

## Methods

- `forgetAccounts()`
- `forgetAccountsEx()`
- `getAccounts()`
- `getAccountTenantID()`
- `getGlobalPrivilegeACL()`
- `getGlobalPrivileges()`
- `getPermissions()`
- `getPermissionsEx()`
- `getPrivilegesStatus()`
- `isMember()`
- `joinGroups()`
- `leaveGroups()`
- `renameAccountsEx()`
- `updateGlobalPrivilegeACL()`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
