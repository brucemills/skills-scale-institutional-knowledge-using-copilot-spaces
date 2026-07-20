# OctoAcme — Role-Responsibility Matrix

## Purpose
Provide a concise, phase-by-phase view of which roles are engaged at each stage of the OctoAcme project lifecycle, and how they collaborate. Use this to reduce handoff ambiguity and clarify accountability.

---

## Role Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| EM | Engineering Manager / Tech Lead |
| DEV | Developers |
| UX | UX/UI Designer |
| DevOps | DevOps / Platform Engineer |
| QA | QA/Testing |
| CS | Customer Support / Success Representative |
| SEC | Security / Compliance Representative |
| STK | Stakeholders |

**Key:** **L** = Lead / Primary Owner · **C** = Contributor · **I** = Informed

---

## Phase 1 — Initiation

| Activity | PM | PdM | EM | DEV | UX | DevOps | QA | CS | SEC | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Define problem statement and goals | C | **L** | C | | C | | | C | | C |
| Identify stakeholders and sponsors | **L** | C | | | | | | | | **L** |
| Draft project charter / one-pager | **L** | C | C | | | | | | | I |
| Conduct initial security/compliance review | I | I | C | | | | | | **L** | I |
| Confirm feasibility and high-level estimate | C | C | **L** | C | C | C | | | C | I |

---

## Phase 2 — Planning

| Activity | PM | PdM | EM | DEV | UX | DevOps | QA | CS | SEC | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Prioritize and refine backlog | C | **L** | C | C | C | | C | C | | I |
| Define acceptance criteria and DoD | C | **L** | C | C | **L** | | **L** | C | C | I |
| Estimate scope and capacity | C | C | **L** | **L** | C | C | C | | | |
| Create release plan and milestones | **L** | C | C | | | C | | | | I |
| Identify risks and dependencies | **L** | C | C | C | | C | | | C | I |
| Define security and compliance requirements | I | C | C | | | C | | | **L** | I |
| Plan environment and CI/CD readiness | I | | C | C | | **L** | | | C | |

---

## Phase 3 — Execution

| Activity | PM | PdM | EM | DEV | UX | DevOps | QA | CS | SEC | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Implement features | | | C | **L** | C | | | | | |
| Design review and UX alignment | | C | C | C | **L** | | | | | |
| Code review and technical standards | | | **L** | **L** | | | | | | |
| Maintain CI/CD and environment health | | | C | C | | **L** | | | | |
| Track progress and remove blockers | **L** | | C | | | | | | | |
| Validate against acceptance criteria | C | C | C | C | C | | **L** | | | |
| Security review (if required) | I | | C | C | | C | | | **L** | |

---

## Phase 4 — Release

| Activity | PM | PdM | EM | DEV | UX | DevOps | QA | CS | SEC | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Confirm release readiness | **L** | C | C | | | C | C | C | C | I |
| Run smoke tests and pre-deploy checks | | | | C | | **L** | **L** | | | |
| Deploy to staging and production | I | | C | | | **L** | | | | |
| Post-deploy verification | C | C | C | C | | **L** | C | | | |
| Draft and approve release notes | C | **L** | C | | | | | **L** | | I |
| Communicate release to stakeholders | **L** | C | | | | | | **L** | | **L** |
| Confirm support team readiness | I | | | | | | | **L** | | |

---

## Phase 5 — Close & Retrospective

| Activity | PM | PdM | EM | DEV | UX | DevOps | QA | CS | SEC | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective | **L** | C | C | C | C | C | C | C | C | |
| Capture learnings and action items | **L** | C | C | C | | | | | | |
| Review customer and support feedback | C | **L** | | | C | | | **L** | | |
| Update process docs and runbooks | **L** | C | C | C | | C | | | C | |
| Archive project artifacts | **L** | | | | | | | | | |

---

## Cross-Phase Collaboration Checklist

Use this checklist to confirm key collaboration touchpoints are covered before moving between phases:

### Initiation → Planning
- [ ] Problem statement and success metrics agreed by PdM and PM
- [ ] Stakeholders identified and initial security/compliance input received from SEC
- [ ] EM has confirmed high-level feasibility

### Planning → Execution
- [ ] Backlog prioritized with acceptance criteria (PdM, QA, UX sign-off)
- [ ] Release plan and milestone map approved (PM, EM, DevOps)
- [ ] Risk register initialized with owners (PM)
- [ ] Security/compliance requirements documented (SEC)

### Execution → Release
- [ ] All acceptance criteria met and verified (QA, PdM, UX)
- [ ] CI/CD pipeline and deployment plan ready (DevOps, EM)
- [ ] Release notes drafted and reviewed (PdM, CS)
- [ ] Rollback/mitigation plan documented (DevOps, PM)
- [ ] Support team briefed and ready (CS)

### Release → Close
- [ ] Post-deploy verification complete (DevOps, QA)
- [ ] Stakeholders and customers notified (PM, CS)
- [ ] Retrospective scheduled (PM)
- [ ] Learnings and action items captured and assigned (PM)
