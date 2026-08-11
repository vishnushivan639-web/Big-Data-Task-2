# 📊 Big Data Analysis – Task 2


---

## 📌 Project Overview

This project is part of my **Big Data Task 2

In this project, I worked with a **Superstore dataset** and performed different data analysis and visualization operations using Python.

The main purpose of this project is to understand the dataset, prepare the data for analysis, explore important columns, and visualize different patterns related to **Sales, Profit, Category, Discount, and Delivery Days**.

This project helped me understand how raw business data can be processed and converted into meaningful information using Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**.

The complete work was developed and tested using a **Google Colab / Jupyter Notebook environment**.

---

# 🎯 Objectives of the Project

The main objectives of this project are:

- To load the Superstore dataset using Python.
- To understand the structure of the dataset.
- To inspect the first few records.
- To understand column names and data types.
- To generate basic statistical information.
- To convert date columns into the correct datetime format.
- To calculate the number of delivery days for each order.
- To identify the different product categories.
- To check whether the dataset contains missing values.
- To calculate total sales for each category.
- To visualize sales by category.
- To understand the distribution of sales values.
- To analyze profit by category.
- To compare sales distribution across categories.
- To understand the distribution of profit.
- To analyze profit variation across different categories.
- To study the relationship between discount and profit.
- To calculate correlations between numerical variables.
- To visualize the correlation matrix using a heatmap.

---

# 🛠️ Technologies Used

The following technologies and Python libraries were used in this project:

### 🐍 Python

Python is the main programming language used for data loading, preprocessing, analysis, and visualization.

### 🐼 Pandas

Pandas is used for:

- Loading the Excel dataset
- Data inspection
- Data preprocessing
- Grouping data
- Date conversion
- Creating new columns
- Handling and analyzing tabular data

### 🔢 NumPy

NumPy is imported for numerical operations and working with numerical data.

### 📈 Matplotlib

Matplotlib is used to create visualizations such as:

- Bar charts
- <img width="721" height="560" alt="image" src="https://github.com/user-attachments/assets/0c2c852a-c132-4dba-a4dc-7901b88e1ea8" />

- Sales Distribution
- <img width="704" height="470" alt="image" src="https://github.com/user-attachments/assets/c6308641-57b4-4e0a-8021-d1078a80b186" />

- Basic data plots

### 📊 Seaborn

Seaborn is used for statistical visualizations such as:

- Bar plots
- <img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/13f0708e-b61a-45e7-b346-3678d8556e76" />
- <img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/9c705cf6-d6b6-4317-a4a4-2f8169b99ccb" />

- Box plots
- <img width="592" height="416" alt="image" src="https://github.com/user-attachments/assets/432e45ab-9bb1-4f06-b520-8fb4d0c1fbd4" />
- <img width="592" height="455" alt="image" src="https://github.com/user-attachments/assets/59fbdc59-662d-43e8-97be-1925b99bee0c" />

- Scatter plots
- <img width="592" height="455" alt="image" src="https://github.com/user-attachments/assets/a20ecde7-32af-4fc3-9d9e-36d88bba41e6" />

- Correlation heatmaps
- <img width="609" height="518" alt="image" src="https://github.com/user-attachments/assets/e6132e34-2a2d-4e42-ba9b-52420c8092fd" />


### ☁️ Google Colab

The project was developed using Google Colab, which provides a notebook environment for executing Python code and displaying analysis results.

---

# 📂 Dataset

The project uses a **Sample Superstore Excel dataset**.

The dataset is loaded into a Pandas DataFrame using:

```python
df = pd.read_excel("/content/sample_data/samplesuperstore.xlsx")
