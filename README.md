# 📊 AdventureWorks Business Performance Dashboard  

### Created by **Crystal Andrea Dsouza**

This repository showcases an interactive **Power BI dashboard** built using the **AdventureWorks dataset** as part of the **Microsoft Power BI Desktop course by Maven Analytics**.  

The dashboard provides a comprehensive, multi-page analysis of business performance, enabling users to explore revenue trends, customer insights, product profitability, and regional performance through dynamic, data-driven visuals.

---

## 🧠 Project Objective  

The goal of this project is to analyze **AdventureWorks' sales and profitability performance** using Power BI. Through calculated DAX measures and visual storytelling, the dashboard helps identify key business trends, track KPIs, and support data-driven decision-making.

---

## ⚙️ Tools & Technologies  

- **Microsoft Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **AdventureWorks Sample Dataset**  
- **Data Modeling and Relationship Building**  
- **Interactive Visualizations and Drill-Throughs**  

---

## 📁 Dashboard Pages  

### 1. 📊 Executive Summary  

This Power BI dashboard provides a comprehensive overview of AdventureWorks' key business metrics, enabling stakeholders to monitor performance, identify trends, and explore product-level insights.  

#### 🔍 Key Features  
- **Top-Level KPIs**  
  - Revenue: $24.9M  
  - Profit: $10.5M  
  - Orders: 25.2K  
  - Return Rate: 2.2%  
- **Revenue & Profit Trend** – Dual-line chart showing monthly revenue and profit (Jan–Dec 2022), highlighting consistent growth.  
- **Orders by Category** – Bar chart displaying order distribution:  
  - Accessories (13.7K)  
  - Bikes (7.3K)  
  - Clothing (4.1K)  
  (Hover to see details via tooltip.)
<img width="600" height="965" alt="image" src="https://github.com/user-attachments/assets/8506f04b-39c5-48f8-8910-46cb2094ff4b" />

- **Monthly Metrics Comparison**  
  - Revenue: $1.83M (↑ from $1.77M)  
  - Orders: 2.15K (↓ from 2.81K)  
  - Return Rate: 166% (↓ from 176%)  
- **Top 10 Products Matrix** – Interactive product-level data with order count, revenue, and return rate. Drill-through enabled by right-clicking on Product Name.
 <img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/8b598d81-ffb2-4f5c-9a50-f92506ad82af" />

- **Product Type Highlights** – Most Ordered: *Tires and Tubes* | Most Returned: *Tires and Tubes*  

#### 🎯 Purpose  
To support data-driven decision-making by surfacing high-impact KPIs and enabling granular product-level exploration for profitability, return analysis, and category insights.  

<img width="800" height="1037" alt="image" src="https://github.com/user-attachments/assets/cfd0afb9-1796-43f0-abda-053f0a93d6b4" />

---

### 2. 🌍 Global Performance Map  

An interactive Power BI map visual showcasing AdventureWorks' regional business performance across key markets. It provides a geographic breakdown of orders, customers, profit, returns, and revenue.  

#### 🗺️ Key Features  
- Dark-themed world map with turquoise data points sized by metric magnitude.  
- Regional segmentation via slicers: *Select All, Europe, North America, Pacific.*  
- Example (United States):  
  - Total Orders: 8,700  
  - Customers: 7,235  
  - Profit: $3.45M  
  - Returns: 624  
  - Revenue: $7.84M  
- Additional regions: Canada, UK, France, and Australia.  
- Azure-powered visual layer for cloud scalability.  

#### 🔍 Interactivity  
- Hover to reveal detailed metrics by country.  
- Region-based filters for focused analysis.  

#### 🎯 Purpose  
To enable stakeholders to assess performance by country, identify high-performing regions, and prioritize strategic initiatives globally.  


<img width="800" height="1037" alt="image" src="https://github.com/user-attachments/assets/2717d169-3b31-4677-9820-0b2cdb906772" />

---

### 3. 🛍️ Product Performance Detail  

This page offers a focused view of a single product’s performance, enabling granular analysis of sales, profitability, and returns.  

#### 🔍 Key Features  
- **Selected Product:** Example – *Water Bottle – 30 oz*  
- **Monthly KPIs vs Targets**  
  - Orders: 404  
  - Revenue: $4,067  
  - Profit: $2,546  
- **Visuals:**  
  - Line chart: *Total Profit vs Adjusted Profit*  
  - Return % Over Time  
  - Interactive **Price Adjustment Simulation** (−10% to +10%)  
- **Metric Selector:** Toggle between *Orders, Revenue, Profit,* and *Returns*  
- **Tooltip Summary:** Highlights peak return dates and profit changes  

#### 🧭 Navigation & Interactivity  
- Change the product via filter pane  
- Drill through from the **Executive Summary matrix** for direct access  

#### 🎯 Purpose  
Empowers product managers and analysts to evaluate product performance, test pricing strategies, and monitor return behavior for informed decision-making.  

<img width="800" height="1038" alt="image" src="https://github.com/user-attachments/assets/3c8bf05d-c88d-47bc-821a-a1620b3849bf" />

---

### 4. 👥 Customer Revenue Analytics  

This dashboard explores customer behavior and revenue generation patterns to help identify high-value customers and guide engagement strategies.  

#### 🔍 Key Features  
- **Top-Level Metrics**  
  - Revenue per Customer: $1.4K  
  - Unique Customers: 17.4K  
- **Customer Revenue Trend:** Line chart (July 2020–July 2022)  
- **Demographic Insights:**  
  - Orders by Income Level (High, Medium, Low)  
  - Orders by Occupation (Skilled Manual, Management, Clerical)  
- **Top 100 Customers Table:**  
  - Columns: Customer Key, Full Name, Orders, Revenue  
  - Highlights:  
    - *Mr. Maurice Shan:* 6 Orders, $12,408 Revenue  
    - *Ruben Suarez:* $4,680 Revenue (Skilled Manual)  
- **Filters:** Quick year selection between (2020 - 2022)  

#### 🧭 Navigation & Interactivity  
- Explore customer-level data via slicers and filters  
- Complements other dashboards with a customer-centric focus  

#### 🎯 Purpose  
Supports marketing and sales teams by revealing top customers, revenue sources, and behavioral trends for segmentation and strategic planning.  

<img width="1779" height="1038" alt="image" src="https://github.com/user-attachments/assets/6605eb93-0a90-4b16-adac-453951c26f31" />

---

## 🧮 Key DAX Measures  

This project uses over 30 custom DAX measures to calculate and visualize KPIs including:  
- **Sales & Returns:** `[Quantity Sold]`, `[Quantity Returned]`, `[Total Returns]`  
- **Financials:** `[Total Revenue]`, `[Total Profit]`, `[Average Retail Price]`, `[Revenue Target]`  
- **Rolling Metrics:** `[10 Day Rolling Revenue]`, `[90 Day Rolling Profit]`  
- **Performance Indicators:** `[Order Target]`, `[Profit Target]`, `[Target Gaps]`  
- **Adjustments:** `[Adjusted Price]`, `[Adjusted Profit]`, `[Adjusted Revenue]`  

(Full list of DAX formulas included in this repository.)

---

## 📄 Repository Contents  

| File | Description |
|------|--------------|
| `Crystal_Maven_AdventureWorks_PBI_DB.pdf` | Dashboard overview (PDF export) |
| `Maven_AdventureWorks_PBI_Course.pbix` | Power BI Dashboard (.pbix) |
| `DAX_Measures_List.xlsx` | DAX calculations used in the model |
| `README.md` | Documentation file (this file) |

---

## 🏁 Conclusion  

This Power BI project demonstrates how **data modeling**, **DAX**, and **visual design** can transform raw sales data into actionable insights. The dashboard highlights AdventureWorks’ performance story through clear, interactive visuals that help drive strategic business decisions.
