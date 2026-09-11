# OctoAcme Project Management Docs

## Welcome to OctoAcme's Project Management Framework

OctoAcme uses a structured, customer-first approach to project delivery. These docs provide guidance for managing projects across all lifecycle phases—from initial concept through retrospectives and continuous improvement.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decision-making. The organization operates across five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. 

During initiation, teams validate business needs and create a lightweight Project One-pager that defines the problem, goals, success metrics, and stakeholders. Once approved, the planning phase breaks work into prioritized backlog items with acceptance criteria, estimates scope using T-shirt sizing or story points, and identifies dependencies and risks. This structured approach ensures alignment before execution begins and reduces rework downstream.

Execution and delivery are managed through a team rhythm that combines daily standups (15 minutes), weekly delivery syncs, and sprint-based planning cycles. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforce pull request workflows requiring small, well-documented PRs with automated testing and linting before review. Quality assurance is embedded throughout execution with unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Regular demos and milestone reviews keep stakeholders informed, while a three-level blocker escalation path (team triage → PM escalation → sponsor escalation) ensures critical issues receive prompt attention.

The organization defines three primary personas with distinct accountabilities: **Developers** implement features, maintain tests, and identify technical risks; **Product Managers** define vision, prioritize backlogs, and measure outcomes; and **Project Managers** coordinate schedules, manage risks, and facilitate cross-team communication. Communication is sustained through weekly PM-PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates, with a single source of truth maintained in project repositories. A formal **Risk Register** captures issues with impact, likelihood, owner, and mitigation plans, reviewed at weekly syncs.

Finally, OctoAcme emphasizes continuous improvement through structured retrospectives after each sprint, release, or significant milestone. Teams capture what went well, identify improvements, and assign 2–3 prioritized action items with clear owners and due dates. This learning-oriented culture, combined with governance gates at each phase transition, ensures the organization delivers reliably while systematically refining its processes based on real-world experience.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle at a Glance

**Initiation** → **Planning** → **Execution** → **Release** → **Close & Retrospective**

## Documentation Index

Select a doc based on your current project phase or role:

| Phase/Topic | Document | Purpose |
|---|---|---|
| Overview | [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) | Quick intro to roles, principles, and key artifacts |
| Initiation | [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md) | Validate business need, align stakeholders, go/no-go decision |
| Planning | [OctoAcme Project Planning](./octoacme-project-planning.md) | Break work into shippable increments, define milestones |
| Execution | [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery, workflows, quality, metrics |
| Risk Management | [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify, track, and communicate risks and dependencies |
| Release | [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize release process, checklists, rollback playbook |
| Retrospectives | [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, drive improvements |
| Roles | [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) | Understand PM, PdM, Developer, QA, and Stakeholder roles |

## Quick Start by Role

- **New Project Managers**: Start with [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Risk Management](./octoacme-risks-and-communication.md)
- **Product Managers**: Review [Overview](./octoacme-project-management-overview.md) and [Planning](./octoacme-project-planning.md)
- **Developers**: Focus on [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Release](./octoacme-release-and-deployment.md)
- **QA/Testing**: Review [Execution & Tracking](./octoacme-execution-and-tracking.md) for quality standards and [Release](./octoacme-release-and-deployment.md) for deployment procedures
- **All Roles**: Review [Roles and Personas](./octoacme-roles-and-personas.md) to understand responsibilities

## How to Use These Docs

1. **Onboarding**: New team members should start with this README, then review the [Roles and Personas](./octoacme-roles-and-personas.md) doc to understand their position in the framework.

2. **Project Setup**: When starting a new project, follow the sequence: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution & Tracking](./octoacme-execution-and-tracking.md).

3. **Cross-functional Work**: Reference [Risk Management & Communication](./octoacme-risks-and-communication.md) to coordinate dependencies and keep stakeholders aligned.

4. **Release Management**: Before deploying to production, consult [Release & Deployment Guide](./octoacme-release-and-deployment.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md) for quality gates.

5. **Continuous Improvement**: After completing a sprint or release, follow the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) process to capture learnings.

6. **Adding to Copilot Spaces**: To use these docs as context in Copilot Spaces, add them to `.copilot/` or reference them in your project's Copilot Space configuration.

## Key Contacts & Communication

Refer to your project charter or project README for PM and Product Lead contact info.

---

**Last Updated**: September 2026  
**Maintained By**: Project Management Office  
**Questions?** Refer to the relevant process doc or reach out to your Project Manager.
