## IT Incident & SLA Performance Dashboard

This project analyzes IT incident data and SLA performance to identify operational inefficiencies and improvement opportunities. Built entirely as a self-initiated portfolio project using a Kaggle dataset, it applies 5 years of IT Service Management experience through a data analytics lens.

## Objective

To understand incident patterns, identify root causes, and evaluate SLA performance across departments, priorities, and locations — translating operational knowledge into KPI-driven insights that leadership can act on.

## Tech Stack

Power BI — Dashboard design, data visualization & interactive reporting

Power Query — Data cleaning & transformation

DAX — Calculated columns & measures

## Dataset

Source: Kaggle (publicly available IT incident dataset)

## KPI

Total Incidents- 1,200 

Breached Incidents- 873

SLA Breached %- 72.75%

Critical Incidents- 320

## Key Insights

-72.75% overall SLA breach rate — indicates significant performance gaps in incident resolution efficiency.

-Critical incidents breach SLA at 95.88% — averaging ~35 hrs against a 1–4 hr target, nearly 9x over SLA.

-High priority at 89.20% breach rate — against a 4–8 hr target, still significantly over acceptable thresholds

-IT Support handles the highest volume (268) and highest SLA breach rate (74.63%)

-Security & Server issues drive the majority of High (324) and Critical (320) priority incidents

-Medium & Low priority incidents remain comfortably within SLA.

-October–November shows peak SLA breaches, indicating possible seasonal operational strain

-Remote Site 1 reports the highest number of incidents (276)

** Not all SLA breaches are avoidable — major outages, resource constraints, and unforeseen incidents are unavoidable operational realities. However, a 95.88% Critical breach rate signals a systemic escalation gap beyond acceptable thresholds.**

## SLA Performance by Priority

| Priority | Avg Resolution | SLA Target | Status |
|----------|---------------|------------|--------|
| Critical | 34.6 hrs | 1–4 hours | Breaching ~9x |
| High | 35.2 hrs | 4–8 hours | Breaching ~5x |
| Medium | 38.3 hrs | 24–48 hours | Within SLA |
| Low | 36.1 hrs | 3–5 days | Within SLA |

## Dashboard Features

-SLA compliance tracking across departments, priorities and locations

-Incident trend analysis over time (monthly & quarterly)

-Priority-wise breakdown of incidents and SLA breach %

-Department-wise performance comparison

-Root cause analysis via treemap visualization

-Interactive filters — SLA Status, Priority, Month, Quarter, Root Cause

## Recommendations

-Implement a dedicated P1/P2 escalation queue — separate Critical & High incidents into a fast-track resolution workflow with dedicated resources.

-Set up automated SLA breach alerts — triggers notifications when Critical incidents exceed 2 hrs without resolution updates.

-Investigate October–November spike — assess whether staffing levels, change freeze periods, or seasonal factors contribute to the breach peak.

-Review IT Support workload distribution — highest volume AND highest breach rate suggests understaffing or skill gap.

-Introduce real-time SLA dashboards for team leads — visibility into live breach risk enables proactive intervention before SLA is missed.

-Root cause focus on Security & Server — targeted preventive measures for top incident drivers could significantly reduce High/Critical volumes.

## Business Impact

-Identifies P1/P2 escalation gaps where Critical incidents average ~9x over SLA target

-Supports prioritization of high-risk incident categories (Security & Server)

-Improves visibility into SLA performance across teams and locations

-Enables better resource allocation by distinguishing escalation problems from capacity problems

-Provides seasonal trend insight for proactive operational planning

## Dashboard Preview

![dashboard](https://github.com/DataAnalyst-Komal/it-incident-sla-performance-analysis/blob/main/snapshot-it-incident-sla-dashboard.PNG)

## Learnings

Gained hands-on experience with ITSM data and incident lifecycle analysis

Built calculated columns and measures using DAX for SLA performance tracking

Developed understanding of SLA tier structures (P1–P4) and their operational implications

Improved dashboard design and data storytelling skills

Strengthened ability to translate operational data into actionable business insights

Learned to distinguish between descriptive analytics (what happened) and diagnostic analytics (why it happened)


Built with Power BI | Power Query | DAX • Dataset: Kaggle • Portfolio Project
