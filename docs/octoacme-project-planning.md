# OctoAcme — Project Planning

## Purpose
Turn an approved initiative into an actionable plan and backlog for delivery.

## Objectives
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities

## Activities
1. Kickoff meeting with stakeholders and delivery team (including QA Lead, UX Designer, Data Analyst, Release Manager, and Change Manager where applicable)
2. Create prioritized backlog with acceptance criteria
3. Estimate scope (T-shirt sizing or story points)
4. Define Definition of Done (DoD) — see [Definition of Done Addendum](#definition-of-done-addendum) below
5. Identify dependencies and integration points
6. Create release plan and milestone map

## Backlog Item Template
- Title:
- Description:
- Acceptance criteria:
- Priority:
- Estimate:
- Owner:
- Related docs/links:

## Sprint / Iteration Planning
- Timebox planning to agreed sprint length
- Pull items that meet DoD and have clear acceptance criteria
- Ensure team capacity is respected

## Risk & Dependency Management
- Capture in Risk Register:
  - ID, Description, Impact, Probability, Owner, Mitigation
- Mark cross-team dependencies in the project board and escalate during weekly syncs

## Planning Checklist
- [ ] Project kickoff held (PM, PdM, Developers, QA Lead, UX Designer, Data Analyst, Release Manager as applicable)
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented (including QA, UX, and metrics criteria — see addendum below)
- [ ] Initial test plan / QA approach drafted with QA Lead
- [ ] UX Designer engaged and design assets planned
- [ ] Success metrics defined with Data Analyst
- [ ] Change Manager notified of significant planned changes

*See also:* [Cross-functional Touchpoints Checklist](octoacme-cross-functional-checklist.md), [Roles & Personas](octoacme-roles-and-personas.md)

## Definition of Done Addendum

In addition to standard coding and review criteria, items are only considered **Done** when:

**QA**
- [ ] QA Lead has reviewed and signed off on acceptance criteria coverage
- [ ] All critical and high-severity defects are resolved or deferred with explicit approval
- [ ] Regression suite passes (automated or manual as agreed)

**UX**
- [ ] UX Designer has reviewed the implemented feature against the approved design
- [ ] Accessibility requirements met (e.g., keyboard navigation, screen reader support, color contrast)
- [ ] Any open UX feedback is resolved or explicitly deferred

**Analytics / Metrics**
- [ ] Success metrics defined and agreed with Product Manager and Data Analyst
- [ ] Instrumentation (events, logs, or telemetry) is implemented and verified
- [ ] Relevant dashboards updated or created

*See also:* [Execution & Tracking — Quality & Testing](octoacme-execution-and-tracking.md)
