# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, customer-first project management approach focused on **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. This documentation contains guidance for all phases of the project lifecycle.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles and responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation** - Validate business need, align stakeholders, define success criteria
2. **Planning** - Break work into shippable increments, identify dependencies and risks
3. **Execution** - Build, test, review, and iterate with regular tracking
4. **Release** - Deploy to production and verify success
5. **Retrospective** - Capture learnings and drive continuous improvement

---

## How OctoAcme Executes Projects

### Approach & Lifecycle

OctoAcme employs a structured, customer-first project management methodology organized around five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. The approach is grounded in five core principles: prioritizing customer value and usability, delivering small testable increments iteratively, maintaining clear ownership through named roles, making data-informed decisions, and fostering psychological safety for feedback and learning. Each project begins with lightweight validation through a Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics before advancing to detailed planning. This ensures alignment early and reduces wasted effort on misaligned initiatives.

### Roles, Responsibilities & Communication

Three primary personas drive OctoAcme projects: **Project Managers** coordinate delivery, schedules, risks, and communications; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; and **Developers** collaborate on design, implementation, testing, and quality standards. The organization maintains a consistent communication rhythm: weekly PM–Product Manager alignment, twice-weekly delivery team standups, monthly stakeholder updates, and ad-hoc escalations as needed. Risk management and dependencies are tracked through a formal Risk Register and escalated through a tiered path (team-level → PM → Product Lead → Sponsor), ensuring that blockers and issues surface quickly without getting lost in silos.

### Execution, Quality & Continuous Improvement

During execution, teams follow a structured cadence with daily standups, weekly delivery syncs, and sprint-based planning to manage workload and track progress against milestones. Quality is embedded throughout: unit and integration tests are mandatory, automated CI/CD handles security scanning and linting, and smoke tests precede any production release. The project board (e.g., GitHub Projects) provides transparency across Backlog, Ready, In Progress, In Review, QA, and Done columns. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. Finally, retrospectives held after each sprint or milestone capture learnings and convert them into prioritized action items with named owners and due dates, creating a culture of continuous improvement and institutional knowledge retention.

---

## Documentation Index

### Core Framework & Guidance

- **[Project Management Overview](./octoacme-project-management-overview.md)** - Introduction to OctoAcme's approach, roles, artifacts, and communication cadence. *Start here for a high-level understanding.*

- **[Roles & Personas](./octoacme-roles-and-personas.md)** - Definitions of typical project roles (Developers, Product Managers, Project Managers) and their responsibilities.

### Project Lifecycle Phases

- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template.

- **[Project Planning](./octoacme-project-planning.md)** - Turn an approved initiative into an actionable plan and backlog. Covers sprint planning, risk management, and the Definition of Done.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Day-to-day execution, team rhythm, quality standards, and progress tracking. Includes blocker escalation procedures.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Standardized release process, deployment procedures, rollback planning, and release notes template.

### Supporting Processes

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Identify, manage, and communicate risks and dependencies. Includes the Risk Register template and escalation paths.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings, run effective retrospectives, and drive continuous improvements with action tracking.

---

## Quick Start Guides

### I'm new to OctoAcme. Where do I start?
→ Read [Project Management Overview](./octoacme-project-management-overview.md)

### I'm starting a new project. What should I do?
→ Follow [Project Initiation Guide](./octoacme-project-initiation.md), then [Project Planning](./octoacme-project-planning.md)

### I need to understand my role or team responsibilities.
→ Check [Roles & Personas](./octoacme-roles-and-personas.md)

### I need guidance on day-to-day delivery.
→ See [Execution & Tracking](./octoacme-execution-and-tracking.md)

### I need to manage risks or escalate issues.
→ Use [Risk Management & Communication](./octoacme-risks-and-communication.md)

### I'm preparing for a release.
→ Follow [Release & Deployment Guide](./octoacme-release-and-deployment.md)

### I'm running a retrospective or improving our process.
→ Check [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## Key Contacts & Communication

- **Weekly sync**: PM + PdM alignment
- **Twice-weekly standups**: Delivery team (or as agreed)
- **Monthly updates**: Stakeholder briefings
- **Ad-hoc escalations**: As needed for blockers or risks

---

## Contributing to OctoAcme Docs

To suggest updates or additions to these process documents, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

*Last updated: 2026-05-19*
