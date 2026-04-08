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

## UX Designer

### Role Summary
UX Designers own the end-to-end user experience and design system. They translate product requirements into prototypes and validate solutions with users to ensure the product is usable and delightful.

### Responsibilities
- Create wireframes, user flows, and interactive prototypes
- Conduct user research and usability testing to validate solutions
- Maintain a consistent design system and component library
- Advocate for user needs throughout the product lifecycle
- Deliver design assets (specs, mock-ups) ready for developer handoff

### Goals
- Ensure a high-quality, intuitive user experience
- Reduce usability issues discovered in QA or post-release
- Align design decisions with product and business objectives

### Typical Communication
- Design reviews and critiques with Product Managers and Developers
- Usability test reports and findings summaries
- Annotated prototypes and design specs in collaborative tools (e.g., Figma)

### Interactions
- **Product Managers:** Collaborate on translating requirements into user flows; participate in backlog refinement to clarify UX scope
- **Developers:** Hand off design specs and assets; review implementations for fidelity and provide feedback
- **Business Analysts:** Align on user scenarios and acceptance criteria derived from business requirements
- **Project Managers:** Communicate design milestone progress and flag blockers affecting timelines
- **Support / Customer Success Managers:** Incorporate user feedback and reported pain points into design iterations

---

## DevOps / Platform Engineer

### Role Summary
DevOps / Platform Engineers ensure continuous integration, delivery, and operational reliability. They build and maintain automation pipelines, infrastructure, and observability tooling that enables teams to ship safely and quickly.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and release automation
- Provision and manage cloud infrastructure, environments, and secrets
- Implement monitoring, alerting, and incident-response runbooks
- Optimize system performance, reliability, and security posture
- Support Developers with local development environments and tooling

### Goals
- Maximize deployment frequency and minimize mean time to recovery (MTTR)
- Ensure infrastructure is secure, cost-effective, and scalable
- Reduce toil through automation and self-service tooling

### Typical Communication
- Infrastructure runbooks and architecture decision records (ADRs)
- On-call rotation schedules and incident post-mortems
- Pipeline status updates and deployment notifications in team channels

### Interactions
- **Developers:** Collaborate on build tooling, container images, and performance improvements; pair on CI/CD configuration
- **Project Managers:** Coordinate deployment windows and communicate release pipeline readiness
- **Product Managers:** Provide input on non-functional requirements (reliability, latency) during planning
- **Support / Customer Success Managers:** Respond to production incidents and provide root-cause updates
- **Business Analysts:** Clarify infrastructure constraints that may affect feature feasibility or timelines

---

## Business Analyst

### Role Summary
Business Analysts bridge business objectives with technical execution. They analyze workflows, gather requirements, and ensure the team is solving the right problem before writing a line of code.

### Responsibilities
- Gather, model, and document business requirements from stakeholders
- Define and maintain acceptance criteria for features and user stories
- Identify process gaps and recommend improvements
- Facilitate requirement workshops and sign-off sessions
- Maintain traceability between business goals and delivered features

### Goals
- Ensure delivered solutions meet documented business requirements
- Reduce rework caused by misunderstood or incomplete requirements
- Improve cross-functional alignment through clear, shared documentation

### Typical Communication
- Requirements documents and user story maps
- Acceptance criteria attached to backlog items
- Workshop summaries and stakeholder sign-off records

### Interactions
- **Product Managers:** Collaborate on translating strategy into detailed requirements; support backlog prioritization with business impact data
- **Developers:** Clarify requirements and acceptance criteria during sprint planning and refinement; validate implementations against requirements
- **Project Managers:** Share requirements status to inform timelines; flag scope changes that affect the plan
- **UX Designers:** Align on user scenarios and validate that designs satisfy stated business requirements
- **Support / Customer Success Managers:** Incorporate customer pain points and usage patterns into requirements analysis

---

## Support / Customer Success Manager

### Role Summary
Support / Customer Success Managers advocate for end users and manage feedback loops between customers and the product team. They track customer issues, drive post-release adoption, and ensure engineering teams have the context needed to prioritize improvements.

### Responsibilities
- Manage inbound support requests, triage issues, and coordinate escalations
- Surface systemic customer pain points to Product Managers and Developers
- Drive user adoption, onboarding, and education activities post-release
- Maintain customer-facing documentation and release communications
- Monitor customer health metrics and escalate churn risks proactively

### Goals
- Maximize customer satisfaction and product adoption
- Reduce support ticket volume through proactive education and product improvements
- Close the feedback loop between users and the engineering team efficiently

### Typical Communication
- Customer-facing release announcements and changelogs
- Internal escalation reports and support trend summaries
- Stakeholder updates on customer health and adoption metrics

### Interactions
- **Product Managers:** Share aggregated customer feedback and support trends to inform roadmap prioritization
- **Developers:** Escalate critical bugs with reproduction steps; validate fixes resolve the reported customer issue
- **DevOps / Platform Engineers:** Coordinate incident communications and follow up on production issues affecting customers
- **Project Managers:** Align on release timing to prepare customer communications and support readiness
- **Business Analysts:** Provide real-world usage data and pain points that feed into requirements analysis

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [OctoAcme Responsibility Matrix](./octoacme-responsibility-matrix.md) for a cross-functional view of ownership across the project lifecycle.

