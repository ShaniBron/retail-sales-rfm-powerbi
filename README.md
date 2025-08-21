# Retail Sales Analysis & RFM Dashboard (Python + Power BI)

**Goal:** Explore retail transactions, build an RFM segmentation, and present a business-ready Power BI dashboard.

## Contents
- `notebooks/` – data cleaning, EDA, RFM
`data/retail_cleaned.csv` – cleaned dataset used by notebook + dashboard
- `dashboards/` – Power BI report (PDF) and .pbix if size allows
- `images/` – screenshots

## Key Results
- Total revenue: **1.58M** | Transactions: **64k+** | ATV: **24.40**
- Clear monthly seasonality (Dec peak) and Thursday uplift
- High-value customers (Champions + Loyal) ≈ **72%** of revenue

## How to view
- Notebook: open `notebooks/Retail_Sales_EDA.ipynb` in GitHub  
- Dashboard: view screenshots in `images/` folder 

## Reproduce (Python)
```bash
pip install -r requirements.txt
# then open notebooks/Retail_Sales_EDA.ipynb
