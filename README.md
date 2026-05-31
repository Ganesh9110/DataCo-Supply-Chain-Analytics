# DataCo-Supply-Chain-Analytics
End-to-end Supply Chain Analytics project built with Microsoft Fabric, SQL, DAX and Power BI — covering Bronze to Gold Medallion Architecture with descriptive, diagnostic, predictive and prescriptive analytics.

### End-to-End Microsoft Fabric & Power BI Analytics Solution
## Project Overview

This project delivers an end-to-end analytics solution built using Microsoft Fabric, SQL, DAX, and Power BI.

The solution analyzes 180,519 supply chain transactions across 5 global markets to uncover operational inefficiencies, delivery performance issues, fraud risks, and profitability drivers while providing actionable business recommendations through descriptive, diagnostic, predictive, and prescriptive analytics.

## Business Problem

- 54.82% late delivery rate
- $1.57M revenue at risk
- Profit margin erosion from discounts
- Fraud detection gaps

  ## Architecture

  Data Factory Pipeline
        ↓
Lakehouse (Bronze)
        ↓
Dataflow Gen2 (Silver)
        ↓
Warehouse (Gold)
        ↓
Semantic Model
        ↓
Power BI Dashboard
        ↓
Data Activator Alerts

## Data Pipeline
| Layer | Tables | Rows |
|-------|--------|------|
| Bronze | Raw CSV | 180,519 |
| Silver | 4 tables | cleaned |
| Gold | 3 tables | star schema |


## Dashboard Pages

### Page 1 – Executive Overview

<img width="497" height="567" alt="Screenshot 2026-05-31 123457" src="https://github.com/user-attachments/assets/8bcb3675-143a-474d-9ed0-193f34e7df70" />

- Revenue and Profit KPIs
- Revenue Trend Analysis
- Market and Segment Performance
- Executive Insights

### Page 2 – Delivery & Profit Analysis

<img width="496" height="514" alt="Screenshot 2026-05-31 123556" src="https://github.com/user-attachments/assets/687936d5-2336-4151-b328-766f8e3eaf36" />

- Delivery Status Monitoring
- Shipping Mode Performance
- Regional Delay Analysis
- Discount Impact on Profitability
- Operational Insights

### Page 3 – Strategic Analytics & Recommendations

<img width="495" height="503" alt="Screenshot 2026-05-31 123656" src="https://github.com/user-attachments/assets/3bc8a312-069f-496a-849c-cffe2ae4ff52" />

- Descriptive Analytics
- Diagnostic Analytics
- Predictive Analytics
- Prescriptive Analytics


  ## Key Findings

- Generated $36.78M revenue and $3.97M profit
- Identified a 54.82% late delivery rate impacting 98,977 shipments
- First Class shipping recorded a 95.32% late delivery rate
- Europe and LATAM contributed 57.6% of total revenue
- Higher discount levels were associated with lower average profitability
- $1.57M revenue was exposed to cancellation and fraud-related risk

## Business Monitoring & Alerts

Configured KPI alerts for:

- Late Delivery % > 55%
- Revenue at Risk > $1.6M
- Profit Margin % < 8%

  ## Author

  Kolluri Venkata Ganesh
Data Analyst | Power BI | SQL | Microsoft Fabric
  
