# Organization Chart

Status: Approved

Owner:
Chief AI Company Architect

Repository management:
Jarvis (CTO)

Version:
1.1

Created:
2026-06-29

---

The canonical organizational structure of AICOS, including the **Executive
Governance Model v0.1**. This document records **organizational roles** and the
people or AI employees currently filling them. Roles are stable; the operator
behind a role may change without changing the role (see AEP-0000, *Role over
Provider*).

## Executive Leadership

Architecture and Technology are **separate executive functions**. Both report
directly to the Founder and collaborate as peers; neither is subordinate to the
other.

### Founder — Jefferson

Vision · Strategy · Capital Allocation · Final Decisions · Organizational
Direction.

> The Founder decides **WHERE** the company goes.

### Chief AI Company Architect — Luke

Company Architecture · Organizational Architecture · Knowledge Architecture ·
Governance · AEP · ADR · Principles · Long-term Consistency · Architecture Review.

> The Chief AI Company Architect decides **HOW the company should operate**. The
> role governs the company operating system. It does **not** manage engineering
> execution.

### Chief Technology Officer — Jarvis

Engineering · Repository · Git · Software Delivery · Technical Review ·
Engineering Standards · Release Management · Engineering Team.

> The CTO decides **HOW technology is implemented**. The CTO does **not** own
> company architecture.

## Reporting model

```
Founder (Jefferson)
├── Chief AI Company Architect (Luke)
└── Chief Technology Officer (Jarvis)
        ├── Software Engineer (Kodi)
        ├── Platform Engineer (Hermes)
        ├── Assistant & Intelligence (Mark)
        └── QA & Local Intelligence (Goose)
```

- The **CTO** and the **Chief AI Company Architect** are peers under the Founder.
- **Engineering execution remains under the CTO.** Every AI employee reports
  through the CTO.

## Governance split

| Chief AI Company Architect owns | CTO owns |
| --- | --- |
| Architecture | Engineering |
| Standards | Delivery |
| Organizational Principles | Repository |
| Long-term Evolution | Technical Execution |

> Architecture defines the destination. Technology builds the road.

## Engineering organization

| Role | Member | Responsibility |
| --- | --- | --- |
| Software Engineer | Kodi | Implementation: coding, refactoring, bug fixing, testing. |
| Platform Engineer | Hermes | Platform, MCP, skills, tools, dispatcher, internal infrastructure. |
| Assistant & Intelligence Agent | Mark | Assistant tasks, reminders, intelligence and collection, market-operation suggestions. |
| QA & Local Intelligence | Goose | Verification, QA, local search, RAG, summaries. |

## Onboarding of future AI employees

Every future AI employee is onboarded **through the CTO**, following
[`onboarding.md`](onboarding.md). New roles or changes to this chart are proposed
through the Chief AI Company Architect and recorded here after Founder approval.

## References

- [AEP-0000 — What Is AICOS](../aep/AEP-0000-what-is-aicos.md) (Organization Model, Core Principles)
- [`onboarding.md`](onboarding.md)
