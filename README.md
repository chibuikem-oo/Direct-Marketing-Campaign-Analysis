## Project Overview

This project presents a data-driven analysis of a direct marketing campaign conducted by a Portuguese banking institution. The campaign used phone calls as a medium to promote term deposits. This analysis aims to uncover actionable insights that can guide the bank's future marketing strategies. Using Microsoft Excel, an interactive dashboard was created to explore customer demographics, financial behavior, and campaign performance.

## Objectives

1. **Customer Demographics**: Understand the customer base's age, job type, and loan status distribution.
2. **Financial Behavior**: Examine average balances across age groups and loan status.
3. **Monthly Trends**: Identify trends in average customer balances by month.
4. **Campaign Performance**: Analyze campaign success by outcome type and contact channel.
5. **Recommendations**: Provide actionable insights to improve future marketing outcomes.

## Data Sources and Tools Used

* **Dataset**: Portuguese Bank Marketing Campaign Dataset (cleaned and prepared for Excel analysis).
* **Tool**: Microsoft Excel – Used for data cleaning, pivot table creation, visualizations, and dashboard development.

## Exploratory Data Analysis (EDA)

### Data Description

Key columns in the dataset include:

* **Age**, **Job Type**, **Loan Status**
* **Balance**: Customer’s average yearly balance.
* **Contact Method**: Method used for outreach (cellular, telephone, unknown).
* **Campaign Outcome**: Result of the marketing call (success, failure, unknown, other).
* **Month of Contact**

### Methodology

* Cleaned and categorized data by age group and loan status.
* Created pivot tables for campaign outcomes, balances, and customer demographics.
* Visualized key metrics using bar and pie charts.
* Developed a unified, interactive dashboard using slicers and dynamic charts.

### Key Insights & Interpretation

#### 1. **Customer Demographics**

* **Age Group Distribution**: Adults make up the majority (53%), followed by young adults (30%).
* **Loan Status**: 85% of customers do not have a loan; only 15% do.
* **Job Type Distribution**: The most common job types are admin, blue-collar, and technician roles.

#### 2. **Financial Behavior**

* **Average Balance by Age Group**: Seniors have the highest average balance (€1,514), while young adults have the lowest (€1,346).
* **Impact of Loans**: Customers without loans have a higher average balance (€1,521) compared to those with loans (€917).

#### 3. **Monthly Trends**

* The highest average balances occurred in December (€3,567), followed by November (€2,603) and October (€2,739).
* A notable dip appears in July (€789), which may reflect seasonal patterns.

#### 4. **Campaign Performance**

* **Outcome Distribution**: The majority of the outcomes are “unknown” (82%), with a small success rate (3%).
* **Channel Effectiveness**: Most successful contacts occurred via cellular, while telephone and “unknown” channels showed low effectiveness.
* **Monthly Contact Pattern**: The most outreach occurred from March to May, yet success rates remained low, pointing to inefficiencies in contact timing.

## Data Visuals

The Excel dashboard includes:

* **Bar Charts**: Age group distribution, average balances, campaign outcomes.
* **Pie Charts**: Loan status and campaign outcome shares.
* **Line Chart**: Monthly balance trend.
* **Slicers**: To filter views by age group, month, job type, and channel.


### **Dashboard Preview**

![image](https://github.com/user-attachments/assets/44bb5a03-ed2b-4ae2-9b02-e48db23e14c0)


This interactive dashboard provides a clear visual summary of key metrics from the dataset. It enables stakeholders to explore customer segments, financial trends, and campaign effectiveness dynamically using Excel's slicers and charts. The design supports real-time exploration of insights to guide decision-making.


## Summary

The Portuguese Bank's marketing campaign reveals valuable insights into customer profiles and campaign performance. While the majority of outreach was targeted at adults without loans, the success rate remained low, emphasizing the need for better audience segmentation and contact strategies.

### Recommendations

1. **Refine Target Audience**: Focus on seniors and customers without loans, who hold the highest balances.
2. **Optimize Contact Channels**: Prioritize cellular over telephone contact methods.
3. **Improve Data Collection**: Reduce the high rate of “unknown” outcomes to ensure clearer analysis.
4. **Seasonal Strategy**: Align future campaigns with months showing higher average balances (October–December).
5. **Job Type Targeting**: Concentrate efforts on job types with historically higher balances or better response rates.

### Conclusion

This project demonstrates how data analytics can support more effective marketing decisions. By leveraging Excel for visualization and insight generation, the bank can identify opportunities to optimize contact strategies, enhance segmentation, and increase campaign ROI.

### Limitations

* **Outcome Ambiguity**: A large proportion of “unknown” outcomes skews campaign effectiveness analysis.
* **Data Currency**: The dataset represents historical campaigns and may not reflect current customer behavior.
* **Categorical Granularity**: Some job types and age groups were generalized, which could mask deeper patterns.
