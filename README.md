# Customer Churn & Retention Analytics

> Business Analytics | Python | Tableau

An end-to-end customer churn analysis project focused on identifying churn patterns, high-risk customer segments, revenue exposure, and actionable retention opportunities.

## Business Objective

Analyze customer behavior to identify where churn is concentrated, which customer segments require retention attention, and how customer risk can be connected to potential revenue exposure.

## Tools
**Python:** Pandas, Matplotlib, Scikit-learn  
**BI:** Tableau Public  
**Environment:** Google Colab

## Analytical Approach

Data Quality & Cleaning
→ Exploratory Data Analysis
→ Customer Segmentation
→ Churn Driver Analysis
→ Customer Risk Scoring
→ Revenue-at-Risk Analysis
→ Tableau Business Intelligence

## Key Insights

- **7,043 customers** analyzed
- **26.54% overall churn rate**
- Month-to-month customers: **42.71% churn**
- 0–6 month customers: **52.94% churn**
- High-value customers: **34.09% churn**
- 0–6 month + High-value customers: **77.21% churn**
- 7–12 month + High-value customers: **69.14% churn**
- Electronic Check customers: **45.29% churn**
- Fiber Optic customers: **41.89% churn**
- Customers without Technical Support: **41.64% churn**
- Customers without Online Security: **41.77% churn**

## Dashboards

### Executive Churn Overview
![Executive Churn Overview](Images/dashboard_overview.png)

### Customer Risk & Revenue
![Customer Risk & Revenue](Images/dashboard_risk.png)

## Business Recommendations

- Focus retention and onboarding efforts on customers in their **first 6–12 months**.
- Prioritize **high-value customers with short tenure**, especially the 0–6 month segment.
- Encourage migration from **month-to-month contracts** toward longer-term plans through suitable retention offers.
- Investigate the higher churn observed among **Electronic Check** and **Fiber Optic** customers to identify pricing, service, or customer-experience issues.
- Strengthen adoption of **Technical Support and Online Security** services among vulnerable customer groups.
- Prioritize retention actions using **churn risk together with customer value**, rather than churn probability alone.

## Business Outcome

The project converts customer data into **actionable retention priorities**, helping identify vulnerable segments, quantify potential revenue exposure, and support data-driven customer retention decisions.

## Skills Demonstrated

Data Cleaning • EDA • Customer Segmentation • KPI Analysis • Churn Analysis • Revenue Analysis • Risk Scoring • Tableau • Business Insights • Data Storytelling

## Repository Structure

```text
Data/
├── raw/
└── processed/

Images/
├── dashboard_overview.png
└── dashboard_risk.png

Notebooks/
├── 01_data_quality.ipynb
├── 02_eda.ipynb
├── 03_customer_segmentation.ipynb
├── 04_churn_driver_analysis.ipynb
└── 05_churn_model.ipynb

tableau/
└── Customer_Churn_Retention_Analytics.twb

README.md
