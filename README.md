# logistics-analytics
PowerBI project for a real Australian logistics company (the company name and data has been changed for the confidentiality)

## CTI Logistics (CTI Xpress) — Revenue & Customer Insights Dashboard (Power BI)

### Project Background

CTI Xpress manages high-volume freight operations where commercial and operations leaders need quick answers to questions like: **Which customers are growing or declining? What’s driving month-to-month revenue movement? Are changes seasonal or structural? Which regions/suburbs are trending up or down?**

During my internship at CTI Logistics, I developed and maintained a **Power BI reporting pack** to improve visibility of revenue performance across customers, categories, logistics providers, and geographic areas—while reducing manual reporting effort.

---

## Objectives

This project aimed to deliver a decision-ready dashboard that supports:

* **Current month vs prior month comparisons** (absolute $ change and % change)
* **Short- vs long-term context** via **3/6/12-month averages**
* **Driver analysis** (top increases/decreases, customer/category contribution)
* **Geographic insights** (WA suburb breakdown + map view)
* **Consistency & trust** through validation and repeatable logic

---

## Data & Modelling Approach

The reporting model combined operational/commercial datasets into a clean analytics layer suitable for slicing by:

* **Customer / ultimate customer group**
* **Revenue category**
* **Primary logistics company**
* **Time period (monthly + rolling averages)**
* **Geography (e.g., WA suburb / destination area)**

Key modelling practices I applied:

* Built a **calendar/date table** to standardise month logic and rolling windows
* Ensured **correct data grain** (to avoid double counting across groupings)
* Created reusable measures for **CM/PM revenue**, **Δ revenue**, **% change**, and **rolling averages**
* Implemented drill-down friendly tables that keep context consistent across pages

---

## Dashboard Pages (What each page answers)

### 1) Top 15 Revenue by Company

A “what changed this month” view to surface the biggest movers:

* **Top 15 increases** and **Top 15 decreases** (CM vs PM)
* A ranked table of **Top 15 current month revenue** with **3/6/12-month averages**
  **Use case:** quickly identify which accounts need celebration, investigation, or follow-up.

### 2) Revenue Category / Logistics

Two complementary views to separate *mix shift* from *account movement*:

* **Revenue by category** (CM vs PM, change %, rolling averages)
* **Top logistics companies** contributing to current performance
  **Use case:** spot whether performance is driven by category demand, pricing/mix, or provider-level movement.

### 3) Customer Breakdown (Contribution + Detail Table)

A contribution view plus a detailed table for root cause:

* Customer contribution (e.g., pie/share view) to highlight concentration
* Customer table showing CM/PM, Δ, % change, and rolling averages
  **Use case:** identify concentration risk and which customers drive overall results.

### 4) Working Day Average (WDA) Analysis

A normalization view to make month comparisons fair:

* Compares current month performance using **working-day adjusted revenue** vs 3/6/12-month baselines
  **Use case:** avoid false alarms caused purely by different numbers of working days.

### 5) WA Suburb Breakdown + Map

A geographic breakdown for WA:

* Table of suburb-level changes (CM vs PM + rolling averages)
* Map/heat layer for spatial scanning
  **Use case:** detect regional growth/decline pockets and support territory/route planning conversations.

---

## Key Insights (typical patterns this dashboard reveals)

While specific figures are confidential, this reporting commonly surfaces:

* **Revenue concentration:** a small group of customers often drives a large share of monthly movement
* **Mix shift:** category-level shifts can explain changes even when total revenue looks flat
* **“Real” change vs calendar effects:** WDA helps distinguish operational change from month length differences
* **Geographic clusters:** suburb/region views help identify where performance is strengthening or weakening

---

## Recommendations Enabled by the Dashboard

The dashboard supported actions such as:

* Prioritising **account follow-ups** based on largest MoM declines/increases
* Investigating **category downturns** to separate market-driven vs customer-driven movement
* Using **WDA** to make performance reporting more accurate and comparable
* Targeting **regional opportunities** where revenue trends cluster geographically

---

## Tools & Skills Demonstrated

* **Power BI:** semantic modelling, drill-through design, interactive reporting
* **DAX:** CM/PM measures, variance %, rolling averages, working-day adjustments
* **Power Query:** transformation, standardisation, mapping tables
* **Stakeholder reporting:** building “exec-friendly” views that answer business questions fast

---

## Confidentiality / Portfolio Version

This work used internal CTI data. For my portfolio, I only share:

* **Anonymised screenshots (customer names & values masked)** or
* A **synthetic replica dashboard** (same logic + visuals, fake data)

If you want, I can tailor this write-up into a **portfolio-ready one-pager** (with a short “Impact” section and 5–6 bullet highlights) and match the wording exactly to the pages you want to showcase.

