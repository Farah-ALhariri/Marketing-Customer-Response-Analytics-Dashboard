Retail Marketing Performance & Customer Analytics


Project Overview
This repository contains a 10-page Power BI dashboard analyzing retail performance across a customer base of 2,021 individuals. The project evaluates $1.14M in revenue and 25.4K orders, focusing on the intersection of customer demographics and marketing campaign effectiveness.


Data Observations
-▫️Revenue Drivers: Product analysis shows Wine is the primary revenue source (54%), followed by Meat products (29%).
-▫️Purchasing Behavior: A correlation heatmap identifies strong cross-selling potential between Meat, Fish, and Fruits. Conversely, Wine purchases show lower correlation with other categories, suggesting it acts as a standalone driver.
-▫️Channel Distribution: 67% of purchases occur in-store, despite a significant volume of website traffic, highlighting an opportunity to improve online conversion paths.
-▫️Customer Value: High-income households and those without children represent the highest revenue-per-customer segments.
-▫️Marketing Efficacy: Historical campaign analysis shows a 28% overall conversion rate (CVR). Recent campaign performance tracked at 15.4%, with a significant segment (1,458 customers) identified as "Non-Responders."

Report Structure
The dashboard is divided into the following analytical views:
1. Executive Summary: High-level KPIs and revenue share by category/channel.
2. Revenue & Spending: Performance tracking across shopper deal categories.
3. Customer Segments: Distribution by education, marital status, and tenure.
4. Behavioral Analysis: Recency, frequency, and website visit metrics.
5. Value Profiling: Identifying high-value demographic clusters.
6. Campaign Performance: Historical CVR and response segmentation.
7. CVR vs. Spend: Analyzing the relationship between average spend and conversion likelihood.
8. Product Correlation: Statistical heatmap of cross-category purchasing habits.
9. Household Insights: Performance filtered by family size and children in the home.
10. Income Analysis: Scatter plot distribution of income versus total expenditure.


Technical Methodology
▫️ETL Process: Data cleaning and standardization performed in Power Query, including custom binning for age and income brackets.
▫️Modeling: Implementation of a star schema to support cross-filtering across 10 distinct report pages.
▫️DAX Measures: Developed custom logic for CVR percentages, revenue-per-capita, and engagement segmentation (Super Responders vs. Non-Responders).

