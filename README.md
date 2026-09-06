# ClaimFlow — Revenue Cycle & Claims Recovery Analytics

<p align="center">
  <img src="./Docs/01_claimflow_logo.png" alt="ClaimFlow Logo" width="220"/>
</p>

## Project Overview
Healthcare providers lose millions of dollars every year due to insurance claim denials, billing errors, and delayed payments. 

**ClaimFlow** is an end-to-end data analytics project built to tackle this challenge. It provides billing teams and executives with clear visibility into claim statuses, high-risk insurance payers, and recoverable revenue.

---

## Interactive Dashboard Preview
Here is the full 4-page executive dashboard created in Power BI:

<p align="center">
  <img src="./Docs/05_all_pages_grid.png" alt="ClaimFlow Power BI Dashboard Overview" width="100%"/>
</p>

> 📊 **Full Case Study:** [Click here to view the complete 10-slide Case Study PDF](https://github.com/YOUR_GITHUB_USERNAME/ClaimFlow-Healthcare-RCM-Analytics/blob/main/Docs/ClaimFlow_Revenue_Cycle_Analytics_Case_Study.pdf)

---

## Technical Architecture
The data pipeline moves from data generation to storage, cleaning, data modeling, and final interactive visualization.

<p align="center">
  <img src="./Docs/03_project_workflow.png" alt="Technical Data Pipeline" width="100%"/>
</p>

* **Data Generation:** Python script simulating realistic healthcare claim scenarios.
* **Database & Storage:** SQL Server for database creation, structure, and query analysis.
* **ETL & Data Cleaning:** Power Query for data transformation and deduplication.
* **Data Modeling:** Star Schema with 1 Fact table (`fact_claims`) and 3 Dimension tables (`dim_hospitals`, `dim_payers`, `dim_date`).
* **Visualization:** Power BI desktop using DAX measures, dynamic filtering, and custom layouts.

---

## Key Business Insights
1. **High Commercial Denials:** Commercial payers average a 15–18% denial rate, mostly caused by missing documentation during billing submission.
2. **Pending Cash Flow:** Over $450K in revenue remains stuck in pending status, with nearly 20% delayed for over 90 days.
3. **Appeals Opportunity:** Filing systematic claim appeals successfully recovers up to 50% of denied revenue.

---

## Contact & Profile
**Pushpal Kawara** — Data Analyst & BI Specialist
* Email: pushpalanalytics@gmail.com
* Phone: +91 7796004314
* LinkedIn: https://linkedin.com
* Portfolio: will add soon
