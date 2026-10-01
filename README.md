# 🎫 ServiceNow ITSM Incident Management Dashboard

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-View%20Here-293E6B?style=for-the-badge)](https://shanmukhab626.github.io/servicenow-itsm-dashboard)
[![ServiceNow](https://img.shields.io/badge/Platform-ServiceNow-62D84E?style=for-the-badge)](https://www.servicenow.com)
[![CSA](https://img.shields.io/badge/Cert-CSA%20In%20Progress-FF6B00?style=for-the-badge)]()

> **ServiceNow Administrator Project** · ITSM Incident Operations Dashboard · 2026

---

## 📌 Project Overview

A fully interactive **ServiceNow-style ITSM Dashboard** simulating real-world incident management operations for an enterprise IT environment.

Built to demonstrate core **ServiceNow Administrator** competencies including incident lifecycle management, SLA tracking, priority classification, assignment group management, and operational reporting — aligned with the ServiceNow CSA certification exam objectives.

🔗 **[View Live Dashboard →](https://shanmukhab626.github.io/servicenow-itsm-dashboard)**

---

## 📊 Dashboard Metrics

| Metric | Value |
|--------|-------|
| Open Incidents | 47 |
| Resolved Today | 23 |
| In Progress | 31 |
| SLA Compliance | 87.4% |
| Avg Resolution Time | 4.2 hours |
| Monitored Period | 14 days |
| Assignment Groups | 5 |
| Incident Categories | 7 |

---

## 🎯 Key Features

- **Live Incident Queue** — Real-time ticket view with priority, status, SLA timer
- **Priority Filter** — Dynamic filtering by P1/P2/P3/P4
- **14-Day Trend Chart** — Opened vs Resolved incidents over time
- **SLA Compliance Bars** — Compliance % by priority tier
- **Assignment Group Load** — Ticket distribution across IT teams
- **Category Analysis** — Top incident types by volume
- **Operational Insights** — 3 actionable recommendations based on data
- **Live Clock** — UTC timestamp simulation

---

## 📋 SLA Compliance by Priority

| Priority | SLA Window | Compliance |
|----------|-----------|------------|
| P1 Critical | 1 hour | 72% ⚠️ Below target |
| P2 High | 4 hours | 85% ⚠️ Below target |
| P3 Medium | 24 hours | 94% ✅ On track |
| P4 Low | 72 hours | 98% ✅ Excellent |

**Overall SLA: 87.4% — Target: 95%**

---

## 🔍 Incident Categories

| Category | Volume | Trend |
|----------|--------|-------|
| Network | 28 | ↑ Spiking |
| Software | 24 | → Stable |
| Hardware | 18 | → Stable |
| Security | 16 | ↑ Watch |
| Access | 14 | → Stable |
| Database | 12 | → Stable |
| Other | 8 | ↓ Decreasing |

---

## 💡 Key Operational Insights

### 🔴 SLA Breach Risk — P1 Incidents
P1 SLA compliance at 72% — significantly below 95% target. Immediate escalation required for INC0001 and INC0003.

### 🟠 Network Incidents Spiking
Network-related incidents increased 34% this week. Likely underlying problem record needed — investigate recent infrastructure changes.

### 🟢 Resolution Time Improving
Mean time to resolve dropped from 5.0h to 4.2h — 0.8h improvement. Help Desk L1 FCR rate at 68%, up from 61%.

---

## 🛠️ ServiceNow Concepts Demonstrated

| Concept | Dashboard Element |
|---------|-----------------|
| Incident Management | Full ticket lifecycle (Open → In Progress → Resolved) |
| Priority Classification | P1–P4 matrix with SLA windows |
| SLA Management | Compliance tracking per priority tier |
| Assignment Groups | Load distribution across 5 IT teams |
| Performance Analytics | KPI cards, trend charts, category analysis |
| Problem Management | Network spike → Problem record recommendation |
| Service Catalog | Navigation tab (platform awareness) |
| ITSM Reporting | Operational insights from ticket data |

---

## 📁 Repository Structure

```
servicenow-itsm-dashboard/
│
├── index.html              # Live interactive dashboard
├── README.md               # Project documentation
├── methodology.md          # ITSM concepts & approach
├── findings-report.md      # Operational analysis report
└── data/
    └── incident_data.csv   # Sample incident dataset
```

---

## 👩‍💻 Author

**Shanmukha Sree Bendi**
ServiceNow Administrator · MS Information Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/shanmukha-sree)
[![Credly](https://img.shields.io/badge/Credly-14%20Badges-FF6B00?style=flat)](https://credly.com/users/shanmukha-sree-bendi)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=flat&logo=github)](https://github.com/Shanmukhab626)
