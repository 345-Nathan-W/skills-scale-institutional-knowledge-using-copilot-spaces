# OctoAcme — Cross-functional Touchpoints Checklist

## Purpose
Ensure that all relevant supporting roles are engaged at the right times during planning, execution, and release. Use this checklist at project kickoff, sprint start, and release readiness reviews.

*See also:* [Roles & Personas](octoacme-roles-and-personas.md), [Project Planning](octoacme-project-planning.md), [Release & Deployment Guide](octoacme-release-and-deployment.md)

---

## Planning / Kickoff Touchpoints

| Role | Touchpoint | Timing |
|---|---|---|
| QA Lead | Review acceptance criteria; draft test plan | At kickoff and backlog refinement |
| UX Designer | Confirm design assets and accessibility requirements | At kickoff; before sprint start |
| Data Analyst | Define and agree on success metrics; confirm instrumentation plan | At kickoff and sprint planning |
| Release Manager | Review release schedule and deployment window | At kickoff and before each release |
| Change Manager | Review scope for significant changes; initiate change requests if needed | At kickoff and when scope changes |

**Checklist**
- [ ] QA Lead has reviewed and accepted the test plan for this increment
- [ ] UX Designer has confirmed design assets are available and approved
- [ ] Data Analyst has agreed on success metrics and instrumentation approach
- [ ] Release Manager has confirmed the release window and deployment plan
- [ ] Change Manager has been notified of any significant changes in scope

---

## Execution Touchpoints

| Role | Touchpoint | Timing |
|---|---|---|
| QA Lead | Ongoing defect triage; mid-sprint QA review | During sprint; escalate blockers in standup |
| UX Designer | Design review with Developers; usability check on implemented features | During sprint, before feature is marked Done |
| Data Analyst | Verify instrumentation is implemented; review early signal data | Before feature merge/close |
| Release Manager | Confirm release readiness; prepare release notes | 1–2 days before deployment |
| Change Manager | Confirm change approvals are in place; draft stakeholder communications | Before release |

**Checklist**
- [ ] Defects triaged and critical issues resolved or approved for deferral (QA Lead)
- [ ] Implemented features reviewed by UX Designer against approved designs
- [ ] Metrics instrumentation verified by Data Analyst
- [ ] Release notes drafted and reviewed by Release Manager
- [ ] Change approvals recorded and stakeholder communications drafted (Change Manager)

---

## Release Readiness Review

Run this checklist as the final gate before any production deployment.

**Quality**
- [ ] QA Lead has signed off — no critical or high-severity open defects
- [ ] Automated tests (CI) pass on the release candidate
- [ ] End-to-end smoke tests complete on staging

**UX**
- [ ] UX Designer has validated the release candidate against approved designs
- [ ] Accessibility checks complete

**Data / Metrics**
- [ ] Data Analyst has confirmed all success metrics are instrumented
- [ ] Monitoring dashboards are live and baseline established

**Release Coordination**
- [ ] Release Manager has confirmed deployment window and rollback plan
- [ ] Release notes finalized and stakeholder announcement ready

**Change Management**
- [ ] Change Manager has recorded all approved changes
- [ ] Communication sent to impacted teams before deployment

*For the full deployment steps, see* [Release & Deployment Guide — Deployment Checklist](octoacme-release-and-deployment.md).
