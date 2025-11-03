# FMCG Sales Performance Analysis (Python + SQL + Power BI)

### Project Overview
This project focuses on analyzing **Fast-Moving Consumer Goods (FMCG) sales data** from **2022 to 2024** to understand sales patterns, promotional effects, and regional performance.  
I used **Python (Jupyter Notebook)** for data cleaning and preparation, **MySQL** for running queries and validating data, and **Power BI** for building an **interactive dashboard** with meaningful visuals and KPIs.

The dataset includes daily-level FMCG sales transactions such as date, SKU, price, promotion flag, stock availability, delivery details, and units sold.  
I created several **DAX measures** in Power BI to calculate total transactions, revenue, average price per unit, and revenue per transaction.

The dataset used is **“FMCG Daily Sales Data (2022–2024)”** from Kaggle, available here:  
🔗 [FMCG Daily Sales Data – Kaggle](https://www.kaggle.com/datasets/beatafaron/fmcg-daily-sales-data-to-2022-2024)

---

###  Objectives
- Analyze overall **sales performance and growth trends**.  
- Identify **top-performing channels, regions, and product categories**.  
- Study the **impact of promotions** on total units sold and revenue.  
- Evaluate **year-over-year sales trends**.  
- Create an **interactive Power BI dashboard** with filters for Year, Region, Channel, Promotion, and Category.

---

###  Key Insights
- **E-commerce** channel recorded the highest total units sold (~1.26M), showing customers’ growing preference for online purchases.  
- **Promotional campaigns** boosted sales volume by approximately **52%**, confirming that discounts drive strong engagement.  
- **North region** contributed the largest share of total revenue (~34%), indicating higher consumer demand or better marketing reach.  
- **Overall revenue** showed a consistent upward trend from **2022 → 2024**, supported by new product launches and gradual price adjustments.  
- **Average revenue per transaction** (₹104.59) and **average price per unit** (₹5.25) remained steady, showing strong customer retention and balanced pricing.

---

###  Tools Used
- **Python (Jupyter Notebook):** Cleaned and formatted the dataset before exporting to MySQL.  
- **MySQL Workbench:** Used for running SQL queries, aggregation, and trend analysis.  
- **Power BI:** Built interactive visuals, KPIs, and dashboards.  
- **DAX (Data Analysis Expressions):** Created formulas for revenue and other KPIs.  
- **Excel:** Used for quick reviews and pivot analysis.

---###  DAX Measures Used
All DAX formulas used in Power BI (for KPIs like Total Revenue, Avg Price, and Revenue per Transaction) are documented in the file attached.

---

###  Dashboard Snapshots
| Dashboard View | Description |
|----------------|-------------|
| ![Dashboard Overview]( FMCG_Sales_Aalysis/FMCG Dashboard_Main .png.png) | Main dashboard showing KPIs and filters |
> *Note:* The interactive Power BI dashboard for this project is included in the attached .pbix file.

---

###  Summary
This project demonstrates how **Python, SQL, and Power BI** can be combined to turn raw data into insights.  
From cleaning and preparing the data in Python, to querying and validating in MySQL, and finally visualizing results in Power BI — this project covers the **complete analytics workflow** for understanding FMCG sales trends, regional performance, and promotional impact.

