# Power BI Project: blinkit Sales Analysis

## Overview
This Power BI project analyzes blinkit’s sales performance, customer satisfaction, and inventory distribution. I’ll walk through the key steps and insights generated from the dashboard.

## Steps Involved

### 1. Requirement Gathering/Analysis

  **Total Sales**: Overall revenue from all items sold.
  
  **Number of Items**: Total count of different items sold.
  
  **Average Sale**: Average revenue per sale.
  
  **Average Rating**: Average customer rating for items sold.

### 2. Data Collection

I sourced the relevant data from Kaggle, ensuring I had access to the necessary datasets for analysis and further processing [link](https://www.kaggle.com/datasets/tomtillo/blinkit-grocery-list-price-city-date)


### 3. Data Source and Transformation

I loaded data from a source (possibly a CSV file) into Power Query.
Applied various transformations to the data, such as filtering, renaming columns, and changing data types.

### 4. Data Cleaning and Shaping

In the “Query Settings” section, I defined a series of applied steps. These steps represent the sequence of operations performed on the data.

Some of the steps include:
    
“Changed Type”: Converting data types (e.g., from text to numeric).

“Filtered Rows”: Selecting specific rows based on conditions.

“Removed Columns”: Eliminating unnecessary columns.

“Replaced Values”: Replacing specific values with others.

“Grouped Data”: Aggregating data based on certain criteria.

### 5. Insights Generation

#### Key Performance Indicators (KPIs) 

**Total Sales and Average Unit Sales**


**Insight**:

The total sales amount of $1.20M indicates a strong revenue stream. The average unit sale value of $141 suggests that each sale contributes significantly to the overall revenue, highlighting the profitability of individual items.

**Number of Items and Average Rating**


**Insight**:

With 9K items sold and an average rating of 3.9, it shows that a wide variety of products are being offered and customers are generally satisfied with their purchases. This high average rating can be leveraged to promote customer trust and loyalty.

#### Total Sales by Fat Content

   ![image 1](https://github.com/user-attachments/assets/3ffdb246-ab4e-4336-9dc1-6dc32a8d4703)
                 

**Insight**:

The donut chart reveals that regular fat products significantly outperform low-fat products in terms of sales, contributing $776.32K compared to $425.36K. This indicates a strong consumer preference for regular fat items, suggesting that marketing efforts and inventory management should prioritize these products to maximize revenue. Additionally, the notable difference in sales could guide product development strategies to enhance the appeal of low-fat products, potentially through improved taste, packaging, or highlighting health benefits.

#### Fat Content by Outlet for Total Sales


**Insight**:

The “Fat Content by Outlet for Total Sales” chart provides valuable insights into how different types of outlets perform in terms of sales for low-fat and regular-fat content products.

From the chart, we can observe that Tier 3 outlets have the highest total sales for both low-fat and regular-fat products, with $0.31M for low-fat and $0.17M for regular-fat content. This indicates a strong consumer preference for low-fat products in these outlets. Tier 2 outlets follow, with $0.25M in sales for low-fat and $0.14M for regular-fat products. Interestingly, Tier 1 outlets show a different trend, where regular-fat products have higher sales ($0.22M) compared to low-fat products ($0.12M).

This suggests that while low-fat products are generally more popular, certain outlets (like Tier 1) have a higher demand for regular-fat products. These insights can help in tailoring marketing strategies and inventory management to meet the specific preferences of customers at different outlet tiers.

#### Total Sales by Item Type

**Insight**:

The “Total Sales by Item Type” chart provides a clear comparison of sales across various item categories. Snack Foods lead the sales with $0.18M, indicating a high consumer preference for these items. Household items follow with $0.14M in sales, showing their significant contribution to overall revenue. Frozen Foods and Dairy also perform well, with sales of $0.12M and $0.10M respectively. On the lower end, Seafood has the least sales at $0.01M, suggesting it is less popular among consumers. This distribution highlights the importance of focusing on high-performing categories like Snack Foods and Household items to maximize sales and revenue.

#### Total Sales by Outlet Establishment

**Insight**:

The “Total Sales by Outlet Establishment” chart shows the sales trends from 2011 to 2022. Sales started at $78K in 2011 and experienced fluctuations over the years. Notable peaks occurred in 2014 and 2016, both reaching $132K. The highest sales were recorded in 2018 at $205K, indicating a significant growth period. However, after 2018, there was a decline, with sales dropping to $129K by 2022. This trend suggests that while there were periods of strong growth, recent years have seen a downturn, which could be due to various market factors or changes in consumer behavior. Understanding these trends can help in strategizing future business decisions to regain and sustain growth.

#### Sales by Outlet Size

**Insight**:

The “Sales by Outlet Size” chart provides a clear view of how sales are distributed across different outlet sizes. High outlets lead with the highest sales at $507.90K, indicating they are the most significant contributors to overall revenue. Medium outlets follow with $444.79K in sales, showing they also play a crucial role in the sales performance. Small outlets have the lowest sales at $248.99K, suggesting they contribute less compared to the other outlet sizes. This distribution highlights the importance of focusing on high and medium-sized outlets to maximize sales and revenue, while also exploring strategies to boost sales in smaller outlets.

#### Sales by Outlet Location

**Insight**:

The “Sales by Outlet Location” chart reveals that Tier 3 outlets lead in sales performance with $472.13K, followed by Tier 2 outlets at $393.15K, and Tier 1 outlets at $336.40K, which is about 71.3% of the sales benchmark set by Tier 3. This indicates that Tier 3 outlets, likely situated in high-traffic areas or having a larger customer base, are the most successful. In contrast, Tier 1 outlets, possibly in less busy locations, show room for improvement. Focusing on strategies that make Tier 3 outlets successful could help boost sales in Tier 1 and Tier 2 outlets.

#### All Metrics by Outlet Type

**Insight**:

The “All Metrics by Outlet Type” chart provides a comprehensive comparison of various metrics across different outlet types. Supermarket Type1 leads in total sales with $787.55K and has a high number of items sold (5577), indicating strong performance and customer reach. Grocery Stores have the highest number of items (1083) and item visibility (0.10), but their total sales are lower at $151.94K, suggesting a wide product range but lower revenue per item. Supermarket Type2 and Supermarket Type3 have similar total sales figures ($131.48K and $130.71K, respectively) and item visibility (0.06), but differ slightly in the number of items sold and average sales. This chart highlights the strengths and weaknesses of each outlet type, providing valuable insights for optimizing inventory and sales strategies.





