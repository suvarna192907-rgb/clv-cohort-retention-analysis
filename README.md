# E-Commerce Customer Lifetime Value (CLV) & Cohort Retention Analysis

Analysis of the Online Retail II dataset (Dec 2009 to Dec 2011) to find high-value customer segments and recommend where to spend the retention marketing budget.

## Tools
PostgreSQL, Python (Pandas, NumPy, Scikit-Learn), Jupyter Notebook, Power BI

## What is in this repository
- Executive summary report with findings and recommendations
- Jupyter notebook with RFM segmentation (K-Means) and CLV
- Power BI dashboard (clv_dashboard.pbix)
- CSV outputs: rfm_segments, retention_matrix, monthly_revenue

## Method
1. Cleaned the data in PostgreSQL (removed rows with no customer ID, cancelled invoices, and invalid quantity or price)
2. Built a monthly cohort retention matrix in SQL (CTEs, window functions, self-join)
3. Segmented customers with RFM and K-Means (k = 4): Champions, At-Risk, Potential Loyalists, Hibernating
4. Calculated historical and predictive CLV
5. Built a 3-page Power BI dashboard

## Dataset
Online Retail II (UCI), available on Kaggle. The raw file is not included because of its size.
