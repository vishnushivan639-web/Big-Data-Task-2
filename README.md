# Big Data – Week 4: Task 1 & Task 2

## 📌 Project Overview

This repository contains my **Big Data Week 4 – Task 1 & Task 2** work using Python for data analysis and visualization.

The analysis is performed on the **Sample Superstore** dataset. The main focus of this week is to understand the dataset, prepare the date-related columns, analyze sales and profit across product categories, study the effect of discounts on profit, and explore relationships between numerical variables.

---

## 🎯 Objectives

The main objectives of this work are:

- Load and inspect the Superstore dataset
- Understand the structure and summary statistics of the data
- Convert date columns into proper datetime format
- Calculate delivery days
- Identify unique product categories
- Check the dataset for missing values
- Analyze total sales by category
- Visualize the distribution of sales
- Compare profit and sales across categories
- Analyze the distribution and variation of profit
- Study the relationship between discount and profit
- Calculate correlations between numerical variables
- Visualize the correlation matrix using a heatmap

---

## 🛠️ Technologies & Libraries Used

- **Python**
- **Pandas** – Data loading, cleaning, transformation, grouping, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab / Jupyter Notebook** – Development environment

---

## 📂 Dataset

The project uses the **Sample Superstore** dataset stored in an Excel file.

The dataset is loaded using Pandas:

```python
df = pd.read_excel("/content/sample_data/samplesuperstore.xlsx")
