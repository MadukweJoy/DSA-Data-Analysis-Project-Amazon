# Amazon Product Review Analysis

## Table of Contents
- [Project Overview](#Product-Overview)
-	[Data Source](#Data-Source)
-	[Dataset Description](#Dataset-Description)
-	[Tool Used](#Tool-Used)
-	[Exploratory Data Analysis](#Exploratory-Data-Analysis)
-	[Results/Findings](#Results/Findings)
-	[Recommendations](#Recommendations)

### Project Overview
This data analysis project aims to provide e-commerce analytic solution on products and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

### Data Source
The primary dataset used for this analysis the “amazon_data.xlsx” file, containing detailed information about each product sold by the company and customer review.

### Dataset Description
The dataset contains information scraped from Amazon product pages, including: 
- Product details: name, category, price, discount, and ratings.
- Customer engagement: user reviews, titles, and content.
  
### Tool Used
- Microsoft Excel
  -	Data cleaning, analysis and creating report
  (*calculated columns, Pivot tables and Charts*).
 	
  
### Exploratory Data Analysis
EDA involved exploring the Amazon data, using pivot tables and calculated columns to answer key questions such as:
1. What is the average discount percentage by product category?
2. How many products are listed under each category? 
3. What is the total number of reviews per category? 
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
9. What is the total potential revenue (actual price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g.,<₹200, ₹200–₹500, >₹500)? 
11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined.

### Results/Findings
The analysis results are summarized as follows:
- About 50% of products already have discounts greater than or equal to 50%. This will affect the company’s profit/revenue generated. 
- Only three products emerge with a rating of 5.0. indicating consumers' satisfaction.
- Most products fell in the ₹200-₹500 price range bucket showing the highest potential revenue.


<img width="1233" alt="Image" src="https://github.com/user-attachments/assets/e2771101-0759-4afc-8234-2eaf5d863e03" />


### Recommendations
Based on the analysis we recommend the following:
-	Focus on expanding and marketing products with the highest average ratings and within the ₹200-₹500 price range bucket.
-	Promote products with less than 1000 reviews.
