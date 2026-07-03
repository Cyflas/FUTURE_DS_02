## Project Overview
This repository contains Task 2 of Future Interns' Data Science & Analytics Internship.
* **Task 2:** A B2B SaaS customer retention analysis identifying key churn drivers and operational bottlenecks.

## Tools & Technologies Used
* **Data Engineering & Cleaning:** Python (Pandas, Jupyter Notebooks)
* **Data Visualsation & Modeling:** Power BI, DAX
* **Deliverables:** Interactive Dashboards and Clients-Ready PDF Reports

---

## Task 2: Ravenstack SaaS Churn Analysis
**Objective:** Process a relational database of subscription logs, support tickets, and feature usage to identify churn patterns and retention opportunities.

**Methodology:**
Combined 5 raw relational CSV files using Python (`pandas`) to aggregate 25,000+ rows of daily feature interactions and support tickets into a master analytical dataset.

### Key Insights:
* **The Support Friction Threshold:** Accounts that churned experienced noticeably longer average support resolution times than active accounts. 
* **Error Tolerance:** The data revealed that both active and churned users encounter a similar volume of system errors (~28 per account). Product bugs alone do not drive churn; the failure to resolve them quickly does.
* **Recommendation:** Implement strict SLAs for tier-1 support to drastically reduce resolution times and prevent customers from reaching the cancellation threshold.

---

## Repository Structure
* `FUTURE_DS_02`
  * `ravenstack_churn_analysis.ipynb` (Python script used for data cleaning and relational data merging)
  * `ravenstack_master_clean.csv` (The final cleaned dataset exported from Python)
  * `ravenstack_accounts.csv` (List of Accounts)
  * `ravenstack_churn_events.csv` (Churn Events)
  * `ravenstack_feature_usage.csv` (The features used)
  * `ravenstack_subscription.csv` (The subscriptions)
  * `ravenstack_support_tickets.csv` (The support tickets)
  * `Ravenstack_Retention_Dashboard.pbix` (Power BI File)

## How to View the Dashboard
To view the interactive Power BI dashboards:
1. Download the `.pbix` file from this repository.
2. Open it using Power BI Desktop.
