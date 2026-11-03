# Marketing Campaign Performance Analysis

this is an excel project exploring marketing campaign revenue, spending, orders, and lead generation by campaign, category, and day of the week.

## Table of Contents

1. [Introduction](#1-introduction)
2. [Problem Statement](#2-problem-statement)
3. [Data Sourcing](#3-data-sourcing)
4. [Data Transformation and Cleaning](#4-data-transformation-and-cleaning)
5. [Analytical Measures](#5-analytical-measures)
6. [Dashboard and Visuals](#6-dashboard-and-visuals)
7. [General Insights](#7-general-insights)
8. [Recommendations](#8-recommendation)
9. [Conclusion](#9-conclusion)
10. [Author](#10-author)

## 1. Introduction

This project uses Microsoft Excel to analyze marketing campaign performance. The dashboard presents campaign revenue, marketing expenditure, order counts, and lead generation across campaign names and categories. It also compares revenue across the days of the week.

The analysis was made using Excel PivotTables and charts, with slicers for interactive filtering.

## 2. Problem Statement

Stakeholders need a clear way to compare campaign performance across revenue, spending, orders, and lead generation. A consolidated dashboard can help them identify which categories and campaigns may need further review when planning future marketing activity.

This project explores the following questions:

- Which campaign names have the highest displayed revenue?
- How do revenue and marketing spending compare across categories?
- Which categories have the highest order counts and lead generation?
- How does revenue vary across the days of the week?


## 3. Data Sourcing

The dataset for this project was provided to me by **Quantum Analytics**.


## 4. Data Transformation and Cleaning

I performed the data inspection, cleaning, and transformation in Microsoft Excel.

During preparation, I standardized campaign names and categories to lowercase and standardized the `c_date` field to Date format. I used the resulting Excel table, named `MarketingData`, as the source for the PivotTables and dashboard.

### Data Cleaning Summary

| Metric | Value |
|---|---:|
| Original number of rows | 308 |
| Final number of rows | 308 |
| Original number of columns | 11 |
| Final number of columns | 11 |
| Completely empty rows removed | 0 |
| Completely empty columns removed | 0 |
| Duplicate rows identified and removed | 0 |
| Text inconsistencies corrected | Yes — campaign names and categories standardized to lowercase |
| Date formats standardized | Yes — `c_date` converted to Date format |
| Excel Table Name | `MarketingData` |


**view of the cleaned dataset**

<img width="1920" height="1080" alt="Screenshot (105)" src="https://github.com/user-attachments/assets/8e95c8f4-94ef-4869-a871-7f04f795976e" />




## 5. Analytical Measures

I used **Excel PivotTables** to summarize and compare the data. 
The PivotTables summarize:

- **Revenue by campaign name**
<img width="1920" height="1080" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/d7ee512c-660f-4fac-a2f1-5b1e120ec69c" />




- **Revenue by day of the week**

<img width="1920" height="1080" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/b7631ae0-7a0e-4ec5-88cc-33997e78a46f" />




- **Marketing expenditure by category**
<img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/d4746fb9-8652-4503-b710-2bedee9ddf9a" />




- **Revenue by category**
- **Order count by category**
- **Lead generation by category**

## 6. Dashboard and Visuals

The Excel dashboard includes:

- **Top Total Revenue per Campaign Name:** compares revenue across campaign names.
- **Daily Revenue:** shows revenue by day of the week, from Monday to Sunday.
- **Total Marketing Expenditure per Category:** compares marketing spending across influencer, media, search, and social.
- **Total Revenue by Category:** compares revenue across the four categories.
- **Total Number of Orders by Category:** compares order counts across categories.
- **Total Category Lead Generation:** compares lead generation across categories.
- **Category and campaign slicers:** let users filter the dashboard interactively.



<img width="1920" height="1080" alt="Screenshot (104)" src="https://github.com/user-attachments/assets/39f40a8a-a6cc-4b08-97d0-6101a7ed7c74" />


## 7. General Insights

from the analysis 

- **Campaign revenue:** `youtube_blogger` has the longest bar in the campaign revenue chart, suggesting it has the highest displayed revenue among the campaigns shown.
- **Revenue by category:** Influencer has the highest displayed revenue, followed by social, media, and search.
- **Marketing expenditure by category:** Social has the highest displayed spending, while search has the lowest.
- **Orders by category:** Influencer has the highest displayed order count, followed by social, media, and search.
- **Lead generation by category:** Social has the highest displayed lead generation, followed by influencer, media, and search.
- **Daily revenue:** Thursday has the highest displayed revenue, while Saturday has the lowest.


## 8. Recommendations


- **Compare spending with outcomes before reallocating budgets.** Social leads in displayed spending and lead generation, while influencer leads in revenue and orders. Review return on marketing spend and cost per lead to assess efficiency.
- **Review the campaigns driving influencer revenue.** Compare each campaign’s revenue with its spending, orders, and leads to see whether its performance is consistent and cost-effective.
- **Investigate the social category’s lead generation.** Determine whether its leads progress to orders and revenue. Lead volume alone does not show lead quality or conversion.
- **Review the daily revenue pattern.** Thursday is highest and Saturday lowest in the displayed chart. Check whether this pattern holds across the full dataset before changing campaign schedules.


## 9. Conclusion

This Excel project uses PivotTables and charts to present marketing performance across campaigns, categories, and days of the week. The dashboard suggests that influencer leads the displayed revenue and order comparisons, while social leads in spending and lead generation. Stakeholders can use these patterns to guide further review, with spending efficiency and lead-to-order conversion considered before making budget decisions.

## 10. Author

**OSOKAM GIFT**

- [LinkedIn]([add-your-link]
- [Portfolio](add-your-link)
- [GitHub](add-your-link)
````
