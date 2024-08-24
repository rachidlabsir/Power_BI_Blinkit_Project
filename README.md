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

   ![image 2](https://github.com/user-attachments/assets/1e2ac2b7-b4be-4e28-8d28-6122d5fa9c36)

**Insight**:

The total sales amount of $1.20M indicates a strong revenue stream. The average unit sale value of $141 suggests that each sale contributes significantly to the overall revenue, highlighting the profitability of individual items.

**Number of Items and Average Rating**

   ![image 3](https://github.com/user-attachments/assets/7e1dc589-c9dc-4622-82f5-e0a3f1527608)
   
**Insight**:

With 9K items sold and an average rating of 3.9, it shows that a wide variety of products are being offered and customers are generally satisfied with their purchases. This high average rating can be leveraged to promote customer trust and loyalty.

#### Total Sales by Fat Content

   ![image 1](https://github.com/user-attachments/assets/3ffdb246-ab4e-4336-9dc1-6dc32a8d4703)
                 

**Insight**:

The donut chart reveals that regular fat products significantly outperform low-fat products in terms of sales, contributing $776.32K compared to $425.36K. This indicates a strong consumer preference for regular fat items, suggesting that marketing efforts and inventory management should prioritize these products to maximize revenue. Additionally, the notable difference in sales could guide product development strategies to enhance the appeal of low-fat products, potentially through improved taste, packaging, or highlighting health benefits.

#### Fat Content by Outlet for Total Sales

   ![image 4](https://github.com/user-attachments/assets/e4c25f6f-2896-42cd-a05b-7e8e69d96ed0)
   
**Insight**:

The “Fat Content by Outlet for Total Sales” chart provides valuable insights into how different types of outlets perform in terms of sales for low-fat and regular-fat content products.

From the chart, we can observe that Tier 3 outlets have the highest total sales for both low-fat and regular-fat products, with $0.31M for low-fat and $0.17M for regular-fat content. This indicates a strong consumer preference for low-fat products in these outlets. Tier 2 outlets follow, with $0.25M in sales for low-fat and $0.14M for regular-fat products. Interestingly, Tier 1 outlets show a different trend, where regular-fat products have higher sales ($0.22M) compared to low-fat products ($0.12M).

This suggests that while low-fat products are generally more popular, certain outlets (like Tier 1) have a higher demand for regular-fat products. These insights can help in tailoring marketing strategies and inventory management to meet the specific preferences of customers at different outlet tiers.

#### Total Sales by Item Type

   ![image 5](https://github.com/user-attachments/assets/813a3744-9a33-4421-bd57-4a04e87eb44b)
   
**Insight**:

The “Total Sales by Item Type” chart provides a clear comparison of sales across various item categories. Snack Foods lead the sales with $0.18M, indicating a high consumer preference for these items. Household items follow with $0.14M in sales, showing their significant contribution to overall revenue. Frozen Foods and Dairy also perform well, with sales of $0.12M and $0.10M respectively. On the lower end, Seafood has the least sales at $0.01M, suggesting it is less popular among consumers. This distribution highlights the importance of focusing on high-performing categories like Snack Foods and Household items to maximize sales and revenue.

#### Total Sales by Outlet Establishment

   ![image 9](https://github.com/user-attachments/assets/75357178-da82-4aef-af3a-798ab3cfbc2f)

**Insight**:

The “Total Sales by Outlet Establishment” chart shows the sales trends from 2011 to 2022. Sales started at $78K in 2011 and experienced fluctuations over the years. Notable peaks occurred in 2014 and 2016, both reaching $132K. The highest sales were recorded in 2018 at $205K, indicating a significant growth period. However, after 2018, there was a decline, with sales dropping to $129K by 2022. This trend suggests that while there were periods of strong growth, recent years have seen a downturn, which could be due to various market factors or changes in consumer behavior. Understanding these trends can help in strategizing future business decisions to regain and sustain growth.

#### Sales by Outlet Size

   ![image 6](https://github.com/user-attachments/assets/019ab749-c28f-4070-b2ff-332f3a4518e5)

**Insight**:

The “Sales by Outlet Size” chart provides a clear view of how sales are distributed across different outlet sizes. High outlets lead with the highest sales at $507.90K, indicating they are the most significant contributors to overall revenue. Medium outlets follow with $444.79K in sales, showing they also play a crucial role in the sales performance. Small outlets have the lowest sales at $248.99K, suggesting they contribute less compared to the other outlet sizes. This distribution highlights the importance of focusing on high and medium-sized outlets to maximize sales and revenue, while also exploring strategies to boost sales in smaller outlets.

#### Sales by Outlet Location

   ![image 7](https://github.com/user-attachments/assets/cd27cf19-9b67-4d86-8b46-884ad9cf25a0)

**Insight**:

The “Sales by Outlet Location” chart reveals that Tier 3 outlets lead in sales performance with $472.13K, followed by Tier 2 outlets at $393.15K, and Tier 1 outlets at $336.40K, which is about 71.3% of the sales benchmark set by Tier 3. This indicates that Tier 3 outlets, likely situated in high-traffic areas or having a larger customer base, are the most successful. In contrast, Tier 1 outlets, possibly in less busy locations, show room for improvement. Focusing on strategies that make Tier 3 outlets successful could help boost sales in Tier 1 and Tier 2 outlets.

#### All Metrics by Outlet Type

   ![image 8](https://github.com/user-attachments/assets/7bcf4384-54df-46cb-b82b-85e4a986d812)

**Insight**:

The “All Metrics by Outlet Type” chart provides a comprehensive comparison of various metrics across different outlet types. Supermarket Type1 leads in total sales with $787.55K and has a high number of items sold (5577), indicating strong performance and customer reach. Grocery Stores have the highest number of items (1083) and item visibility (0.10), but their total sales are lower at $151.94K, suggesting a wide product range but lower revenue per item. Supermarket Type2 and Supermarket Type3 have similar total sales figures ($131.48K and $130.71K, respectively) and item visibility (0.06), but differ slightly in the number of items sold and average sales. This chart highlights the strengths and weaknesses of each outlet type, providing valuable insights for optimizing inventory and sales strategies.

### 6. Recommendations

#### **Enhance Marketing for Low-Fat Products:**
- While regular-fat products perform well, the company can improve the appeal of low-fat products by emphasizing their **health benefits**, improving **taste**, or experimenting with **new packaging**.

---

#### **Focus on High and Medium-Sized Outlets:**
- Given that high and medium-sized outlets contribute significantly to sales, Blinkit should prioritize **inventory allocation** and **marketing campaigns** in these outlets to maintain and increase revenue.

---

#### **Boost Tier 1 Outlet Performance:**
- Tier 1 outlets underperform compared to Tier 3. Blinkit can implement **targeted marketing strategies**, **promotions**, or **improved customer experiences** in these outlets to boost their sales.

---

#### **Maximize Sales of High-Performing Item Categories:**
- Since **Snack Foods** and **Household Items** lead in sales, Blinkit can focus on expanding these product categories, offering **promotions**, or adding more related items to increase sales.

---

#### **Address Declining Sales Trends Post-2018:**
- Sales have seen a decline after 2018. A detailed analysis of **market conditions**, **consumer preferences**, and potential competitors is needed to understand the decline. Blinkit can introduce **new products**, update its **marketing strategy**, or optimize **pricing** to regain sales growth.

### 7. Key Skills Gained from Blinkit Sales Data Analysis with Power BI

Working on the Blinkit sales data analysis project using Power BI provided me with valuable skills that are essential for data-driven decision-making

#### **Data Analysis & Interpretation:**
- I learned how to analyze and interpret sales data, identifying trends in **customer behavior**, **sales by product categories**, **outlet performance**, and the impact of factors like **fat content** and **outlet size** on total sales.

---

#### **Business Intelligence & Data Visualization:**
- Building the **Power BI dashboard** helped me master visualizing key performance metrics such as **total sales**, **average sales**, and **customer ratings**.
    - I used various chart types to convey insights, like **donut charts** for product categories and **line charts** for sales trends over time.

---

#### **Data Transformation & Cleaning:**
- Through **Power Query**, I gained hands-on experience cleaning and transforming raw data, including **filtering rows**, **renaming columns**, **changing data types**, and **grouping data** for better insights.
    - This strengthened my ability to ensure **data accuracy** and readiness for analysis.

---

#### **Insights Generation & Problem-Solving:**
- I developed the ability to extract meaningful insights from the data, such as identifying **sales patterns** across different **outlet tiers** and **item types**.
    - I also learned how to pinpoint challenges, like **declining sales trends** after 2018, and propose **data-driven solutions**.

---

#### **Market Segmentation & Customer Preferences:**
- By analyzing sales across various **outlet types**, **sizes**, and **locations**, I gained a deeper understanding of how different **market segments** perform.
    - This skill is crucial for tailoring **marketing strategies** and optimizing **product offerings** based on **customer preferences**.

---

#### **Effective Communication of Data:**
- Presenting complex data in a simplified and visually engaging manner allowed me to refine my **communication skills**, ensuring that stakeholders can easily understand the insights and take actionable steps.

## Conclusion:

The Blinkit Sales Analysis Power BI dashboard provides a detailed view of the company’s sales performance, item popularity, and customer satisfaction across various outlets and product categories. Overall, the business has a solid foundation with high sales, customer satisfaction, and strong performances in certain product categories and outlets. However, there are areas for improvement, such as optimizing the sales of low-fat products, boosting sales in Tier 1 outlets, and addressing declining trends post-2018. Implementing the suggested strategies could help Blinkit maintain its competitive edge and achieve sustainable growth.

