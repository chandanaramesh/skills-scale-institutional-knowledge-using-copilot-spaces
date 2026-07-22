# OctoAcme Project Management Docs

This README is the single starting point for OctoAcme's project management process documentation. It summarizes how projects are initiated, planned, executed, released, and continuously improved, and links to detailed guidance for each area.

## Project Management Process Overview

OctoAcme follows a lightweight, iterative project management model that moves work from initiation through planning, execution, release, and retrospective improvement. New work begins with a clear business need, a one-pager, stakeholder alignment, early risk identification, and a go/no-go decision before moving into planning. Once approved, teams break work into shippable increments, build a prioritized backlog with acceptance criteria, estimate scope, define a Definition of Done, and map milestones, dependencies, and release plans. This provides a consistent structure while supporting iterative delivery and small, testable progress.

The documentation defines clear roles across cross-functional delivery. **Project Managers** coordinate delivery, timelines, risks, communication, and project documentation. **Product Managers** define outcomes, prioritize the backlog, and measure success. **Developers** implement features, contribute to planning and estimation, and help identify technical risks. **QA/Testing contributors** validate quality and acceptance criteria. **Stakeholders** provide inputs and approvals. Ownership clarity is treated as a core principle so that decisions, approvals, and delivery responsibilities remain visible throughout the project lifecycle.

Execution relies on regular team rhythms and visible tracking. OctoAcme uses project boards with workflow states such as Backlog, Ready, In Progress, In Review, QA, and Done, supported by daily or twice-weekly standups, weekly PM/PdM delivery syncs, milestone or sprint demos, and monthly stakeholder updates. Communication follows a single source of truth, with weekly status updates covering progress, next steps, risks, blockers, and decisions needed. Risks and dependencies are managed through a risk register, reviewed regularly, and escalated through a defined path from team-level triage to PM, Product Lead, and sponsor-level escalation when business impact increases.

Quality assurance is built into delivery rather than treated as a final step. The process calls for unit tests on new logic, integration testing where appropriate, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed for feature acceptance. Pull requests should stay small when possible, include linked issues and acceptance criteria, and pass automated tests and linting before review, with at least one approval required before merge. Releases are governed by structured pre-release and deployment checklists, including passing CI and security scans, release notes, rollback planning, staging validation, production verification, and post-release communication.

## Documentation Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme — Project Planning](octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](octoacme-roles-and-personas.md)
