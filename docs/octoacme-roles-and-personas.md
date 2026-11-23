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

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads set technical direction, guide architecture and design decisions, and help the delivery team manage implementation and technical risk.

### Responsibilities
- Define implementation approaches and architectural direction
- Identify technical risks and propose mitigations
- Guide Developers through complex design and delivery decisions
- Review significant changes and promote maintainable solutions
- Balance technical quality with delivery constraints

### Goals
- Deliver reliable, scalable, and maintainable solutions
- Improve engineering consistency and technical decision quality
- Reduce avoidable technical debt and delivery uncertainty

### Interactions with Existing Roles
- Work with **Developers** on design, code reviews, estimation, and implementation.
- Work with **Product Managers** to explain feasibility, constraints, and trade-offs.
- Work with **Project Managers** to identify technical dependencies, risks, and schedule impacts.

---

## Release Managers

### Role Summary
Release Managers coordinate release planning and readiness across teams, ensuring that changes are deployed safely and communicated effectively.

### Responsibilities
- Plan release windows and coordinate rollout activities
- Validate release readiness and required approvals
- Coordinate rollback and mitigation plans
- Communicate release status to delivery teams and stakeholders
- Support post-release verification

### Goals
- Reduce release risk and deployment disruption
- Create consistent, observable, and repeatable releases
- Ensure stakeholders and support teams are prepared for change

### Interactions with Existing Roles
- Work with **Project Managers** on release schedules, dependencies, and stakeholder communication.
- Work with **Developers** on release candidates, fixes, and rollback details.
- Work with **QA Leads** on smoke tests and acceptance readiness.
- Work with **Operations / SRE** on deployment, monitoring, and rollback plans.
- Coordinate with customer-facing teams on release announcements and known issues.

---

## UX Researchers and Designers

### Role Summary
UX Researchers and Designers identify user needs and translate them into usable, accessible interaction patterns and requirements.

### Responsibilities
- Conduct user research and validate assumptions
- Define interaction patterns, prototypes, and usability requirements
- Translate findings into acceptance criteria and design guidance
- Review implementation for usability and accessibility
- Communicate findings and decisions to delivery teams

### Goals
- Improve product usability and accessibility
- Reduce the risk of building solutions that do not meet user needs
- Create consistent, evidence-based customer experiences

### Interactions with Existing Roles
- Work with **Product Managers** on discovery, outcomes, and prioritization.
- Work with **Developers** on design constraints, implementation details, and feedback.
- Work with **QA Leads** to incorporate usability and accessibility checks into acceptance.
- Work with **Project Managers** to surface design dependencies and validation needs.

---

## Operations and Site Reliability Engineers (SRE)

### Role Summary
Operations and SRE personas ensure that products are observable, supportable, scalable, and recoverable in production.

### Responsibilities
- Define operational readiness, capacity, and reliability requirements
- Establish monitoring, alerting, and incident-response practices
- Maintain runbooks and recovery procedures
- Identify production risks and operational dependencies
- Support deployments and post-release verification

### Goals
- Improve service reliability and operational efficiency
- Reduce mean time to detect and resolve incidents
- Ensure production readiness before and after release

### Interactions with Existing Roles
- Work with **Developers** on instrumentation, runbooks, and reliability improvements.
- Work with **Release Managers** on deployment readiness, rollback plans, and verification.
- Work with **Project Managers** to communicate operational risk and escalation needs.
- Work with **Security Leads** on security operations and incident response.

---

## Security Leads

### Role Summary
Security Leads establish security requirements, identify threats and vulnerabilities, and guide secure implementation and incident response.

### Responsibilities
- Define security requirements and review critical threats
- Coordinate vulnerability assessment and remediation
- Guide secure design and implementation practices
- Support security reviews and incident response
- Communicate security risks and required actions

### Goals
- Reduce security vulnerabilities and compliance risk
- Build security considerations into planning and delivery
- Improve incident readiness and recovery

### Interactions with Existing Roles
- Work with **Developers** on secure implementation and remediation.
- Work with **QA Leads** on security test coverage and validation.
- Work with **Project Managers** to plan security work and escalate unresolved risk.
- Work with **Operations / SRE** during security incidents and production hardening.
- Advise **Product Managers** on security trade-offs and customer impact.

---

## Business Analysts / Requirements Analysts

### Role Summary
Business Analysts clarify business rules and requirements, maintain traceability, and help teams resolve ambiguity before and during delivery.

### Responsibilities
- Document, validate, and refine business requirements
- Maintain traceability between needs, requirements, and acceptance criteria
- Identify cross-process dependencies and edge cases
- Facilitate requirement reviews with stakeholders
- Resolve ambiguities and maintain a single understanding of scope

### Goals
- Improve requirement clarity and traceability
- Reduce rework caused by ambiguity or missed dependencies
- Improve alignment between business needs and delivered outcomes

### Interactions with Existing Roles
- Work with **Product Managers** to clarify outcomes, priorities, and scope.
- Work with **Developers** to explain business rules and constraints.
- Work with **QA Leads** to define acceptance scenarios and edge cases.
- Work with **Project Managers** to communicate requirement dependencies and changes.
- Work with stakeholders to validate that documented needs reflect real expectations.

---

## Customer Support and Success Leads

### Role Summary
Customer Support and Success Leads represent customer impact, surface recurring needs and incidents, and prepare teams and customers for adoption.

### Responsibilities
- Collect and prioritize customer feedback and operational pain points
- Communicate known issues, workarounds, and impacts
- Prepare support content and customer-facing guidance
- Represent adoption and service concerns in planning
- Coordinate feedback after releases and milestones

### Goals
- Improve customer satisfaction and adoption
- Ensure customer impact is visible in product decisions
- Reduce confusion and support effort during releases

### Interactions with Existing Roles
- Work with **Product Managers** to provide customer evidence and roadmap feedback.
- Work with **Developers** and **Release Managers** on issue reproduction, fixes, workarounds, and release readiness.
- Work with **Project Managers** on communications, training, and launch dependencies.
- Work with **UX Researchers and Designers** to share behavioral and usability feedback.

---

## QA Leads / Test Managers

### Role Summary
QA Leads and Test Managers define testing strategy, coordinate quality activities, and confirm that work meets agreed acceptance and release criteria.

### Responsibilities
- Define test strategy and quality gates
- Coordinate unit, integration, end-to-end, and manual testing efforts
- Identify quality risks and coverage gaps
- Confirm acceptance criteria and readiness for release
- Track defects and coordinate resolution priorities

### Goals
- Improve test coverage and defect prevention
- Provide clear, evidence-based quality decisions
- Reduce escaped defects and release uncertainty

### Interactions with Existing Roles
- Work with **Developers** on testability, defect triage, and automated coverage.
- Work with **Product Managers** to clarify and validate acceptance criteria.
- Work with **Project Managers** to communicate quality risk and release timing.
- Work with **Release Managers** on smoke tests and deployment readiness.
- Work with **UX and Security Leads** to incorporate usability and security validation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Keep responsibilities and decision boundaries clear so each role complements, rather than duplicates, existing roles.

