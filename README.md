# Sales-Performance-Analytics-Dashboard
## Description
A Power BI-based analytics project analyzing sales performance, budget adherence, customer behavior, and product trends across regions and time periods (2019–2021). Designed to uncover actionable insights for revenue optimization and strategic planning.
## Power BI Dashboard
https://app.powerbi.com/view?r=eyJrIjoiNTViNTEyNjMtYWFkYi00NDQ4LWJiZDAtMjk5Y2E1MGQ2YWNhIiwidCI6IjU1YmQ5ZTdkLTdkMWEtNGZlNy1hNmZmLTJhOWY0YzdkZjAxYSJ9
## Project Overview
### Business Problem
The business lacks visibility into seasonal sales trends, product performance, and customer segmentation, leading to inefficient budget allocation and missed growth opportunities.
### Objective
Example: Build an interactive dashboard to visualize sales vs. budget, identify top-performing products/customers, and provide data-driven recommendations for improving profitability.
## Target Audience
Sales Managers
Finance Teams
Executive Leadership
Supply Chain Planners
## Data Structure and Data Model
![Sales Insights](https://github.com/user-attachments/assets/851f5934-3fc0-4e20-8a24-2b4b99525fb4)

### Data Sources
Primary Data: Sales transactions (2019–2021) with fields: Year, Month, Customer City, Product Name, Category, Sub-Category, Sales, Budget.
Secondary Data: Customer purchase history (top 10 customers by revenue).
### Data Cleaning
Handled missing Customer City entries.
Standardized product naming conventions (e.g., "Mountain-200 Black, 42").
Aligned budget data with fiscal calendar.
### Data Model
Star Schema: Central Sales fact table linked to Time, Product, Customer, and Geography dimensions.
Key Relationships:
Sales[Month] → Time[Month]
Sales[Product Name] → Product[Product Name]
Sales[Customer City] → Geography[City]
### Tools Used
Analytics: Power BI, DAX (for measures like Sales vs. Budget Variance).
Data Processing: Power Query, Excel.
Version Control: GitHub.
## Executive Summary
### Key Findings
Sales exceeded budget by $1.05M (6.8%), driven by Q4 performance.
Bikes dominate revenue (93.9%), while Accessories lag at 4.1%.
Top 10 customers (e.g., Jordan Turner) collectively contribute ~$100K.
### Impact
Identified $5.6M+ revenue from the Mountain-200 product series.
Highlighted seasonal gaps (e.g., low Feb sales) for targeted promotions.
Insights Deep-Dive
Interactive Dashboard Link
## Detailed Insights
![image](https://github.com/user-attachments/assets/700cabcf-c7cf-45bb-a455-120757162fa5)
![image](https://github.com/user-attachments/assets/455b781d-696d-4087-b92f-66253163aa0d)
![image](https://github.com/user-attachments/assets/32e9b613-cea5-4c51-9fb7-d5f496273963)
### Product Performance:
#### Dominance of Mountain-200 Series:
The Mountain-200 Black, 42 model alone generated $970,781 in sales, making it the top-performing product.

6 variants of the Mountain-200 series (Black/Silver, sizes 38–46) collectively contributed $5.6M+, representing 34% of total revenue.

Why It Sells: Likely due to its positioning as a premium, versatile mountain bike appealing to both casual and professional riders.

Risk: Over-reliance on a single product line exposes the business to market shifts (e.g., competitor launches, supply chain disruptions).
#### Underperformance of Accessories:
Accessories contributed only 4.1% ($668,242) of total sales, despite their potential for higher margins.

Root Cause: Lack of bundling strategies (e.g., helmets/locks with bike purchases) or targeted marketing campaigns.

Opportunity: Increasing accessories’ share to 10% could add ~$1M annually without significant overhead.

### Customer Analysis:
#### Top Customer Behavior:
Jordan Turner (top spender at $11,484) made 55% of his annual purchases in June ($3,239) and April ($2,433), suggesting bulk buying for seasonal demand (e.g., summer cycling events).

Maurice Shan ($10,861) and Janet Munoz ($10,418) showed consistent quarterly spending, indicating loyalty.

Risk: Top 10 customers account for ~$100K (0.6% of total revenue), highlighting fragmented demand.

#### Geographic Gaps:
While customer cities are filterable in the dataset, specific regional trends are invisible.

Recommendation: Drill into city-level data to identify high-potential markets (e.g., urban vs. rural demand).

### Seasonality:
#### Q4 Dominance:
December alone contributed $1.87M (11.4% of annual sales), driven by holiday gifting and year-end discounts.

October–December collectively generated $5.33M (32.6% of annual revenue), emphasizing the criticality of Q4 planning.
#### Mid-Year Slumps:
February had the lowest sales ($771,349), likely due to post-holiday budget constraints.

July–August averaged $1.46M/month, underperforming compared to Q4 months.

Opportunity: Launch “off-season” promotions (e.g., summer cycling challenges) to boost mid-year sales.
## Recommendations
### Actionable Recommendations
Launch Q4 promotional campaigns to capitalize on peak demand.
Bundle accessories with bikes to boost underperforming categories.
Allocate higher budgets to H2 (Jul–Dec) based on historical overperformance.
### Business Impact
5–10% revenue growth by optimizing inventory for high-demand products.
15% margin improvement via cost renegotiation for low-performing categories.
## Skills Demonstrated
### Technical Skills
Power BI dashboard development (e.g., drill-downs, bookmarks).
DAX for dynamic metrics (Sales vs. Budget Variance).
Data modeling (star schema, relationships).
### Soft Skills
Stakeholder communication (translating data to strategy).
Storytelling with visualizations (e.g., seasonal trends).
## Challenges and Learnings
### Challenges
Data granularity: Missing customer demographics.
Budget alignment: Discrepancies in monthly vs. annual targets.
### Learnings
Seasonal trends heavily influence inventory planning.
Top 10 products drive 80% of revenue—focus on diversification.
