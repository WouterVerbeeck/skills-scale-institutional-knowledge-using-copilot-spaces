# OctoAcme Project Management – Docs

This folder contains the full set of process documents that describe how OctoAcme plans, delivers, and continuously improves software projects. Use this README as a starting point to navigate the documentation.

## Summary

OctoAcme uses a lightweight, lifecycle-based project management approach that moves work through clear stages: **Initiation → Planning → Execution → Release → Retrospective / Continuous Improvement**. In initiation, teams validate the business need and define success up front using a concise **Project One-pager** (problem statement, SMART objective, success metrics), plus a stakeholder list, high-level milestones, initial risks, and resourcing needs. A simple decision gate determines whether the work is approved to proceed into planning once outcomes, priority, and availability are clear.

During planning, OctoAcme translates an approved initiative into an actionable delivery plan by running a kickoff, creating a prioritized backlog with acceptance criteria, estimating scope (T-shirt sizing or story points), and documenting a **Definition of Done**. Dependencies and risks are explicitly captured (e.g., in a risk register) and surfaced during recurring sync points. Planning also includes aligning a release timeline and milestone map so that responsibilities, sequencing, and integration points are visible before execution begins.

Execution emphasizes steady team rhythm and transparent tracking. Day-to-day work is coordinated through short **daily standups**, a **weekly delivery sync**, and a demo/review at the end of each sprint or milestone. Work is tracked on a board (e.g., GitHub Projects) flowing from **Backlog → Ready → In Progress → In Review → QA → Done**, and blockers follow a clear escalation ladder from team triage to PM-led escalation and, if needed, sponsor-level attention. Communication is structured around stakeholder needs with regular updates and a single source of truth for status, supported by templates for weekly status reporting and incident communications.

Roles are clearly defined to keep ownership unambiguous: the **Project Manager** coordinates delivery, timelines, risks, and cross-team communication; the **Product Manager** defines outcomes, prioritizes, and measures impact; **Developers** implement and collaborate on design and testability; and **QA/Testing** validates acceptance and quality. Quality assurance is embedded in the workflow via small, reviewable pull requests, required approvals, and automated CI checks (tests, linting, security scans), complemented by integration testing where appropriate and end-to-end smoke tests before release. Releases follow a standardized checklist (release notes, rollback/mitigation plan, staging verification, post-deploy checks, and stakeholder announcements), and the process closes with retrospectives that convert learnings into owned, trackable action items.

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level overview of the end-to-end OctoAcme project lifecycle |
| [Project Initiation](./octoacme-project-initiation.md) | How to validate, scope, and get approval for a new initiative |
| [Project Planning](./octoacme-project-planning.md) | Backlog creation, estimation, dependencies, and milestone mapping |
| [Execution and Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery rhythm, board workflow, and escalation paths |
| [Release and Deployment](./octoacme-release-and-deployment.md) | Release checklist, staging verification, and post-deploy practices |
| [Release Readiness Review Checklist](./octoacme-release-readiness-review-checklist.md) | Cross-functional sign-off checklist for QA, Security, SRE / Ops, and Support before release |
| [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Structured retro format and action-item tracking |
| [Risks and Communication](./octoacme-risks-and-communication.md) | Risk register practices, stakeholder communication, and templates |
| [RACI / Ownership Template](./octoacme-raci-and-ownership-template.md) | Default ownership matrix for lifecycle phases and recurring activities |
| [Project Operating Rhythm Checklist](./octoacme-project-operating-rhythm-checklist.md) | Lightweight template for cadence, meetings, reporting, and escalation triggers |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Definitions and responsibilities for each project role |
