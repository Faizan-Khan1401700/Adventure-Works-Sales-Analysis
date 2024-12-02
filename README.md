# Adventure Works Sales Analysis - Power BI Report

## Table of Contents
1. Overview
2. Features
    - Data Cleaning with Power Query
    - DAX Measures
    - Interactive Visualizations
3. Dashboard Pages
    - Main Dashboard
    - Product Page
    - Customer Page
    - Page Navigation
4. Dataset
5. Technologies Used
6. Key Learnings
7. Contact

---

## Overview

The **Adventure Works Sales Analysis** project is an interactive Power BI report designed to analyze the sales data from the **Adventure Works** dataset. The report offers insightful visualizations for sales performance, customer segmentation, and product analysis. The goal is to help stakeholders understand business trends, identify areas of improvement, and make data-driven decisions to optimize sales and profits.

This report uses several Power BI features:
- **Power Query** for data cleaning and transformation,
- **DAX (Data Analysis Expressions)** for custom calculations and measures,
- **Interactive visualizations** to present complex data in an easy-to-understand format.

The report is organized into three main pages:
- **Main Dashboard**: Provides a high-level overview of the sales performance.
- **Product Page**: Focuses on product-level analysis, including top-selling products and profitability.
- **Customer Page**: Analyzes customer segmentation, purchase behavior, and regional trends.

---

## Features

### Data Cleaning with Power Query
Power Query was used extensively in this project for data cleaning, ensuring that the data was transformed and structured properly for analysis. This included tasks such as:
- **Handling Missing Values**: Identifying and filling or removing missing values where necessary.
- **Data Type Conversion**: Ensuring the correct data types were assigned (e.g., dates, numerical values) for accurate calculations.
- **Merging Tables**: Combining data from multiple sources (e.g., sales, products, customers) into a single unified dataset for better analysis.
- **Filtering and Transforming Data**: Applying filters and transformations to clean up the raw data and make it suitable for visualization.

These steps were critical for ensuring data quality and consistency, which is essential for generating accurate business insights.

### DAX Measures
**DAX (Data Analysis Expressions)** was used to create custom measures and calculations for generating KPIs and deriving business insights. Key DAX measures created in this project include:
- **Total Sales**: The sum of all sales transactions.
- **Profit Margin**: Calculated as the difference between sales and costs, divided by sales.
- **Year-over-Year Growth**: Comparison of sales performance across different time periods (e.g., current year vs. previous year).
- **Top Products**: Identifying the best-selling products and categories based on total sales or profit.
- **Customer Retention**: Calculating customer repeat purchases or identifying loyal customers.

These custom measures allow for more dynamic and insightful reporting, enabling users to explore data from multiple perspectives.

### Interactive Visualizations
The report leverages a range of visualizations to present the data in an engaging and easy-to-understand manner:
- **Bar and Column Charts**: Used for comparing sales and performance across different categories or time periods.
- **Line Charts**: Used for analyzing trends over time, such as sales growth or seasonal changes.
- **Pie Charts**: Used for showing the percentage distribution of sales across product categories, regions, or customer segments.
- **Heatmaps**: Utilized to show regional performance or customer concentration in a geographical view.
- **Tables**: Detailed tables with filters to allow users to dive deeper into specific data points, such as individual product performance or customer details.

These visualizations are interactive, allowing users to filter and drill down into specific aspects of the data for deeper analysis.

---

## Dashboard Pages

### Main Dashboard

![Main](https://github.com/user-attachments/assets/bb01d353-6fe8-4217-94e9-a884a99fe94b)


The **Main Dashboard** provides a high-level view of the company’s overall sales performance and business health. Key features of this page include:
- **Total Sales & Profit**: Overview of the total sales, total profit, and key performance indicators (KPIs).
- **Sales Trends**: Line graphs displaying sales trends over time (monthly, quarterly, yearly).
- **Year-over-Year Comparison**: A comparison of sales performance in the current year versus previous years to understand growth patterns.
- **Sales by Product Category**: A visual breakdown of sales by different product categories (e.g., bikes, accessories, clothing).
- **Geographic Overview**: A heatmap or map showing the sales performance by region or territory.

This page provides a summary of the key business metrics and enables users to quickly assess the company's overall performance.

### Product Page

![ProductPage](https://github.com/user-attachments/assets/dd0b1c39-c2db-420e-a291-f65112ecc96c)


The **Product Page** focuses on analyzing product sales, profitability, and performance:
- **Top-Selling Products**: Displays the best-selling products and product categories based on total sales or profit.
- **Product Profitability**: A measure of profit margins by product or category, helping to identify the most profitable products.
- **Product Trends**: Line graphs showing how the sales of individual products have changed over time.
- **Sales by Subcategory**: Drill-down features to analyze sales performance at the subcategory level (e.g., different types of bikes or accessories).

This page is particularly useful for product managers and stakeholders looking to optimize their product mix or focus on high-performing items.

### Customer Page

![CustomerPage](https://github.com/user-attachments/assets/cce2dcf3-2ca1-4339-b1cb-b0796a3a6f36)


The **Customer Page** provides insights into customer demographics, segmentation, and purchasing behavior:
- **Customer Segmentation**: Analysis of sales by different customer segments, such as age groups, income brackets, or geographic locations.
- **Repeat Customers**: Identification of customers who make frequent purchases, helping businesses improve customer retention strategies.
- **Geographical Insights**: Sales performance by region, showing how different areas contribute to overall sales.
- **Customer Purchase Behavior**: Analysis of how different customer segments behave over time, such as seasonality or product preferences.

This page helps businesses understand their customer base better and make data-driven decisions to improve marketing and customer engagement strategies.

### Page Navigation
To easily navigate between the different pages of the report, the dashboard includes **three icons** at the top of the report. These icons allow users to quickly switch between the following pages:
- **Home Dashboard**: The main overview page with key performance indicators and trends.
- **Product Page**: The detailed product-level analysis of sales and profitability.
- **Customer Page**: The customer segmentation and purchasing behavior insights.

These navigation icons are designed to make it simple for users to switch between different sections of the report with a single click, improving the usability and interactivity of the dashboard.

---

## Dataset

The **Adventure Works** dataset is a sample database created by Microsoft, designed to represent a multinational company’s sales operations. The dataset contains:
- **Sales Orders**: Records of customer orders, including quantities, prices, and dates.
- **Product Information**: Detailed information about the products sold, including categories and subcategories.
- **Customer Data**: Demographic details of customers, including age, location, and income.
- **Geography**: Regional and territorial data for understanding sales performance by location.

The Adventure Works database is publicly available and can be accessed from the [Adventure Works GitHub repository](https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/adventure-works).

---

## Technologies Used

- **Power BI**: Data visualization and reporting tool used to create interactive dashboards.
- **SQL Server**: Database platform used for storing the Adventure Works dataset.
- **DAX (Data Analysis Expressions)**: Formula language used for creating custom measures and calculations.
- **Power Query**: Used for cleaning and transforming the data before importing it into Power BI.
- **GitHub**: Platform used for version control and project hosting.
- **Markdown**: Markup language used for documentation.

---

## Key Learnings

- **Data Transformation with Power Query**: Using Power Query to clean, merge, and transform raw data into an actionable format.
- **Advanced DAX Calculations**: Creating custom calculations to derive business insights, such as sales growth, profitability, and customer segmentation.
- **Effective Use of Visualizations**: Leveraging Power BI's wide range of visualizations to display complex data in a digestible and interactive format.
- **Sales Performance Analysis**: Gaining insights into product performance, customer behavior, and regional sales, helping to make data-driven decisions.

---

## Contact

For any inquiries or feedback, feel free to reach out:

- **Email**: [sk1401700@gmail.com](mailto:sk1401700@gmail.com)
- **LinkedIn**: [Faizan Khan](https://www.linkedin.com/in/faizan-khan-399a47205/)
- **GitHub**: [Faizan-Khan1401700](https://github.com/Faizan-Khan1401700)

---

