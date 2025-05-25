# 📊 Power BI DAX Mastery

Welcome to the **Power BI DAX Repository**, your go-to reference for mastering DAX (Data Analysis Expressions) from beginner to advanced level. This repository provides categorized DAX examples and use cases using realistic retail datasets including product, sales, and customer data.

## 📁 Repository Structure

This repository is organized by DAX proficiency level:

- `Beginner/` – Covers core DAX concepts and fundamental functions.
- `Intermediate/` – Introduces filtering, time intelligence, and calculated columns.
- `Advanced/` – Dives into complex measures, dynamic segmentation, advanced time logic, and optimization patterns.

---

## 🧠 Beginner DAX Concepts

**Focus:** Understanding basic calculations and context transition.

📄 Topics Covered:
- **Aggregation Functions:** `SUM`, `AVERAGE`, `MIN`, `MAX`, `COUNT`, `DISTINCTCOUNT`
- **CALCULATE Function:** Modify filter context to create dynamic measures.
- **Iterators:** `SUMX`, `AVERAGEX`, `MINX`, `MAXX` for row-by-row evaluation.

📊 Example Measures:
- Total Product Cost
- Profit = Product Price – Product Cost
- Sales by Category
- Total Returns by Product Subcategory

🗂️ Tables Used:
`fact_sales`, `fact_return`, `dim_product`, `dim_category`, `dim_product_price`, `dim_calendar`

---

## 🧩 Intermediate DAX Concepts

**Focus:** Introducing relationships, advanced filters, time-based analysis.

📄 Topics Covered:
- **Filter Functions:** `FILTER`, `ALL`, `REMOVEFILTERS`, `KEEPFILTERS`, `VALUES`
- **Time Intelligence:** `DATEADD`, `SAMEPERIODLASTYEAR`, `PARALLELPERIOD`, `TOTALYTD`, `PREVIOUSMONTH`
- **Conditional Logic:** `IF`, `SWITCH`, `CONTAINS`, `IN`

📊 Example Measures:
- Year-over-Year Sales Growth
- Dynamic Product Ranking by Sales
- Returns Excluding Specific Territories
- Custom YTD & MTD Measures

🗂️ Additional Tables Used:
`dim_territories`, `dim_customer`, `dim_calendar`

---

## 🚀 Advanced DAX Concepts

**Focus:** Deep dive into context transition, dynamic calculations, and performance optimization.

📄 Topics Covered:
- **Virtual Tables:** `ADDCOLUMNS`, `SUMMARIZE`, `SELECTCOLUMNS`
- **Advanced Time Calculations:** Custom fiscal calendars, rolling averages
- **Dynamic Segmentation:** Creating buckets like "Top 10 Customers", "High Margin Products"
- **Performance Optimization:** Using `VAR`, reducing row context, efficient filtering

📊 Example Measures:
- Rolling 3-Month Average Sales
- Top N Customers by Profit (Dynamic slicer-based)
- Margin Buckets using Nested `SWITCH`
- Revenue Forecast vs Actual

🧠 Techniques:
- Context Transition with `CALCULATE`
- Evaluation Context in Nested `X` functions
- Parameterized Measures

---

## 📌 Getting Started

To get started:
1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/powerbi-dax.git
   cd powerbi-dax
Open the corresponding .pbix files in Power BI Desktop.

Use the included comments and descriptions to learn, modify, and test DAX queries.

🎯 Target Audience
Beginners exploring DAX for the first time

Analysts seeking structured DAX knowledge

Data Modelers aiming to optimize and scale data models

Developers building powerful dashboards with dynamic logic
