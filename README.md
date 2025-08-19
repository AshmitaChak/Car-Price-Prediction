
## 🚗 Car Price Prediction – Exploratory Data Analysis (EDA)

Welcome to the **Car Price Prediction EDA Project** repository!
This project explores the factors influencing car prices in the U.S. market using structured exploratory data analysis techniques.

---
## 📖 Problem Statement

Geely Auto, a Chinese automobile company, is planning to enter the U.S. market by establishing local manufacturing facilities to compete with U.S. and European automakers.

To ensure success, Geely Auto wants to:

Understand the key factors affecting car prices.
Identify significant variables that influence pricing in the American automobile market.

Dataset: Car Price Prediction Dataset – Kaggle

---
## 🛠️ EDA Workflow
1️⃣ Data Loading & Initial Inspection

Import dataset from CSV.

Inspect data structure, missing values, and data types.

Generate initial summary statistics.

---
## 2️⃣ Data Cleaning

Handle missing values through imputation/removal.

Detect outliers 

Standardize categorical values for consistency.

---
 ## 3️⃣ Data Exploration

Statistical Summary: Mean, median, variance, skewness, kurtosis.

Distribution Analysis: Study price, engine size, horsepower, mileage, etc.

Correlation Analysis: Identify key correlations with car price.

---

## 4️⃣ Visual Analysis

Univariate Analysis: Histograms, boxplots, pie charts for numerical features.

Bivariate Analysis: Scatter plots & boxplots to explore relationships with price.

Multivariate Analysis: Heatmaps for feature interactions.


## 📊 Key Insights (to be updated after analysis)

Engine size, horsepower, and curb weight are strong predictors of car price.

Certain categorical features (e.g., fuel type, body style) also influence pricing.

High correlation among predictors like horsepower and engine size may require feature selection.

## 📂 Repository Structure
eda/
│
├── eda_car_price.ipynb       # Jupyter Notebook with complete EDA
├── plots/                    # Saved visualizations from EDA
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   └── price_vs_engine.png
├── README.md                 # EDA project documentation (this file)
└── datasets/                 
    └── car_price.csv         # Raw dataset from Kaggle

## 🚀 Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
