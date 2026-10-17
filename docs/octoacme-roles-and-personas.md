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

## Additional Suggested Personas
The following personas are recommended additions to clarify ownership for cross-functional responsibilities, improve handoffs, and speed decision-making. Each entry includes responsibilities and interaction notes with existing roles.

### Technical Lead
Role Summary: A senior engineering role responsible for technical direction, architecture decisions, and maintaining codebase health.

Responsibilities:
- Make and document architecture and design decisions for the project
- Lead technical design reviews and approve significant technical changes
- Mentor engineers and raise technical quality standards
- Identify technical debt and propose mitigation plans

Interactions:
- Works with PM and PdM to evaluate technical feasibility and trade-offs when defining scope
- Coordinates closely with Developers to ensure designs are implemented as intended
- Collaborates with QA to define testability and acceptance criteria for complex features
- Advises the Release Manager on deployment risks and readiness

### Release Manager
Role Summary: Coordinates and owns release planning, runbooks, and verification for deployments to staging and production.

Responsibilities:
- Plan and schedule releases across teams and components
- Maintain release checklists, runbooks, and rollback plans
- Coordinate pre-release smoke tests, canary rollouts, and post-deploy verification
- Communicate release windows and post-release status to stakeholders

Interactions:
- Works with PM to align release timing with product priorities and stakeholder needs
- Collaborates with Developers and Technical Lead to confirm deployment readiness
- Coordinates with QA for smoke tests and verification plans
- Engages Support Liaison and on-call teams for post-release monitoring and incident response

### Support Liaison (Customer / Support Representative)
Role Summary: The primary contact between customer/support and the delivery team for operational issues and escalations.

Responsibilities:
- Triage and document customer-reported issues with reproduction steps and impact
- Serve as an escalation point for high-severity customer incidents
- Coordinate communication between Support, Engineering, and Product teams
- Maintain records of incidents and contribute to post-incident analysis

Interactions:
- Notifies PM and Release Manager when customer-impacting issues affect releases or timelines
- Works with Developers and Technical Lead to reproduce and prioritize fixes
- Updates the Risk Register and communicates status to stakeholders
- Provides user-facing context for retrospective and continuous improvement

### Data Analyst / Measurement Lead
Role Summary: Owns metrics, telemetry, and measurement plans to evaluate feature impact and guide decisions.

Responsibilities:
- Define success metrics and instrumentation requirements for features and experiments
- Build dashboards and run analyses to measure releases and experiments
- Validate data quality and ensure telemetry is actionable
- Surface insights and recommendations based on usage and performance data

Interactions:
- Partners with PdM on defining measurable success criteria
- Works with Developers to ensure required telemetry is implemented
- Shares regular reports with PM, PdM, and stakeholders to inform prioritization and retrospectives
- Helps QA and Release Manager by providing signals for release verification

### UX Researcher / Designer Representative
Role Summary: Represents user research and design considerations to ensure usability and accessibility are considered in feature delivery.

Responsibilities:
- Conduct user research and usability testing
- Define usability acceptance criteria and accessibility requirements
- Provide design reviews and feedback during planning and implementation
- Collaborate on prototypes and validate user flows

Interactions:
- Works closely with PdM to translate user needs into feature requirements
- Collaborates with Developers to ensure designs are implemented faithfully
- Provides inputs to QA for usability-focused test cases
- Contributes to retrospectives with qualitative user feedback

### Security / Compliance Representative
Role Summary: Ensures security, privacy, and compliance considerations are included in planning, development, and release activities.

Responsibilities:
- Identify security/compliance requirements and review designs
- Run or review security scans and threat assessments
- Advise on mitigations, controls, and documentation needed for compliance
- Escalate security incidents to the Security on-call and relevant stakeholders

Interactions:
- Engages during planning to annotate risks and required controls
- Reviews PRs or designs that affect sensitive areas or compliance boundaries
- Works with Technical Lead and Developers to remediate findings
- Coordinates with PM and Release Manager on compliance gates for releases

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## How these additions improve project outcomes
- Clarifies decision ownership and reduces delays in technical and release decisions
- Improves release reliability and incident response through clearer coordination
- Ensures better measurement and user-centered design decisions inform prioritization
- Makes cross-team handoffs explicit and reduces rework and ambiguity

---
