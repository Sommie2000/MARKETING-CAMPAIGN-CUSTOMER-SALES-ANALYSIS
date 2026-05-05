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

### DATA CLEANING 
* Handled missing values in the Income column using median imputation.
* Reviewed outliers in income and spending; retained them as they represent high-value customers.
* Created derived columns:
 > Income Group (Low, Medium, High)
* Ensured proper data types and formatting for analysis.

###  DASHBOARD FEATURES
📊 Key Metrics
- 💰 Total Revenue: 1M
- 👥 Total Customers: 2,216
- 🌐 Total Web Purchases: 9,053
- 📢 Campaign Acceptance: 661
- 💵 Average Income: 52K

* KPI Cards:
    * Total Revenue
    * Total Customers
    * Total Web Purchases
    * Average Income
    * Campaign Acceptance
 
* Visuals:
    * Product Performance Analysis
    * Campaign Success Comparison
    * Income vs Web Purchases
    * Customer Profile Summary
    * Web vs Catalog Purchase Relationship
    * Channel Performance Analysis
* Interactive Slicers:
    * Country
    * Income Group

⸻

🔍 Key Insights

1. Data Quality

The dataset was largely clean with minimal missing values. Outliers were retained to preserve high-value customer insights.

⸻

2. Factors Influencing Web Purchases

* Income: High-income customers contribute the most to web purchases.
* Website Visits:
    * Purchases peak at 6–7 visits per month
    * Decline after that → indicates browsing without conversion
* Catalog Purchases:
    * Strong relationship with web purchases → shows omnichannel behavior

⸻

3. Most Successful Campaign

* One campaign significantly outperformed others in acceptance rate.
* Indicates better targeting and messaging strategy.

⸻

4. Average Customer Profile

* Average Age: 57 years
* Average Income: 52K
* Moderate spending behavior
* Engages across multiple channels

⸻

5. Best Performing Products

Top categories:

* Meat Products
* Wine
* Premium (Gold) Products

These categories drive the highest revenue.

⸻

6. Channel Performance

* Strong performance across:
    * Web
    * Store
* Lower performance observed in:
    * Catalog channel

⸻

💡 Marketing ROI Perspective

Although direct campaign costs were not available, ROI was evaluated using proxy metrics:

* Campaign acceptance (conversion rate)
* Revenue contribution
* Customer purchasing behavior

Key Takeaway:

* High-income customers and moderately active website visitors deliver the highest return potential.
* Campaigns with higher acceptance rates indicate stronger marketing effectiveness.

⸻

📈 Business Recommendations

* 🎯 Focus on high-income customer segments
* 🔁 Retarget high-visit, low-conversion users
* 📢 Replicate strategies from the most successful campaign
* 🛍 Promote high-performing product categories
* 🔗 Encourage multi-channel engagement to increase customer value

⸻
