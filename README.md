# Customer Churn & Retention Analytics

> Business Analytics | Python | Tableau

An end-to-end customer churn analysis project focused on identifying churn patterns, high-risk customer segments, revenue exposure, and actionable retention opportunities.

## Tools
**Python:** Pandas, Matplotlib, Scikit-learn  
**BI:** Tableau Public  
**Environment:** Google Colab

## Analysis
- Data quality and cleaning
- Exploratory data analysis
- Customer segmentation
- Churn driver analysis
- Customer-level churn risk scoring
- Revenue-at-risk analysis
- Interactive Tableau dashboards

## Key Insights
- **7,043 customers** analyzed
- **26.54% overall churn rate**
- Month-to-month customers: **42.71% churn**
- 0–6 month customers: **52.94% churn**
- High-value customers: **34.09% churn**
- 0–6 month + High-value customers: **77.21% churn**

## Dashboards

### Executive Churn Overview
![Executive Churn Overview](Images/dashboard_overview.png)

### Customer Risk & Revenue
![Customer Risk & Revenue](Images/dashboard_risk.png)

## Business Outcome
The project converts customer data into **actionable retention priorities**, helping identify vulnerable segments, quantify potential revenue exposure, and support data-driven customer retention decisions.

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
