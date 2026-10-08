# Sales_Analysis
# Analyzing and Visualizing Regional Sales Performance

**Author:** Praveen  
**Domain:** Retail Sales Analytics  
**Tools & Technologies:** Microsoft Excel, Data Cleaning, Pivot Tables, Advanced Formulas, Interactive Dashboards, Regression Analysis[cite: 1]  

---

## 📌 Project Overview

This project focuses on evaluating the sales performance of **ABC Electronics** across various regions and product categories using Microsoft Excel[cite: 1]. The primary goal is to process and analyze transaction data, calculate key performance indicators (KPIs), perform simple regression analysis on promotional discounts, and build an interactive dashboard to empower strategic decision-making in inventory management and marketing strategies[cite: 1].

---

## 🛠️ Key Skills & Features

* **Data Cleaning & Preprocessing:** Standardizing regional and category text values using `TRIM`, `UPPER`, and `LOWER` functions[cite: 1].
* **Searching & Filtering:** Advanced multi-criteria date and categorical filtering (e.g., isolating orders in specific regions like "South" for "Electronics")[cite: 1].
* **Excel Formulas & Aggregations:** Utilizing `SUM`, `AVERAGE`, `AVERAGEIFS`, and calculated columns for regional sales averages and category profit metrics[cite: 1].
* **Dynamic Pivot Tables & Slicers:** Aggregating sales metrics dynamics with interactive slicer filters by region and category[cite: 1].
* **Data Visualization:** Custom regional bar charts, category contribution pie charts, and stacked bar charts for cross-categorical regional analysis[cite: 1].
* **Statistical Regression Analysis:** Scatter plot trendline analysis examining the relationship between Discount (%) and Sales Amount[cite: 1].
* **Interactive Executive Dashboard:** High-level overview displaying key metrics, conditional formatting highlights for top performers, and dynamic slicers[cite: 1].

---

## 📊 Dataset Structure

The dataset contains **4,000 order records** covering transactions for ABC Electronics[cite: 1].

| Column Name | Description |
| :--- | :--- |
| `Order ID` | Unique identifier for each customer transaction[cite: 1] |
| `Order Date` | Date when the order was placed[cite: 1] |
| `Region` | Geographic region (e.g., North, South, East, West)[cite: 1] |
| `Product Category` | Category of the product (e.g., Electronics, Furniture)[cite: 1] |
| `Sales Amount` | Total monetary value of the sale (in ₹)[cite: 1] |
| `Quantity Sold` | Total number of units sold[cite: 1] |
| `Discount (%)` | Discount percentage applied to the order[cite: 1] |
| `Profit` | Net profit earned from the transaction[cite: 1] |

---

## 🚀 Execution Steps & Implementation

### 1. Data Cleaning & Formatting
* Used `TRIM()`, `UPPER()`, and `LOWER()` to eliminate leading/trailing whitespace and ensure clean, uniform string formatting across regions and product categories[cite: 1].
* Applied **Conditional Formatting** rules to highlight high-value orders (Sales Amount > ₹4,000) and high-margin sales (Profit Margin > 50%)[cite: 1].

### 2. Multi-Criteria Search & Aggregation
* Filtered sales records dynamically for regional and category sub-analyses (e.g., extracting South region orders for Electronics)[cite: 1].
* Merged calculated regional average sales back into the main dataset using lookup/averaging functions (`AVERAGEIFS`) for baseline performance comparisons[cite: 1].
* Calculated total sales per region with `SUM` and computed category-level metrics (e.g., average discount % and profit for Furniture) using `AVERAGE`[cite: 1].

### 3. Dynamic Summarization & Charts
* Built dynamic **Pivot Tables** summarizing total revenue and profit margin splits by region and category[cite: 1].
* Generated **Bar Charts** for regional revenue rankings, **Pie Charts** for category market share, and **Stacked Bar Charts** for multi-variable distribution across regions[cite: 1].

### 4. Regression Analysis
* Executed a simple linear regression using a **Scatter Plot with a Trendline** to evaluate how varying Discount (%) levels affect Sales Amount and overall profit margins[cite: 1].

### 5. Interactive Dashboard Assembly
* Integrated high-level KPI card blocks (Total Sales, Total Profit, Top-Selling Category) with dynamic visual charts and interactive Timeline/Slicer controls[cite: 1].
<img width="1917" height="870" alt="Screenshot 2026-10-08 121822" src="https://github.com/user-attachments/assets/ec711f11-f640-46cf-aea4-47c77dd2c36c" />
<img width="1916" height="861" alt="Screenshot 2026-10-08 121802" src="https://github.com/user-attachments/assets/4c83a702-5965-480d-aae7-166484b6ff87" />
<img width="1591" height="1388" alt="Sales_Analysis_Dashboard" src="https://github.com/user-attachments/assets/45e0a5f8-9186-41bb-8453-704f52ffd398" />


---

## 📁 Repository Deliverables

```text
├── Data/
│   └── Sales_Performance_Analysis.csv    # Raw 4,000 row transaction dataset
├── Reports/
│   └── Regional_Sales_Performance.xlsx   # Cleaned Excel workbook with Dashboard, Pivot Tables & Charts
└── README.md                             # Project documentation
📬 Author & Acknowledgments
Author: Praveen[cite: 1]
