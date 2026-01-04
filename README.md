# Subscription Intelligence Board -
Project Overview
The Challenge: Company XYZ needs to retain recurring subscribers (Claude Pro/Team) to maximize ARR. The current churn rate is ~26%, but the "Why" is unclear.
The Solution: A 3-page BI solution to identify "High Risk" cohorts and operationalize retention.

---
 Dashboard Previews

1. Executive Summary
High-level view of MRR, Churn Rate, and Revenue at Risk.
Executive Dashboard(Executive Overview.png)

2. AI-Powered Churn Risk Analysis
Used Power BI's "Decomposition Tree" and "Key Influencers" to automatically detect that Month-to-Month Fiber Optic users are 2.5x more likely to churn.*
   Risk Analysis(Risk Analysis.png)

3. Customer Detail List
A drill-through operational list for the Customer Success team to contact at-risk accounts immediately.
   (customer details.png)

---

Technical Steps
1. Data Modeling: Transformed raw Kaggle data (Star Schema not needed for single table, but logic applied).
2. Advanced DAX: Calculated `Churn Rate %` and `Revenue Lost` using `CALCULATE` and time-intelligence logic.
3. UX Design: Implemented "Dark Mode" for modern tech aesthetic and "Sync Slicers" for seamless navigation.

---

Key Insights
High Churn Segment: Users on Month-to-Month contracts have a 40% failure rate.
Payment Friction:Electronic Check users are the highest risk group.
Recommendation: Offer a 10% discount to move Month-to-Month users to Annual plans to save $150k in Revenue.
