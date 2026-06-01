# synent-task5-salesanalysis-aryanverma.
# Task 5: Sales Data Analysis - Superstore Performance

## 📋 Problem Statement
This project analyzes the business performance of a retail superstore dataset to track monthly revenue trends, identify top-selling products, and conduct a detailed profit analysis to pinpoint areas where the business might be losing money.

## 📊 Dataset Details
* **Source:** Kaggle (Sample Superstore Dataset)
* **Key Features Used:** Order Date, Sales, Profit, Category, Sub-Category, State

## ⚙️ Step-by-Step Approach
1. **Data Cleaning:** Imported the data using Pandas, handled encoding constraints, checked for missing values, and parsed date columns into structured datetime objects.
2. **Trend Analysis:** Aggregated data by Year-Month to plot continuous revenue and profit line trends.
3. **Product & Category Evaluation:** Isolated top-performing items via descending revenue metrics using Seaborn bar plots.
4. **Profit & Loss Identification:** Grouped net profits by sub-category and geographic regions to isolate unprofitable segments.

## 📈 Key Results & Insights
* **Seasonality:** A consistent sales revenue spike occurs globally towards the fourth quarter (Q4) of each fiscal year.
* **Profit Drainage:** While Categories like Technology maintain solid margins, the **Tables** and **Supplies** sub-categories are actively losing money due to unsustainable discount rates.
* **Geographic Warning:** Texas and Ohio represent the top two states accumulating significant net losses.
