# Customer-Shopping-Behavior-Analysis-

Tech Stack: Python | SQL | Power BI
📋 Project Overview
This project provides a comprehensive end-to-end analysis of customer shopping behavior. By integrating data engineering and business intelligence techniques, I transformed raw transactional data into actionable insights. The goal was to identify growth opportunities, optimize marketing focus, and understand the drivers behind customer retention and revenue.

🚀 Key Insights & Business Impact
Subscription Opportunity: Identified that 73% of customers are non-subscribers, revealing a massive untapped opportunity for retention programs and subscription-based conversion strategies.

Product Performance: Discovered that Clothing is the dominant category in both volume and revenue, whereas Outerwear is the lowest performer, suggesting a pivot in inventory and marketing focus.

Demographic Value: Analysis of age-wise trends revealed that Young Adults generate the highest revenue, pinpointing the most valuable segment for targeted promotional campaigns.

Geographic & Seasonal Trends: Mapped sales density across regions to identify top-performing states for logistics and supply chain optimization.

🛠️ Data Pipeline & Workflow
1. Data Cleaning & Transformation (Python)
Used Pandas and NumPy to handle the initial data prep:

Standardized categorical values and handled missing data.

Segmented ages into groups (Teenager, Young Adult, Adult, Senior) for deeper demographic analysis.

Calculated key metrics such as Average Order Value (AOV) and Churn Risk.

2. Business Logic & Exploration (SQL)
Performed complex queries to extract specific business metrics:

Segmentation: Grouped revenue by subscription status and product category.

Trend Analysis: Aggregated monthly sales to identify seasonal peaks.

SQL Operations: Utilized Joins, CTEs, and Window Functions to prepare clean datasets for visualization.

3. Data Visualization (Power BI)
Developed an interactive dashboard focusing on:

Executive Summary: High-level KPIs (Total Revenue, Total Orders, Average Rating).

Customer Segmentation: Donut and Bar charts showing the Subscriber vs. Non-Subscriber split.

Category Analysis: Comparative view of sales across different product lines.

Interactive Slicers: Allowed for real-time filtering by State, Gender, and Value Deals.

📂 Repository Structure
├── Data/               # Raw and Cleaned datasets
├── Python/             # Jupyter Notebooks for data cleaning
├── SQL/                # Scripts for data exploration and view creation
├── PowerBI/            # .pbix file and dashboard screenshots
└── README.md           # Project documentation

💡 Conclusion
The analysis highlights that business growth should focus on converting the 73% non-subscriber base and doubling down on the Young Adult demographic within the Clothing category. Implementing loyalty programs and targeted discounts for these segments could significantly increase Customer Lifetime Value (CLV).
