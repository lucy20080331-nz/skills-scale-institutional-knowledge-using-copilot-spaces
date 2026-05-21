# OctoAcme Project Management Documentation Overview

Welcome to the OctoAcme project management process documentation! This README gives a brief summary of our core project management approach and links to each document in the `docs/` folder.

## Project Management at OctoAcme

OctoAcme runs cross-functional, customer-focused projects with an emphasis on continuous improvement, iterative delivery, clear ownership, and transparent communication. Our processes are grounded in five core principles: prioritizing customer value and usability, delivering in small testable increments, establishing clear ownership with named Project Managers and Product Leads, making data-informed decisions based on measurable outcomes, and fostering psychological safety for feedback and learning.

The OctoAcme project management approach spans the complete project lifecycle, from initial concept validation through release and continuous improvement. Teams are organized around clear roles—Project Managers coordinate delivery and risk management, Product Managers define outcomes and prioritize work, Developers implement features with quality and testability, and QA/Testing teams validate acceptance criteria. Our communication strategy emphasizes transparency through a single source of truth (typically GitHub Projects), structured team rhythms (daily standups, weekly syncs, regular retrospectives), and escalation frameworks that ensure blockers are surfaced quickly and resolved at the appropriate level.

Quality is embedded throughout our workflow rather than treated as a final stage. Development teams write unit and integration tests as part of implementation, run automated CI pipelines with linting and security scanning before PR approval, and prepare smoke tests before each release. Releases are treated as deliberate, repeatable processes with clear pre-release requirements, deployment checklists, and rollback plans. After each sprint, release, or incident, teams conduct structured retrospectives to capture learnings and prioritize 2–3 actionable improvements, creating a culture of measured, evidence-based iteration.

## Documentation Structure

Our project management processes are documented across the following guides:

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validating business need, aligning stakeholders, defining success criteria, and creating the Project One-pager. Use this when a new project idea or feature proposal is ready to be explored.

- **[Project Planning](./octoacme-project-planning.md)** — Breaking down work into shippable increments, identifying dependencies and risks, and creating a prioritized backlog with acceptance criteria and a Definition of Done.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Managing day-to-day execution, team rhythm, PR workflows, quality checks, blocker escalation, and progress reporting toward project milestones.

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identifying, assessing, and monitoring risks; maintaining the Risk Register; escalating appropriately; and communicating status to stakeholders and handling incidents.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardizing how features are released to production with clear pre-release requirements, deployment checklists, verification steps, and rollback procedures.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running structured retrospectives, capturing learnings, tracking action items, and building a culture of continuous, measured improvement.

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Reference guide defining typical roles (Developers, Product Managers, Project Managers), their responsibilities, goals, and communication styles.

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level overview of our principles, core roles, key artifacts, project lifecycle, and communication cadence.

## Getting Started

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction to our approach.
- **Kicking off a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate the idea and align stakeholders.
- **Planning a project?** Use the [Project Planning](./octoacme-project-planning.md) guide to break down work and create your backlog.
- **Managing execution?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day workflows and quality standards.
- **Preparing a release?** See the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for checklists and best practices.
- **Running a retrospective?** Check [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) for structure and templates.

## Key Artifacts & Templates

Each process document includes checklists, templates, and examples to support consistent execution:

- **Project One-pager** — Problem, Goal, Success Metrics, Stakeholders, Timeline, Risks, Team/Roles
- **Backlog Item Template** — Title, Description, Acceptance Criteria, Priority, Estimate, Owner
- **Definition of Done** — Acceptance criteria, tests, documentation, reviews, and deployment readiness
- **Risk Register** — ID, Description, Impact, Probability, Owner, Mitigation, Status
- **Release Notes Template** — Release name, Date, Summary, Changes, Migrations, Known Issues
- **Weekly Status Template** — Progress, Next Steps, Risks/Blockers, Decisions Needed
- **Retrospective Action Items** — Title, Description, Owner, Due Date, Success Criteria

## Questions or Feedback?

These docs are living artifacts. If you identify gaps, have suggestions for improvements, or want to add clarity to any process, please:

1. Create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
2. Propose your changes with context on why the update is needed.
3. Collaborate with your teammates and Product Lead to refine the guidance.

Our goal is to keep these processes useful, current, and grounded in the real work of the team.
