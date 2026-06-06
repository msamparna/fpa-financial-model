# KPI Framework & Tracking Logic

## 🎯 Overview

This framework defines the KPIs tracked across business units, their calculation methodology, and escalation thresholds used in the FP&A model.

## 📊 Financial KPIs

| KPI | Definition | Target | Warning Threshold |
|---|---|---|---|
| Revenue Growth | YoY revenue change % | +12% | <8% |
| Gross Margin | (Revenue - COGS) / Revenue | 38% | <32% |
| EBITDA Margin | EBITDA / Revenue | 20% | <15% |
| Cost-to-Income Ratio | Total Costs / Revenue | <72% | >80% |
| Budget Variance | (Actual - Budget) / Budget | <±5% | >±10% |

## 📈 Operational KPIs

| KPI | Definition | Target | Warning Threshold |
|---|---|---|---|
| Project Delivery Rate | % projects delivered on time | 95% | <85% |
| Vendor On-Time Payment | % invoices paid by due date | 98% | <90% |
| Report Accuracy Rate | % reports with zero errors | 100% | <98% |
| Process Automation Rate | % manual tasks automated | 30% | <15% |

## 🚦 Status Logic

| Achievement % | Status | Action |
|---|---|---|
| ≥ 100% | ✅ On Track | No action required |
| 85% – 99% | 🟡 At Risk | Monitor weekly |
| 70% – 84% | 🟠 Off Track | Corrective plan required |
| < 70% | 🔴 Critical | Escalate to leadership |

## 🔄 Review Cadence

- **Weekly:** Operational KPIs reviewed by team leads
- **Monthly:** Financial KPIs reviewed by CFO/CEO
- **Quarterly:** Full KPI framework review and target reset
