# Supermart_Grocery_Sales_Prediction

A machine learning project to predict sales based on historical transaction data using regression techniques.

## 🔍 Project Overview

This notebook explores:
- Data preprocessing
- Feature engineering
- Linear Regression vs. Random Forest Regressor vs. XGBoost
- Model performance evaluation

## 📊 Methodology

- **Models used**: Linear Regression, Random Forest Regressor, XGBoost
- **Evaluation Metrics**: R² Score, Mean Squared Error
- **Key Findings**: Random Forest outperformed Linear Regression in prediction accuracy.

## 📂 Dataset

| Property | Details |
|----------|---------|
| **Name** | Supermart Grocery Sales |
| **Records** | 8 415 rows × 17 columns *(≈ 1.5 MB CSV)* |
| **Time span** | Jan 2011 – Dec 2015 |
| **File(s)** | `data/supermart_grocery_sales.csv` |

### Column dictionary 📑

| Column Name     | Data Type | Description                                              |
| --------------- | --------- | -------------------------------------------------------- |
| `Order ID`      | String    | Unique identifier for each order                         |
| `Customer Name` | String    | Name of the customer placing the order                   |
| `Category`      | Category  | Main product category (e.g., Furniture, Office Supplies) |
| `Sub Category`  | Category  | Subcategory of the product (e.g., Chairs, Binders)       |
| `City`          | Category  | City where the order was placed                          |
| `State`         | Category  | State where the city is located                          |
| `Region`        | Category  | Geographical region (e.g., East, West, South, Central)   |
| `Order Date`    | DateTime  | Date of purchase in the format DD-MM-YYYY                |
| `Sales`         | Float     | Sales value in USD                                       |
| `Discount`      | Float     | Discount applied on the order                            |
| `Profit`        | Float     | Net profit earned from the order                         |
| `month_no`      | Integer   | Numerical month (1–12) extracted from `Order Date`       |
| `Month`         | String    | Full name of the month (e.g., January, February)         |
| `year`          | Integer   | Extracted year of the order (e.g., 2015, 2016)           |


> **Tip:** If you add or drop columns during preprocessing, keep this table updated so new contributors know exactly what to expect.

## 📝 Project Summary

This project, **Supermart Grocery Sales Prediction**, applies machine learning techniques to forecast sales based on historical supermarket transaction data. The goal is to support better decision-making in inventory planning, customer segmentation, and revenue optimization.

We explore and compare two regression models: **Linear Regression** and **Random Forest Regressor**, using real-world retail data. The Random Forest model demonstrated significantly better performance, achieving an R² score above 0.99 on cross-validation.

### 🔑 Key Highlights

- ✅ End-to-end pipeline: Data cleaning, feature engineering, model training & evaluation
- 📈 Achieved **high predictive accuracy** with Random Forest
- 📊 Compared models using **Mean Squared Error** and **R² Score**
- 🔍 Identified **top sales drivers** using feature importance
- 📁 Well-structured, reproducible notebook with modular code

This repository includes the full notebook, dataset description, required libraries, and project documentation for easy reproduction or extension.

