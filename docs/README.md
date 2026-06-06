# OctoAcme Project Management Docs

Welcome to the central hub for all project management processes used by OctoAcme.

## Overview: Project Management Processes

OctoAcme employs a structured, lifecycle-driven approach to project management that emphasizes customer value, iterative delivery, and clear accountability. The methodology spans five key phases: Initiation (validating business need and securing stakeholder alignment), Planning (breaking work into shippable increments and mapping dependencies), Execution & Tracking (managing daily progress through standups, demos, and blocker escalation), Release & Deployment (standardizing production releases with pre-flight checklists and rollback plans), and Retrospective & Continuous Improvement (capturing learnings and converting them into actionable improvements). This end-to-end approach ensures projects are delivered predictably and stakeholders remain aligned throughout.

The framework relies on three core roles with distinct responsibilities: Project Managers coordinate delivery schedules, manage risks and cross-team dependencies, and maintain transparent communication; Product Managers define success metrics, prioritize the backlog, and validate solutions through data-driven insights; and Developers implement features, write tests, collaborate on design, and help identify technical risks. Communication cadences are structured around daily standups (15 minutes), weekly PM-PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates, supported by a Risk Register that is reviewed and updated weekly. This multi-layered communication strategy ensures issues surface early and escalations follow a clear path: team-level triage → PM → Product Lead → Sponsor.

Quality and testing are embedded throughout execution, with practices including unit and integration tests for new logic, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance. The team uses a structured Pull Request workflow requiring PRs ≤400 lines, clear acceptance criteria, automated CI testing and linting, and at least one approval before merge. A GitHub Projects board tracks workflow with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done, providing real-time visibility into progress. Success is measured through velocity tracking, burndown analysis, and dashboards monitoring key signals like errors, latency, and usage, ensuring the team stays aligned to the metrics defined in each project's One-pager.

## Process Document Links

Explore the detailed process documentation:

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, core roles, key artifacts, and project lifecycle.
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and create a lightweight project one-pager.
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, estimate scope, identify dependencies, and create a release plan.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, conduct reviews, and escalate blockers.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify and manage risks, maintain a risk register, and communicate transparently with stakeholders.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize release processes, prepare pre-flight checklists, and handle rollbacks.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, track action items, and continuously improve processes.
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of project manager, product manager, and developer roles and responsibilities.

---

## Getting Started

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) documents.
- **Managing an active project?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day guidance.
- **Preparing for release?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md).

For details on contributing or updating process docs, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
