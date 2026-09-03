# 📊 Store Sales Time Series Analysis

## 📌 Project Overview

This project analyzes historical store sales data using Python and time series analysis techniques.

The main objective is to understand monthly sales trends, identify fluctuations and possible seasonal patterns, and generate business insights that can support better sales and inventory planning.

---

## 🎯 Objectives

- Analyze historical store sales data.
- Convert order dates into a proper datetime format.
- Aggregate sales on a monthly basis.
- Identify sales trends and fluctuations over time.
- Visualize monthly sales performance.
- Identify high and low sales periods.
- Generate meaningful business recommendations.
- Prepare the data for future sales forecasting.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Time Series Analysis

---

## 📂 Dataset

The dataset contains store transaction information, including:

- Order Date
- Sales
- Other order and store-related information

The `Order Date` column was converted into datetime format to perform time-based analysis.

---

## 🔄 Data Preparation

The following data preparation steps were performed:

1. Loaded the dataset using Pandas.
2. Examined the dataset structure and columns.
3. Converted `Order Date` into datetime format.
4. Set `Order Date` as the time-series index.
5. Resampled the data on a monthly basis.
6. Calculated total monthly sales.
7. Reset the index for further analysis and visualization.

## Conclusion
The Store Sales Time Series Analysis provided valuable insights into the company’s sales performance and monthly sales trends. By cleaning and preparing the sales data, converting the Order Date into a proper datetime format, and aggregating sales on a monthly basis, the analysis helped identify changes and patterns in sales over time.


)

monthly_sales.head()
