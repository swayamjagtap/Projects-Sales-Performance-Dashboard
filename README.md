# Product Sales Analysis Dashboard (Excel)

## Project Overview
This project presents an interactive sales dashboard built in Microsoft Excel. It offers a comprehensive analysis of product sales performance, quantity trends over time, and distribution by product, enabling quick insights into key business metrics.

## Data Source
The dashboard is powered by a transactional dataset containing sales records, including:
* **Date:** The date of the transaction.
* **Product Name:** The specific product sold.
* **Quantity:** The number of units sold.
* **Price:** The price per unit.
* **Total Amount:** The total revenue for the transaction.
* **State:** The geographical location of the sale.
* **Customer Name:** The name of the customer.

A sample of the raw data used can be seen below:
![Raw Data Sample](image_e8f0ee.png)

## Dashboard Features & Visualizations

The dashboard is designed to provide clear and concise insights through various visualizations:

1.  **Product Sales Summary (PivotTable):**
    * A detailed table summarizing the `Sum of Units Sold` and `Sum of Total Sales` for each distinct product. This offers an immediate overview of top-performing products.

2.  **Product Sales Distribution (Nested Doughnut Chart):**
    * This unique chart visually represents the percentage breakdown of `Units Sold` and `Total Sales` for each product. The inner ring shows unit distribution, while the outer ring shows total sales distribution, allowing for quick comparisons between volume and revenue contribution.

3.  **Product Sales Trend Over Time (Multi-Line Chart):**
    * A dynamic line graph plotting `Units Sold` (Y-axis) against `Date` (X-axis) for each of the five distinct products. Each product is represented by a different colored line, allowing for easy tracking of individual product performance trends.
    * **Moving Averages:** This chart also incorporates a 2-period moving average for key products (Ergo Chair, Laptop Pro X, Smart Webcam) to smooth out daily fluctuations and highlight underlying sales trends more clearly.

## Dashboard Screenshot
Below is a screenshot of the dashboard in action:
![Dashboard Overview](Screenshot%202025-05-29%20151635.png)

## How to Use
1.  **Download:** Clone this repository or download the `YourExcelDashboardFile.xlsx` file. (Replace `YourExcelDashboardFile.xlsx` with the actual name of your Excel file, e.g., `Sales_Dashboard.xlsx`)
2.  **Open:** Open the Excel file using Microsoft Excel (version 2019 or Microsoft 365 recommended for full functionality of charts like Map charts if you add one later).
3.  **Navigate:** The dashboard is typically located on a dedicated sheet named "Dashboard" or similar.
4.  **Explore:** Interact with the PivotTables and charts. If slicers are implemented, use them to filter the data by `State`, `Customer Name`, or `Product Name` for deeper dives.

## Future Enhancements (Potential Next Steps)

* **Geographical Sales Map:** Integrate a map chart to visualize sales distribution across different states.
* **Interactive Filters (Slicers):** Add more slicers for `State` and `Customer Name` to enhance dashboard interactivity.
* **Key Performance Indicator (KPI) Cards:** Include prominent display cards for overall metrics like "Total Revenue," "Total Units Sold," and "Average Order Value."
* **Profitability Analysis:** Add calculations and visualizations for profit margin per product if cost data is available.

---
