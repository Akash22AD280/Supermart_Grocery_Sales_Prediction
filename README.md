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
| **Source** | Originally published on Kaggle (Supermarket Sales), curated for this project. |
| **License** | Creative Commons Attribution 4.0 (CC BY 4.0) – please cite the original Kaggle dataset if you reuse it. |
| **File(s)** | `data/supermart_grocery_sales.csv` |

### Column dictionary 📑

| Column | Type | Description |
|--------|------|-------------|
| `Invoice_ID` | string | Unique transaction identifier |
| `Date` | datetime | Purchase date (DD‑MM‑YYYY) |
| `Branch` | category | A, B, C – three store branches |
| `City` | category | Yangon, Mandalay, Naypyitaw |
| `Customer_Type` | category | Member / Normal |
| `Gender` | category | Male / Female |
| `Product_Line` | category | 6 grocery departments (e.g. Beverages, Snacks) |
| `Unit_Price` | float | Price per unit in USD |
| `Quantity` | int | Number of units sold |
| `Tax_5%` | float | 5 % VAT collected |
| `Total` | float | Subtotal + VAT |
| `Payment` | category | Cash / Credit card / E‑wallet |
| `COGS` | float | Cost of goods sold |
| `Gross_Income` | float | Revenue – COGS |
| `Rating` | float | 1 – 10 customer rating |
| `Month` | int | Extracted feature: numerical month |
| `Year` | int | Extracted feature: 2011 … 2015 |

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

