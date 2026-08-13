# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality assurance strategies, manage testing processes, and validate that solutions meet acceptance criteria and quality standards.

### Responsibilities
- Define testing strategy and approach (unit, integration, end-to-end, regression)
- Create and maintain test plans aligned with release requirements
- Validate acceptance criteria before features are marked complete
- Identify and triage quality issues with severity and priority
- Collaborate with developers on testability and automation
- Report quality metrics and trends to project leadership

### Goals
- Ensure shipped features meet quality standards and acceptance criteria
- Reduce defects reaching production
- Improve test coverage and automation over time

### Typical Communication
- Participation in sprint planning and acceptance criteria review
- Daily standups and quality status updates
- Test reports and regression test results before releases

### Interaction with Other Roles
- Works closely with **Developers** to establish testability requirements and review automated tests
- Collaborates with **Product Managers** to validate acceptance criteria and feature completeness
- Partners with **Project Managers** to identify quality risks and ensure testing timelines align with release schedules
- Supports **Technical Leads** in defining test automation architecture and coverage strategies

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, evaluate technical trade-offs, and ensure solutions are scalable, maintainable, and aligned with technical standards.

### Responsibilities
- Review technical designs and propose improvements
- Identify technical risks and propose mitigations
- Guide technology selection and architectural decisions
- Mentor developers on best practices and code quality
- Ensure solutions align with platform standards and scalability requirements
- Participate in design and code reviews

### Goals
- Deliver technically sound, maintainable solutions
- Minimize technical debt and refactoring needs
- Enable team growth through mentorship and guidance

### Typical Communication
- Technical design discussions and code reviews
- Architecture decision records (ADRs)
- Risk identification in sprint planning and weekly syncs

### Interaction with Other Roles
- Mentors and guides **Developers** on architectural patterns and technical best practices
- Advises **Project Managers** on technical feasibility and complexity estimates
- Collaborates with **QA/Testing Leads** to define test automation architecture
- Supports **Product Managers** with feasibility assessments of product features
- Works with **DevOps Engineers** to ensure architectural decisions support deployment and operations

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on process improvements and collaborative practices.

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and reviews
- Remove impediments and blockers that prevent team progress
- Coach team members on agile practices and self-organization
- Track sprint metrics and communicate status
- Drive process improvements based on team feedback
- Foster psychological safety and inclusive team dynamics

### Goals
- Enable teams to deliver consistently within sprints
- Increase team velocity and predictability over time
- Create a culture of continuous improvement and learning

### Typical Communication
- Sprint ceremonies and team huddles
- One-on-ones to identify and resolve blockers
- Retro action item tracking and follow-up

### Interaction with Other Roles
- Enables **Developers** by removing blockers and facilitating collaboration
- Supports **Project Managers** in coordinating delivery and managing team capacity
- Coaches all roles on agile principles and team effectiveness
- Escalates impediments to **Project Managers** and stakeholders when needed

---

## Business Stakeholder / Sponsor

### Role Summary
Business Stakeholders provide strategic direction, approve resource allocation, and ensure projects align with business objectives and priorities.

### Responsibilities
- Define business objectives and success criteria
- Approve project scope, timeline, and resource requirements
- Provide guidance on business priorities and trade-offs
- Communicate project value to executive leadership
- Review progress against business metrics
- Make go/no-go decisions at key project gates

### Goals
- Ensure projects deliver measurable business value
- Align product delivery with strategic business priorities
- Maintain executive visibility and stakeholder confidence

### Typical Communication
- Project kickoff and approval meetings
- Monthly stakeholder updates and reviews
- Executive escalations and decision gates
- Release announcements

### Interaction with Other Roles
- Sets strategic direction for **Product Managers** and **Project Managers**
- Reviews progress with **Project Managers** and provides guidance
- Approves resource allocation with **Project Managers**
- Receives status updates and metrics from **Product Managers** on business outcomes

---

## Operations / DevOps Engineer

### Role Summary
DevOps Engineers manage infrastructure, deployment pipelines, monitoring, and incident response to ensure reliable production operations.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Manage cloud infrastructure, networking, and security configurations
- Monitor production systems and establish alerting for critical issues
- Respond to incidents and coordinate incident resolution
- Document runbooks and deployment procedures
- Optimize system performance, reliability, and cost

### Goals
- Ensure reliable, secure, and performant production systems
- Reduce deployment friction and enable rapid, safe releases
- Minimize incident frequency and resolution time

### Typical Communication
- Deployment coordination with development teams
- Incident response and post-incident reviews
- Infrastructure decisions and capacity planning
- Release coordination and deployment procedures

### Interaction with Other Roles
- Collaborates with **Developers** on deployment requirements and environment setup
- Works with **Technical Leads** on infrastructure architecture and scalability
- Coordinates with **Project Managers** on release timelines and deployment windows
- Supports **QA/Testing Leads** with test environment provisioning
- Responds to incidents triggered by issues discovered by **QA** or users

---

## UX / Design Lead

### Role Summary
UX/Design Leads drive user experience strategy, lead design collaboration, and ensure solutions are usable, accessible, and aligned with design standards.

### Responsibilities
- Conduct user research and translate insights into design requirements
- Create wireframes, prototypes, and design specifications
- Collaborate with developers on implementation and design fidelity
- Validate designs through user testing and feedback
- Define accessibility and design standards for the platform
- Mentor team members on UX and design best practices

### Goals
- Deliver user-centered, accessible solutions that delight customers
- Reduce friction and improve user satisfaction
- Establish consistent, scalable design systems and patterns

### Typical Communication
- Design reviews and feedback sessions
- Collaboration with developers during implementation
- User research and testing results
- Design system documentation and guidelines

### Interaction with Other Roles
- Partners with **Developers** during implementation to ensure design fidelity
- Collaborates with **Product Managers** to translate customer needs into design
- Works with **QA/Testing Leads** to define acceptance criteria for user experience
- Advises **Project Managers** on design complexity and timeline implications
- Shares design standards with **Technical Leads** for consistency and scalability

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
