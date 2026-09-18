# OctoAcme Project Management Docs

This directory contains the process documentation for planning and delivering OctoAcme projects. It provides a shared, searchable reference for project managers, product managers, developers, QA partners, and stakeholders.

## Project management lifecycle

OctoAcme uses a lifecycle that moves from **initiation** to **planning**, **execution**, **release**, and **close/retrospective**. Initiation validates the business need, identifies stakeholders, defines measurable success criteria, and establishes an initial timeline, risks, and resource needs. Planning turns an approved initiative into a prioritized backlog with acceptance criteria, estimates, dependencies, milestones, and a Definition of Done.

During execution, teams deliver small, testable increments using a project board and a regular rhythm of standups, delivery syncs, and milestone demos or reviews. Project managers coordinate schedules, risks, dependencies, and communications; product managers own outcomes and prioritization; developers build and test the solution; QA validates quality and acceptance criteria; and stakeholders provide input and approvals. Status, decisions, risks, and dependencies should remain visible through the project board, risk register, and shared project documentation.

Communication is structured around regular team and stakeholder touchpoints. Teams use daily or agreed-frequency standups to surface progress and blockers, weekly PM/product or delivery syncs to review progress and risks, and weekly or milestone-based stakeholder updates to communicate decisions and asks. Escalation proceeds from team-level triage to the PM, Product Lead, and sponsor when business impact or cross-team constraints require broader intervention. A project README or release document should serve as the single source of truth for status.

Quality is built into the workflow through unit tests, integration tests where appropriate, end-to-end smoke tests for critical flows, CI linting and automated tests, security scanning, and manual QA when feature acceptance requires it. Before release, acceptance criteria must be met, CI and security checks must pass, release notes and rollback or mitigation plans must be prepared, and staging and production deployments must be verified. After each sprint, release, milestone, or incident, retrospectives capture what went well, what can improve, and a small set of owned, time-bound action items that are tracked through the backlog or issues.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, artifacts, lifecycle, and communication cadence.
- [Project Initiation](octoacme-project-initiation.md) — Validate an initiative, align stakeholders, define outcomes, and make the planning decision.
- [Project Planning](octoacme-project-planning.md) — Build the backlog, estimate work, define the Definition of Done, and map milestones and dependencies.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Manage delivery workflows, team rhythm, quality practices, reporting, and blocker escalation.
- [Risks and Communication](octoacme-risks-and-communication.md) — Maintain the risk register, communicate status, and follow escalation paths.
- [Release and Deployment](octoacme-release-and-deployment.md) — Prepare, deploy, verify, communicate, and roll back releases safely.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — Responsibilities, goals, and communication patterns for key project personas.

## How to use these docs

Use the overview as an introduction, then refer to the lifecycle document that matches the current stage of work. Keep project-specific plans, risks, decisions, release information, and retrospective actions updated in the project repository so the team has a current source of truth.
