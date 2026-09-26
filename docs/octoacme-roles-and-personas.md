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

## Executive Sponsor

### Role Summary
Executive Sponsors provide strategic sponsorship, secure funding, and make major trade-off decisions. They champion the initiative at the leadership level and serve as the escalation point for business-impacting issues.

### Responsibilities
- Approve project charter and resource allocation
- Make go/no-go decisions at key gates
- Resolve business-level trade-offs and dependencies
- Ensure alignment with organizational strategy
- Support escalations and remove blockers at the leadership level
- Review progress and outcomes at key milestones

### Goals
- Ensure project delivers measurable business value
- Maintain strategic alignment and resource availability
- Support team success and risk mitigation

### Decision Authority
- Budget and resource approval
- Major scope and timeline trade-offs
- Escalation resolution for business-impacting issues

### Interactions with Existing Roles
- **With Project Manager**: reviews project plan, approves milestones, escalates blockers
- **With Product Manager**: aligns on business outcomes and success metrics
- **With Developers**: understands technical trade-offs and risks
- **With Stakeholders**: communicates strategic decisions and progress

### Typical Communication
- Project charter review and approval (initiation)
- Milestone and gate reviews (planning, execution)
- Monthly executive updates and risk escalations
- Decision logs for major trade-offs

---

## Business Analyst

### Role Summary
Business Analysts elicit and document business needs, translate stakeholder input into clear requirements, and maintain traceability throughout the project. They bridge the gap between business intent and technical implementation.

### Responsibilities
- Conduct stakeholder interviews and discovery sessions
- Document requirements and acceptance criteria
- Create and maintain requirements traceability matrices
- Support product manager with use cases and user stories
- Clarify scope and ambiguities with stakeholders
- Validate solutions against original business needs

### Goals
- Ensure requirements are clear, complete, and testable
- Reduce misunderstandings and rework
- Maintain clear linkage between business needs and deliverables

### Decision Authority
- Requirement validation and approval (with Product Manager)
- Scope clarification and change impact assessment

### Interactions with Existing Roles
- **With Product Manager**: collaborates on requirements definition and prioritization
- **With Developers**: clarifies acceptance criteria and technical feasibility
- **With QA/Testing**: ensures test coverage aligns with requirements
- **With Project Manager**: tracks requirement status and scope changes

### Typical Communication
- Requirements workshop and discovery sessions (planning)
- Requirement reviews and sign-off (execution)
- Traceability and scope change documentation
- Requirements validation in testing and UAT

---

## UX/UI Designer or Researcher

### Role Summary
UX/UI Designers and Researchers represent user needs and advocate for usability. They conduct user research, design experiences, and validate solutions to ensure features are intuitive, valuable, and meet user expectations.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Validate design solutions with users and stakeholders
- Ensure accessibility and inclusive design principles
- Collaborate on feature prioritization based on user impact
- Support QA/Testing with usability test scenarios

### Goals
- Deliver intuitive, user-centered experiences
- Reduce user friction and support burden
- Ensure accessibility for all users

### Decision Authority
- Usability acceptance criteria and validation approach
- Design trade-offs and UX recommendations

### Interactions with Existing Roles
- **With Product Manager**: influences prioritization based on user research and impact
- **With Developers**: reviews technical feasibility of design solutions
- **With QA/Testing**: defines usability test scenarios and acceptance criteria
- **With Project Manager**: advises on user impact of timeline and scope changes

### Typical Communication
- User research findings and insights (initiation, planning)
- Design reviews and feedback sessions (planning, execution)
- Usability testing results and recommendations
- Design specifications and component documentation

---

## Technical Lead or Architect

### Role Summary
Technical Leads and Architects own technical direction, define system architecture, and ensure solutions are scalable, maintainable, and aligned with technical standards. They balance technical excellence with project constraints.

### Responsibilities
- Define technical architecture and design patterns
- Review technical design and code
- Identify technical risks and propose mitigation strategies
- Ensure alignment with technical standards and best practices
- Support estimation and capacity planning
- Mentor developers on technical approaches

### Goals
- Deliver technically sound, maintainable solutions
- Minimize technical debt and future rework
- Ensure system scalability and performance

### Decision Authority
- Technical architecture and major design decisions
- Technical trade-offs and trade-offs between speed and quality
- Technical risk escalation

### Interactions with Existing Roles
- **With Developers**: guides implementation and design reviews
- **With Product Manager**: advises on technical feasibility and constraints
- **With Project Manager**: estimates and flags technical dependencies and risks
- **With Release/Operations**: ensures operational readiness and monitoring capabilities

### Typical Communication
- Architecture and design reviews (planning)
- Technical spike investigations and recommendations
- Technical risk assessment and mitigation plans
- Code review and design walkthroughs

---

## Release/Deployment Manager or Site Reliability/Operations Representative

### Role Summary
Release/Deployment Managers and Site Reliability/Operations Representatives coordinate production readiness, manage deployments, ensure system reliability, and support operational handoff. They are accountable for safe, observable, and reversible releases.

### Responsibilities
- Coordinate release planning and readiness verification
- Manage deployment execution and rollback procedures
- Ensure observability, monitoring, and alerting are in place
- Prepare operational runbooks and incident response procedures
- Conduct pre-release smoke testing and health checks
- Support production troubleshooting and incident response

### Goals
- Enable safe, reliable releases to production
- Minimize downtime and customer impact
- Maintain high system observability and operational excellence

### Decision Authority
- Release go/no-go approval (with Product Manager and Technical Lead)
- Deployment timing and approach decisions
- Rollback decisions in case of critical issues

### Interactions with Existing Roles
- **With Developers**: ensures code is ready for production (performance, logging, monitoring)
- **With QA/Testing**: verifies functional and operational readiness
- **With Project Manager**: coordinates release timeline and risk communication
- **With Technical Lead**: validates architecture supports operational requirements
- **With Support/Enablement**: communicates release notes and operational changes

### Typical Communication
- Release readiness checklist review (execution)
- Deployment and rollback procedures (release)
- Post-deploy verification and incident response
- Operational monitoring and on-call escalations

---

## Security/Privacy Representative

### Role Summary
Security and Privacy Representatives advise on threat modeling, privacy requirements, and security reviews. They ensure solutions are secure by design and comply with security and privacy standards.

### Responsibilities
- Participate in threat modeling and risk assessment
- Review security and privacy requirements
- Conduct security code reviews and architectural reviews
- Advise on vulnerability remediation and mitigation
- Ensure compliance with security and privacy standards
- Support incident response and post-incident analysis

### Goals
- Build security and privacy into the solution from the start
- Minimize security vulnerabilities and compliance risks
- Enable rapid incident response and recovery

### Decision Authority
- Security and privacy requirement approval
- Security issue prioritization and remediation decisions
- Release security approval (go/no-go for security posture)

### Interactions with Existing Roles
- **With Technical Lead**: advises on security architecture and design patterns
- **With Developers**: reviews code for security vulnerabilities
- **With QA/Testing**: defines security testing and validation scenarios
- **With Release/Operations**: advises on security monitoring and incident response
- **With Project Manager**: escalates security risks and compliance issues

### Typical Communication
- Threat modeling and security design reviews (planning)
- Security code review and vulnerability scanning (execution)
- Security incident response and post-incident retrospectives
- Compliance and security audit participation

---

## Customer Support or Enablement Representative

### Role Summary
Customer Support and Enablement Representatives bring customer-impact perspective to prioritization, prepare support and enablement materials, and ensure the organization is ready to support customers post-release.

### Responsibilities
- Represent customer impact and support burden in prioritization
- Prepare support documentation and FAQs
- Create enablement materials for customers and internal teams
- Coordinate training and communication for releases
- Provide feedback on usability and support impact
- Support incident response and customer communication

### Goals
- Ensure customers are enabled and satisfied with releases
- Reduce support burden and customer friction
- Accelerate customer time-to-value

### Decision Authority
- Enablement and support readiness approval
- Release communication and customer messaging approval

### Interactions with Existing Roles
- **With Product Manager**: advises on customer impact and support burden
- **With UX/UI Designer**: validates usability from support perspective
- **With Developers**: clarifies implementation for support and troubleshooting
- **With Project Manager**: coordinates customer communication and training
- **With Release/Operations**: ensures operational changes are communicated to customers

### Typical Communication
- Customer impact assessments and feedback (planning)
- Support readiness reviews and documentation (execution)
- Release notes and customer communication review
- Customer training and enablement planning

---

## Data/Analytics Partner

### Role Summary
Data and Analytics Partners define measurement plans, instrument solutions for data collection, and analyze outcomes. They enable data-driven decisions and measure impact against success metrics.

### Responsibilities
- Define measurement plans and success metrics instrumentation
- Design analytics dashboards and reporting
- Implement data collection and logging requirements
- Analyze post-release performance and impact
- Provide data-driven insights for optimization
- Support A/B testing and experimentation

### Goals
- Enable measurement of project success and customer impact
- Provide data for informed decision-making and iteration
- Demonstrate ROI and business value of initiatives

### Decision Authority
- Measurement plan approval and metrics definition
- Analytics and data collection approach decisions

### Interactions with Existing Roles
- **With Product Manager**: collaborates on success metrics and measurement approach
- **With Developers**: defines instrumentation and logging requirements
- **With Release/Operations**: ensures reliable data collection and dashboards
- **With Project Manager**: reports on outcome metrics and ROI

### Typical Communication
- Measurement plan and metrics definition (initiation, planning)
- Instrumentation and logging reviews (execution)
- Analytics dashboard setup and reporting (release)
- Post-release analysis and impact reporting

---

## Project Lifecycle-to-Role Responsibility Matrix

This matrix shows which roles have primary accountability (A), secondary responsibility (R), consultation input (C), or informational awareness (I) across key project phases:

| Activity | Sponsor | PM | PdM | Developer | BA | Designer | Tech Lead | Release/Ops | Security | Support | Analytics |
|----------|---------|----|----|-----------|----|----|-----------|------------|----------|---------|-----------|
| **Initiation** |
| Validate business need | A | R | R | I | C | I | I | I | I | C | C |
| Define success metrics | R | R | A | I | C | C | I | I | I | C | A |
| Stakeholder alignment | A | R | R | I | I | I | I | I | I | I | I |
| Identify risks | R | A | R | C | I | I | C | C | C | I | I |
| **Planning** |
| Define requirements | R | C | A | C | A | C | C | I | C | C | I |
| Create acceptance criteria | R | C | A | C | A | C | I | I | C | C | I |
| Design solution | R | I | A | C | C | A | A | C | C | C | I |
| Identify technical risks | I | R | I | C | I | I | A | C | C | I | I |
| Identify security needs | I | C | I | I | I | I | C | I | A | I | I |
| Plan testing strategy | I | R | C | C | C | C | C | C | C | C | C |
| Define measurement plan | I | C | A | I | I | I | I | I | I | I | A |
| **Execution** |
| Implement features | I | I | I | A | I | C | C | I | I | I | I |
| Code review | I | I | I | A | I | I | A | I | C | I | I |
| Testing & QA | I | R | C | C | C | C | C | C | C | I | I |
| Usability validation | I | C | A | C | I | A | I | I | I | C | I |
| Security review | I | I | I | C | I | I | C | I | A | I | I |
| **Release** |
| Pre-release verification | I | R | C | C | I | I | C | A | C | C | C |
| Deploy to production | I | C | I | C | I | I | C | A | C | I | I |
| Run smoke tests | I | C | I | C | I | I | C | A | I | I | I |
| Customer communication | R | R | A | I | I | I | I | C | I | A | I |
| **Retrospective** |
| Review outcomes | A | A | A | C | C | C | C | C | C | C | A |
| Capture learnings | R | A | A | C | C | C | C | C | C | I | I |
| Document action items | R | A | R | I | I | I | I | I | I | I | I |

**Legend:** A = Accountable (primary decision-maker), R = Responsible (does the work), C = Consulted (provides input), I = Informed (kept updated)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Lifecycle-to-Role Matrix to clarify responsibilities and escalation paths in specific project scenarios.
