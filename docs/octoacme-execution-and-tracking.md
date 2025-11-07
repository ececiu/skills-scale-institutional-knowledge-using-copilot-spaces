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

## Cross-functional Responsibilities During Execution

### Developers
- **Daily**: Commit code, update PR status, attend standups
- **Hand-off to QA Lead**: PR ready for testing with test instructions
- **Hand-off to UX Designer**: Implementation ready for design review
- **Collaboration with DevOps Engineer**: Deployment issues and build failures

### QA Lead
- **Daily**: Execute test plans, triage defects, update test results
- **Hand-off to Developers**: Defect reports with reproduction steps
- **Hand-off to Project Manager**: Test status and quality metrics
- **Collaboration with Business Analyst**: Validate requirements interpretation

### DevOps Engineer
- **Daily**: Monitor CI/CD pipelines, address build issues
- **Hand-off to Developers**: Pipeline failures and infrastructure issues
- **Hand-off to QA Lead**: Test environment availability
- **Collaboration with Project Manager**: Deployment readiness updates

### UX Designer
- **Weekly**: Review implementations against design specs
- **Hand-off to Developers**: Design feedback and iteration requests
- **Hand-off to QA Lead**: UI/UX acceptance criteria clarifications
- **Collaboration with Customer Success**: User feedback incorporation

### Business Analyst
- **As needed**: Clarify requirements and acceptance criteria
- **Hand-off to Developers**: Requirement refinements
- **Hand-off to QA Lead**: Updated test scenarios
- **Collaboration with Product Manager**: Scope change impact analysis

### Customer Success Manager
- **Weekly**: Share customer feedback and priority escalations
- **Hand-off to Product Manager**: Feature requests and pain points
- **Hand-off to QA Lead**: Customer-reported issues for validation
- **Collaboration with Project Manager**: Customer impact communications

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] **Developers**: Code reviews completed within 24 hours
- [ ] **QA Lead**: Test results reported daily
- [ ] **DevOps Engineer**: Pipeline health monitored continuously
- [ ] **UX Designer**: Design reviews conducted weekly
- [ ] **Business Analyst**: Requirement changes documented and communicated
- [ ] **Customer Success Manager**: Customer feedback incorporated into backlog

**Related:** Cross-functional accountability improvements per [Issue #6](https://github.com/ececiu/skills-scale-institutional-knowledge-using-copilot-spaces/issues/6).
