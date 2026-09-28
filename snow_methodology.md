# 🔬 ITSM Analysis Methodology

## Project: ServiceNow Incident Management Dashboard
**Author**: Shanmukha Sree Bendi | ServiceNow Administrator Project | 2026

---

## 1. ITSM Framework Overview

This dashboard is built on core **IT Service Management (ITSM)** principles aligned with:
- **ServiceNow Platform** — Incident, Problem, Change, and Service Catalog modules
- **ITIL Framework** — Incident lifecycle, SLA management, escalation procedures
- **NIST Guidelines** — Security incident classification and response

---

## 2. Incident Priority Matrix

| Priority | Label | SLA Window | Business Impact | Response |
|----------|-------|-----------|----------------|----------|
| P1 | Critical | 1 hour | Complete service outage | Immediate — all hands |
| P2 | High | 4 hours | Major feature unavailable | Urgent — senior team |
| P3 | Medium | 24 hours | Minor impact, workaround exists | Standard queue |
| P4 | Low | 72 hours | No immediate impact | Scheduled |

---

## 3. Incident Lifecycle

```
New → Assigned → In Progress → Pending (if needed) → Resolved → Closed
```

Each stage tracked in dashboard:
- **Open** — Created, not yet assigned
- **In Progress** — Actively being worked
- **Pending** — Awaiting user/third party
- **Resolved** — Fix applied, awaiting confirmation
- **Closed** — Confirmed resolved, ticket closed

---

## 4. SLA Calculation

```
SLA Compliance % = (Tickets resolved within SLA / Total tickets) × 100

P1 Target: 95% within 1 hour
P2 Target: 95% within 4 hours
P3 Target: 95% within 24 hours
P4 Target: 95% within 72 hours
```

Current overall compliance: **87.4%** — below 95% target, driven by P1/P2 breaches.

---

## 5. Key Performance Indicators

| KPI | Formula | Current | Target |
|-----|---------|---------|--------|
| SLA Compliance | Resolved in SLA / Total × 100 | 87.4% | 95% |
| MTTR | Sum of resolution times / Count | 4.2 hrs | < 4 hrs |
| FCR Rate | Resolved at L1 / Total × 100 | 68% | 75% |
| Backlog Growth | New - Resolved per day | +2/day | 0 |

---

## 6. Assignment Group Strategy

Tickets routed based on category:
- **Network Operations** → Connectivity, VPN, DNS issues
- **IT Infrastructure** → Server, storage, compute issues
- **Security Team** → Security alerts, access violations
- **Database Admin** → DB performance, connectivity
- **Help Desk L1** → Password resets, basic software, access requests

---

*Methodology Document | Shanmukha Sree Bendi | ServiceNow Administrator Project | 2026*
