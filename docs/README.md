# OctoAcme Project Management Docs

This directory contains the core project management process documents used by OctoAcme. Together, they define how the team initiates work, plans delivery, tracks execution, manages risks, communicates status, and improves processes over time. The overall model is built around iterative delivery, clear ownership, regular stakeholder communication, and disciplined quality gates.

OctoAcme’s project management approach starts with validating the business problem and defining measurable success criteria, then moves into backlog planning, milestone alignment, and execution with defined roles and clear ownership. The team follows a regular cadence of standups, weekly syncs, and milestone reviews, while using project boards and PR standards to keep work visible and moving forward. Risks and blockers are tracked and escalated through defined escalation paths, and releases are controlled through checklist-based deployment, smoke testing, and rollback planning. Quality is reinforced through CI checks, test coverage, manual QA where needed, and a culture of continuous improvement.

## Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — A concise introduction to OctoAcme’s project lifecycle, principles, roles, and core artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — Covers how to validate an idea, align stakeholders, define success metrics, and decide whether to move into planning.
- [Project Planning](./octoacme-project-planning.md) — Explains backlog creation, estimation, release planning, definition of done, and dependency management.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Details team cadence, delivery workflows, reporting, QA expectations, and blocker escalation.
- [Risks & Communication](./octoacme-risks-and-communication.md) — Defines risk registers, stakeholder communication patterns, and escalation routes for issues.
- [Release & Deployment](./octoacme-release-and-deployment.md) — Outlines release types, pre-release requirements, deployment checklists, and rollback playbooks.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Provides a structure for capture learning, tracking action items, and improving team practices.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Describes the core roles and responsibilities used across OctoAcme project work.

## How to use this folder

Use this folder as the central knowledge base for OctoAcme project operations. New team members can start with the overview and initiation guide, then move into planning and execution documents as needed. When adding new process content, keep the structure consistent and update this README with a short summary of the document so the directory remains easy to navigate.

## Related workflow

- Use GitHub Projects or an equivalent board with columns: Backlog, Ready, In Progress, In Review, QA, and Done.
- Keep PRs small when possible, include issue links and acceptance criteria, and require CI checks before review.
- Track key risks, communicate status regularly, and review retrospectives to convert insights into action items.
