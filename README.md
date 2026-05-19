# Sales Analysis – KajoData Space
### Competition Project | Data Acolyte × KajoDataSpace

---

![Dashboard Preview](https://github.com/user-attachments/assets/edd3f87e-53b3-414a-82b3-4a9370798c57)

## Project Overview
---
A sales data analysis for the KajoData Space store, completed as part of a competition organized by Data Acolyte and KajoDataSpace.
The goal was to explore customer purchasing behavior and derive actionable insights to support the store's marketing strategy.

## Business Brief
---
The dataset covers transactions from November 2023 to March 2026. The analysis is designed to answer the following business questions:
- What is the retention rate of new customers?
- How do pricing levels affect new customer retention?
- Should the business introduce promotions or price increases for new customers?

## Objectives
---
- Identify key revenue sources by payment type
- Analyze customer retention and behavior over time
- Evaluate the effectiveness of subscription vs. one-time payment models
- Develop strategic recommendations for the marketing team

## Data & Preparation
---
The raw dataset contains 4,228 records and 3 columns: transaction date, customer ID, and transaction amount.

**Original columns:**
- `transaction_date` – date of each purchase
- `customer_id` – unique customer identifier
- `amount` – transaction value in PLN

**Columns added after cleaning:**
- `active_status` – flags each customer as active or inactive
- `subscription_type` – categorizes the type of subscription
- `price_range` – groups transaction values into pricing tiers
- `month`, `year` – extracted from transaction_date for time-series analysis

## Analysis
---
KPI metrics were used to measure average revenue per customer (ARPU) and churn rate from 2024 to 2025. Time-series charts were built to illustrate how retention and average basket value fluctuate over time. The visualizations also break down revenue contribution by subscription type, showing which models drive the most income.

## Key Findings
---
- One-time payments represent the second largest transaction group in terms of revenue generated (~14%). Customers in this segment prefer higher-priced, broader packages over single-product subscriptions.
- August recorded the highest retention rate among new customers — making it the ideal window for onboarding and cross-sell campaigns.
- Active customers most frequently choose monthly packages in the 100–500 PLN range and below 100 PLN. Regular, lower-value payments appear to support long-term loyalty.
- 55% of customers acquired in 2024 did not return in 2025. During that period, ~90% of users were on regular subscriptions, which may point to limited long-term LTV potential within that group.

## Strategic Recommendations
---
- **Break up all-in-one bundles** – replacing broad packages with smaller, focused but still relatively high-priced offerings helps maintain ARPU while creating room to grow LTV through gradual upsell.
- **Launch a campaign in August** – retention among new customers peaks in this month, making it the most effective window for onboarding, promotions, and cross-sell initiatives.
- **Adjust monthly package pricing upward** – a moderate price increase on monthly plans can grow recurring revenue without putting stable MRR at risk.

## Tools & Technologies
---
- **Excel** – data cleaning, preparation and calculations
- **Power BI** – data visualization and dashboarding

## Competition
---
This project was completed as part of an analytics competition organized by:
- [Data Acolyte](https://www.dataacolyte.com)
- [KajoDataSpace](https://www.kajodataspace.com)
