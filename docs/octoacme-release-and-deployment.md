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
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Role-Specific Release Responsibilities

### QA Lead
- **Pre-release**: Complete final test pass in staging
- **Release day**: Execute production smoke tests
- **Post-release**: Monitor for quality regressions
- **Sign-off required**: Test completion confirmation

### DevOps Engineer
- **Pre-release**: Validate deployment pipeline and rollback procedures
- **Release day**: Execute deployment and monitor system health
- **Post-release**: Review deployment metrics and performance
- **Sign-off required**: Infrastructure readiness confirmation

### Business Analyst
- **Pre-release**: Validate all acceptance criteria met
- **Release day**: Available for requirement clarifications
- **Post-release**: Coordinate UAT if needed
- **Sign-off required**: Requirements fulfillment confirmation

### UX Designer
- **Pre-release**: Validate design implementation in staging
- **Release day**: Review production UI/UX
- **Post-release**: Monitor user feedback on design changes
- **Sign-off required**: Design quality confirmation

### Customer Success Manager
- **Pre-release**: Prepare customer communications and training materials
- **Release day**: Announce release to customers
- **Post-release**: Monitor customer feedback and adoption
- **Sign-off required**: Customer readiness confirmation

### Product Manager
- **Pre-release**: Validate feature completeness against roadmap
- **Release day**: Approve final release decision
- **Post-release**: Monitor success metrics
- **Sign-off required**: Product acceptance confirmation

### Project Manager
- **Pre-release**: Coordinate all sign-offs and communications
- **Release day**: Facilitate release coordination and escalations
- **Post-release**: Update stakeholders and close project artifacts
- **Sign-off required**: Overall release readiness confirmation

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] **QA Lead**: Sign-off on test completion
- [ ] **DevOps Engineer**: Sign-off on infrastructure readiness
- [ ] **Business Analyst**: Sign-off on requirements fulfillment
- [ ] **UX Designer**: Sign-off on design quality
- [ ] **Customer Success Manager**: Sign-off on customer readiness
- [ ] **Product Manager**: Sign-off on product acceptance
- [ ] **Project Manager**: Confirm all sign-offs received
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Cross-functional Release Hand-offs

### QA Lead → DevOps Engineer
- Hand off: Test results and known issues
- Expected action: Proceed with deployment or hold decision
- Timing: Pre-deployment gate

### DevOps Engineer → Project Manager
- Hand off: Deployment status and system health metrics
- Expected action: Stakeholder communication
- Timing: Post-deployment

### Project Manager → Customer Success Manager
- Hand off: Release notes and known issues
- Expected action: Customer communication and support enablement
- Timing: Immediately after production deployment

### Customer Success Manager → Product Manager
- Hand off: Early customer feedback and adoption metrics
- Expected action: Success metric tracking and issue prioritization
- Timing: 24-48 hours post-release

**Related:** Release accountability framework per [Issue #6](https://github.com/ececiu/skills-scale-institutional-knowledge-using-copilot-spaces/issues/6).

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
