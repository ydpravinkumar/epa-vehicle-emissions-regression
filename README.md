# 🚗 EPA Vehicle Emissions Regression Analysis

## 📌 Project Overview

This project utilizes EPA vehicle emissions data from the past decade to perform a comprehensive **Exploratory Data Analysis (EDA)** and prepare a clean dataset for **regression modeling**. The objective is to understand how different features, such as vehicle displacement and emissions coefficients, vary across time and manufacturers, and to create a reliable dataset for predicting fuel efficiency and emissions performance.

## 📂 Contents

* Jupyter Notebook: `EPA_Vehicle_Emissions_EDA.ipynb`
* Cleaned & Stacked Dataset: `epa_cleaned_data.csv`
* Visualizations: `/visualizations/`
* Summary Report: `summary_report.md` (this file)

## 📈 Data Source

Data was sourced from the **U.S. Environmental Protection Agency (EPA)**, which includes:

* Vehicle emissions test results
* Engine specifications
* Emissions coefficients (e.g., Set Coef A, B, C)
* Fuel economy (mpg estimates)
* Model year, manufacturer info

Years included: **2015 through 2024**

## 📁 Folder Structure

```
/epa-vehicle-regression/
│
├── data/
│   ├── EPA_2015.csv
│   ├── ...
│   └── EPA_2024.csv
│
├── notebooks/
│   └── EPA_Vehicle_Emissions_EDA_Part1.ipynb
│
│
│
├── summary_report.md
└── README.md
```

## 🎯 Objectives

* Load, explore, and clean EPA emissions datasets from 2015–2024.
* Perform EDA to identify key trends and anomalies.
* Standardize and prepare a unified dataset for regression.
* Analyze patterns in fuel efficiency, emissions, and manufacturer differences.
* Provide actionable insights for model development.

## 🛠️ Tasks

### Part 1: Exploratory Data Analysis (EDA)

1. **Initial Summary Statistics**
2. **Check Structure & Missing Values**
3. **Standardize Column Names**
4. **Distribution Trends Over Time**
5. **Correlation Analysis**
6. **Combine Multi-Year Datasets**
7. **Standardize Continuous Variables**
8. **Temporal Trends by Model Year**
9. **Manufacturer-wise Analysis**
10. **Create Final Clean Dataset for Modeling**

## ⚠️ Limitations

* Incomplete or missing data in some years and columns.
* Assumption-based imputation for some missing values.
* Possible inconsistencies in manufacturer naming conventions.
* Model generalizability may be limited without additional external validation.

## 📄 License

This project is licensed under the **MIT License**. EPA datasets are publicly available and used under the **Open Government License**.
