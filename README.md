# Oracle OAS SOAP Skills

A structured, capability-driven **skill map** for **Oracle Analytics Server (OAS)** SOAP services.

This repository is intentionally designed in the same conceptual spirit as the **AI skill abstraction model** used in modern agent frameworks — where complex systems are exposed to AI through **explicit, well-scoped skills**, not raw APIs.

If you are familiar with the idea behind AI skills as defined here:
https://github.com/anthropics/skills/tree/main

this repository applies the **same mental model** to **Oracle Analytics Server SOAP APIs**.

---

## Why This Exists (AI & Skill-Oriented Context)

Modern AI systems (LLMs, agents, orchestrators) do not work well with:
- Large, unstructured API surfaces
- Raw documentation or WSDLs
- Implicit or undocumented capabilities

They work best when systems are exposed as **explicit skills**:
- Each skill has a clear **scope**
- Each skill defines **what it can do**
- Each skill maps user intent → executable operations

This repository exists to make **Oracle OAS understandable and usable by AI systems** by translating its SOAP APIs into **clear, machine-reasonable skills**.

In other words:
> This repo helps an AI understand *what Oracle OAS can do* when you describe a task in natural language.

---

## What This Repository Is

- A **skill abstraction layer** over Oracle OAS SOAP services
- A **method-level capability map** aligned with Oracle’s official contracts
- A **bridge between human intent, AI reasoning, and OAS execution**

It is designed to be consumed by:
- AI agents
- Skill-based orchestration systems
- Automation frameworks
- Programmatic BI workflows

This is **not**:
- A tutorial
- A client SDK
- A UI tool

---

## Covered SOAP Services

Each Oracle OAS SOAP service is represented as a standalone **skill**, with:
- Explicit scope
- Supported methods
- Execution and dependency patterns

Examples include:
- Metadata discovery and cache management
- Web Catalog CRUD and ACLs
- Report execution and export
- HTML and XML rendering
- Scheduler job inspection and control
- Security, privileges, and permissions
- Session management and impersonation
- Agents (iBots) and alerts

A consolidated **SOAP Skill Map** is included for fast navigation across all services.

---

## Design Principles

- **Skill-first, not API-first**
- **Exact Oracle semantics** (no renaming or abstraction drift)
- **Composable capabilities**
- **AI-readable structure**
- **Automation-ready by default**
- **Faithful to Oracle’s official SOAP contracts**

---

## Intended Use Cases

- Enabling AI agents to reason about Oracle Analytics Server
- Mapping natural-language BI intents to executable OAS actions
- Building agent-driven or automated OAS workflows
- Documenting enterprise OAS capabilities in a machine-friendly way
- Serving as a foundation for higher-level AI tooling

---

## License

MIT License

You are free to use, modify, distribute, and integrate this repository in any project — including commercial and closed-source products.

---

## Disclaimer

This project is **not affiliated with Oracle**.
Oracle, Oracle Analytics Server, and related names are trademarks of Oracle Corporation.
This repository is provided as-is, without warranty.
