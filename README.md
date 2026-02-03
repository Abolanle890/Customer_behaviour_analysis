# Customer Behaviour Analysis

## Table of Content
- [project overview](#project-overview)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Data source](#data-source)
- [Dataset Overview](#dataset-overview)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Conclusion](#conclusion)


## project overview

This project analyzes customer income, spending, and payment behavior across multiple cities to understand how different customer segments earn, spend, and transact. The objective is to generate practical insights to support business decisions, including customer segmentation, marketing strategy, and payment optimization.

The analysis focuses on identifying high-value customer groups, understanding spending priorities, and highlighting preferred payment methods that can be leveraged to improve customer engagement and revenue outcomes.


## Key Insights

- Income Spending Imbalance: Several professional groups show spending levels that significantly exceed their reported average income, indicating potential overconsumption or reliance on credit.

- Disproportionate Gaps: In some segments, average spending is multiple times higher than average income (e.g., spending totals around 207M compared to income of approximately 53.1M), highlighting an unsustainable financial gap.

- Variation by Occupation: While income levels differ across occupations, spending behavior does not scale proportionally, suggesting that earning more does not necessarily lead to more controlled spending.

- City-Level Patterns: Overspending tendencies are more pronounced in certain cities, indicating that location may influence cost-of-living pressures or lifestyle-driven consumption.

- Payment Behavior Insight: High usage of digital payment methods may be enabling easier spending without immediate income visibility, contributing to the observed spending–income gap.

## Business Recommendations

- Highlight Financial Risk Signals: Use income-versus-spending comparisons to flag customer segments and cities where spending consistently exceeds income, supporting early identification of financial stress patterns.

- Support Financial Planning Insights: The findings can inform the design of budgeting tools, financial literacy programs, or policy discussions focused on improving personal financial management.

- City-Level Cost Analysis: Policymakers and researchers can combine these insights with cost-of-living data to better understand how location impacts consumer financial behavior.

- Payment Behavior Monitoring: High reliance on digital payment methods suggests the need for clearer spending visibility, such as monthly summaries or alerts that help individuals track expenses relative to income.

- Data-Driven Research Use: The dataset can serve as a foundation for further academic or policy-oriented research into income sustainability, consumer debt risk, and urban spending behavior.

## Data source

The dataset is a simulated customer spending and income dataset shared through a professional network and used strictly for analytical and educational purposes.

## Dataset Overview
The project utilizes two datasets:

- Customer Demographics (dim_customers.xlsx): Includes age group, city, occupation, gender, marital status, and average income for 4,000 customers.
- Customer Spending Data (fact_spends.xlsx): Captures 864,000 records of monthly spending by customers across categories, payment types, and transaction values.


## Tools 

- EXCEL - Data cleaning 
- POWER BI - Data Analysis & Visualization 

  ## Data Preparation

Data preparation was completed in Microsoft Excel to ensure reliability and analytical accuracy. Key steps included:

- Removing duplicate customer records to maintain a one-to-one customer identifier

- Validating spending values to ensure all transactions reflected positive amounts

- Standardizing text fields such as occupation and city names for consistency

- Verifying links between customer records and transaction data to ensure accurate analysis at the customer level

These steps ensured the dataset was consistent, complete, and suitable for business analysis.


### Conclusion
This analysis provides a city-level view of how income relates to actual spending behavior across different professional groups. The results reveal significant gaps between what customers earn and what they spend, pointing to potential financial sustainability risks rather than revenue opportunities. By focusing on income–spending alignment, this project demonstrates how data can be used to assess consumer financial health, identify systemic overspending patterns, and support more informed economic and behavioral insights.
