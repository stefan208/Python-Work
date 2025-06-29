# 📊 Financial & Operational KPI Data Cleaning, Merging, Preparation & Trend Analysis Pipeline

This project builds a comprehensive data pipeline that loads, merges, cleans, and analyzes financial and operational KPI data.  
It performs advanced trend analysis on revenue, providing actionable insights for financial and operational performance monitoring.

---

## 🎯 Key Objectives

- Load and merge financial and operational KPI data by date.  
- Clean and prepare the combined dataset: standardize column names, remove duplicates, sort chronologically, and fill missing values.  
- Calculate key trend metrics on revenue, including Compound Annual Growth Rate (CAGR) and Year-over-Year (YoY) growth.  
- Apply linear regression to identify long-term revenue trends and assess model fit (R²).  
- Decompose the revenue time series into trend, seasonal, and residual components for deeper insights.  
- Visualize revenue and decomposition components to support strategic decision-making.

---

## 📂 Expected Data Structure

The data should include:

| Column           | Description                 |
|------------------|-----------------------------|
| `date`           | Monthly date                |
| `revenue`        | Revenue and other financial KPIs       |
| Operational KPIs | Operational KPIs           |

---

## ▶️ Code Structure

- **Data Loading:** Reads financial and operational KPI data.  
- **Data Cleaning & Merging:** Standardizes, merges on `date`, removes duplicates, sorts, and fills missing values.  
- **Trend Analysis Functions:**  
  - CAGR calculation  
  - YoY growth calculation  
  - Linear regression for trend slope and R²  
- **Time Series Decomposition:** Splits revenue into trend, seasonal, and residual components.  
- **Visualization:** Plots revenue and decomposed components for interpretation.

---

## 🛠 Dependencies

This project requires the following Python libraries:

- pandas  
- numpy  
- scikit-learn  
- statsmodels  
- matplotlib

You can install them using:

```bash
pip install pandas numpy scikit-learn statsmodels matplotlib

