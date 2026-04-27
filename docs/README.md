# OctoAcme Project Management Docs

This README is the entry point for OctoAcme's project management methodology. It provides a brief overview of how cross-functional projects are run at OctoAcme and links to all detailed process documents in this folder.

---

## Overview of OctoAcme's Project Management Processes

OctoAcme follows a lightweight, repeatable project lifecycle designed to keep cross-functional work aligned and measurable. Work moves through five phases: **Initiation** (clarify the problem, objective, and success metrics), **Planning** (break scope into shippable increments with estimates and a Definition of Done), **Execution** (build, test, and review in small iterations), **Release** (deploy with verification and clear release notes), and **Close/Retrospective** (capture learnings and convert them into tracked action items). The process emphasizes iterative delivery, clear ownership, and data-informed decisions, with key artifacts—project charter, prioritized backlog with acceptance criteria, release plan, and risk register—serving as the source of truth throughout delivery.

Roles are intentionally explicit so responsibilities don't blur across teams. **Project Managers (PMs)** coordinate delivery, timelines, risks, and communications, while **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success. **Developers** implement features, collaborate on design and testability, and contribute to estimation and risk identification. **QA/Testing** validates features against acceptance criteria, and **Stakeholders** provide input and approvals at key milestones. This division supports clear ownership while encouraging collaboration—especially around trade-offs, acceptance criteria, and operational readiness.

Communication is structured around a consistent team rhythm and targeted stakeholder updates. Execution typically includes daily standups (progress, blockers, dependencies), a weekly delivery sync to review progress and risks, and demos or reviews at the end of each sprint or milestone. Risk and dependency management is operationalized via a **risk register** (impact, likelihood, owner, mitigation, status) that is reviewed in weekly syncs, with defined escalation paths from team triage up through Product Lead and sponsors for business-impacting issues. Stakeholder updates follow a standardized weekly status template covering progress, next steps, risks/blockers, and asks/decisions.

Quality assurance is embedded across development, review, and release. OctoAcme encourages small pull requests with clear descriptions that link the relevant issue and acceptance criteria, and requires CI to pass (tests and linting) with at least one approval before merge. Testing expectations include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release, complemented by security scanning in CI and manual QA when needed. Releases are gated by "done" criteria—acceptance criteria met, CI/security passing, release notes written, rollback plan in place—and are followed by post-deploy verification. Retrospectives then translate lessons learned into backlog items with owners and due dates, closing the loop on continuous improvement.

---

## Process Documentation

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and the high-level project lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a project: problem statement, stakeholders, charter, and success metrics |
| [Project Planning](octoacme-project-planning.md) | Scope definition, backlog preparation, milestones, estimates, and Definition of Done |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint/iteration workflows, standups, progress tracking, and blocker resolution |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, stakeholder updates, and incident communication |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release gates, deployment checklist, rollback plans, and post-deploy verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and feeding learnings back into the process |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each role |
