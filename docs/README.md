# OctoAcme Project Management Docs

Welcome to the central index for OctoAcme's project management process documentation. This knowledge base centralizes scattered program-management guidance into searchable, versioned artifacts — turning tacit team knowledge into a shared resource that accelerates onboarding and serves as a daily reference for every team member.

> **Copilot Space purpose:** These docs are stored here so GitHub Copilot can use them as grounded context, enabling role-specific, process-aware answers for PMs, PdMs, developers, QA, and stakeholders alike.

---

## Project Management Lifecycle

OctoAcme follows an end-to-end delivery lifecycle. Click any stage to read the full process document.

| Stage | What happens |
|---|---|
| [Initiation](#initiation) | Validate the idea, align stakeholders, define success criteria, and decide go/no-go |
| [Planning](#planning) | Define scope, milestones, resources, and dependencies |
| [Execution & Tracking](#execution--tracking) | Build, test, review, and iterate in sprints |
| [Risk Management & Communication](#risk-management--communication) | Identify, score, and mitigate risks; run escalation paths |
| [Release & Deployment](#release--deployment) | Deploy, verify, and announce the release |
| [Retrospective & Continuous Improvement](#retrospective--continuous-improvement) | Capture learnings and drive improvement actions |

---

## Lifecycle Stages

### Initiation
Define the problem, identify stakeholders, and get alignment before committing resources.  
Key deliverables: Project One-pager, stakeholder list, high-level timeline, initial risk list.  
📄 [octoacme-project-initiation.md](octoacme-project-initiation.md)

### Planning
Turn the approved idea into a concrete plan with scope, milestones, and resource assignments.  
Key deliverables: detailed project plan, sprint/iteration backlog, dependency map.  
📄 [octoacme-project-planning.md](octoacme-project-planning.md)

### Execution & Tracking
Deliver iteratively — build, test, demo, and track progress against the plan.  
Key deliverables: sprint outputs, status updates, updated risk register.  
📄 [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)

### Risk Management & Communication
Proactively identify, score, and mitigate risks. Maintain clear escalation paths and a consistent communication cadence.  
Key deliverables: Risk Register, escalation log, stakeholder update cadence.  
📄 [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)

### Release & Deployment
Coordinate the release: deployment checklist, verification, and stakeholder announcement.  
Key deliverables: release notes, deployment runbook, go/no-go sign-off.  
📄 [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)

### Retrospective & Continuous Improvement
Review what went well, what didn't, and commit to action items that improve the next cycle.  
Key deliverables: retrospective notes, improvement backlog items.  
📄 [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)

---

## Roles & Personas

| Role | Core responsibility |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and cross-team communications |
| **Product Manager (PdM)** | Defines outcomes, owns the backlog, measures success |
| **Developers** | Implement features, maintain tests and documentation, identify technical risks |
| **QA / Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs, review progress, and approve key decisions |

📄 [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)

---

## All Process Documents

- 📄 [Project Management Overview](octoacme-project-management-overview.md)
- 📄 [Project Initiation Guide](octoacme-project-initiation.md)
- 📄 [Project Planning](octoacme-project-planning.md)
- 📄 [Execution & Tracking](octoacme-execution-and-tracking.md)
- 📄 [Risk Management & Communication](octoacme-risks-and-communication.md)
- 📄 [Release & Deployment Guide](octoacme-release-and-deployment.md)
- 📄 [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- 📄 [Roles & Personas](octoacme-roles-and-personas.md)

---

## How to Use & Update These Docs

1. **Read:** Browse the documents linked above or ask GitHub Copilot (in a Copilot Space backed by this repo) for process guidance.
2. **Propose an update:** Open a GitHub Issue using the **[Add/Update Process Doc template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)**. Fill in the document you want to change, summarize the new content, and explain the rationale.
3. **Submit a PR:** Once your issue is reviewed, open a pull request against `main` that edits (or adds) the relevant file in `docs/`. Reference your issue in the PR description (e.g., `Closes #<issue-number>`).
4. **Review & merge:** A maintainer will review the PR, request any changes, and merge when ready.

> Keeping these docs up-to-date ensures Copilot Spaces always have accurate, current context for your team.
