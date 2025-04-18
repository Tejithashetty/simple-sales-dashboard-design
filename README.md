#  Sales Dashboard – Superstore Dataset

##  Overview

This project is part of the **Data Analyst Internship – Task 8**.
The objective was to design a simple, interactive dashboard that visualizes sales performance across different dimensions such as time, region, and product category using the **Superstore Sales** dataset.

---

## Dataset

- **Name:** Superstore_Sales.csv
- **Columns Used:** `Order Date`, `Region`, `Category`, `Sales`, `Profit`

---

##  Tools Used

- Power BI (for dashboard creation)

---

## Visualizations

1. **Average Sales per Month**  
   - *Type:* Line Chart  
   - *Insight:* Shows monthly trends and identifies peak sales periods.

2. **Overall Sales by Region**  
   - *Type:* Bar Chart  
   - *Insight:* Highlights regional performance and top-contributing regions.

3. **Overall Sales by Product Category**  
   - *Type:* Donut Chart  
   - *Insight:* Visualizes sales distribution across product categories.

---

##  Key Insights

1. Certain months consistently show higher average sales, indicating potential seasonal trends.
2. The **West** region records the highest overall sales.
3. The **Technology** category leads in total sales among all product segments.

---

##  Data Preparation

- Converted `Order Date` to **Month-Year** format using Power BI DAX:
  ```DAX
  MonthYear = FORMAT('Superstore_Sales'[Order Date], "MMM-YYYY")
