# Sales Analytics and Operations Report - Power BI Dashboard

## Project Overview

This Power BI project delivers a comprehensive Sales Analytics and Operations Report designed to provide key stakeholders with actionable insights into the company's sales performance, operational efficiency, and inventory status. The dashboard is structured across three interconnected pages, offering a granular view of various business aspects, enabling data-driven decision-making.

## Key Features & Business Questions Addressed

This report is designed to answer critical business questions across three key areas:

1.  **Overall Company Performance (Main Page):**
    * Provides a high-level, general view of the company's total sales, costs, and profits.
    * Offers an overview of performance across different geographical areas (locations).
    * Summarizes sales contribution by individual salespersons and general order frequency.
    * Highlights top-performing products.

2.  **Sales Team Performance (Person Page):**
    * Evaluates individual sales team member performance to inform reward programs.
    * Enables comparison of individual salesperson performance against peers.
    * Facilitates comparison of performance against previous months and quarters.

3.  **Inventory Report (Product Page):**
    * Delivers insights into product-level performance, focusing on inventory status and contribution to sales.
    * Analyzes sales by product categories and sizes.
    * Highlights top products based on sales.

## Data Sources & Model

The report leverages a robust data model built upon several interlinked tables to ensure comprehensive analysis:

* `vw_DimProducts`
* `vw_DimSalesPersons`
* `vw_DimShipMethods`
* `vw_DimStatuses`
* `vw_DimTerritories`
* `vw_FactOrderDetails`
* `DimDate` (Created using DAX)

## Dashboard Design & Usability

* **Clarity & Organization:** All visuals are designed to be clear, well-organized, and intuitive, facilitating easy interpretation of complex data.
* **Interactive Filters:** All filters are synced across different pages of the report, ensuring a consistent analytical experience.
* **Seamless Navigation:** Users can easily carry their selected filters through various pages, enabling dynamic exploration of specific data segments across the entire report.
* **Visual Theme:** A custom theme (`Professional Blue & Gray`) has been applied to ensure a consistent, modern, and professional aesthetic throughout the dashboard, enhancing data readability and user engagement.

## Technical Skills Applied

* **Data Modeling:** Designing and implementing a star schema (or similar) with robust relationships between fact and dimension tables.
* **DAX (Data Analysis Expressions):** Creation of calculated columns and measures, including the `DimDate` table, to derive key performance indicators and time-intelligence functions.
* **Data Transformation (Power Query):** Cleaning, shaping, and loading data from various sources (though not explicitly listed as a requirement, it's standard practice).
* **Data Visualization:** Designing a variety of charts (bar charts, line charts, maps, KPI cards, tables) to effectively communicate insights.
* **Report Design & Usability:** Implementing interactive slicers, cross-page filtering, and custom themes for an enhanced user experience.
* **Business Acumen:** Translating complex business requirements (overall performance, sales team evaluation, inventory insights) into practical and actionable dashboard features.

## How to Use the Report

1.  [cite_start]**Download:** Obtain the `Sales_Analytics_Report.pbix` file. 
2.  **Open:** Open the file using Power BI Desktop.
3.  [cite_start]**Explore Pages:** Navigate between the "Main", "Place", "Time", and "Person" pages using the top navigation bar to access different levels of analysis. 
4.  [cite_start]**Apply Filters:** Use the slicers (e.g., Year, Month, Store Type, Category) to dynamically filter the data and focus on specific segments. 
5.  **Interact with Visuals:** Click on elements within charts (e.g., bars, map regions) to cross-filter other visuals on the same page for deeper insights.

## Contact

For any questions or further details, please contact:
**Mohamed Fares**
Email: mohamedhfares5@gmail.com
LinkedIn: [linkedin.com/in/mohamedfarez]
