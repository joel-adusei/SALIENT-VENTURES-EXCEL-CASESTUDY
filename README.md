# SALIENT VENTURE Q4 SALES ANALYSIS

## Evaluating the Success of a Strategic Business Turnaround Using Advanced Microsoft Excel Analytics

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/tim-gouw-KigTvXqetXA-unsplash.jpg?raw=true)


***Disclaimer⚠️:** All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis on healthcare dataset*

![image]()

## INTRODUCTION

SALIENT Ventures experienced a significant business downturn throughout the first three quarters of 2025, recording a consistent 20% quarter-over-quarter decline in revenue. The decline was largely attributed to poor inventory management, weak customer retention, and limited market penetration.

To reverse this trend, the company's Board of Directors engaged the 10Alytics Team to implement a strategic recovery plan focused on:

Performance-based employee incentives
Inventory diversification into high-affinity product categories
Aggressive regional marketing expansion

Following the implementation of these initiatives, management submitted the company's Q4 2025 transaction dataset to evaluate whether the turnaround strategy delivered measurable business improvement.

This project leverages Microsoft Excel's advanced analytics capabilities to assess the effectiveness of the intervention and provide actionable recommendations for 2026 planning.

## BUSINESS PROBLEM

Although transaction volume increased significantly during Q4 2025, management lacked sufficient visibility into the underlying drivers of growth.

Key concerns included:

Was the increase in sales truly profitable?
Which products and customer segments contributed most to recovery?
Did regional marketing efforts generate meaningful returns?
Was customer engagement improving or simply generating short-term activity?

Without data-driven answers, leadership could not confidently approve strategic investments for the 2026 fiscal year.

## PROJECT OBJECTIVES

The primary objective of this analysis was to determine whether SALIENT Ventures' Q4 recovery strategy resulted in sustainable business growth.

Specifically, the project aimed to:

1. Evaluate Sales Performance
Calculate Total Revenue
Calculate Total Expenses
Calculate Total Profit
Determine Profit Margin
Analyze weekly revenue and profit trends throughout Q4
2. Validate the Turnaround Strategy
Assess whether increased transaction volume translated into profitability
Identify high-performing products and categories
Evaluate regional performance after marketing expansion
3. Understand Customer Behavior
Identify top revenue-generating customers
Analyze purchasing patterns by gender
Evaluate revenue contribution by customer age groups
4. Support Executive Decision-Making
Build a dynamic Excel dashboard
Deliver actionable insights for budgeting and strategic planning
DATASET OVERVIEW

The dataset contains all recorded sales transactions between:

October 1, 2025 – December 31, 2025

The data captures customer activity, product sales, employee performance, and geographic distribution across multiple states.

Key Data Fields
Category	Attributes
Customer Information	Customer ID, Customer Name, Gender, Age, City
Transaction Information	Order ID, Order Date, Quantity
Product Information	Product ID, Product Name, Category
Financial Information	Selling Price, Cost Price
Employee Information	SalesPerson



![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/rawdata.JPG?raw=true)

Initial raw data before cleanup and transformations



## METHODOLOGY
STEP 1: Data Cleaning & Preparation

The dataset was first cleaned and standardized within Microsoft Excel to ensure data quality and analytical accuracy.
Below are the exact tasks, formulas, and screenshot targets

1. Removed duplicates
   
   The dataset was made up of three different tables (Orders, Customers and Products). Duplicated values were removed from each table
   using their respective primary keys; OrderID, CustomerID and ProductID respectively.

   Action: Use remove Duplicates from the Data Section in Excel.

   ![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/remove%20duplicates.JPG?raw=true)


   ![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/duplicates%20found.JPG?raw=true)

   
   
3. Handled missing values

    Missing values from the customers table were handled by removing them.

4. Converted range to an Excel Table

    Action: Select the range and press Ctrl+T → name the table CleanTable. This enables structured references and slicer connectivity for the dashboard.
   

6. Standardize Text Columns

   Applied TRIM() to normalize text for CustomerName and City columns.

   ![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/standardize.JPG?raw=true)


7. Created Expenses and Revenue Columns
   

   Expenses

![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/Expenses.JPG?raw=true)


   Revenue

![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/Revenue.JPG?raw=true)


8. Using XLOOKUP, I merged the customers and Products Table with the Orders table for easy analysis.
   

![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/Xlookup.JPG?raw=true)



9. Format Columns for Consistency
- Applied date formatting (dd-mm-yyyy) for Order Date.
- Applied number formatting for Expenses and Revenue fields ($ currency).





This ensured consistency before analysis and dashboard development.



STEP 2: Data Analysis Using Pivot Tables

Pivot Tables were used extensively to summarize and analyze business performance.

The analysis focused on:

Sales Performance
Total Revenue
Total Expenses
Total Profit
Profit Margin
Weekly Revenue Trends
Weekly Profit Trends
Product Performance
Top 10 Products by Profit
Profit by Product Category
Top 5 Products by Quantity Sold
Customer Insights
Top 5 Customers by Revenue
Revenue by Gender
Revenue by Age Group
Regional Analysis
Profit by State
City-Level Profitability


![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Images/pivot.JPG?raw=true)




STEP 3: DASHBOARD

![image](https://github.com/joel-adusei/SALIENT-VENTURES-EXCEL-CASESTUDY/blob/main/Sales_Analysis_Dashboard.JPG?raw=true)


Interactive charts were developed to transform summarized data into actionable business insights.

Visualizations included:

KPI Cards
Line Charts
Bar Charts
Donut Charts
Geographic Profit Map
Top-N Product Rankings
STEP 4: Dashboard Development

An executive-level dashboard was created in Microsoft Excel to provide a comprehensive view of Q4 performance.

Dashboard Features
Month Filters
Product Category Filters
State Filters
Profit Trend Analysis
Customer Segmentation Analysis
Geographic Performance Tracking
Product Profitability Monitoring
Dashboard Overview

The dashboard provides visibility into:

Revenue performance
Expense management
Profit generation
Customer demographics
Product profitability
Regional expansion effectiveness
DASHBOARD SUMMARY
Key Performance Indicators
Metric	Value
Total Revenue	$115M
Total Expenses	$98M
Total Profit	$17M
Total Products	34
Profit Margin	15%

These figures indicate a substantial improvement from previous quarters and suggest the turnaround initiatives generated positive financial outcomes.

## KEY INSIGHTS
1. Sales Recovery Was Successful

SALIENT Ventures generated:

$115M Revenue
$17M Profit
15% Profit Margin

The company successfully reversed its declining revenue trend and returned to profitable growth during Q4.

2. Product Diversification Delivered Results
Most Profitable Categories
Category	Profit
Accessories	$4.06M
Games	$3.07M
Gym	$2.86M
Sports	$2.58M
Clothing	$2.45M
Electronics	$2.21M

The newly expanded categories significantly contributed to overall profitability, validating the inventory diversification strategy.

3. High-Affinity Products Drove Growth
Top Profit-Generating Products
Gold Bracelets
Yoga Mat
Kids Games
Gold Rings
Gym Gloves

These products generated the highest profit contributions and align directly with the strategic recommendation to expand into gym and lifestyle categories.

4. Customer Demographics Reveal Key Buyers
Revenue by Gender
Female Customers: $9.25M Profit Contribution
Male Customers: $7.93M Profit Contribution

Female customers contributed slightly more profit, suggesting stronger purchasing engagement.

Revenue by Age Group
Young Adults (18–35): $7.49M
Older Adults (36–55): $9.78M

Older customers generated the highest revenue and represent the most valuable customer segment.

5. Regional Marketing Expansion Produced Positive Results

The profit distribution map highlights strong performance across key states including:

California
Texas
Illinois
Georgia
Washington

This suggests regional marketing efforts successfully expanded market reach beyond traditional territories.

6. Strong Weekly Profit Trends

Profit remained consistently above $0.8M throughout Q4 and peaked multiple times above $1.5M.

This indicates sustained business performance rather than a short-lived sales spike.

7. Customer Concentration Remains Important

The top five customers each generated over $2.4M in revenue.

This presents opportunities for:

VIP retention programs
Personalized offers
Strategic account management


## RECOMMENDATIONS
Expand High-Performing Categories

Increase inventory investment in:

Accessories
Gym Products
Games
Sports Equipment

These categories generated the strongest profitability.

Strengthen Customer Retention Programs

Develop:

Loyalty rewards
Personalized promotions
VIP customer programs

to retain top-value customers.

Scale Regional Marketing Efforts

Increase marketing spend in high-performing states while replicating successful campaigns in emerging markets.

Optimize Product Portfolio

Reduce focus on lower-performing products and prioritize inventory allocation toward high-margin categories.

Leverage Demographic Insights

Design targeted campaigns for:

Female shoppers
Customers aged 36–55

who currently generate the highest value.


## BUSINESS IMPACT

This analysis demonstrates that SALIENT Ventures' Q4 strategic turnaround was successful.

The company achieved:

✅ Revenue growth recovery

✅ Improved profitability

✅ Strong category diversification

✅ Expanded regional penetration

✅ Enhanced customer engagement

The dashboard provides management with a centralized decision-support tool for monitoring performance and guiding strategic planning for the 2026 fiscal year.

### BUSINESS IMPACT

This analysis identified key profitability drivers, underperforming product lines, seasonal trends, customer concentration risks, and regional growth opportunities, providing actionable insights to support data-driven business decisions.

