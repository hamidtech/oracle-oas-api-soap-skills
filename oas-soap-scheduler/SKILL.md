---
name: oas-soap-scheduler
description: Oracle OAS SOAP SchedulerService Service methods. Trigger when requests map to this service domain and operations.
---

# SchedulerService Service Skill

## Scope

- Use for scheduler jobs/job instances: inspect, cancel, remove, and purge.
- Source: `Oracle docs\SchedulerService Service.mhtml`

## Methods

- `logon()`
- `getJobReferences()`
- `getJobInstanceReferences()`
- `getJob()`
- `getJobInstance()`
- `cancelJobInstance()`
- `removeJobs()`
- `purgeJobInstances()`

## Enumerations

- `JobInstanceStatus`

## Execution Pattern

- Validate if operation requires a valid OAS session token.
- Map user intent to the closest method in this service first.
- Preserve Oracle method naming and argument semantics exactly.
- Return actionable errors and include next-step method choices when failures occur.
