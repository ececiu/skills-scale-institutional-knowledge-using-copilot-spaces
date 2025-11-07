# OctoAcme Project Management Docs

This README provides a single entry point to the OctoAcme project management process documents. It summarizes how we run cross-functional projects and links to the detailed process artifacts in the docs/ folder so contributors and stakeholders can quickly find the guidance they need.

OctoAcme follows a lightweight, stage-gated lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. Projects begin with a Project One‑pager to validate the business need, define success metrics, and align stakeholders. Approved initiatives are translated into prioritized, estimated backlog items with clear acceptance criteria and a documented Definition of Done; from there the team builds a release plan and milestone map to guide delivery.

Execution is organized around a visible project board and a disciplined pull request workflow: small, testable PRs linked to issues, automated CI checks, and required reviews before merging. Teams track progress with regular standups, weekly delivery syncs, sprint demos, and dashboards for key metrics. Risks and dependencies are recorded in a Risk Register and escalated through defined levels when necessary to keep delivery on track.

Roles and communications are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, risks, and stakeholder communications; Developers implement and test; QA validates acceptance criteria; and Stakeholders provide input and decisions. Quality assurance emphasizes automated unit/integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and a staged release process with rollback playbooks. Retrospectives capture learnings and convert them to prioritized improvement work.

## Process Documents
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs
- Use this README as the first place to orient yourself to OctoAcme processes.
- Keep the Project One-pager and key artifacts in the project repo under docs/ or .copilot/ so Copilot Spaces can use them as context.
- If you need a new process doc or an update, create an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/.
