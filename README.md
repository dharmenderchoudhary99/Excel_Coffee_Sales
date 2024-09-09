# COFFEE SALES DASHBOARD PROJECT IN MS EXCEL
            Overview
                This project focuses on creating an interactive and insightful dashboard in MS Excel to analyze the coffee sales data. The goal of the project is to identify trends in sales 
                patterns, customer preferences, and key performance metrics. The dashboard leverages pivot tables, slicers, and calculated measures to provide a comprehensive view of coffee 
                sales across different variables such as time, location, product category, and size.

            Objectives
                The primary objectives of this project include:

                    1.Analyzing sales trends by day of the week and hour of the day.
                    2.Identifying peak sales activity times.
                    3.Calculating total sales revenue for each month.
                    4.Exploring sales variation across different locations.
                    5.Calculating the average price per order.
                    6.Identifying the best-selling product based on both quantity and revenue.
                    7.Analyzing sales variation by product category and type.
                
            Data Preparation Process
                The data preparation steps involved:
                1.Download Coffee Sales Data: Loaded the raw data from the provided Excel sheet.
                2.Data Cleaning:
                    Created a column named Size to categorize coffee sizes (LG for Large, SM for Small, RG for Regular).
                    Removed size from product details.
                    Applied the TRIM function to remove extra spaces from product details.
                
                3.Additional Columns:
                    Added a Total Bill column using the currency formula.
                    Removed unnecessary data from the Transaction Time column.
                    Created Month and Day columns extracted from the Transaction Date column.
                    Extracted an Hour column from the Transaction Time column for more granular time-based analysis.
                    Created a Day of the Week column based on the transaction date.
                
                4.Sorting & Organization:
                    Used pivot tables to sort the data by month and created a column to ensure month order is correctly displayed.
            
            Pivot Tables Created
                The following pivot tables were created to explore the sales data:

                1.Sales by Hour and Quantity: Analyzed the distribution of sales based on the hour of the day.
                2.Total Sales by Month: Calculated the total revenue for each month.
                3.Sales by Day of the Week: Analyzed sales patterns across different days.
                4.Product Category & Total Bill: Explored sales based on product categories.
                5.Location & Transaction IDs: Analyzed sales by store locations.
                6.Location & Total Bill: Explored revenue generation across different store locations.
                7.Product Details & Total Bills: Analyzed sales performance based on specific product details.
                8.Size & Transaction IDs: Investigated the relationship between coffee sizes and the number of transactions.
                9.Product Type & Total Bill: Analyzed sales by product type (e.g., espresso, cappuccino, etc.).
                
            Dashboard Features
                The dashboard provides an interactive view of the sales data using the following features:

                1.Transaction Quantity by Hour: Visualizes the variation in transaction volumes throughout the day.
                2.Product Category by Total Bill: Shows which categories generate the highest revenue.
                3.Transaction ID by Store Location: Displays transaction distribution across different locations.
                4.Product Type by Total Bill: Illustrates revenue generation by different product types.
                5.Size by Transaction ID: Analyzes customer preferences for coffee sizes.
                6.Interactive Slicers: Slicers for Month and Day allow users to filter the dashboard to view sales data for a specific time period.
                7.Measures for Key Metrics:
                    Sales: Total revenue.
                    Footfall: Total number of transactions.
                    Average Bill: Average transaction value.
                    Average Orders: Average number of orders per transaction.
            
            Findings and Conclusion
                Sales Trends: The analysis shows that sales peak during certain hours of the day and on specific days of the week, helping identify the best times for promotional activities.
                Best-Selling Products: Both in terms of quantity and revenue, certain product categories and sizes outperform others, allowing for focused marketing strategies.
                Location Insights: Some store locations perform better than others, indicating areas with higher foot traffic and demand.
                Average Order Value: Understanding the average order value helps in devising pricing and upsell strategies.
            This dashboard offers valuable insights into the coffee sales data, which can aid decision-making regarding pricing, inventory management, marketing, and operations. It provides a clear picture of    
            sales patterns, customer preferences, and key business metrics.