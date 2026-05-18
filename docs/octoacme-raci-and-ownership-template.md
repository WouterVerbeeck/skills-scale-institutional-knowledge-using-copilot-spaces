# OctoAcme — RACI / Ownership Template

## Purpose
Provide a lightweight template for clarifying ownership across the project lifecycle and for recurring cross-functional activities.

## How to use
- Copy this template into the project repo or working doc for the initiative.
- Keep the role list aligned with the personas in [OctoAcme Personas](./octoacme-roles-and-personas.md).
- Adjust the RACI assignments based on project risk, scale, and delivery model.

## Role key
- **PM** = Project Manager
- **PdM** = Product Manager
- **EM** = Engineering Manager
- **TL** = Technical Lead / Staff Engineer
- **UX** = UX / Product Designer
- **Dev** = Developers
- **QA** = QA / Test Engineer
- **Sec** = Security / AppSec Reviewer
- **SRE** = SRE / Operations / Platform Engineer
- **Support** = Customer Support / Support Lead
- **Data** = Data Analyst / Data Scientist

## RACI legend
- **R** = Responsible
- **A** = Accountable
- **C** = Consulted
- **I** = Informed

## Lifecycle phase ownership

| Phase | PM | PdM | EM | TL | UX | Dev | QA | Sec | SRE | Support | Data |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Initiation | A | R | C | C | C | I | I | I | I | C | C |
| Planning | A | R | C | R | C | C | C | C | C | I | C |
| Execution | A | C | C | R | C | R | R | C | C | I | C |
| Release | A | C | C | C | I | R | R | R | R | R | I |
| Retrospective | A | C | C | C | I | C | C | I | C | C | R |

## Recurring activity ownership

| Activity | PM | PdM | EM | TL | UX | Dev | QA | Sec | SRE | Support | Data |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Definition of Done | A | C | C | R | I | R | R | I | I | I | I |
| Design review | C | C | I | A | R | R | I | C | C | I | I |
| Security review | C | I | I | C | I | R | I | A | C | I | I |
| QA sign-off | C | C | I | I | I | C | A | I | I | I | I |
| Release readiness review | A | C | C | C | I | C | R | R | R | R | I |
| Incident communications | A | I | C | I | I | C | I | C | R | R | I |

## Project-specific overrides
- Named PM:
- Named PdM:
- Named engineering owner:
- Named release owner:
- Exceptions to the default RACI:

