📊 APEX | Business Analysis & Insights Dashboard
Project Background

APEX, established in 2018, is a fictional global e-commerce company that sells popular electronic products worldwide via its website and mobile application.

The dataset used in this project is a synthetic e-commerce dataset created for analytical and educational purposes. It is designed to closely resemble real-world business operations, including sales activity, marketing efforts, operational efficiency, product offerings, and a customer loyalty program.

This project analyzes and synthesizes this data to uncover actionable business insights that can support strategic decision-making and improve overall commercial performance.

Insights and recommendations are provided across the following key areas:

Sales Trends Analysis: Evaluation of historical sales patterns, both globally and by region, focusing on Revenue, Order Volume, and Average Order Value (AOV).

Product Level Performance: Analysis of product lines to understand their contribution to sales, order concentration, and returns.

Loyalty Program Success: Assessment of the loyalty program’s impact on customer retention and spending behavior.

Regional Comparisons: Evaluation of sales and order trends across geographic regions.

📥 An interactive Power BI dashboard used for this analysis can be downloaded here:
APEX Business Analysis Dashboard (.pbix)

🧱 Data Structure & Initial Checks

APEX’s database structure consists of four core tables:

orders

customers

geo_lookup

order_status

The dataset contains 108,127 total records, structured to reflect a realistic e-commerce analytics environment.

<img width="1875" height="1114" alt="APEX ERD" src="https://github.com/user-attachments/assets/8969a04d-ba3f-4278-a200-ac60c88cde17" />

Prior to beginning the analysis, a series of initial data quality checks were conducted to identify inconsistencies, missing values, duplicates, and unexpected ranges.

The SQL queries used for these initial checks can be found here:
SQL Queries / Example Initial Data Checks.sql

🧹 Data Cleaning & Preparation

After completing the initial checks, the data was cleaned, standardized, and enriched to ensure it was suitable for analysis and reporting. Key steps included:

Resolving inconsistent product naming

Standardizing currency and geographic fields

Engineering new analytical features (brand, product category, customer order sequence)

Cleaning invalid operational time metrics

Preparing a unified, analytics-ready dataset for visualization

The SQL queries used for data cleaning and preparation can be found here:
SQL Queries / Cleaning Data for Analysis.sql

🧠 Targeted Business Questions

With the cleaned dataset in place, targeted SQL queries were developed to answer practical business questions related to sales performance, fulfillment efficiency, customer behavior, and product popularity.

These business-focused SQL queries can be found here:
SQL Queries / Targeted Business Questions.sql

📈 Executive Summary
Overview of Findings

After peaking in late 2020, APEX’s sales performance declined steadily, with the most significant drops occurring in 2022. Key performance indicators showed notable year-over-year decreases:

Order Volume: ↓ ~40%

Revenue: ↓ ~46%

Average Order Value (AOV): ↓ ~10%

While part of this decline aligns with post-pandemic normalization of consumer behavior, further analysis highlights additional contributing factors and potential opportunity areas.

Below is an overview page from the Power BI dashboard.

<img width="1506" height="804" alt="image" src="https://github.com/user-attachments/assets/5c2fd1ee-f3a0-4856-aa27-f7896959979f" />


📉 Sales Trends

Sales peaked in December 2020, driven by pandemic-era consumer spending.

Beginning in April 2021, revenue declined on a year-over-year basis for an extended period, reaching a low point in late 2022.

Despite the overall decline, full-year 2022 performance remained above the pre-2019 baseline, supported by a strong first quarter.

AOV fluctuations were influenced by changes in product mix, particularly higher-priced laptop purchases.

<img width="1498" height="802" alt="image" src="https://github.com/user-attachments/assets/03c274f7-6a05-4ca8-8973-0c1c257957b5" />


📦 Product Performance

A small number of products accounted for the majority of orders and revenue, indicating high product concentration risk.

Certain products consistently underperformed despite competitive pricing.

Accessories increased as a share of order volume but remained a minor contributor to total revenue.

Revenue was heavily dependent on a limited number of premium product categories.

<img width="1477" height="800" alt="image" src="https://github.com/user-attachments/assets/7b4be323-60cd-4739-9c31-bc77eee88aec" />


⭐ Loyalty Program

Loyalty program adoption increased steadily over time, reaching a majority share of total revenue.

Loyalty members demonstrated higher average order values and stronger repeat purchase behavior.

While non-members occasionally spent more on initial purchases, loyalty members significantly outperformed on returning orders.

<img width="1475" height="803" alt="image" src="https://github.com/user-attachments/assets/eebbba39-2a28-4d84-a9b4-6461bc525457" />


🌍 Regional Comparisons

North America emerged as the strongest region by both revenue and AOV.

Sales and AOV declined across all regions in 2022.

Certain regions showed improving order share toward the end of the analysis period, suggesting potential growth opportunities.

<img width="1457" height="797" alt="image" src="https://github.com/user-attachments/assets/c4a6769f-48fa-444e-93f9-9d0fe135419d" />


✅ Business Recommendations

Based on the insights uncovered, the following recommendations were identified:

Diversify the product portfolio to reduce reliance on a small set of high-performing products.

Expand complementary and accessory product lines to create upsell opportunities.

Strengthen loyalty program marketing to convert high-value non-members.

Re-evaluate consistently underperforming products through promotions, bundling, or discontinuation.

Use regional insights to better align marketing and inventory strategies.

📌 Data Disclaimer

This project uses a synthetic dataset created for analytical and educational purposes. The data does not represent any real company or customers but is designed to closely mirror real-world e-commerce business scenarios.

👤 Project Ownership

This project was analyzed, structured, and visualized by Abhinav Shandilya as part of a Business Analyst portfolio, focusing on data-driven insights and decision support.
