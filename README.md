# DSA_PROJECT

###  Project Topic: Amazon Product Review Analysis

[Project overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

### Project overview
---
The aim of this data analysis project is to create insightful views on sales performance for the e-commerce site over a specified period. By analyzing customer and product reviews, the project will discover trends that will guide product improvement, enhance marketing, and enhance customer interaction. Insights generated will enable management decision-making and aid in sharing compelling data-driven stories, highlighting best-selling products and general company performance.

### Data Sources
---
The primary source of Data used here is amazon case study.xlsx and this is an open source data given as a project from DSA Incubator Hub.

### Tools Used
---
- Microsoft Excel
  1.  For Data Cleaning
  2.  For Analysis
  3.  For Data Visualization
     
- GitHub for Portfolio Building

  ### Data Cleaning and Preparation
  ---
  In the initial phase of the Data cleaning and preparations, we perform the following action;
  
   1. Data loading and Inspection
   2. Handling missing variables
   3. Data cleaning and formatting

 ### Exploratory Data Analysis
 ---
 EDA involved the exploring of the Data to answer some questions about the Data such as:
 
1. What is the average discount percentage by product category? 
2. How many products are listed under each category? 
3. What is the total number of reviews per category?  
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0,4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)? 
11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined.

### Data Analysis
---
This is where we include some basic lines of code or queries or even some of the DAX expressions used during the analysis;
 - What is the average discount percentage by product category?

   Pivot tables and calculated columns
```
- Calculated Column:
1. Discount % = ((Actual Price - Discounted Price) / Actual Price) * 100

- Pivot Table:
1. Rows: Product Category
2. Values: Average of Discount %
```

### Data Visualization
-
📱 


  
