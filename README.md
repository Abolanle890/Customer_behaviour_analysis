# Customer Behaviour Analysis

## Table of Content
- [project overview](#project-overview)
- [Data source](#data-source)
- [Dataset Overview](#dataset-overview)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Key Insights](#key-insights)
- [Recomendations](#recomendations)
- [Conclusion](#conclusion)


### project overview
----
This project explores a customer payment dataset to uncover purchasing behavior, spending trends, and the financial habits of various occupations. The goal is to derive actionable insights to support data-driven decision-making in consumer analytics.

![Image Alt](https://github.com/Abolanle890/Customer_behaviour_analysis/blob/89b9c1c3c590b623ffaefbc53c8b37346486a067/Bar%20chart.png)

![Image Alt](https://github.com/Abolanle890/Customer_behaviour_analysis/blob/768d528ccd49c5749c8acf4fd42dc874c9bc0737/Pie%20chart.png)

### Data source

The datasets were shared via a LinkedIn connection.[Download Here](https://github.com/Abolanle890/Customer_behaviour_analysis/blob/cc7ae1950d6714461c38de8d9410c8d987e1fed1/Customer_behaviours.xlsx)


### Dataset Overview
The project utilizes two datasets:

- Customer Demographics (dim_customers.xlsx): Includes age group, city, occupation, gender, marital status, and average income for 4,000 customers.
- Customer Spending Data (fact_spends.xlsx): Captures 864,000 records of monthly spending by customers across categories, payment types, and transaction values.


### Tools 

- EXCEL - Data cleaning 
- POWER BI - Data Analysis & Visualization 

  ### Data Cleaning
Data cleaning was performed in Microsoft Excel to ensure the dataset is accurate, consistent, and ready for analysis. The following steps were undertaken:

- Removing Duplicate Customer IDs
- Ensured each customer had a unique identifier.
- Ensuring Positive Integer Values for Spending
- Checked all spending values to ensure they were positive integers.
- Standardizing Text Entries
- Applied title casing to text entries like occupation and city names for consistency.
- Verifying Referential Integrity Between Customers and Transactions
- Cross-checked customer IDs with transaction records to ensure proper links between customers and their transactions.

### Key Insights
- Top Spending Occupations: Salaried IT employees and business owners had the highest average monthly spend.
- High-Income vs. High-Spending: Occupations with the highest average income did not always correlate with the highest spending.
- Popular Categories: Bills, Groceries, electronics, and health & wellness were the most frequently purchased categories.
- Preferred Payment Methods: Credit cards and UPI were the most common payment types.
- Behavior by Occupation: Distinct differences in spending patterns were observed across various occupational groups.

### Recomendations
-  Create targeted marketing campaigns or special offers for these high-spending occupations. Tailor promotions that align with their interests, such as technology or business-related products, to maximize engagement and revenue.
-  Segment customers by occupation and create personalized offers. For instance, offer health-related discounts for healthcare professionals, or tech-related products for IT professionals. Personalization can increase customer satisfaction and loyalty.
-  Implement automated systems for fraud detection that flag any unusual spending patterns or outliers. Additionally, regularly audit the data to ensure it remains clean and reliable for future analysis.
-  Invest in marketing campaigns that focus on these high-demand categories. Offer bundle deals or discounts on popular items within these categories to further increase customer spending
-  Strengthen the mobile payment experience by enhancing UPI functionality and offering mobile-first payment options. Streamlining the checkout process will improve conversion rates, especially for tech-savvy customers.

### Conclusion
- Analyze the link between occupation and spending/income
- Understand consumer trends across cities and age groups
- Visualize key business metrics for decision-making

