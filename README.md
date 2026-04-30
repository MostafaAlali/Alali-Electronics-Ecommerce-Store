# 📊 Alali Electronics Sales & Business Analysis (2019–2022)

---

# 📌 Project Background

Alali Electronics, established in 2018, is a global e-commerce company selling electronic products worldwide through its website and mobile application.

The company holds extensive data across:
- Sales performance  
- Marketing effectiveness  
- Operational efficiency  
- Product portfolio  
- Loyalty programs  

However, this data has been underutilized.  
This project analyzes and synthesizes the dataset to extract actionable insights that improve business performance and decision-making.

---

# 🎯 Project Objectives

This analysis focuses on three core business areas:

## 1. Sales Trends Analysis
Evaluation of historical performance across:
- Revenue
- Order Volume
- Average Order Value (AOV)

## 2. Product Performance Analysis
Understanding product-level contribution to revenue and identifying underperforming categories.

## 3. Regional Performance Analysis
Comparison of sales and order distribution across regions.

---

# 📁 Data Sources

- 📊 Tableau Dashboard: [Link Dashboard](https://public.tableau.com/app/profile/mostafa.alali/viz/Alali-Electronics-Ecommerce-Store/dashpord)
- 📦 Raw Data: [orders_data_raw_sheet](work_book/Alali_Analysis.xlsx)  
- 🧹 Clean Data: [orders_data_clean_sheet](work_book/Alali_Analysis.xlsx) 
- ⚠️ Issues Log: [issues_log_sheet](work_book/Alali_Analysis.xlsx) 
- 📈 Insights & Recommendations: [insights_tab_sheet](work_book/Alali_Analysis.xlsx)  

---

# 🧾 Data Structure & Quality Checks

- Dataset contains approximately **108K orders**
- Data quality validation and cleaning steps were documented in the **issues_log sheet**
- Initial checks ensured consistency in:
  - Product mapping  
  - Sales values  
  - Time-series integrity  

---

# 📊 Executive Summary

Between 2019 and 2022, total sales reached approximately **$24M**, with monthly revenue ranging from **$166K to $880K**, showing strong volatility and a clear growth-then-decline cycle.

## 📌 Key Insights ([pivot_table_1])
- Strong growth during **2020–2021**, followed by decline after 2021  
- Major spike in **April–May 2020** (external demand shock)  
- Sustained high performance from **March 2020 – May 2021** (> $700K monthly)  
- Post-2021 shows consistent downward trend  

## 📦 Product Performance
- **Top Product:** Gaming Monitor (~$8.4M total sales)  
- **Worst Product:** Headphones (~$3K → potential data issue)  
- Weak categories: Apple iPhone + SoundSport (~$200K)  

## ⚠️ Key Risk
- Heavy dependency on a small number of high-performing products
  
<img width="1194" height="545" alt="piovt_table_1" src="https://github.com/user-attachments/assets/ce12e641-5f28-400c-9ad8-4b6e06836f1d" />

---

#  Deep Dive Insights

## 1. Overall Sales Trend ([Tableau Tab → overall_usd])
- Sales more than doubled in early 2020  
- Peak performance: **Oct & Dec 2020**  
- Major declines:
  - Feb 2021  
  - Sep 2021  
  - Feb 2022  
- Post-2021 trend returns toward pre-COVID levels

  <img width="982" height="517" alt="prouduct_usd" src="https://github.com/user-attachments/assets/06cf884b-c99b-4c4e-9b12-3592485e3dbe" />

---

## 2. Product Performance Drivers ([Tableau Tab → prouduct_usd])
- Key drivers:
  - Gaming Monitor  
  - Apple AirPods Headphones  
  - MacBook Air  
- Lifecycle pattern:
  **Growth → Plateau → Decline (2021–2022)**  

📌 Insight:  
Revenue decline is structural across core products, not isolated.

<img width="982" height="517" alt="prouduct_usd" src="https://github.com/user-attachments/assets/c4db8866-158b-4e12-98c5-c25c112c0ac1" />

---

## 3. Marketing Channel Analysis ([Tableau Tab → markiting_usd])
- Direct channel dominates revenue  
- Other channels contribute marginally  

📌 Insight:  
High dependency on Direct traffic creates strategic risk and limits growth scalability.

<img width="984" height="520" alt="markiting_usd" src="https://github.com/user-attachments/assets/cedd3702-982e-4bfe-95f2-6a8fe2f8f091" />

---

## 4. Regional Analysis ([Tableau Tab → region_usd])
- All regions show similar decline in 2021–2022  

📌 Insight:  
This reflects a **global/macroeconomic trend**, not regional weakness.

<img width="979" height="528" alt="region_usd" src="https://github.com/user-attachments/assets/a74700d0-b551-447a-8864-de8dabb1c4ed" />

---

## 5. Product × Marketing Analysis ([Tableau Tab → prouduct_usd_markiting])
- MacBook shows significant decline in **Direct traffic (early 2021)**  
- Stronger drop compared to other products  

📌 Possible Causes:
- Funnel / UX changes  
- Competitive pressure  
- Regional demand shift (North America)
  
<img width="983" height="514" alt="prouduct_usd_markiting" src="https://github.com/user-attachments/assets/8e0631eb-a58c-4ab9-903c-6842994af74b" />

---

## 6. Product × Region Analysis ([Tableau Tab → prouduct_usd_region])
- MacBook decline concentrated in **North America**  
- Strong link with Direct channel performance  

📌 Insight:  
Issue is **localized to NA**, not global.

<img width="981" height="535" alt="prouduct_usd_region" src="https://github.com/user-attachments/assets/9b689a92-9789-4ec3-93f0-19a2aee7db3e" />

---

# ⚠️ Final Business Takeaways

- COVID period created a **temporary artificial demand surge (2020–2021)**  
- Post-2021 decline reflects **market normalization + product lifecycle saturation**  
- Business is highly dependent on:
  - Few key products  
  - Direct traffic channel  
- MacBook performance in North America requires urgent investigation  
- Overall trend indicates **structural slowdown, not random fluctuation**

---

# 📌 Recommendations

## 🧩 Product Team
- Audit “Headphones” data gap (~$3K anomaly)
- Investigate MacBook decline in North America
- Consider sunsetting underperforming categories (iPhone, SoundSport)

## 📣 Marketing Team
- Diversify away from Direct traffic dependency
- Launch re-engagement campaigns (2020 customer cohort)
- Strengthen SEO, Paid Ads, Affiliate channels
- Target North America with focused campaigns

## 💰 Finance Team
- Normalize post-2020 revenue expectations
- Avoid forecasting based on COVID spikes
- Apply lean inventory strategy
- Analyze profitability beyond revenue (shipping-heavy products vs margin impact)

---

#  Tools Used
- Excel / Pivot Tables  
- Tableau  
- Data Cleaning & KPI Analysis  

---

#  Author
Mostafa Alali

