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

## Quality Assurance Lead

### Role Summary
The QA Lead oversees test strategies, coordinates QA efforts across the team, and ensures quality standards are met before features reach production.

### Responsibilities
- Design and maintain test plans (manual and automated)
- Review acceptance criteria with the Product Manager and Developers
- Execute or coordinate functional, regression, and exploratory testing
- Report, triage, and escalate critical defects
- Maintain the QA sign-off gate as part of the Definition of Done

### Goals
- Prevent defect leakage to production
- Build confidence in each release through consistent, repeatable testing
- Improve test coverage and shift testing earlier in the cycle

### Typical Communication / Touchpoints
- Sprint planning and backlog grooming with the Product Manager and Developers
- Daily standups for defect status and blocking issues
- Release readiness review with the Release Manager and Project Manager
- Post-release retrospectives to improve test coverage and processes
- *See also:* [Execution & Tracking — Quality & Testing](octoacme-execution-and-tracking.md), [Release & Deployment — Pre-release requirements](octoacme-release-and-deployment.md)

---

## UX Designer

### Role Summary
The UX Designer drives user-centered design, ensuring that features are usable, accessible, and aligned with user needs before and during development.

### Responsibilities
- Create wireframes, mockups, and interactive prototypes for new features
- Conduct user research and usability testing
- Define and enforce accessibility standards (e.g., WCAG compliance)
- Collaborate with Developers to ensure design fidelity in implementation
- Provide design sign-off before a feature is considered complete

### Goals
- Reduce usability issues discovered late in the cycle
- Ensure features are accessible and inclusive by default
- Align design intent with technical implementation

### Typical Communication / Touchpoints
- Kickoff meetings and requirements sessions with the Product Manager
- Design reviews with Developers (async or sync)
- Usability testing sessions; share findings with Product Manager and Project Manager
- Release readiness check to confirm UX acceptance
- *See also:* [Project Planning — Cross-functional kickoff](octoacme-project-planning.md), [Execution & Tracking — Quality & Testing](octoacme-execution-and-tracking.md)

---

## Data Analyst

### Role Summary
The Data Analyst provides data-driven insights to guide feature decisions, define success metrics, and measure outcomes after delivery.

### Responsibilities
- Define and instrument success metrics in collaboration with the Product Manager
- Build and maintain dashboards for live monitoring of key signals
- Analyze usage data to support prioritization and retrospectives
- Identify anomalies or unexpected trends post-release

### Goals
- Enable evidence-based decision-making across the team
- Ensure metrics are instrumented before launch, not after
- Surface actionable insights from data in a timely way

### Typical Communication / Touchpoints
- Planning sessions with the Product Manager to define success metrics
- Sprint reviews to report on current signal health
- Release sign-off to confirm metrics instrumentation is in place
- Retrospectives to present data findings on previous cycle outcomes
- *See also:* [Execution & Tracking — Reporting & Metrics](octoacme-execution-and-tracking.md), [Project Planning](octoacme-project-planning.md)

---

## Release Manager

### Role Summary
The Release Manager coordinates all deployment activities, manages pre- and post-release checklists, and communicates release status to stakeholders.

### Responsibilities
- Manage and own the deployment schedule and release calendar
- Run pre-release and post-release checklists
- Coordinate go/no-go decisions with QA Lead, Project Manager, and Developers
- Draft and distribute release notes and stakeholder announcements
- Oversee rollback and incident plans for each release

### Goals
- Deliver releases on schedule with minimal risk
- Ensure all release gates (QA, UX, metrics, change approval) are met before deployment
- Provide clear and timely release communication to all stakeholders

### Typical Communication / Touchpoints
- Release planning sessions with Project Manager and Developers
- Go/no-go review with QA Lead and Product Manager
- Post-deploy verification coordination with Developers
- Stakeholder and support team announcements after each release
- *See also:* [Release & Deployment Guide](octoacme-release-and-deployment.md), [Cross-functional Touchpoints Checklist](octoacme-cross-functional-checklist.md)

---

## Change Manager

### Role Summary
The Change Manager ensures that significant changes are properly reviewed, approved, and communicated to minimize disruption to teams and stakeholders.

### Responsibilities
- Maintain the change request and approval workflow
- Assess change impact and coordinate approval with relevant stakeholders
- Communicate approved changes and timelines to impacted teams
- Track post-change outcomes and gather feedback
- Maintain a change log for audit and compliance purposes

### Goals
- Reduce unplanned disruption from undocumented or unapproved changes
- Ensure all significant changes have an owner, an approval record, and a rollback option
- Improve stakeholder confidence through transparent change communication

### Typical Communication / Touchpoints
- Change review sessions with Project Manager and Release Manager
- Pre-release communications coordinated with Release Manager
- Post-change retrospective inputs shared with Project Manager
- Stakeholder briefings before and after significant changes
- *See also:* [Risk Management & Communication](octoacme-risks-and-communication.md), [Release & Deployment Guide](octoacme-release-and-deployment.md)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

