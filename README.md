# Retail Sales Data Visualization Dashboard

## Overview
This project focuses on transforming retail transactional data into clear, actionable business insights through effective data visualization.  
The objective is to demonstrate the ability to not only analyze data, but also **communicate insights visually** in a way that supports business decision-making.

The workflow combines **Python (data preparation & validation)** and **Tableau Public (interactive dashboard visualization)**.

---

## Business Objective
The dashboard is designed to answer key business questions such as:
- How does total revenue trend over time?
- Is revenue growth driven by higher order value or higher order volume?
- Which regions and product categories contribute the most to revenue and profit?
- Which products generate high revenue but low or negative profit?
- Where should the business focus to improve profitability?

---

## Dataset
- **File**: `retail_sales.csv`
- **Records**: 9,994 rows
- **Features**: 21 columns

### Key Fields
- Order Date, Ship Date  
- Sales, Profit, Discount, Quantity  
- Product Category & Sub-Category  
- Region & Customer Segment  

The dataset represents retail transaction data from **2016–2017**.

---

## Tools & Technologies
- **Python 3.10**
  - pandas
  - numpy
- **Tableau Public 2025.3**
- **Git & GitHub**

---

## Project Workflow

### 1. Data Validation & Preparation (Python)
Python was used to:
- Validate data structure and data types
- Convert date fields to proper datetime format
- Verify numeric fields (Sales, Profit, Discount, Quantity)
- Create derived metrics used for visualization:
  - Monthly aggregation
  - Average Order Value (AOV)
  - Profit Margin
  - Shipping delay (days)

Data checks were performed to ensure:
- No missing critical values
- Numeric fields are correctly interpreted
- Aggregations match expected totals

---

### 2. Data Visualization (Tableau Public)
The cleaned dataset was visualized in Tableau to create an interactive dashboard with the following components:

#### Key Visualizations
- **Revenue by Month**  
  Trend analysis of total revenue over time (MMM YY format)

- **Revenue vs AOV Trend**  
  Dual-axis analysis to understand whether growth is driven by order value or volume

- **Revenue by Region**  
  Comparison of sales and profit contribution across regions

- **Revenue by Category**  
  Category-level performance analysis

- **Top 10 Products by Profit**  
  Identification of high- and low-performing products, including loss-making items

#### Interactivity
- Date range filter
- Category filter
- Region filter
- Business-focused tooltips for clean visuals

---

## Key Insights
- Revenue shows steady growth with seasonal peaks toward the end of the year.
- Average Order Value (AOV) remains relatively stable, indicating that revenue growth is primarily driven by order volume.
- The Technology category contributes the highest revenue and profit.
- Some top-selling products generate negative profit, largely driven by heavy discounting.
- Certain regions deliver high revenue but lower profitability, indicating margin optimization opportunities.

---

## Business Recommendations
- Improve AOV through bundling or upselling strategies.
- Review discount policies on low-margin or loss-making products.
- Focus growth initiatives on high-margin categories and regions.
- Use profitability, not just revenue, as a primary performance metric.

---

## Tableau Public Dashboard
🔗 **Live Dashboard**:   
`https://public.tableau.com/views/Book1_17664712728520/SalesMonitoring?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link`

---

## Repository Structure
├── dashboard/
│ └── Retail_Sales_Performance_Dashboard.twb
│ └── Tableu_Public_Link_-_Retail_Sales_Performance_Dashboard
├── data/
│ └── retail_sales.csv
│ └── retail_sales_clean.csv
├── images/
│ └── Dashboard_Preview.JPG
├── notebooks/
│ └── 01_eda_retail.ipynb
└── README.md

---

## Key Skills Demonstrated
- Data validation and preparation using Python
- Business-oriented data aggregation
- Data visualization best practices
- Dashboard storytelling for business stakeholders
- Translating data into actionable insights

---

## Author
**Faris**  
Aspiring Data Analyst with a background in Sales and business strategy  
Focused on using data to drive practical, measurable business decisions
