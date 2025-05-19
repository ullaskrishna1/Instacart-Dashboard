# Instacart-Dashboard
Visualizing Blinkit’s Sales Performance and Operational Trends in Power BI

**Problem Statement:**
InstaCart, a leading quick-commerce platform, is seeking to improve its sales performance and customer satisfaction by gaining deeper insights into its operational data. However, the existing sales and outlet data is underutilized, making it difficult to identify patterns related to product performance, outlet efficiency, and customer preferences. There is a need for a dynamic and visual reporting solution that can consolidate key performance metrics and enable data-driven decision-making. This project aims to address that gap by developing an interactive Power BI dashboard to analyze total sales, item attributes, outlet types, and customer ratings, ultimately uncovering opportunities for optimization and strategic growth.

**Business Requirements**
Key business questions addressed include:
•	How does fat content influence total sales and other performance metrics?
•	Which item types perform best in terms of sales and customer ratings?
•	What is the impact of outlet characteristics such as type, size, location, and establishment year on overall sales?
•	How are sales geographically distributed across different outlets?
•	What is the overall performance of different outlet types across all KPIs?

**KPI's Identified**
The primary KPIs identified in the file are:
•	Total Sales: This represents the overall revenue generated from all items sold.
•	Average Sales: This measures the average revenue per sale.
•	Number of Items: This captures the total count of unique items sold.
•	Average Rating: This reflects the average customer rating for the items sold.

**Business Requirements**
Key business questions addressed include:
•	How does fat content influence total sales and other performance metrics?
•	Which item types perform best in terms of sales and customer ratings?
•	What is the impact of outlet characteristics such as type, size, location, and establishment year on overall sales?
•	How are sales geographically distributed across different outlets?
•	What is the overall performance of different outlet types across all KPIs?


**Project Steps / Methodology**
Step 1: Requirement Gathering
The project began with requirement gathering, where I understood the business needs and defined clear goals such as evaluating total sales, item performance, customer ratings, and outlet characteristics. This step helped in identifying the KPIs and charts that would be most relevant for analysis.

Step 2: Data Walkthrough
Next, I performed a data walkthrough, reviewing the structure and content of the available datasets. This helped in understanding column relevance, data types, missing values, and the relationships between item and outlet-level data.

Step 3: Data Connection
Once the datasets were reviewed, I established data connections in Power BI, loading the item and outlet information into the model. I ensured proper formatting and consistency in column types to avoid errors during transformation and visualization.

Step 4: Data Cleaning and Quality Checks
I then moved on to data cleaning and quality checks, where I handled missing values, removed duplicates, and standardized inconsistent entries like fat content labels. This ensured data integrity and reliability throughout the analysis.

Step 5: Data Modeling
Following data cleaning, I worked on data modeling, establishing relationships between tables using primary and foreign keys. I ensured one-to-many relationships were properly defined and created hierarchies where needed, such as Outlet → Location.

Step 6: Data Transformation and DAX Calculations
With a solid model in place, I proceeded to data transformation and processing using Power Query and DAX. I created calculated columns and measures for KPIs such as Total Sales, Average Sales, Number of Items, and Average Rating, enabling dynamic metric calculations.

Step 7: Dashboard Layout and Design
I then focused on dashboard layout and design, sketching the structure of the report for logical flow and user-friendly navigation. The layout was designed to show summary metrics at the top, followed by detailed visualizations segmented by various dimensions like item type, fat content, and outlet type.

Step 8: Chart Development and Formatting
During chart development, I used a variety of visuals including donut charts, bar charts, stacked column charts, line graphs, funnel maps, and matrix cards. Each chart was tailored to specific business questions, such as analyzing sales by fat content or comparing performance across outlet types.

Step 9: Insight Generation and Conclusion
Finally, I compiled the complete dashboard and generated insights. Key findings included the impact of fat content on sales and ratings, the superior performance of certain outlet types and locations, and the positive sales correlation with outlet size and age. These insights can inform inventory planning, marketing focus, and operational improvements.

**Visualizations & Dashboard Highlights**
Donut Chart – Total Sales by Fat Content
Bar Chart – Total Sales by Item Type
Stacked Column Chart – Fat Content by Outlet
Line Chart – Total Sales by Outlet Establishment Year
Pie/Donut Chart – Sales by Outlet Size
Funnel Map – Sales by Outlet Location
Matrix Card – All KPIs by Outlet Type

**Conclusion**
This Power BI dashboard provides a powerful lens into InstaCart’s sales performance and outlet operations. It highlights actionable insights on where to focus for boosting sales, improving customer satisfaction, and optimizing inventory allocation.

This is how the dashboard looks like: https://github.com/ullaskrishna1/Instacart-Dashboard/blob/main/Dashboard%20Image.PNG


![Dashboard Image](https://github.com/user-attachments/assets/a9cbc3d0-947d-442f-86e7-93d5c8596313)

