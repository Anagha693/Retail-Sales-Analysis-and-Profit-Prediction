# Retail Sales Analysis and Profit Prediction

## Project Overview

This project focuses on analyzing retail sales data to uncover business insights and build machine learning models for profit prediction. The analysis was performed using Python for data preprocessing, exploratory data analysis (EDA), and machine learning, while Power BI was used for interactive dashboard visualization.

The project aims to understand sales trends, profitability patterns, customer behavior, and the impact of discounts on profit.

---

## Problem Statement

Retail businesses generate large volumes of transactional data daily. Understanding factors affecting sales and profitability is important for improving business decisions, inventory management, and pricing strategies.

This project aims to:

- Analyze retail sales trends and profit patterns
- Identify factors affecting profitability
- Explore the relationship between discounts and profit
- Build machine learning models to predict profit
- Create an interactive business dashboard for visualization

---

## Dataset Information

- Dataset: Sample Superstore Dataset
- Source: Kaggle
- Total Records: 9,994
- Features: 21 columns

### Important Features

- Order Date
- Ship Date
- Category
- Sub-Category
- Region
- Sales
- Quantity
- Discount
- Profit

---

## Tools and Technologies Used

### Programming & Analysis
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

### Visualization
- Power BI

---

## Project Workflow

### 1. Data Cleaning
- Checked missing values
- Converted date columns
- Removed unnecessary columns
- Created Month-Year features
- Handled data formatting issues

### 2. Exploratory Data Analysis (EDA)
- Sales analysis by category and region
- Profit trend analysis
- Discount vs profit analysis
- Monthly sales trend visualization
- Correlation analysis

### 3. Feature Engineering
- Extracted Month and Year from order date
- Encoded categorical variables
- Selected important business features

### 4. Machine Learning
Models used:
- Linear Regression
- Random Forest Regressor
- Hyperparameter Tuned Random Forest

### 5. Model Evaluation
Evaluation metrics used:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### Model Comparison

| Model | MAE | RMSE | R² Score |
|------|------|------|------|
| Linear Regression | 67.79 | 282.42 | -0.645 |
| Random Forest | 25.11 | 220.00 | 0.001 |
| Tuned Random Forest | 25.35 | 217.41 | 0.025 |

---

## Key Insights

- Technology category generated the highest sales
- Higher discounts often reduced profitability
- Certain regions contributed more profit than others
- Sales showed strong variation across categories and time periods
- Random Forest performed better than Linear Regression for this dataset

---

## Power BI Dashboard

The project also includes an interactive Power BI dashboard featuring:

- KPI Cards
- Sales by Category
- Profit by Region
- Monthly Sales Trend
- Discount vs Profit Analysis
- Interactive Filters

---

## Repository Structure

```text
Retail-Sales-Analysis-and-Profit-Prediction
│
├── notebooks/
│   └── retail_sales_analysis.ipynb
│
├── dashboard/
│   └── retail_dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
├── README.md
└── requirements.txt