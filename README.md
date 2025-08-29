# 📊 Sales & Customer Insights Dashboard

## 🚀 Overview

This project analyzes sales, customer, and product performance using a
dataset of **5 tables**:
- **Sales**
- **Customers**
- **Regions**
- **State Regions**
- **Products**

## Project Workflow
1. **Data Preparation (Python, VS Code)**  
   - Cleaned, merged, and transformed 5 datasets: Sales, Orders, Customers, Products, Regions, and State Regions.  
   - Performed Exploratory Data Analysis (EDA) using Python (pandas, matplotlib).  

2. **Business Metrics (DAX in Power BI)**  
   - Created calculated columns and measures using DAX for KPIs like Profit, Revenue, Order Quantity, and Customer Segmentation.  
   - Built time intelligence measures for trend analysis.  

3. **Dashboarding (Power BI)**  
   - Designed 3 interactive dashboards with slicers, filters, and navigation buttons.  
   - Customer Insights, Product & Sales Analysis, and Regional/Market Performance.  


------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Python** → Data Cleaning, Transformation, EDA.
-   **Power BI** → Interactive Dashboard Creation, Data Visualization.
-   **VS Code** → Development Environment.

------------------------------------------------------------------------

## 📂 Dataset Preparation

1.  Merged all 5 tables into a unified dataset.
2.  Cleaned missing values, corrected column names, and standardized
    formats.
3.  Created new calculated fields (profit, revenue, order value,
    margins).
4.  Exported the clean dataset into Power BI for visualization.

------------------------------------------------------------------------

## 📊 Dashboards

### 1️⃣ Sales Performance Overview

-   **KPIs**: Total Orders, Avg Order Value, Total Revenue, Total
    Profit, Profit Margin %.
-   **Visuals**:
    -   Revenue Tree Map by Products
    -   Revenue by Channel (Wholesale, Distributor, Export)
    -   Revenue & Profit Trend by Year
    -   Revenue Distribution by Region

👉 **Goal**: High-level **business performance monitoring**.

------------------------------------------------------------------------

### 2️⃣ Customer & Market Insights

-   **Visuals**:
    -   Map of Total Revenue & Number of Counties by State
    -   Revenue & Profit by Location Type 
    -   Revenue by Customer ID (Top Customers)
    -   Regional Analysis: Households, Orders, and Population

👉 **Goal**: Identify **customer behavior & regional opportunities**.

------------------------------------------------------------------------

### 3️⃣ Product & Operations Insights

-   **Visuals**:
    -   Table: Customer Name, Order Quantity, Profit (Year/Month
        breakdown)
    -   Profit by Product Name (Treemap)
    -   Profit Margin % by Year, Quarter, and Channel
    -   Scatter Plot: Revenue vs Profit by Product & Channel

👉 **Goal**: Optimize **products, operations, and sales channels**.

------------------------------------------------------------------------

## 🎛️ Interactivity

-   **Filters & Slicers** added (top-right corner of dashboards):
    -   Time (Year, Quarter, Month)
    -   Customer Type
    -   Product
    -   Regio
    -   Channel

This makes the dashboards fully **dynamic & interactive**.

------------------------------------------------------------------------

## 🔑 Key Insights

-   **Top Products**: Product 25 & 26 are highest contributors to
    revenue.
-   **Top Channel**: Wholesale generates the largest share of total
    revenue.
-   **Regional Insights**: West region leads in revenue, but Northeast
    shows weaker performance.
-   **Customer Analysis**: Few top customers drive a large share of
    revenue.
-   **Area**: Highest revenue by City

------------------------------------------------------------------------

## 📌 How to Use

1.  Open the Power BI file (`.pbix`).\
2.  Use filters on the top-right panel to explore data by year, region,
    customer, and product.\
3.  Navigate through the **3 dashboards** for Sales, Customer & Market,
    and Product Insights.
