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

### Key Inter-role Interactions
- **With Product Managers**: Clarify feature requirements and provide implementation estimates
- **With UX Designer**: Review designs for technical feasibility and implementation details
- **With QA Lead**: Ensure testability and address defects
- **With DevOps Engineer**: Coordinate deployment requirements and troubleshoot infrastructure issues
- **With Business Analyst**: Clarify functional requirements and edge cases

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

### Key Inter-role Interactions
- **With Developers**: Review technical constraints and trade-offs for features
- **With UX Designer**: Define user problems and validate design solutions
- **With Business Analyst**: Provide high-level requirements for detailed analysis
- **With QA Lead**: Define quality standards and acceptance thresholds
- **With Customer Success Manager**: Prioritize features based on customer feedback and impact

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

### Key Inter-role Interactions
- **With Product Managers**: Align on priorities, scope, and timeline trade-offs
- **With Developers**: Track progress, remove blockers, and manage technical dependencies
- **With DevOps Engineer**: Plan infrastructure and deployment schedules
- **With QA Lead**: Coordinate test planning and release readiness
- **With Business Analyst**: Manage requirement changes and impact assessment
- **With Customer Success Manager**: Communicate release plans and coordinate customer impact

---

## UX Designer

### Role Summary
UX Designers ensure products are intuitive, accessible, and delightful. They conduct user research, create wireframes and prototypes, and validate designs through usability testing.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, mockups, and interactive prototypes
- Define information architecture and user flows
- Collaborate with Product Managers on feature requirements
- Work with Developers to ensure design implementation fidelity
- Establish and maintain design systems and style guides
- Validate designs through user testing and feedback

### Goals
- Deliver user-centered designs that solve real problems
- Maintain consistency across product experiences
- Reduce friction and improve user satisfaction metrics
- Ensure accessibility standards are met

### Typical Communication
- Weekly design reviews with Product and Engineering
- Usability testing sessions with users
- Design handoff documentation and implementation reviews
- Feedback sessions with Customer Success on user pain points

### Key Inter-role Interactions
- **With Product Managers**: Translate requirements into user flows and validate solutions against user needs
- **With Developers**: Provide detailed design specs, review implementations, and iterate on feasibility
- **With QA Lead**: Collaborate on acceptance criteria for UI/UX quality
- **With Business Analyst**: Incorporate business requirements into user experience design
- **With Customer Success**: Gather user feedback to inform design improvements

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather requirements, analyze processes, define acceptance criteria, and ensure deliverables meet stakeholder expectations.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into functional specifications
- Create process maps and data flow diagrams
- Define detailed acceptance criteria for features
- Conduct gap analysis and feasibility assessments
- Facilitate requirements workshops and reviews
- Support UAT (User Acceptance Testing) planning and execution

### Goals
- Ensure solutions align with business objectives
- Minimize requirement ambiguity and rework
- Improve process efficiency through analysis
- Facilitate clear communication between business and technical teams

### Typical Communication
- Requirements gathering sessions with stakeholders
- Specification reviews with Development team
- UAT coordination with QA and business users
- Status updates to Project Manager on requirement changes

### Key Inter-role Interactions
- **With Product Managers**: Refine product vision into detailed requirements
- **With Project Managers**: Provide requirement clarity and impact analysis for scope changes
- **With Developers**: Clarify functional requirements and answer implementation questions
- **With QA Lead**: Define test scenarios based on business requirements
- **With UX Designer**: Ensure designs meet business process needs

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, CI/CD pipelines, and automation that enable reliable, fast deployments. They ensure system reliability, observability, and security.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC) and cloud resources
- Implement monitoring, logging, and alerting systems
- Automate deployment and rollback procedures
- Ensure security scanning and compliance in pipelines
- Support incident response and root cause analysis
- Optimize system performance and cost efficiency

### Goals
- Reduce deployment friction and lead time
- Maximize system uptime and reliability
- Automate repetitive operational tasks
- Maintain security and compliance standards

### Typical Communication
- Daily collaboration with Developers on build/deployment issues
- Incident post-mortems and on-call handoffs
- Infrastructure planning with Project and Product teams
- Security reviews with QA Lead

### Key Inter-role Interactions
- **With Developers**: Enable smooth code integration and deployment workflows
- **With Project Managers**: Provide deployment estimates and infrastructure planning
- **With QA Lead**: Integrate automated testing into CI/CD pipelines
- **With Product Managers**: Ensure infrastructure supports product roadmap needs
- **With Customer Success**: Provide system health metrics and incident updates

---

## QA Lead

### Role Summary
QA Leads ensure quality standards are met throughout the development lifecycle. They define test strategies, coordinate testing activities, and advocate for quality in all deliverables.

### Responsibilities
- Define test strategy and quality standards
- Create and maintain test plans and test cases
- Coordinate manual and automated testing efforts
- Review acceptance criteria and Definition of Done
- Execute and oversee test execution across environments
- Track and triage defects with appropriate severity
- Ensure test coverage for critical user journeys
- Facilitate UAT and beta testing programs

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and effectiveness
- Reduce time to identify and resolve quality issues
- Advocate for testability in design and implementation

### Typical Communication
- Test plan reviews with Project and Product teams
- Daily defect triage with Developers
- Test readiness and sign-off for releases
- Quality metrics reporting to stakeholders

### Key Inter-role Interactions
- **With Developers**: Collaborate on testability, review test coverage, and triage defects
- **With Business Analyst**: Validate test scenarios against business requirements
- **With DevOps Engineer**: Integrate automated tests into CI/CD pipelines
- **With UX Designer**: Validate UI/UX implementation against design specifications
- **With Project Managers**: Report quality risks and testing progress

---

## Customer Success Manager

### Role Summary
Customer Success Managers ensure customers achieve their goals using the product. They gather feedback, coordinate support escalations, and advocate for customer needs in product development.

### Responsibilities
- Onboard new customers and ensure product adoption
- Monitor customer health metrics and engagement
- Gather and synthesize customer feedback and pain points
- Coordinate support escalations and resolution
- Advocate for customer needs in product planning
- Identify expansion and upsell opportunities
- Conduct customer training and enablement sessions

### Goals
- Maximize customer satisfaction and retention
- Drive product adoption and value realization
- Reduce churn and increase customer lifetime value
- Surface customer insights to inform product roadmap

### Typical Communication
- Regular check-ins with key customer accounts
- Feedback synthesis and prioritization with Product team
- Escalation coordination with Support and Engineering
- Success metrics and case studies for stakeholders

### Key Inter-role Interactions
- **With Product Managers**: Provide customer insights and prioritize feature requests
- **With UX Designer**: Share user feedback on experience and usability
- **With QA Lead**: Coordinate customer-reported issues for testing validation
- **With Project Managers**: Communicate customer impact of planned releases
- **With Developers**: Facilitate customer demo sessions and gather technical feedback

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The inter-role interactions highlight collaboration points and hand-off responsibilities across the project lifecycle.

