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

## Engineering Manager (EM) / Tech Lead Manager

### Role Summary
Engineering Managers ensure the team can deliver sustainably. They support staffing, delivery health, escalation handling, and coordination across the engineering organization.

### Responsibilities
- Confirm team capacity and delivery constraints during planning
- Support prioritization trade-offs with Product Managers and Project Managers
- Remove organizational blockers that slow execution
- Help surface delivery risks early and secure the right support
- Coach engineering contributors and maintain a healthy delivery pace

### Goals
- Keep delivery predictable and sustainable
- Reduce avoidable delays caused by staffing or dependency issues
- Improve team health, clarity, and execution quality

### Typical Communication
- Weekly delivery and staffing check-ins with Project Managers
- Scope and sequencing discussions with Product Managers
- Escalation support and coaching conversations with Developers and Technical Leads

---

## Technical Lead / Staff Engineer (Architecture Owner)

### Role Summary
Technical Leads guide solution design and architecture decisions for complex changes. They help the team make sound trade-offs while protecting maintainability, reliability, and scalability.

### Responsibilities
- Lead technical design reviews for significant changes
- Identify architectural risks and propose mitigations
- Define implementation guardrails for observability, testing, and operability
- Support Developers with complex implementation decisions
- Align technical choices with delivery milestones and constraints

### Goals
- Keep the architecture coherent as the product evolves
- Reduce technical risk before implementation and release
- Improve the quality and consistency of technical decisions

### Typical Communication
- Design reviews and technical planning with Developers
- Feasibility and sequencing discussions with Project Managers and Product Managers
- Collaboration with Security and SRE partners on higher-risk changes

---

## UX / Product Designer

### Role Summary
UX / Product Designers shape the user experience for new features and workflows. They translate product intent into flows, wireframes, and design guidance that teams can build confidently.

### Responsibilities
- Create user flows, wireframes, prototypes, and design specifications
- Clarify usability requirements and edge cases before development starts
- Support acceptance criteria with user experience expectations
- Validate proposed solutions through lightweight research or feedback loops
- Partner with engineering to keep designs implementable

### Goals
- Improve usability and reduce rework caused by unclear requirements
- Keep customer journeys coherent across releases
- Ensure design decisions support measurable product outcomes

### Typical Communication
- Discovery and prioritization sessions with Product Managers
- Design dependency planning with Project Managers
- Design reviews and implementation handoffs with Developers

---

## QA / Test Engineer

### Role Summary
QA / Test Engineers improve quality by defining test coverage, validating acceptance criteria, and helping the team catch regressions before release.

### Responsibilities
- Define the test approach for new features and high-risk changes
- Create or maintain automated and manual test coverage where needed
- Validate acceptance criteria and edge cases before release
- Coordinate feature acceptance and sign-off with the delivery team
- Surface quality risks early enough to adjust scope or timing

### Goals
- Reduce escaped defects and release-time surprises
- Make quality expectations explicit for the team
- Improve confidence in release readiness

### Typical Communication
- Test planning and defect triage with Developers
- Acceptance coverage and readiness discussions with Product Managers
- Release planning and QA sign-off coordination with Project Managers

---

## Security / AppSec Reviewer

### Role Summary
Security / AppSec Reviewers help the team identify and reduce security risk before changes reach production. They focus on secure design, review depth, and required controls for sensitive work.

### Responsibilities
- Review security-sensitive designs and implementation plans
- Identify when threat modeling or additional controls are needed
- Define required scans, checks, and approvals before release
- Partner with the team to resolve discovered vulnerabilities
- Support incident escalation for security-impacting issues

### Goals
- Reduce the likelihood and severity of security issues
- Make security expectations clear early in the lifecycle
- Avoid release delays caused by late security surprises

### Typical Communication
- Secure design reviews with Technical Leads and Developers
- Risk and release readiness conversations with Project Managers
- Scope and trade-off discussions with Product Managers when security work affects timelines

---

## SRE / Operations / Platform Engineer

### Role Summary
SRE / Operations / Platform Engineers ensure systems are deployable, observable, and reliable in production. They help teams prepare for safe releases and effective incident response.

### Responsibilities
- Review operational readiness for deployments and major changes
- Validate monitoring, alerting, runbooks, and rollback plans
- Identify capacity, reliability, or platform dependencies
- Support release planning for higher-risk or coordinated launches
- Help improve incident response and post-release verification practices

### Goals
- Keep releases safe and recoverable
- Improve production reliability and observability
- Reduce operational toil and unclear ownership during incidents

### Typical Communication
- Deployment planning and escalation discussions with Project Managers
- Instrumentation and operational readiness reviews with Developers
- Reliability trade-off discussions with Product Managers and Technical Leads

---

## Customer Support / Support Lead

### Role Summary
Customer Support / Support Leads represent the customer support perspective during planning and release. They help teams prepare support content, escalation paths, and customer communications.

### Responsibilities
- Share recurring customer pain points and support signals
- Review support readiness for launches, known issues, and troubleshooting guidance
- Coordinate customer-facing communications when changes require it
- Help define escalation paths for customer-impacting issues
- Feed post-release support learnings back into planning and retrospectives

### Goals
- Reduce avoidable support volume after release
- Improve readiness for customer-facing changes and incidents
- Shorten time to resolution when issues are reported

### Typical Communication
- Stakeholder and incident communication planning with Project Managers
- Prioritization input and customer signal reviews with Product Managers
- Troubleshooting guidance and known-issue reviews with Developers and QA

---

## Data Analyst / Data Scientist

### Role Summary
Data Analysts and Data Scientists help the team define how success will be measured. They support tracking plans, analysis, and post-release learning for data-informed decisions.

### Responsibilities
- Define or refine success metrics with Product Managers
- Clarify event tracking, dashboard, or experiment needs during planning
- Validate that required data collection is included in delivery scope
- Analyze early release results and support retrospective discussions
- Highlight data quality or instrumentation gaps that limit decision-making

### Goals
- Improve confidence in outcome measurement
- Reduce ambiguity around whether changes are delivering value
- Support better prioritization with reliable evidence

### Typical Communication
- Success metric and experiment planning with Product Managers
- Tracking implementation reviews with Developers
- Milestone and reporting alignment with Project Managers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
