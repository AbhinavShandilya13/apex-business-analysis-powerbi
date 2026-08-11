# 📊 APEX | Business Analysis & Insights Dashboard (Power BI)

## 📌 Project Background

**APEX**, established in 2018, is a **fictional global e-commerce company** that sells popular consumer electronic products worldwide through its website and mobile application.

This project uses a **synthetic e-commerce dataset** created for analytical and educational purposes. The dataset is designed to closely mirror real-world business operations, including sales activity, customer behavior, marketing channels, operational efficiency, and a loyalty program.

As a **Business Analyst–focused project**, the objective is to analyze and synthesize this data to uncover **actionable insights** that support business decision-making and strategic planning.

### Key business areas analyzed:

- **📈 Sales Trends Analysis** – Revenue, Order Volume, and Average Order Value (AOV) trends over time  
- **📦 Product Performance** – Product-level contribution, concentration, and return behavior  
- **⭐ Loyalty Program Effectiveness** – Spending and retention behavior of loyalty vs. non-loyalty customers  
- **🌍 Regional Comparisons** – Sales and order trends across geographic regions  

📥 **Interactive Power BI Dashboard**  
➡️ [`APEX Electronics.pbix`](./APEX%20Electronics.pbix)

---

## 🧱 Data Structure & Initial Checks

APEX’s database structure consists of four core tables:

- `orders`
- `customers`
- `geo_lookup`
- `order_status`

The dataset contains **108,127 total records**, structured to resemble a real-world e-commerce analytics environment.

![APEX ERD](./APEX%20ERD.png)

Before beginning the analysis, **initial data quality checks** were conducted to identify:

- duplicate records  
- missing or null values  
- inconsistent categorical fields  
- unexpected date and price ranges  

🔍 SQL queries used for initial data inspection:  
➡️ [`Example Initial Data Checks.sql`](./SQL%20Queries/Example%20Initial%20Data%20Checks.sql)

---

## 🧹 Data Cleaning & Preparation

Following the initial checks, the data was cleaned, standardized, and enriched to ensure it was analysis-ready. Key steps included:

- Resolving inconsistent product naming conventions  
- Standardizing currency and geographic fields  
- Engineering analytical features such as:
  - product brand  
  - product category  
  - customer order sequence  
- Cleaning invalid or negative operational time metrics  
- Preparing a unified dataset for reporting and visualization  

🛠️ SQL queries used for data cleaning and preparation:  
➡️ [`Cleaning Data for Analysis.sql`](./SQL%20Queries/Cleaning%20Data%20for%20Analysis.sql)

---

## 🧠 Targeted Business Questions

With the cleaned dataset in place, targeted SQL queries were developed to answer practical, business-driven questions related to:

- sales performance and growth trends  
- fulfillment and delivery efficiency  
- customer purchasing behavior  
- product popularity and concentration risk  
- loyalty program impact on repeat purchases  

📊 Business-focused SQL queries:  
➡️ [`Targeted Business Questions.sql`](./SQL%20Queries/Targeted%20Business%20Questions.sql)

---

## 🎯 The Outcome

- **Revenue Decline:** Following a sales peak in **December 2020**, revenue declined by **~46%**, driven by a **~40%** drop in order volume and a **~10%** decrease in Average Order Value (AOV).
- **Baseline Stability:** Despite recent declines, full-year **2022** performance remained above the pre-2019 baseline.
- **Concentration Risk:** Identified high product concentration risk, with a small number of premium product categories generating the majority of orders and revenue.
- **Category Shifts:** While accessories increased as a share of order volume, they remained a minor contributor to total revenue.
- **Executive Dashboard:** Consolidated these findings into an interactive dashboard to guide strategic product diversification and revenue recovery.

<img width="1506" height="804" alt="image" src="https://github.com/user-attachments/assets/8a0f5b58-2a0d-4d5e-95ff-9981f2a6a940" />

---

## 📉 Sales Trends

- **Sales peaked in December 2020**, driven by pandemic-era consumer spending  
- Revenue declined on a year-over-year basis for most of 2021 and 2022  
- Despite the overall decline, **full-year 2022 remained above the pre-2019 baseline**  
- AOV trends were influenced by shifts toward higher-priced laptop purchases  



<img width="1498" height="802" alt="image" src="https://github.com/user-attachments/assets/a755bfa7-c59d-44b7-b472-deb13410950a" />

---

## 📦 Product Performance

- A small number of products accounted for the majority of orders and revenue, indicating **high product concentration risk**  
- Certain products consistently underperformed despite competitive pricing  
- Accessories increased as a share of order volume but remained a minor contributor to total revenue  
- Revenue remained heavily dependent on a limited number of premium product categories  



<img width="1477" height="800" alt="image" src="https://github.com/user-attachments/assets/26bd6964-d6da-43bf-8630-730c9a3b5c42" />

---

## ⭐ Loyalty Program Insights

- Loyalty program adoption increased steadily, reaching a majority share of total revenue  
- Loyalty members demonstrated **higher average order values and stronger repeat purchase behavior**  
- While non-members occasionally spent more on first purchases, loyalty members significantly outperformed on returning orders  


<img width="1475" height="803" alt="image" src="https://github.com/user-attachments/assets/964af4b9-cfd8-4163-a84d-e08ae2b8b561" />

---

## 🌍 Regional Comparisons

- North America emerged as the strongest region by both revenue and AOV  
- Sales and AOV declined across all regions in 2022  
- Certain regions showed improving order share toward the end of the analysis period, indicating potential growth opportunities  


<img width="1457" height="797" alt="image" src="https://github.com/user-attachments/assets/f09c2660-6ac5-4a4c-9afa-163f1a6e69c6" />

---

## ✅ Business Recommendations

Based on the insights uncovered, the following recommendations were identified:

- Diversify the product portfolio to reduce reliance on a small number of high-performing products  
- Expand complementary and accessory product lines to increase upsell opportunities  
- Strengthen loyalty program marketing to convert high-value non-members  
- Re-evaluate consistently underperforming products through promotions or discontinuation strategies  
- Use regional performance insights to better align marketing and inventory decisions  

---

## 📌 Data Disclaimer

This project uses a **synthetic dataset** created for analytical and educational purposes. The data does not represent any real company or customers but is structured to closely mirror real-world e-commerce business scenarios.

---


