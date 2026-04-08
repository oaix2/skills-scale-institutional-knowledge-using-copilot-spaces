# OctoAcme — Responsibility Matrix & Handoffs

## Purpose
Define cross-functional ownership across the project lifecycle and clarify handoffs between roles to reduce ambiguity and prevent gaps.

For full role descriptions and interaction details, see [OctoAcme Personas](./octoacme-roles-and-personas.md).

---

## Lifecycle Phases & Handoffs

| Phase | Trigger / Input | Key Activities | Handoff Output |
|---|---|---|---|
| **Initiation** | Business need or feature request | One-pager, stakeholder alignment, go/no-go decision | Approved one-pager → Planning phase |
| **Planning** | Approved one-pager | Backlog creation, requirements, risk register, timeline | Groomed backlog + sprint plan → Execution |
| **Execution** | Sprint plan | Development, design, QA, risk monitoring | Merged PRs + passing CI → Release |
| **Release** | All acceptance criteria met | Deployment, release notes, support readiness | Live release + stakeholder announcement |
| **Retrospective** | Post-release or end of sprint | Identify improvements, update action items | Action items → next Planning cycle |

---

## RACI Table — Key Artifacts

> **R** = Responsible (does the work) · **A** = Accountable (final decision/sign-off) · **C** = Consulted · **I** = Informed

| Artifact | Product Manager | Project Manager | Developer | UX Designer | DevOps / Platform Eng. | Business Analyst | Support / CS Manager |
|---|---|---|---|---|---|---|---|
| Project One-pager | **A** | R | I | C | I | C | I |
| Stakeholder Communication Plan | C | **A** | I | I | I | C | C |
| Product Backlog | **A** | C | C | C | I | R | C |
| Acceptance Criteria | C | I | C | C | I | **A** | C |
| Risk Register | C | **A** | C | I | C | C | I |
| UX Prototypes / Design Specs | C | I | C | **A** | I | C | I |
| CI/CD Pipeline & Runbooks | I | I | C | I | **A** | I | I |
| Release Notes | **A** | C | R | I | C | I | C |
| Incident Communications | C | C | C | I | R | I | **A** |
| Retrospective Action Items | C | **A** | C | C | C | C | C |

---

## Phase-by-Phase Handoff Detail

### Initiation
- **Owner of phase:** Product Manager (accountable), Project Manager (coordinates)
- **Key artifact:** Project One-pager
- **Handoff:** Product Manager presents approved one-pager to Project Manager; Business Analyst captures initial requirements scope; UX Designer is consulted on feasibility of proposed UX direction.

### Planning
- **Owner of phase:** Project Manager (schedule/risk), Product Manager (backlog/priorities), Business Analyst (requirements)
- **Key artifacts:** Groomed backlog, acceptance criteria, risk register, sprint plan
- **Handoff:** Business Analyst delivers acceptance criteria to Developers; Project Manager shares sprint plan and risk register with the full team; UX Designer delivers initial wireframes before development begins.

### Execution
- **Owner of phase:** Developers (delivery), Project Manager (tracking), UX Designer (design review)
- **Key artifacts:** Merged PRs, updated risk register, QA sign-off
- **Handoff:** Developers notify DevOps / Platform Engineers when features are ready for staging deployment; UX Designer reviews implementations and approves design fidelity before QA sign-off.

### Release
- **Owner of phase:** DevOps / Platform Engineer (deployment), Product Manager (release notes), Support / CS Manager (customer comms)
- **Key artifacts:** Deployment checklist, release notes, incident runbook, support briefing
- **Handoff:** DevOps / Platform Engineer confirms successful deployment; Product Manager publishes release notes; Support / CS Manager sends customer-facing announcement and prepares the support team.

### Retrospective
- **Owner of phase:** Project Manager (facilitates), entire team (participates)
- **Key artifacts:** Retrospective action items
- **Handoff:** Action items feed into the next planning cycle; Product Manager and Business Analyst evaluate whether any items require new backlog entries.

---

## Notes
- This matrix is a guide, not a rigid contract. Adjust ownership to fit your team's size and structure.
- Update this document when new roles are added or responsibilities shift significantly.
- See individual phase docs for detailed checklists:
  - [Project Initiation](./octoacme-project-initiation.md)
  - [Project Planning](./octoacme-project-planning.md)
  - [Execution & Tracking](./octoacme-execution-and-tracking.md)
  - [Release & Deployment](./octoacme-release-and-deployment.md)
  - [Risk Management & Communication](./octoacme-risks-and-communication.md)
