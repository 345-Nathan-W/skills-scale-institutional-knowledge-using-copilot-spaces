# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- **QA Lead sign-off**: QA Lead confirms test coverage is complete and no critical defects are open
- **UX validation**: UX Designer confirms design intent is met and accessibility standards are satisfied
- **Metrics instrumentation**: Data Analyst confirms success metrics are instrumented and dashboards are live
- **Change approval**: Change Manager has reviewed and approved any significant changes in scope
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Release Manager has confirmed go/no-go with QA Lead and Product Manager
- [ ] QA Lead has signed off (no critical open defects)
- [ ] UX Designer has validated design and accessibility acceptance
- [ ] Data Analyst has confirmed metrics instrumentation is live
- [ ] Change Manager has approved and communicated significant changes
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

*See also:* [Cross-functional Touchpoints Checklist](octoacme-cross-functional-checklist.md), [Roles & Personas — Release Manager, Change Manager](octoacme-roles-and-personas.md)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
