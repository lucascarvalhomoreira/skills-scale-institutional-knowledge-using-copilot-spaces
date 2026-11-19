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

## Scrum Master / Agile Delivery Lead

### Role Summary
The Scrum Master or Agile Delivery Lead protects team delivery flow, facilitates agile ceremonies, coaches delivery practices, and helps remove impediments.

### Responsibilities
- Facilitate planning, standups, reviews, retrospectives, and other agreed ceremonies
- Identify and help remove team-level impediments and dependencies
- Coach the team on iterative delivery, clear work-in-progress limits, and continuous improvement
- Surface delivery risks and improvement opportunities to the Project Manager
- Support the team in keeping backlog items and sprint goals understandable

### Goals
- Improve delivery predictability and team flow
- Reduce avoidable interruptions and cycle time
- Build a collaborative, psychologically safe team environment

### Typical Communication
- Daily delivery ceremonies and sprint planning
- Impediment and dependency tracking
- Retrospective action follow-up

### Interactions with Existing Roles
- Works with Developers to improve flow and resolve team-level blockers.
- Partners with the Product Manager to keep priorities and sprint goals clear without taking ownership of product decisions.
- Coordinates delivery risks, capacity concerns, and cross-team dependencies with the Project Manager.
- Engages Stakeholders when dependency decisions or organizational support require broader alignment.

### Decision and Accountability Boundaries
The Scrum Master facilitates process and delivery health; the Product Manager owns prioritization and outcomes, while the Project Manager owns coordination, schedules, risks, and status reporting.

---

## UX / Design Lead

### Role Summary
The UX/Design Lead represents customer usability and accessibility needs throughout discovery, design, implementation, and acceptance.

### Responsibilities
- Translate user research and customer needs into flows, wireframes, interaction patterns, and acceptance guidance
- Review designs and implementations for usability, consistency, and accessibility
- Collaborate on edge cases and user-facing error states
- Maintain reusable design patterns and usability standards
- Identify experience risks and propose alternatives

### Goals
- Deliver accessible, coherent, and usable experiences
- Reduce late-stage design rework
- Validate that implementation matches intended customer behavior

### Typical Communication
- Discovery and design reviews
- Story and acceptance-criteria refinement
- Usability reviews and design handoffs

### Interactions with Existing Roles
- Partners with the Product Manager on user needs, problem framing, and solution trade-offs.
- Works with Developers during implementation and design review; Developers retain ownership of technical feasibility and implementation.
- Collaborates with QA/Testing on usability and accessibility acceptance checks.
- Raises unresolved customer or experience risks to the Project Manager and relevant Stakeholders.

### Decision and Accountability Boundaries
The UX/Design Lead owns experience and design recommendations. The Product Manager owns product trade-offs, Developers own implementation decisions, and QA/Testing owns validation evidence.

---

## Data / Analytics Representative

### Role Summary
The Data/Analytics Representative ensures that project success measures are observable, instrumented, analyzed, and communicated as evidence for decisions.

### Responsibilities
- Define or refine measurable success metrics with the Product Manager
- Validate event tracking, dashboards, data quality, and reporting requirements
- Analyze experiments and delivery outcomes
- Communicate findings, limitations, and recommendations to delivery and stakeholder audiences
- Identify data dependencies and risks

### Goals
- Increase confidence in data-informed decisions
- Improve measurement coverage and reporting accuracy
- Demonstrate whether delivered work achieves expected outcomes

### Typical Communication
- Metrics and instrumentation planning
- Dashboard reviews and experiment readouts
- Weekly status updates or milestone findings

### Interactions with Existing Roles
- Works with the Product Manager to define outcomes and evaluate whether success criteria are met.
- Coordinates reporting requirements and milestone evidence with the Project Manager.
- Partners with Developers to define, implement, and validate telemetry and data pipelines.
- Presents findings and limitations to Stakeholders and supports QA/Testing when metrics require validation.

### Decision and Accountability Boundaries
The representative owns analysis quality and measurement recommendations. The Product Manager retains prioritization and outcome decisions; the Project Manager owns reporting process and schedule coordination.

---

## Security Lead

### Role Summary
The Security Lead defines security expectations, assesses threats and mitigations, and supports secure delivery and incident response.

### Responsibilities
- Define applicable security requirements and threat-model expectations
- Review design, implementation, dependencies, and release risks
- Coordinate security findings, mitigation ownership, and remediation timelines
- Support incident response and security escalation procedures
- Communicate relevant compliance and risk status

### Goals
- Reduce security and compliance risk
- Make security expectations clear before implementation
- Enable rapid, coordinated response to security incidents

### Typical Communication
- Threat modeling and security reviews
- Risk-register updates and remediation tracking
- Security incident response and post-incident reviews

### Interactions with Existing Roles
- Partners with Developers on secure implementation and remediation; Developers own code changes and security fixes.
- Provides security risks and mitigation status to the Project Manager for planning and escalation.
- Works with the Product Manager and Stakeholders to communicate risk trade-offs and compliance constraints.
- Collaborates with QA/Testing and the Release/DevOps Lead on security validation and release readiness.

### Decision and Accountability Boundaries
The Security Lead advises on security risk and may enforce organizational controls. Final delivery trade-offs are resolved by the accountable product and project leadership and any required security approval authorities.

---

## Release / DevOps Lead

### Role Summary
The Release/DevOps Lead owns deployment automation and operational readiness, including release coordination, rollback planning, and production observability.

### Responsibilities
- Maintain and improve deployment pipelines and environment readiness
- Define release, rollback, verification, and monitoring requirements
- Coordinate release windows and operational approvals
- Support incident detection and recovery for deployments
- Review deployment risk and operational dependencies

### Goals
- Deliver safe, repeatable, and observable releases
- Reduce deployment lead time and rollback risk
- Improve production reliability and recovery speed

### Typical Communication
- Release planning and go/no-go reviews
- Deployment checklists and smoke-test reports
- Post-deployment verification and incident reviews

### Interactions with Existing Roles
- Works with Developers on build, deployment, and production observability requirements.
- Coordinates validation with QA/Testing and confirms acceptance evidence before release.
- Provides release plans, risks, and status to the Project Manager.
- Partners with the Product Manager on rollout sequencing and communicates operational impacts to Stakeholders.
- Collaborates with the Security Lead on security gates and incident procedures.

### Decision and Accountability Boundaries
The Release/DevOps Lead owns operational release readiness and may stop or roll back a deployment according to agreed policy. Product rollout decisions remain with the Product Manager and project leadership.

---

## Support / Customer Success Representative

### Role Summary
The Support/Customer Success Representative represents operational and customer impact concerns, contributes readiness information, and returns real-world feedback to the delivery team.

### Responsibilities
- Communicate customer impact, support readiness, training, and known-issue needs
- Help reproduce or triage customer-reported issues with Developers
- Contribute operational scenarios and release communications
- Share usage feedback and recurring pain points for product prioritization
- Support stakeholder and customer readiness for releases

### Goals
- Improve customer readiness and issue resolution
- Reduce avoidable support volume and release disruption
- Ensure customer feedback informs product decisions

### Typical Communication
- Release readiness reviews
- Customer-impact and incident updates
- Backlog feedback and stakeholder briefings

### Interactions with Existing Roles
- Provides customer needs and operational feedback to the Product Manager.
- Works with Developers to clarify and reproduce customer issues and verify fixes.
- Coordinates support impact, customer communications, and escalation status with the Project Manager.
- Partners with QA/Testing on support scenarios and with Stakeholders on readiness and rollout expectations.

### Decision and Accountability Boundaries
The representative owns operational support readiness and customer-feedback synthesis. Product prioritization remains with the Product Manager, while delivery and escalation coordination remain with the Project Manager and Developers.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When a project does not have a dedicated person for a persona, assign its responsibilities to the appropriate existing role and document that assignment so accountability remains clear.
