# OctoAcme Project Management Docs

This README centralizes the OctoAcme project management process documents, providing quick links and a concise summary of each area to support onboarding and day-to-day reference.

## Document Index

- [Project Management Overview](octoacme-project-management-overview.md) — concise intro to how OctoAcme runs projects: principles, core roles, key artifacts, and lifecycle.
- [Project Initiation Guide](octoacme-project-initiation.md) — steps and templates to validate and authorize new projects.
- [Project Planning](octoacme-project-planning.md) — turning an approved initiative into an actionable plan and backlog.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — day-to-day execution practices, team rhythms, quality, and tracking.
- [Release & Deployment](octoacme-release-and-deployment.md) — release types, deployment checklist, and rollback playbook.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and converting learnings into tracked improvements.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — maintaining a risk register and stakeholder communications.
- [Roles & Personas](octoacme-roles-and-personas.md) — role definitions and responsibilities for Developers, Product Managers, and Project Managers.

## Project Management Processes Summary

OctoAcme follows an iterative, customer-first approach with clear ownership and data-informed decisions. Below is a brief overview of each process area:

### Initiation
Capture the problem statement, identify stakeholders, define success metrics, and produce a project one-pager to reach a go/no-go decision before any planning begins.

### Planning
Run a project kickoff, create a prioritized backlog with acceptance criteria and estimates, define the Definition of Done, identify dependencies, and agree on a release plan and milestone map.

### Execution & Tracking
Keep work moving with daily standups, small PRs with CI checks, a project board tracking each item from backlog to done, and weekly delivery syncs. Escalate blockers through team → PM → Product Lead → Sponsor.

### Release & Deployment
Verify all acceptance criteria are met and CI passes, draft release notes, prepare a rollback plan, then deploy through an automated pipeline with smoke tests and a post-deploy announcement to stakeholders.

### Retrospective & Continuous Improvement
After each sprint, release, or incident, run a timeboxed retrospective (what went well, what to improve, action items). Track improvements in the project backlog and measure their impact.

### Risks & Communication
Maintain a risk register throughout planning and execution, review it at weekly syncs, and provide regular status updates to stakeholders using a single source of truth. Follow clear escalation paths for incidents.

### Roles & Personas
- **Developers** — implement features, write tests, participate in code reviews, and identify technical risks.
- **Product Managers** — define problem statements and success metrics, prioritize the backlog, and validate outcomes.
- **Project Managers** — coordinate delivery, manage schedules and risks, facilitate meetings, and ensure consistent status reporting.
