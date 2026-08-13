# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. Our framework applies to all cross-functional projects that deliver product features, services, and integrations.

### Core Principles
- **Customer-First**: Prioritize customer value and usability in all decisions
- **Iterative Delivery**: Deliver small, testable increments to gather feedback early
- **Clear Ownership**: Each project has a named Project Manager (PM) and Product Lead who are accountable for delivery
- **Data-Informed Decisions**: Measure impact and iterate based on evidence
- **Psychological Safety**: Encourage feedback, learning, and continuous improvement

### Key Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs, context, and approvals

---

## Quick Start by Role

### 👤 Project Managers
Start here to understand OctoAcme's overall project management framework and how to coordinate delivery:
- [Project Management Overview](./octoacme-project-management-overview.md) — High-level framework, roles, and artifacts
- [Project Planning](./octoacme-project-planning.md) — How to create actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery management

### 📊 Product Managers
Start here to understand how to initiate, define, and measure project success:
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate ideas and align stakeholders
- [Project Management Overview](./octoacme-project-management-overview.md) — Core framework and artifacts
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and iterate

### 👨‍💻 Developers
Start here to understand what's expected during planning and execution:
- [Project Planning](./octoacme-project-planning.md) — Backlog items, acceptance criteria, and Definition of Done
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Daily standups, PR workflows, and quality standards
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — How we prepare and deploy releases

---

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle from initiation through continuous improvement.

### Phase 1: Initiation
**Validate ideas and align stakeholders on business need and success criteria.**

- [Project Initiation Guide](./octoacme-project-initiation.md) — Define the problem, identify stakeholders, and create a lightweight plan
- **Key deliverables**: Project One-pager, stakeholder list, initial timeline, risk list
- **Decision gate**: Proceed to planning when success metrics are clear and stakeholders agree on priority

### Phase 2: Planning
**Break work into shippable increments and identify dependencies.**

- [Project Planning](./octoacme-project-planning.md) — Create prioritized backlog, estimate scope, and define Definition of Done
- **Key deliverables**: Prioritized backlog with acceptance criteria, release plan, milestone map, risk register
- **Success criteria**: Clear DoD, estimated items, and identified cross-team dependencies

### Phase 3: Execution
**Build, test, review, and iterate toward milestones.**

- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Daily standups, sprint planning, PR workflows, and quality assurance
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Monitor and communicate risks, dependencies, and status
- **Team rhythm**: Daily standups (15 min), weekly delivery sync, demos at sprint end
- **Quality standards**: Unit tests, integration tests, security scanning, manual QA when needed

### Phase 4: Release
**Deploy to production with confidence and minimal risk.**

- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback procedures
- **Key deliverables**: Release notes, deployment verification, stakeholder announcement
- **Safety measures**: Smoke tests, staging validation, post-deploy verification

### Phase 5: Close & Improve
**Capture learnings and convert them into actionable improvements.**

- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Run retrospectives, track action items, measure impact
- **Cadence**: After each sprint, release, or important milestone
- **Outcome**: Action items with owners and timelines fed back into project backlog

---

## Reference Documentation

### Understanding Team Roles
- [OctoAcme Personas](./octoacme-roles-and-personas.md) — Detailed responsibilities, goals, and communication patterns for Project Managers, Product Managers, and Developers

### Managing Risks & Communication
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, assess, mitigate, and communicate risks throughout the project lifecycle

### Key Frameworks
- [Project Management Overview](./octoacme-project-management-overview.md) — Core framework, lifecycle overview, and communication cadence

---

## Navigation by Use Case

### ❓ "I'm starting a new project"
1. Start with [Project Initiation Guide](./octoacme-project-initiation.md)
2. Understand roles in [OctoAcme Personas](./octoacme-roles-and-personas.md)
3. Review [Project Management Overview](./octoacme-project-management-overview.md) for the big picture

### 📋 "I need to create a project plan"
1. Read [Project Planning](./octoacme-project-planning.md)
2. Reference the backlog item template and Definition of Done
3. Use [Risk Management & Communication](./octoacme-risks-and-communication.md) to identify dependencies

### 🚀 "We're executing and need to stay on track"
1. Follow guidance in [Execution & Tracking](./octoacme-execution-and-tracking.md)
2. Use [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalations
3. Run demos and standups per the team rhythm

### 🎯 "I need to release to production"
1. Consult [Release & Deployment Guide](./octoacme-release-and-deployment.md)
2. Prepare release notes and deployment checklist
3. Plan post-deployment verification and rollback procedures

### 💡 "We're done with the sprint/release. What's next?"
1. Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
2. Track action items in your backlog or project board
3. Measure the impact of improvements from prior retrospectives

---

## Contributing to Process Documentation

These documentation files represent OctoAcme's institutional knowledge and are continuously refined based on team feedback and lessons learned.

### How to suggest updates:

Use the **[Add Content to Project Management Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template to:
- Propose new content or clarifications
- Fill a documented gap in the process
- Incorporate a best practice or lesson learned
- Suggest structural improvements

### What we look for in updates:
- ✓ Content aligns with existing process docs
- ✓ Update improves clarity or closes a documented gap
- ✓ Proposed content has been reviewed with stakeholders (if needed)

---

## Key Artifacts at a Glance

| Artifact | Purpose | Maintained by | Updated |
|----------|---------|---|---|
| Project One-pager | Problem, goal, success metrics, risks, timeline | Product Manager | Initiation & Planning |
| Backlog | Prioritized list of work items with acceptance criteria | Product Manager | Every sprint |
| Definition of Done (DoD) | Team-agreed standards for what "done" means | Team | Planning phase |
| Risk Register | ID, description, impact, likelihood, mitigation, owner | Project Manager | Weekly |
| Release Plan | Milestones, timeline, deployment checklist | Project Manager | Planning & pre-release |
| Retrospective Notes | Learnings, action items, owners, due dates | Project Manager | After sprint/release |

---

## Communication Cadence

- **Daily**: Standups (15 min) — focus on progress, blockers, dependencies
- **Weekly**: PM + PdM sync — alignment on roadmap, priorities, risks
- **Twice-weekly** (or as agreed): Delivery team standups
- **Monthly**: Stakeholder updates — status, impact, upcoming priorities
- **Ad-hoc**: Escalations — blockers, security incidents, high-impact risks

---

## Questions?

- **Onboarding help**: Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Process improvements**: Open an issue using the [Add Content to Project Management Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- **Questions about your role**: Refer to [OctoAcme Personas](./octoacme-roles-and-personas.md)

---

**Last updated**: August 13, 2026  
**Scope**: Applies to all cross-functional projects at OctoAcme
