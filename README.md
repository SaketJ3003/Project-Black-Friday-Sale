# Black Friday Sale Data Analysis

## Prerequisites

To run this project, ensure you have the following Python libraries installed:

- **Pandas**
- **NumPy**
- **Seaborn**

## About Black Friday

Black Friday is a shopping holiday that occurs the day after Thanksgiving. It is renowned for deep discounts and special deals on various products such as electronics, home goods, clothing, and more. Many retailers offer doorbuster deals and extended hours, making it one of the busiest shopping days of the year.

## Dataset Overview

The dataset contains **537,578 rows** and **12 columns**. Our primary goal is to perform various types of analysis to derive insights that can help businesses make informed decisions and gain a competitive edge in the market.

## Project Workflow

This project is divided into the following seven parts:

1. **Dataset Walkthrough**
2. **Analyzing Columns**
3. **Analyzing Gender**
4. **Analyzing Age & Marital Status**
5. **Multi-Column Analysis**
6. **Occupation and Products Analysis**
7. **Combining Gender & Marital Status**

### 1. Dataset Walkthrough

- Explored the dataset to understand its structure.
- Checked for null values and data types of the columns.
- Identified a significant number of null values in `Product_Category_2` and `Product_Category_3`.
- Decided to remove these columns entirely to avoid potential data loss.

### 2. Analyzing Columns

- Used `unique()` and `nunique()` functions to identify unique values in each column.
- Determined the total number of customers (`User_ID`) and products (`Product_ID`).
- Examined unique values in `Gender` and `Age` columns to understand their distributions.

### 3. Analyzing Gender

- Focused on analyzing the `Gender` column, which contains "Male" and "Female" values.
- Observed that the dataset has a higher proportion of male data compared to female data.
- Used the `groupby` function to analyze purchasing trends by gender.
- Visualized the findings using pie charts and bar plots.

### 4. Analyzing Age & Marital Status

- Analyzed the `Age` and `Marital Status` columns.
- Identified the age group with the highest number of orders and the highest purchasing amount.
- Found that 60% of the dataset is unmarried, while 40% is married.
- Presented the insights through pie charts and bar plots.

### 5. Multi-Column Analysis

- Conducted multi-column analysis to identify relationships between different variables.
- Utilized the Seaborn library for advanced visualizations.
- Focused on analyzing the `Age` and `Gender` columns using Seaborn's hue parameter.
- Demonstrated how multi-column analysis can uncover deeper insights.

### 6. Occupation and Products Analysis

- Performed data visualizations for `Occupation`, `Product_ID`, and `Product_Category_1` columns.
- Used `countplot` and bar plots to analyze purchasing patterns.
- Identified products with the maximum purchasing amounts using the `groupby` function.

### 7. Combining Gender & Marital Status

- Combined the `Gender` and `Marital Status` columns for deeper insights.
- Used Seaborn's `countplot` to visualize data distributions and identify patterns.
- Highlighted how combining columns can provide a more comprehensive view of customer behavior.

## Conclusion

This project demonstrates how exploratory data analysis (EDA) can help uncover valuable insights from a dataset. By dividing the analysis into focused sections, we derived actionable insights that can assist businesses in understanding customer behavior and optimizing their strategies.

## Visualizations

All visualizations, including pie charts, bar plots, and Seaborn plots, are included within the project to provide a clear representation of the findings.

---


