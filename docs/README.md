# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Guide. This folder contains comprehensive documentation for how OctoAcme runs projects from initiation through closure.

## Quick Start

OctoAcme follows a structured five-phase lifecycle:
1. **Initiation** - Validate the business need and align stakeholders
2. **Planning** - Break work into shippable increments and identify risks
3. **Execution** - Build, test, review, and iterate with clear quality standards
4. **Release** - Deploy to production with confidence and proper verification
5. **Retrospective** - Capture learnings and drive continuous improvement

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Named Project Manager and Product Lead for each project
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

OctoAcme maintains a structured approach to project management that emphasizes delivery excellence and strategic alignment. Each project is anchored by clear ownership—a dedicated Project Manager (PM) handles coordination and risk management, while a Product Manager (PdM) defines outcomes, prioritizes the backlog, and measures success. This dual-leadership model ensures both delivery excellence and strategic alignment. 

Projects begin with lightweight validation through a Project One-pager that captures the problem statement, measurable success metrics, stakeholders, timeline, and initial risks. Once stakeholders align and resources are confirmed, the team moves into detailed planning where work is broken into shippable increments with clear acceptance criteria and dependencies mapped.

During execution, OctoAcme maintains a structured cadence with daily standups (15 minutes), weekly delivery syncs, and sprint/milestone-based demos. Teams use GitHub Projects with a standardized workflow: Backlog → Ready → In Progress → In Review → QA → Done. Quality is non-negotiable: all code requires unit tests, integration tests where applicable, security scanning in CI, and manual QA for feature acceptance. Pull requests follow best practices with a 400-line guideline, mandatory issue linking, automated testing, and at least one approval before merge.

Risk management is proactive and systematic. Teams maintain a Risk Register tracking ID, description, impact, likelihood, owner, mitigation plan, and status—reviewed weekly during syncs. Communication is built into the cadence: weekly PM-PdM alignment, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations as needed. After each sprint, release, or milestone, teams conduct retrospectives to capture learnings and drive continuous improvement, with action items feeding back into the project backlog.

## Documentation by Phase

| Phase | Document | Best For |
|-------|----------|----------|
| Overview | [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) | Everyone - start here to understand the full approach |
| Initiation | [Project Initiation Guide](./octoacme-project-initiation.md) | Project sponsors, PMs, and stakeholders defining new work |
| Planning | [Project Planning](./octoacme-project-planning.md) | Project Managers and teams breaking down scope and timelines |
| Execution | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Developers, QA, and teams managing day-to-day delivery |
| Risk & Comms | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Project leads managing stakeholder communication and risk |
| Release | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Release managers and deployment teams |
| Retrospective | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Project leads capturing learnings post-project |
| Reference | [Roles and Personas](./octoacme-roles-and-personas.md) | Anyone learning about typical OctoAcme roles |

## By Role

- **Developers**: Start with [Execution & Tracking](./octoacme-execution-and-tracking.md), then review [Planning](./octoacme-project-planning.md) and [Roles](./octoacme-roles-and-personas.md)
- **Product Managers**: Review [Overview](./octoacme-project-management-overview.md) and [Initiation](./octoacme-project-initiation.md)
- **Project Managers**: Read all documents in order; focus on [Planning](./octoacme-project-planning.md), [Risk Management](./octoacme-risks-and-communication.md), and [Retrospectives](./octoacme-retrospective-and-continuous-improvement.md)
- **Stakeholders & Sponsors**: Review [Overview](./octoacme-project-management-overview.md) and [Initiation](./octoacme-project-initiation.md)
- **New Team Members**: Start with [Overview](./octoacme-project-management-overview.md) and [Roles](./octoacme-roles-and-personas.md)

## Key Artifacts

Across all phases, teams create and maintain:
- Project Charter / One-pager
- Prioritized backlog with acceptance criteria
- Risk register
- Sprint/iteration plans
- Release notes and deployment checklists
- Retrospective notes and action items
- Definition of Done (DoD)
- Weekly status reports

## Communication Cadence

- **Daily**: Team standups (15 minutes) - focus on progress, blockers, dependencies
- **Weekly**: PM-PdM alignment and delivery team syncs
- **Bi-weekly/Sprint-based**: Sprint planning and demos
- **Monthly**: Stakeholder updates
- **Post-milestone/release**: Retrospectives and incident reviews
- **Ad-hoc**: Escalations as needed

## Quality & Testing Standards

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Pull Request requirements: ≤400 lines, issue link, acceptance criteria, passing CI, ≥1 approval

## Getting Help

For questions about a specific process phase, consult the relevant document above. For cross-cutting concerns or process improvements, raise an issue with the label `process improvement`.

---

**Last Updated**: July 2026  
**Maintainer**: OctoAcme Project Management Office
