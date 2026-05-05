# MARKETING-CAMPAIGN-CUSTOMER-SALES-ANALYSIS

### TABLE OF CONTENT
* [Project Overview](#project-overview)
* [Tools](#tools)
* [Dataset Overview](#dataset-overview)
* [Data Cleaning](#data-cleaning)
* [Data Exploration](#data-exploration)
* [Dashboard](#dashboard)
* [Power Bi Dashboard](#power-bi-dashboard)
* [Key Questions And Insights](#key-questions-and-insights)
* [Key Takeaway](#key-takeaway)
* [Interactive Features](#interactive-features)
* [Recommendation](#recommendation)
* [Data Source](#data-source)
* [Conclusion](#conclusion)


### PROJECT OVERVIEW
This project presents a comprehensive analysis of a marketing campaign dataset using Power BI with the goal of uncovering insights of customer behavior, campaign performance, product trends, and sales channels.The dashboard transforms raw data into actionable business intelligence, helping stakeholders understand what drives customer purchases and how to optimize marketing strategies.

#### OBJECTIVES
The analysis was guided by the following key business questions:
1. Are there any null values or outliers? How were they handled?
2. What factors are significantly related to the number of web purchases?
3. Which marketing campaign was the most successful?
4. What does the average customer look like?
5. Which products are performing best?
6. Which channels are underperforming?


### TOOLS
* Power BI – Data modeling, transformation and visualization
* Power Query – Data cleaning and transformation
* DAX – Measures and calculated columns

### DATASET OVERVIEW

COLUMNS:
- ID
- Year_Birth
- Education
- Marital_Status
- Income
- Kidhome
- Teenhome
- Dt_Customer
- Recency
- MntWines
- MntFruits
- MntMeatProducts
- MntFishProducts
- MntSweetProducts
- MntGoldProds
- NumDealsPurchases
- NumWebPurchases
- NumCatalogPurchases
- NumStorePurchases
- NumWebVisitsMonth
- AcceptedCmp3
- AcceptedCmp4
- AcceptedCmp5
- AcceptedCmp1
- AcceptedCmp2
- Response
- Complain
- Country
  

DATASET SAMPLE PREVIEW:
|ID|Year_Birth|Education|Marital_Status|Income|Kidhome|Teenhome|Dt_Customer|Recency|MntWines|MntFruits|MntMeatProducts|MntFishProducts|MntSweetProducts|MntGoldProds|NumDealsPurchases|NumWebPurchases|NumCatalogPurchases|NumStorePurchases|NumWebVisitsMonth|AcceptedCmp3|AcceptedCmp4|AcceptedCmp5|AcceptedCmp1|AcceptedCmp2|Response|Complain|Country|
|---|---------|---------|--------------|------|-------|--------|-----------|--------|--------|--------|---------------|---------------|---------------|-------------|-----------------|---------------|-------------------|-----------------|-----------------|------------|-------------|-----------|------------|------------|--------|--------|--------|
|1826|1970|Graduation|Divorced|84835|0|0|6/16/2014|0|189|104|379|111|189|218|1|4|4|6|1|0|0|0|0|0|1|0|Spain|
|1|1961|Graduation|Single|57091|0|0|6/15/2014|0|464|5|64|7|0|37|1|7|3|7|5|0|0|0|0|1|1|0|Canada|
|10476|1958|Graduation|Married|67267|0|1|5/13/2014|0|134|11|59|15|2|30|1|3|2|5|2|0|0|0|0|0|0|0|USA|
|1386|1967|Graduation|Together|32474|1|1|5/11/2014|0|10|0|1|0|0|0|1|1|0|2|7|0|0|0|0|0|0|0|Australia|
|5371|1989|Graduation|Single|21474|1|0|4/8/2014|0|6|16|24|11|0|34|2|3|1|2|7|1|0|0|0|0|1|0|Spain|



### DATA CLEANING 
* Handled missing values in the Income column using median imputation.
* Reviewed outliers in income and spending; retained them as they represent high-value customers.
* Created derived columns:
 > Income Group (Low, Medium, High)
* Ensured proper data types and formatting for analysis.

###  DASHBOARD FEATURES
 KPI Metrics
- 💰 Total Revenue: 1M
- 👥 Total Customers: 2,216
- 🌐 Total Web Purchases: 9,053
- 📢 Campaign Acceptance: 661
- 💵 Average Income: 52K
 
 DASHBOARD CHARTS
- 🍷  Product Performance Analysis (The best performing products are wines, meat products and gold)
- 💹 Campaign Success Comparison (The most successful marketing campaign is campaign 4)
- 📊 Income Group vs Web Purchases (The highest income group contributes the most to web purchases)
- 🧑 Customer Profile Summary (Average customer profile includes; Average Age: 57 years, Average Income: 52K, Moderate spending behavior and Engages across multiple channels)
- 📈 Relationship between web purcahse and web visits month (Purchases peak at 6–7 visits per month and decline after that → indicates browsing without conversion)
- 📊 Purchase Channel Performance Analysis (Underperforming purchase channel are Deal Purchase and Catalogue Purchase)

  

🔍 KEY QUESTIONS AND INSIGHTS 

1. Data Quality
   > Are there Null values or outliers? How will they be handled?
The dataset was largely clean with minimal missing values. Outliers were retained to preserve high-value customer insights.

2. What Factors Are Significantly Related to the Number of Web Purchases?
 > Two major factors demonstrated strong relationships with web purchases:
- Income: Income has a strong positive relationship with web purchases. Customers in the high-income group generate the highest number of online purchases, while low-income customers contribute the least.
- Website Visits: Website visits are strongly related to web purchases. Customers who visit the website 6–7 times per month generate the highest number of purchases. Beyond this point, purchases decline, suggesting that highly frequent visitors may need additional encouragement to convert.
Income and cross-channel engagement are strong predictors of online purchasing behavior.

3. Which Marketing Campaign Was the Most Successful?
Among all five campaigns, Campaign 4 recorded the highest customer acceptance rate by 24.8%, outperforming the others in total conversions.
Key Insight
Campaign 4 resonated most effectively with customers, indicating superior messaging, targeting and structure, Campaigns with higher acceptance rates indicate stronger marketing effectiveness.


4. What Does the Average Customer Look Like?
The typical customer profile can be summarized as follows:
- Average Age: 57 years
- Average Income: 52K (Medium-to-high income earner)
- Moderate spending behavior
- Married or in a relationship
- Shops across multiple channels
- Responds positively to marketing campaigns
- Prefers wine and meat products
The average customer is middle-aged, earns a good income, is financially stable, spends consistently, actively shops online and is highly engaged across multiple purchase channels.

5. Which Products Are Performing Best?
Product category analysis shows that the top-performing products are:
- MntWine
- MtnMeat Products
- MntGold Products
These categories generate the highest customer spending and purchase frequency annd Premium and lifestyle-oriented products dominate customer spending patterns.

6. Which Channels Are Underperforming?
The Underperforming channels are:
 - Deals Purchase
 - Catalogue Purchase
Store purchase remain the strongest channel, followed by web purchase
Customer preference is shifting toward digital and in-store shopping experiences.


### POWER BI DASHBOARD

<img width="913" height="506" alt="Esther marketing campaign dashboard" src="https://github.com/user-attachments/assets/1f5c3b02-93ff-4bcb-83d7-1b809c028927" />


📈 Business Recommendations

* 🎯 Focus on high-income customer segments
* 🔁 Retarget high-visit, low-conversion users
* 📢 Replicate strategies from the most successful campaign
* 🛍 Promote high-performing product categories
* 🔗 Encourage multi-channel engagement to increase customer value

⸻
