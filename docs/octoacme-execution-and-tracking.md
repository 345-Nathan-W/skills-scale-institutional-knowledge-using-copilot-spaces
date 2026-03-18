# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed — coordinated by the **QA Lead**
- **UX review**: UX Designer confirms design fidelity and accessibility before a feature moves to Done
- **QA sign-off gate**: QA Lead must approve before any item is closed or included in a release
- *See also:* [Roles & Personas — QA Lead and UX Designer](octoacme-roles-and-personas.md), [Release & Deployment — Pre-release requirements](octoacme-release-and-deployment.md)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager — owned by the **Data Analyst**
- Use dashboards for key signals (errors, latency, usage) — set up and maintained by the **Data Analyst**
- Confirm metrics instrumentation is in place before each release

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] QA Lead assigned and test plan drafted
- [ ] UX Designer assigned and design assets available to Developers
- [ ] Success metrics defined and instrumentation confirmed with Data Analyst

*See also:* [Cross-functional Touchpoints Checklist](octoacme-cross-functional-checklist.md), [Roles & Personas](octoacme-roles-and-personas.md)
