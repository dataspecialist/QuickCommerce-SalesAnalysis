# Quick Commerce-Sales Analysis

## 📌Project overview:
This project presents an **end-to-end Power BI dashboard** analyzing **Blinkit's grocery sales performance** across outlets, item categories, sizes, and locations. The goal is to simulate **a real-world business analytics use case** suitable for interviews, portfolio reviews, and stakeholder storytelling.

## 📂 Dataset description:
* **Source:** `Blinkit Grocery Data.csv`.
* **Volume:** 8,523 Records.
* **Key Attributes:**
    * `Item Fat Content`: Low Fat vs. Regular.
    * `Item Type`: Category (Fruits, Snacks, etc.).
    * `Outlet Location Type`: Tier 1, Tier 2, Tier 3.
    * `Outlet Size`: High, Medium, Small.
    * `Outlet Type`: Grocery Store, Supermarket Type 1/2/3.
 
## 📈 Key Performance Indicators (KPIs):
* **Total Sales:** $1.20M (Revenue generated).
* **Average Sales:** $141 (Avg transaction value).
* **Number of Items:** 9K (Total items sold).
* **Average Rating:** 4/5 (Customer satisfaction score).

## 🧹 Data Preparation & Semantic Layer:
To ensure data integrity and optimal dashboard performance, the following technical steps were implemented:
* **Advanced Data Cleaning:** Utilized Power Query to standardize inconsistent categorical values (e.g., mapping "LF" and "low fat" to "Low Fat") to ensure accurate aggregation.
* **DAX Measure Development:** Authored complex calculated measures using DAX to track real-time KPIs, including Total Sales, Average Rating, and Year-over-Year growth simulations.
* **Star-Schema Modeling:** Designed a robust semantic model optimized for performance, utilizing a star-schema approach to facilitate seamless filtering across multiple dimensions (Outlet, Item Type, and Location).
* **Attribute Engineering:** Created custom groupings and bins for outlet sizes and item categories to provide deeper granularity in stakeholder reporting.
  
## Dashboard Screenshot:-
Check out the dashboard here - 
 **[Dashboard](https://github.com/dataspecialist/QuickCommerce-SalesAnalysis/blob/main/Blinkit%20Dashboard.pbix)** 
 
 <p align="center">
  <img src="[path/to/your/image.png](https://github.com/dataspecialist/QuickCommerce-SalesAnalysis/blob/main/image.png)" width="600" />
</p>

## 🔍 Key Insights:
1.  **Consumer Health Shift:** "Low Fat" products generate significantly higher sales ($776K) compared to "Regular" products ($425K).
2.  **Tier 3 Dominance:** Surprisingly, Tier 3 locations lead in total sales ($472K), outperforming Tier 1 ($336K).
3.  **Outlet Efficiency:** Medium-sized outlets are the most profitable, contributing ~42% of total sales.
4.  **Category Leaders:** "Fruits & Vegetables" and "Snack Foods" are the top revenue-generating categories.

## 💡Decisions & Actions (The "So What?"):
Based on the data, the following strategic actions are recommended:

| **Observation** | **Recommended Action** | **Owner** | **Expected Impact** |
| :--- | :--- | :--- | :--- |
| **1. Tier 3 cities have highest sales** | **Expand infrastructure** (Dark Stores) in Tier 3 cities rather than saturating Tier 1. | Operations / Expansion Team | 15-20% increase in regional market share. |
| **2. Low Fat items sell more** | **Adjust Inventory:** Increase stock of Low Fat items by 20% and reduce shelf space for Regular items. | Supply Chain Manager | Reduction in inventory holding cost & waste. |
| **3. Medium outlets perform best** | **Standardize new outlets** to "Medium" size (~40% of revenue) rather than High/Small. | Franchise / Strategy Team | Higher revenue per sq. ft. efficiency. |
| **4. Fruits/Snacks are top sellers** | **Bundle Offers:** Create "Healthy Snacking" bundles (Fruit + Low Fat Snack) to increase Average Order Value (AOV). | Marketing Team | 5-10% uplift in Average Order Value. |
