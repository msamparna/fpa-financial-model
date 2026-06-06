# Scenario Analysis Framework

## 🎯 Overview

This model uses a three-scenario approach to support strategic planning and risk management. All scenarios are driven from the assumptions sheet and toggle dynamically.

## 📊 Scenario Definitions

### 🟢 Best Case
- Market conditions are favourable; client acquisition exceeds targets
- Revenue growth: **+18% YoY**
- Key drivers: new client wins, expanded service lines, improved realization rates
- Hiring plan: full headcount as per plan

### 🟡 Base Case
- Steady-state growth; market conditions are neutral
- Revenue growth: **+12% YoY**
- Key drivers: existing client retention, moderate new business
- Hiring plan: 80% of planned headcount

### 🔴 Worst Case
- Market slowdown; client churn or delayed projects
- Revenue growth: **+5% YoY**
- Key drivers: project deferrals, pricing pressure, increased competition
- Hiring plan: freeze on non-critical roles; cost optimization activated

## 🔄 Sensitivity Analysis

| Variable | Impact on EBITDA (Base Case) |
|---|---|
| Revenue ±5% | ±₹12L impact |
| Personnel costs ±3% | ±₹8L impact |
| Vendor costs ±5% | ±₹4L impact |
| Gross margin ±2% | ±₹6L impact |

## 📋 Decision Rules

| Condition | Action |
|---|---|
| Actual revenue < 90% of base | Trigger worst-case cost plan |
| Actual revenue > 110% of base | Activate best-case hiring plan |
| EBITDA margin < 15% | Escalate to leadership for review |
| Cash runway < 3 months | Immediate cost freeze |
