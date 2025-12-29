# Super Store Sales Dashboard

## Overview
The **Super Store Sales Dashboard** is a comprehensive **Power BI analytics project** developed to analyze retail sales performance using historical transactional data.  
The dashboard is designed to support **business decision-making** by presenting key performance indicators, sales trends, regional performance, and operational behavior in a clear and interactive manner.

The project follows a **two-level analytical approach**:
- **Page 1** focuses on executive-level performance monitoring.
- **Page 2** provides detailed operational and behavioral insights to explain observed trends.

---

## Objective
The primary objectives of this project are:
- To analyze overall sales, profit, and quantity performance
- To identify high-performing and underperforming regions, categories, and cities
- To understand customer segments, payment behavior, and shipping patterns
- To enable interactive exploration of data using Power BI visuals

---

## Tools and Technologies
- **Power BI Desktop** – Dashboard development and visualization
- **DAX (Data Analysis Expressions)** – Measures and calculated metrics
- **CSV Dataset** – Source data
- **Data Modeling** – Relationships and filtering logic

---

## Dataset Description
The dataset used in this project contains **order-level retail transaction data**.  
It includes the following major attributes:

- **Order Information**
  - Order ID
  - Order Date
  - Ship Date

- **Product Details**
  - Category
  - Sub-Category
  - Product Name

- **Sales Metrics**
  - Sales
  - Profit
  - Quantity

- **Geographical Data**
  - Region
  - State
  - City

- **Customer Information**
  - Segment

- **Operational Data**
  - Ship Mode
  - Payment Mode
  - Returns

The dataset enables both **summary-level analysis** and **detailed operational exploration**.

---

## Dashboard Design and Navigation
The dashboard is structured into **two interconnected pages** to ensure a logical analytical flow.

---

## Page 1: Executive Sales Overview


![Page 1](https://raw.githubusercontent.com/<username>/<repo>/main/Screenshots/page1.png)

### Purpose
Page 1 provides a **high-level snapshot** of business performance.  
It is designed for stakeholders who need a **quick understanding of key metrics and trends**.

### Key Components
- **KPI Cards**
  - Total Sales
  - Total Profit
  - Total Quantity
  - Best Performing Region

- **Sales by Category**
  - Compares performance across major product categories

- **Sales by Sub-Category**
  - Identifies top-performing and low-performing product groups

- **Monthly Sales Trend**
  - Displays sales performance by month and year
  - Enables year-over-year comparison

- **Monthly Profit Trend**
  - Highlights profitability fluctuations over time

- **Geographical Analysis**
  - Sales and profit distribution across states using map visualization

- **Segment Analysis**
  - Shows contribution of Consumer, Corporate, and Home Office segments

- **Shipping Mode Analysis**
  - Evaluates sales distribution across different shipping methods

- **Payment Mode Analysis**
  - Displays customer payment preferences

### Business Question Answered
**“What is the overall performance of the business?”**

---

## Page 2: Detailed Operational and Behavioral Analysis

### Purpose
Page 2 is designed to **drill deeper into operational details** and explain the patterns observed in Page 1.  
It focuses on **order behavior, city-level activity, and operational efficiency**.

### Key Components
- **Sales by Order Date**
  - Granular visualization of sales behavior over time
  - Helps identify peaks, dips, and volatility

- **Quantity by City**
  - Identifies cities contributing high order volumes

- **Payment Mode by City**
  - Analyzes city-wise customer payment behavior

- **Returns Analysis**
  - Highlights return patterns associated with sales

- **Sales by Region**
  - Compares regional contribution in detail

### Business Question Answered
**“Why are these trends and patterns occurring?”**

---

## Analytical Flow Between Pages
- Page 1 highlights **key trends and performance indicators**
- Page 2 provides **root-cause level insights**
- Consistent filters and interactions ensure smooth navigation
- The design follows **standard enterprise BI reporting practices**

---

## Key Insights
- The **West region** contributes the highest overall sales
- **Office Supplies** lead among product categories
- **Standard Class** is the most frequently used shipping mode
- **COD and Online** payments dominate customer transactions
- Certain cities show **high order volume with operational risk**
- Sales and profit exhibit **seasonal and regional variation**

---

## Conclusion
This Power BI dashboard delivers an **end-to-end sales analysis solution** by combining executive summaries with detailed operational insights.  
It enables stakeholders to:
- Monitor business performance effectively
- Identify risks and opportunities
- Make informed, data-driven decisions using interactive visuals

---

## Repository Structure
```
Super-Store-Sales-PowerBI/
│
├── powerbi/
│ └── Super_Store_Sales_Dashboard.pbix
│
├── dataset/
│ └── SuperStore_Sales_Dataset.csv
│
├── screenshots/
│ ├── page1_overview.png
│ └── page2_analysis.png
│
└── README.md
```
## Author

Rushikesh Sable

rushikeshsable9850@gmail.com
