# Telco Customer Churn Analysis

## Overview
This project analyzes customer churn for a fictional telecom company using IBM's publicly available Telco Customer Churn dataset. The dataset contains 7,043 customers with 21 features covering demographics, services, billing information, and churn status.

The goal is to identify key churn drivers and provide actionable business insights through an interactive 4-page Power BI report built on a star schema data model.

---

## Tools & Techniques
- **Power BI** — Report development and visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Calculated measures and columns
- **Star Schema** — Data modeling

---

## Data Model
The data was structured into a star schema with the following tables:
- **Fact_Churn** — Central fact table containing churn status, charges, and foreign keys
- **Dim_Customer** — Customer demographics
- **Dim_Services** — Services subscribed
- **Dim_Billing** — Billing and contract information
- **Services_SS** — Unpivoted Security & Support services for grouped analysis
- **Services_EC** — Unpivoted Entertainment & Communication services for grouped analysis

---

## Report Pages
1. **Overview** — High-level KPIs and top churn drivers
2. **Customer Segments** — Churn analysis by customer demographics
3. **Services Analysis** — Churn by subscribed services with interactive bookmark navigation
4. **Billing & Contract** — How payment behavior and contract type affect churn

---

## Key Findings
- Overall churn rate: **26.54%** (1,869 out of 7,043 customers)
- Lost revenue from churned customers: **$2,862,926.90**
- Month-to-month customers churn at **42.71%** — 15x higher than two-year contract holders at 2.83%
- Fiber Optic customers churn at **41.89%** despite having the better service
- Electronic check users have the highest churn rate at **45.29%**
- New customers (0-12 months) churn at **47.44%** dropping to 9.51% for long-term customers
- Senior citizens churn at **41.68%** compared to 23.61% for non-seniors

---

## Business Recommendations
1. **Incentivize longer contracts** — offering discounts for annual or biannual commitments could significantly reduce churn
2. **Investigate Fiber Optic pricing** — premium service customers churning at high rates suggests a pricing or quality issue
3. **Focus retention efforts on new customers** — nearly half of customers in their first year leave
4. **Encourage automatic payment methods** — electronic check users churn at more than double the rate of automatic payment users

---

## Screenshots
<img width="1074" height="717" alt="image" src="https://github.com/user-attachments/assets/924cbc09-d737-4dad-bdc0-f5c432420809" />
<img width="1649" height="793" alt="image" src="https://github.com/user-attachments/assets/c515f482-2070-4cc4-96a5-0d86b080301a" />
<img width="1643" height="797" alt="image" src="https://github.com/user-attachments/assets/57ccc5d0-89cd-4781-b724-92be93d5e868" />
<img width="1641" height="789" alt="image" src="https://github.com/user-attachments/assets/a43b6c3d-df41-488a-be85-b978023e6886" />
<img width="1654" height="793" alt="image" src="https://github.com/user-attachments/assets/c3fed5d5-2f44-45e8-8a72-30dc0d183345" />






