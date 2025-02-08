Grocery Store Sales Analysis

Overview

This project focuses on optimizing grocery store sales, particularly for fresh produce, by leveraging data science techniques. Our goal is to maximize sales while minimizing waste through demand forecasting and pricing optimization.

Problem Statement

Grocery stores deal with perishable inventory that must be carefully managed to reduce losses and maximize revenue. By analyzing historical sales trends, forecasting future demand, and identifying key pricing patterns, we can help grocery stores make data-driven decisions on pricing and inventory management.

Approach

1. Data Cleaning & Preprocessing

Loaded grocery sales data from food data.csv.

Handled missing values using median imputation.

Converted date columns to datetime format for proper time-series analysis.

2. Exploratory Data Analysis (EDA)

Identified seasonal trends in grocery sales.

Visualized category-wise sales over time.

Scaled the data to ensure consistency in analysis.

3. Forecasting Future Sales

Implemented a SARIMA time-series model to predict future demand for vegetables, considering seasonality.

Extended the forecast for one year ahead to assist in better inventory planning.

Evaluated the accuracy of the forecast and adjusted model parameters as needed.

4. Pricing Optimization

Built a regression-based pricing model to analyze the impact of different factors on produce sales.

Used RMSE as the evaluation metric to assess the model’s effectiveness.

5. Final Insights & Additional Metrics

Computed 7-day and 30-day moving averages for trend analysis.

Analyzed total category-wise sales to identify high-performing product categories.

Generated visual reports to summarize findings.

Findings

Seasonal demand variations significantly affect produce sales, especially vegetables.

The SARIMA model forecasts a stable trend for vegetable sales, helping optimize inventory purchases.

The pricing model suggests that minor adjustments in pricing strategies can improve sales without causing excess inventory.

Certain categories like "All Foods" and "Commercially Prepared Items" dominate total sales, offering strategic pricing opportunities.

Conclusion

This project provides actionable insights to improve inventory and pricing decisions for grocery stores. By leveraging data science, we can reduce waste, increase revenue, and create a more efficient supply chain for perishable goods
