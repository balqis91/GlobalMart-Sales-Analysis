### GlobalMart Sales Analysis
This repository contains a comprehensive data analysis project focused on GlobalMart's sales performance. Exploring product profitability, regional sales trends, and the relationship between discounts, sales, and profits. Includes data cleaning, EDA, visualizations, and actionable insights using Python in Jupyter Notebook.
## Introduction
GlobalMart is a pronminent retailer which has a dataset containing detailed information on its sales performance. This report analyses key metrics such as sales, profit, and discounts across different product categories, regions, and time periods. The primary objectives are to uncover trends, identify high-performing products and regions, and examine the impact of discounts on profitability. The insights aim to inform strategic decisions for optimizing revenue and profitability.

## Overview of the Dataset
The dataset consists of 1,000 rows and 24 columns, detailing transactions across various regions, product categories, and customer segments. Key variables include Sales, Profit, Discount, Ship Mode, and Order Date. The data spans multiple years, providing a robust foundation for trend analysis and performance evaluation.
![image](https://github.com/user-attachments/assets/e680cbe5-5545-4395-a24e-d6ca36f0f792)

## Data Cleaning and Preprocessing
# Importing the Dataset
The first step in any data analysis process is loading the dataset. In this project, I utilized the pandas library to load the Global Superstore dataset into Jupyter Notebook.
![image](https://github.com/user-attachments/assets/f328f164-6d7c-41c9-bd67-cf57f5b3093e)
# Output 
The data was successfully loaded into the jupyter notebook and the code snippet below was used to view the first rows of the dataset to confirm it has been successfuylly loaded.
![image](https://github.com/user-attachments/assets/8af2f63b-1fc7-4170-9704-3cfd2b43e0d2)
The analysis futher delve into checking the shape of the dataset in the jupytrer notebook and the following code snippet was run and the code returned a result showing Postal code has 194 entries of non-missing values and others data entries in this column has missing values :
![image](https://github.com/user-attachments/assets/476f62c8-372f-470a-8a1b-87de7ca43164)

To ensure the data was ready for analysis:
- Missing values in relevant columns such as "Postal Code" were replaced with zeros(0) for consistency.
  
![image](https://github.com/user-attachments/assets/acd4df15-5ecf-4b05-81be-22e6966ed2de)

- Date fields like "Order Date" and "Ship Date" were converted to datetime objects to facilitate time-based analysis using the code below and the result was printed to show.

![image](https://github.com/user-attachments/assets/696c4deb-85d2-4ed2-b529-0675bb452f78)
  
- Duplicate rows were removed to maintain data integrity and the analysis futher look into statistical analysis of the dataset to summarise the data and also foundation for exploring deeper trends, relaionships, and actionable recommendations.
![image](https://github.com/user-attachments/assets/15fd4bfc-259c-4b8a-b39e-8b367d94d209)

- Non-numeric columns were reviewed for categorical consistency (e.g., Product Category).
After successful cleaning of the dataset, the analysis proceed to the exploratory data analyis(EDA).

## Exploratory Data Analysis (EDA)
The Dataset undergoes the EDA to futher understand the structure, patterns, and relationships in  the dataset before applying more complex analyses or models in other to identify trends,anomalies, and insigts. Therefore, the key findings from the initial analysis include:
- Total Sales and Profit: The result for the analysis of GlobalMart total sales and profit shows that GlobalMart has achieved a total sales of $1.71 million and a total profit of $288,920.
  
![image](https://github.com/user-attachments/assets/b4a917a8-164f-4549-9bfd-204b284fff4c)

- TTop-Selling Products: Chairs and Phones emerged as the top-performing products, driving significant sales across regions. Chairs achieved the highest sales, followed closely by Phones, showcasing their strong demand and contribution to GlobalMart’s overall revenue.

![image](https://github.com/user-attachments/assets/e1970a09-4da4-478a-bfb9-ca9dc9afc958)

- Regional Variations: Western Europe and Oceania emerged as the highest revenue-generating regions with total sales of $259,576.28 and $228,809.08, respectively. In contrast, Canada and Western Africa recorded the lowest sales, contributing $887.01 and $1,669.25, respectively. However, the analysis also view the company sales across all region in other to provide an indept insight to GlobalMart.
  
![image](https://github.com/user-attachments/assets/4283a432-ad8d-4dbb-98a1-e4063cf58cc7) 

- Profitability: Technology products consistently showed higher profitability compared to furniture and office supplies.
## Visualizations
- Bar Chart of Sales by Product Category: The image below shows that Technology led in sales, followed by furniture and office supplies. This highlights the need to invest more in the technology segment.
![image](https://github.com/user-attachments/assets/40c32a20-2f4b-4ae8-93c9-0c839ea874d5)

- Line Graph of Monthly Sales Trends: The image below shows that Sales showed seasonal peaks in Q4, likely influenced by holiday shopping, while Q2 generally recorded lower sales.
![image](https://github.com/user-attachments/assets/562d1b6f-5988-4696-9e6e-cba935184245)

- Scatter Plot of Sales vs. Profit: A positive correlation was observed, indicating that higher sales often led to higher profits. However, a few transactions showed high sales with negative profit, warranting a review of discounting practices.
![image](https://github.com/user-attachments/assets/ff80b5ea-70ea-49cb-b0af-81644707b3e5)

- Heatmap of Sales by Region and Product Category: Technology dominated across all regions, with Europe excelling in furniture sales. Office supplies remained consistent but underperformed compared to other categories.
![image](https://github.com/user-attachments/assets/46dc67ec-5a52-40b7-b3e5-d31221561edd)

## Key Findings
- Most Profitable Categories: The analyis shhows that Technology products, particularly phones and accessories, contributed significantly to overall profit margins.
- Sales Trends: Seasonal patterns indicate an opportunity to capitalize on Q4 sales through targeted promotions and inventory optimization.
- Regional Insights: North America and Europe are strong markets; focusing on improving penetration in underperforming regions like Africa could boost global sales.
- Discount Impact: While discounts helped drive sales, they negatively impacted profit in some cases. A more strategic discounting approach could optimize both metrics.
## Recommendations
The following are the recommendations from the analysis:
- Focus on High- Margin Products: GlobalMart should increase its marketing efforts and inventory investment in high-performing categories like technology and furniture.
- Refine Discount Strategies: Reduce heavy discounting on low-margin products to avoid profit erosion.
- Expand Regional Outreach: Allocate resources to grow sales in emerging markets like Africa and South America while maintaining dominance in Europe and North America.
- Seasonal Promotions: Prepare for Q4 demand surges by optimizing inventory and offering tailored promotions to maximize revenue during peak seasons.
## Conclusion
This analysis highlights key drivers of GlobalMart's sales performance, offering actionable insights to enhance profitability and efficiency. By leveraging these findings, GlobalMart can strengthen its market position, optimize its product portfolio, and develop more effective regional and seasonal strategies.
