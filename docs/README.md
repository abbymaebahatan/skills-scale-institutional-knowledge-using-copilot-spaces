# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains guidance for running projects at OctoAcme, from initiation through release and continuous improvement. These docs are intended to serve as a single source of truth to help teams plan, execute, and improve consistently.

OctoAcme runs projects with a clear, artifact-driven lifecycle that moves work from initiation through planning, execution, release, and retrospective. Projects begin with a lightweight Project One-pager to confirm the problem, success metrics, stakeholders, and a high-level timeline. Once approved, planning breaks the initiative into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan. Core artifacts—one-pagers, roadmaps, sprint backlogs, risk registers, and retrospective notes—are stored in this docs/ folder and maintained as the canonical project record.

Work is organized using a project board and a disciplined PR workflow to keep delivery predictable. Teams use the board columns: Backlog → Ready → In Progress → In Review → QA → Done, favor small pull requests (<= 400 lines), link PRs to issues with acceptance criteria, and run automated CI checks (tests, linters, security scans) before requesting review. Delivery is supported by a regular cadence of daily standups, sprint planning, weekly delivery syncs, and end-of-sprint demos so progress, risks, and dependencies are surfaced early.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, risks, and stakeholder communications; Developers implement and test features; QA validates acceptance and quality. Quality controls include unit and integration tests, end-to-end smoke tests for critical flows, manual QA when required, and pre-release checklists (release notes, rollback plan, staging verification). A maintained risk register and clear escalation paths ensure issues are triaged and escalated from team-level to sponsor-level as needed.

## Process Documents (this folder)

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Quick Reference

Key Artifacts by Phase
- Initiation: Project One-pager, Stakeholder list, Risk list
- Planning: Backlog, Release plan, Risk Register, Definition of Done
- Execution: Project board, PRs and CI, Issue tracking, Risk Register (updated)
- Release: Release notes, Deployment checklist, Rollback plan
- Retrospective: Action items, Improvements log

Communication Cadence
- Daily standups (15 min)
- Weekly PM + PdM sync
- Twice-weekly or agreed delivery team standups
- Weekly stakeholder updates
- Sprint / milestone demos and reviews
- Monthly stakeholder updates

## Getting Started
New to OctoAcme? Start with the Project Management Overview, then follow the Initiation → Planning → Execution → Release → Retrospective sequence for your project. Keep project artifacts up to date in the repo and use the templates and checklists in each process doc to ensure consistency.
