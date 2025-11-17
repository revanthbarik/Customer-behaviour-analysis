link to dashboards
https://public.tableau.com/app/profile/revanth.barik/viz/custbehavdash/Dashboard1?publish=yes
https://public.tableau.com/app/profile/revanth.barik/viz/custbehavdash/Dashboard2?publish=yes

Customer Behavior & Churn Analysis (Tableau)

This repository contains my code, data, and Tableau workbook for a customer behavior analysis project. I built two main dashboards:

RFM Customer Segmentation: To identify high-value and at-risk customer segments.

Churn Analysis: To understand the primary drivers of customer attrition.

🚀 Live Dashboards

You can view and interact with my final, live dashboards on Tableau Public:

Dashboard 1: RFM Customer Segmentation

Dashboard 2: Churn Analysis

1. Project Objective

My objective for this project was to:

Analyze a customer behavior dataset to identify key customer segments using RFM (Recency, Frequency, Monetary) analysis.

Investigate the primary drivers of customer churn.

Provide actionable recommendations for marketing and retention strategies.

2. Data Transformation

I processed the raw data using a Python script (available in the /code folder). My key transformation steps included:

Calculating Recency, Frequency, and Monetary values for each customer.

Creating RFM Segment scores based on purchasing behavior.

Engineering a Churn feature based on [<- Explain your logic here, e.g., "customers with Recency > X days"].

I then exported the final, clean dataset (/data/Customer_Behavior_Analysis.csv) to use in Tableau.

3. Dashboard 1: RFM Customer Segmentation

This dashboard breaks down the customer base by their purchasing habits to identify core business drivers.

(placeholder for Dashboard 1 screenshot)

Key Insights from my analysis:

Insight 1 (Histogram): The Monetary Distribution is heavily right-skewed, with a massive concentration of customers (~270k) in the lowest spending bin. This shows the business model is driven by a high volume of low-value, single-purchase customers.

Insight 2 (Heatmap): The Recency vs Frequency heatmap confirms this, showing the customer base is clustered in the "low frequency, low recency" corner. This means most customers are new or one-time buyers who have not yet made a second purchase.

4. Dashboard 2: Churn Analysis

This dashboard identifies which customers we are losing and where the churn is coming from.

(placeholder for Dashboard 2 screenshot)

Key Insights from my analysis:

Insight 1 (KPI): The overall churn rate is [Your % from Sheet 4].

Insight 2 (Bar Chart): The "Churn by Segment" chart identifies [Your highest churn segment, e.g., '144'] as the segment contributing the most to customer loss.

Insight 3 (Heatmap): The churn heatmap clearly shows that churn is highest among customers with high recency (haven't bought in a long time) and low frequency. My analysis proves the business is failing to convert one-time buyers into loyal, repeat customers.

5. Recommendations

Based on my analysis, I recommend two key actions:

Target "At-Risk" Segments: Launch a targeted "win-back" email campaign for the highest-churning segments identified in Dashboard 2 (e.g., [Your highest churn segment]).

Encourage Repeat Purchases: Since the primary problem is retaining new, one-time buyers, implement a loyalty program or a "second purchase" discount code to improve retention and move customers from a frequency of 1 to 2.

6. How to Use

View Live: Interact with my dashboards on Tableau Public.

View Code: See my Python data transformation logic in the /code folder.

View Workbook: Download my complete Tableau Packaged Workbook (.twbx) from the /dashboard folder to explore the charts and calculations.
