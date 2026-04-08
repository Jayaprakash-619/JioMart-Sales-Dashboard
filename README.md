# JioMart-Sales-Dashboard

JioMart Grocery Sales Dashboard 
JioMart Grocery Sales Insights Dashboard:
A dynamic, interactive data visualization tool built to explore JioMart Grocery Sales data focusing on Outlet Insights, Product Insights and Overall Performance.

This dashboard provides a comprehensive overview of sales performance, product trends and outlet efficiency for JioMart. It helps track key metrics like Total Sales, Item Count, Average rating and Average Sales distributioin across outlet types, sizes and locations. The purpose of the dashboard is to identify top-performing categories and outlets while highlighting areas that need improvement. Overall, it supports data driven decision-making to optimize sales strategy and business growth.

The dashboard was built using the following tools and technologies:
MS Excel - Data was collected from various sources and organized in excel for better understanding and analysis.
Power BI Desktop - Main data visualization platform used for report creation.
Power Query - Data Transformation and cleaning layer for reshaping and preparing the data.
DAX (Data Analysis Expressions) - Used for calculated measures, dynamic visuals and conditional logic.
Data Modeling - Relationships established among tables to enable cross-filtering and aggregation.
File Format - .pbix (or) .pbip for development and .png for dashboard preview.

Source: Bigmart sales dataset & public platform like Kaggle.

Data on JioMart Grocery Sales across the city was collected for a specific month, including detail information on products, outlet characteristics and sales performance. The dataset captures key aspects such as item categories, outlet types, locations and revenue metrics, enabling comprehensive analysis of business performance during that period.

Business problem
Goal of the dashboard
Walk through of Key values
Business Impact & Insights

JioMart is facing challenges in understanding sales performance across different outlets, product categories and locations leading to inefficiencies in decision-making and resource allocation.  

What is the Total Sales trend over time, and when does it peak or decline ? 
Which Outlet Type generates the highest revenue ?
Which Product Category contribute the most to total sales ? 
Do customers prefer Low Fat or Regular products ?
Which Outlets have the highest number of items sold ?
Where should new outlets be opened for maximum profit ?

The Goal of the dashboard is to provide a clear and interactive view of JioMart Grocery Sales performance for a specific period. It aims to help stakeholders monitor key metrics such as sales, item performance and outlet efficiency in one place. The dashboard is designed to identify top-performing products, outlets and locations while also highlighting underperforming areas that need attention. It enables better understanding of customer preferences and sales trends. Overall, the goal is to support data driven decision making to improve sales, optimize operations and enhance business growth.    

KPIs (Key Performance Indicator) - It shows Total Sales ($1.20M), Average Sales ($141M), Total Items (8523) and Average Rating (3.9). These KPIs were built with the help of aggregated functions like SUM, AVERAGE & COUNTROWS. It gives a quick snapshot of overall performance without needing deep analysis.     

Sales Trend (Line Chart) - It shows the variation of total sales over time. In X-axis Outlet Establishment Year & in 
Y-axis Total Sales. The visualization helps identify how much sales generated in each year, making it easier to observe trends, growth patterns and fluctuations in performance over time.   

Item Type (Stacked Bar Chart) - It shows Sales contribution by product categories. In X-axis metrics (it is nothing but combining of all KPIs) & in Y-axis Item Type. This visual highlights top and low-performing categories. It is used to easy comparison across multiple categories.

Fat Content (Donut Chart) - It shows sales split between Low Fat vs Regular items. In Legend Fat content & in Values metrics (it is nothing but combining of all KPIs). It shows customer preference distribution.

Outlet Size (Donut Chart) - It shows Sales contribution by outlet size (Small, Medium and High). In Legend Outlet Size & in Values Total Sales. Medium outlets contributing the most (42.27%) followed by Small outlets (37.01%) and High (20.72%).     

Outlet Location (Funnel Chart) - It shows sales by Tier 1, Tier 2 and Tier 3 locations. In category Outlet location & in Values Sum of sales. Tier 3 (472.13K) contributes the highest followed by Tier 2 (393.15K) and Tier 1 (336.40K).  

Outlet Type (Matrix) - It shows Outlet Type vs Total Sales, No.of Items, Average Sales, Average Rating & Item visibility. In Rows Outlet Type & in Values Total Sales, No.of Items, Average Sales, Average Rating & Item visibility. Supermarket Type 1 dominates across metrics.    

Fat Outlet (Clustered Bar Chart) - It shows sales of Low Fat and Regular products across different outlet location tiers (Tier 1, Tier 2 and Tier 3). In X-axis metrics (it is nothing but combining of all KPIs) & in Y-axis Outlet Location & in Legend Fat Outlet. Each cluster contains two bars (Low fat and Regular) for easy comparison within each tier.    

Slicers - It shows allows filtering by Outlet location Type, Outlet Size & Item Type. It makes dashboard interactive and user-friendly. 

Revenue Optimization: Focus on high performing outlets (Tier 3, medium size) to maximize returns. 
Marketing Strategy: Run campaigns to boost Low fat product sales, use targeted promotions based on location and outlet performance. 
Category Concentration: Business is highly dependent on limited product categories, a few categories like Fruits, Snacks and household items dominate sales.   
Moderate Customer Satisfaction: Average Rating around 3.9, There is a room for improvement in customer experience. 





