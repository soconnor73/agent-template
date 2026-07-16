# Agentic Cowork Templates

A structured, document-first template system designed to kickstart human-AI collaboration (cowork) in software projects. 

AI agents excel when provided with clear context boundaries, strict conventions, and explicit expectations. This repository provides a boilerplate directory structure and markdown templates to align human developers and AI coding agents from day one.

---

## 🗺️ Template Map

These templates are organized to guide both you and your AI agents through the entire software development lifecycle:

| Phase | Path | Description |
| :--- | :--- | :--- |
| **Root Entry** | [AGENTS.md](file:///C:/Users/t0187391/agent-project-templates/AGENTS.md) | The single source of truth for the agent regarding project status, active phases, and non-negotiables. |
| **Design** | [docs/design/PRD.md](file:///C:/Users/t0187391/agent-project-templates/docs/design/PRD.md) | Product Requirements Document mapping out the "why" and "what". |
| | [docs/design/DECISIONS.md](file:///C:/Users/t0187391/agent-project-templates/docs/design/DECISIONS.md) | Architecture Decision Records (ADR) detailing design trade-offs. |
| | [docs/design/GLOSSARY.md](file:///C:/Users/t0187391/agent-project-templates/docs/design/GLOSSARY.md) | Definition of domain-specific terminology to align LLM vocabulary. |
| **Planning** | [docs/planning/ROADMAP.md](file:///C:/Users/t0187391/agent-project-templates/docs/planning/ROADMAP.md) | High-level milestones and phase breakdowns. |
| | [docs/planning/BACKLOG.md](file:///C:/Users/t0187391/agent-project-templates/docs/planning/BACKLOG.md) | Prioritized feature lists, tasks, and bugs. |
| | [docs/planning/RISKS.md](file:///C:/Users/t0187391/agent-project-templates/docs/planning/RISKS.md) | Identified technical debt, constraints, and assumptions. |
| **Building** | [docs/building/CONVENTIONS.md](file:///C:/Users/t0187391/agent-project-templates/docs/building/CONVENTIONS.md) | Coding style, architectural rules, and project patterns. |
| | [docs/building/DEV_SETUP.md](file:///C:/Users/t0187391/agent-project-templates/docs/building/DEV_SETUP.md) | Local developer environment requirements, env vars, database seeding, and mocks. |
| | [docs/building/API_CONTRACTS.md](file:///C:/Users/t0187391/agent-project-templates/docs/building/API_CONTRACTS.md) | Defined interfaces, payload shapes, and endpoint contracts. |
| | [docs/building/SECURITY.md](file:///C:/Users/t0187391/agent-project-templates/docs/building/SECURITY.md) | Threat models, sensitive data handling, and compliance rules. |
| **Testing** | [docs/testing/STRATEGY.md](file:///C:/Users/t0187391/agent-project-templates/docs/testing/STRATEGY.md) | How the application should be tested (unit, integration, E2E). |
| | [docs/testing/ACCEPTANCE_CRITERIA.md](file:///C:/Users/t0187391/agent-project-templates/docs/testing/ACCEPTANCE_CRITERIA.md) | Specific criteria for verifying features are complete. |
| **Documentation** | [docs/documentation/README_TEMPLATE.md](file:///C:/Users/t0187391/agent-project-templates/docs/documentation/README_TEMPLATE.md) | Template for your project's main user-facing README. |
| | [docs/documentation/ARCHITECTURE.md](file:///C:/Users/t0187391/agent-project-templates/docs/documentation/ARCHITECTURE.md) | High-level design, data flow, and component relationships. |
| | [docs/documentation/RUNBOOK.md](file:///C:/Users/t0187391/agent-project-templates/docs/documentation/RUNBOOK.md) | Operational guidelines, deployment steps, and troubleshooting. |
| | [docs/documentation/CHANGELOG.md](file:///C:/Users/t0187391/agent-project-templates/docs/documentation/CHANGELOG.md) | Historic record of modifications and releases. |

---

## 🚀 Quickstart

1. **Bootstrap Your Project**
   Copy the `docs/` folder and [AGENTS.md](file:///C:/Users/t0187391/agent-project-templates/AGENTS.md) into the root of your new project repository.

2. **Initialize Alignment**
   Fill out [AGENTS.md](file:///C:/Users/t0187391/agent-project-templates/AGENTS.md) to define your project name, the current development phase, and any absolute **non-negotiables** (e.g., target frameworks, performance requirements).

3. **Configure Your Agent's System Instructions**
   Instruct your AI agent to read [AGENTS.md](file:///C:/Users/t0187391/agent-project-templates/AGENTS.md) at the start of every session to establish context. If you are using Antigravity, add it as a system rule.

---

## 🤝 Best Practices for Human-Agent Cowork

* **Document-First Workflow**: Before asking an agent to write code, write or update the corresponding specification (e.g., [docs/design/PRD.md](file:///C:/Users/t0187391/agent-project-templates/docs/design/PRD.md) or [docs/building/API_CONTRACTS.md](file:///C:/Users/t0187391/agent-project-templates/docs/building/API_CONTRACTS.md)). Use these specifications as the contract for the agent's work.
* **Keep Documents Current**: As requirements change, update the templates first. AI agents will read these documents as their source of truth.
* **Use AGENTS.md as a Compass**: Keep the `Current phase` field in [AGENTS.md](file:///C:/Users/t0187391/agent-project-templates/AGENTS.md) updated so the agent knows whether it should focus on brainstorming designs, refining plans, writing production code, or drafting tests.
