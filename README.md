# Supply Chain Data Analysis Project

This project focuses on analyzing supply chain data to optimize product availability, sales performance, and operational efficiency. The project was developed under the **Digital Egypt Pioneers Initiative** and leverages tools like **SQL**, **Python**, and **Tableau** for data cleaning, analysis, and visualization.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Stages](#data-stages)
3. [Analysis Questions](#analysis-questions)
   - [SQL Analysis](#sql-analysis)
   - [Python Analysis](#python-analysis)
4. [Visualization Dashboard](#visualization-dashboard)
5. [Technologies Used](#technologies-used)
6. [Team](#team)
7. [Conclusion](#conclusion)

---

## Introduction
The objective of this project is to improve decision-making and efficiency in supply chain management by focusing on key factors such as:
- Product pricing
- Stock levels
- Shipping costs
- Defect rates

Our analysis helps to evaluate supplier performance, plant efficiency in defect detection, and overall product profitability.

---

## Data Stages
### Data Cleaning and Preprocessing
Before analysis, the raw data was assessed and cleaned using Python. Key steps include:
- **Data Overview**: Examined dataset structure using `info()` to understand data types and completeness.
- **Null Value Check**: Verified the absence of missing values.
- **Duplicate Record Detection**: Ensured no duplicate rows existed to maintain data integrity.

### Data Enhancements
Three new columns were created to support in-depth analysis:
1. **Total Cost**: Sum of manufacturing and operational costs.
2. **Operational Profit**: Difference between revenue and total cost.
3. **Profit Margin**: Percentage of profit relative to revenue, which enables standardized product comparisons.

---

## Analysis Questions

### SQL Analysis
We used SQL queries to explore patterns and trends, focusing on these key questions:
- **Revenue by Product Type**: Identified the most profitable product categories.
- **Effect of Gender on Product Use**: Determined how customer demographics affect product sales.
- **Products Across Locations**: Compared product sales across different cities.
- **Transportation Modes and Products**: Analyzed the most popular modes of transportation for various product types.

### Python Analysis
In the Python phase, we answered these questions using libraries like **Pandas** and **Matplotlib**:
1. **Defect Rates by Product Type**: Calculated and visualized the percentage of defective products using bar charts.
2. **Sales by Region**: Analyzed regional sales performance, providing insights into geographic differences in product demand.

---

## Visualization Dashboard
The **Tableau** dashboard presents a summary of the key insights from the SQL and Python analyses, offering interactive visuals to support decision-making.

---

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib): For data cleaning, analysis, and visualization.
- **SQL**: For querying data from the database.
- **Tableau**: For creating interactive visualizations and dashboards.

---

## Team
- **Mohamed Samy Omar**
- Hassan Nasr
- Mohamed Omar
- Ahmed Abdel-Aziz
- Mohamed Ahmed
- Amr Taher

---

## Conclusion
This project provided a comprehensive analysis of the supply chain data, offering actionable insights into product profitability, supplier performance, and regional sales trends. By utilizing SQL, Python, and Tableau, we were able to clean, analyze, and visualize the data, helping stakeholders make informed decisions to enhance operational efficiency and product quality.

The findings highlight opportunities to improve supplier selection, reduce defect rates, and optimize logistics, all of which are crucial for maintaining a competitive edge in the supply chain industry.
