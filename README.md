# Sales Analysis
### Project Overview 
This data analysis project aims to provide insights into the sales performance of an e-commerce company over the past years. By analyzing various aspect of the sales data we 
seek to identify trends, make data driven recommendations and gain a deeper understanding of the company's performance.

### Data Sourcing:
The primary dataset used for this analysis is the "Shop_Data.cvs" file,containing detailed
information about each sales made by the company.

### Tools
-Power BI /Data Cleaning processes,Data Analysis and Dax calculation,Creating of Dashboard report.[Download Here](https://microsoft.com)

### Data Cleaning/Preparation
In the initial data prepration phase,we performed the following tasks
1. Data loading and inspection
2. Handling missing values
3. Data Cleaning and formatting

### Exploratory Data Analysis
EDA involves exploring the sales data to answer key questions such as :
- WHat is the overall sales trend?
- Which means of transaction has the highest purchase?
- What are the peak sales periods?
 ### Data Analysis
 Some interesting code features
 Price_Category = IF(shop_data[price]<100,"Low",IF(shop_data[price]<250,"Medium","High"))

### Results & Findings
The analysis result are summarized as follows:
1. There were high sales on the year 2023 compared to other years.
2. Between the various payment method i found out that paypal has the lowest purchased rate. Therefore,there should be reduction in the cost of maintaining the website for online purchase.

### Recommendation
Based on the analysis i recommended the following actions:
- Invest in marketing and promotions during peak Sales season to maximize revenue.
- Focus on expanding and promoting products.
- Implementing a customer segmentation strategy to target high purchase effectively.

### Limitations
I had to remove all zero values from price column and profit columns because they would have affected the acuracy of my calculations from the analysis
