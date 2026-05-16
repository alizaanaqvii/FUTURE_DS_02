# FUTURE_DS_02

# Customer Churn & Retention Analysis Dashboard

## Project Overview
This project analyzes customer subscription data to identify churn patterns, retention drivers, and customer lifetime behavior using Power BI. The goal is to understand why customers leave a subscription-based service and provide actionable insights to improve customer retention and business growth.


## Business Problem
Subscription-based companies often face high customer churn, which directly impacts revenue and growth. This project answers key business questions such as:

- Why are customers leaving the service?
- Which customer segments are most likely to churn?
- What role do contract types and payment methods play in churn?
- Which services influence customer retention?
- When do customers typically churn during their lifecycle?


## Dataset Used
- **Telco Customer Churn Dataset**  
- Source: Kaggle  
- Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn  


## Tools Used
- Power BI (Dashboard creation)
- DAX (Data modeling and calculations)  
- Excel / CSV (Data source)

---
## Project Structure

customer-churn-analysis-powerbi/
│
├── dashboard/
│ └── churn_dashboard.pbix
│
├── data/
│ └── telco_churn.csv
│
├── images/
│ ├── page1.png
│ ├── page2.png
│ ├── page3.png
│ ├── page4.png
│ └── page5.png
│
└── README.md

---
## Dashboard Structure

The project consists of 5 key dashboard pages:

### 1. Overview Dashboard
- Total Customers
- Churn Rate
- Active vs Churned Customers
- Churn by Contract Type

### 2️. Contract & Payment Analysis
- Contract Type vs Churn
- Payment Method vs Churn
- Internet Service vs Churn
- Paperless Billing Impact

### 3️. Tenure & Customer Lifecycle Analysis
- Churn Rate by Tenure Group
- Customer Distribution by Tenure
- Average Customer Lifespan

### 4️. Service Usage Analysis
- Internet Service Impact
- Tech Support vs Churn
- Online Security vs Churn
- Additional Service Impact

### 5️. Insights & Recommendations
- Key churn insights summary
- Business recommendations to reduce churn
- Strategic retention suggestions
  


## Key Insights

- Month-to-month contracts have the highest churn rate  
- Customers churn most within the first 0–3 months  
- Lack of Tech Support and Online Security increases churn risk  
- Fiber optic customers show higher churn compared to other services  
- Electronic check payment method is associated with higher churn  


## Recommendations

- Encourage long-term contracts (1–2 years)
- Improve onboarding experience for new customers
- Bundle Tech Support and Online Security with basic plans
- Investigate pricing/service issues in Fiber optic plans
- Promote more secure and stable payment methods for better retention  


## Dashboard Preview

- Page 1: Overview
![Overview Dashboard](customer-churn-analysis-powerbi/screenshots/page1_overview.png)

- Page 2: Contract & Payment Analysis
![Contract Analysis](customer-churn-analysis-powerbi/screenshots/page2_contract.png)

- Page 3: Tenure Analysis
![Tenure Analysis](customer-churn-analysis-powerbi/screenshots/page3_tenure.png)

- Page 4: Service Analysis
![Service Analysis](customer-churn-analysis-powerbi/screenshots/page4_service.png)

- Page 5: Insights & Recommendations
![Insights Page](customer-churn-analysis-powerbi/screenshots/page5_insights.png)

---

