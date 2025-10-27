# 📊 Task 5: Data Analysis on CSV Files

## 🎯 Objective
The goal of this task is to perform **data analysis on sales data using Pandas**. The analysis includes exploring the dataset, understanding its structure, and visualizing different insights using **Matplotlib** and **Seaborn**.  

This helps in understanding sales patterns, category-wise performance, and overall data trends.

---

## 🧰 Tools & Libraries Used
- **Python**
- **Pandas** – for data loading, manipulation, and analysis  
- **Matplotlib** – for creating basic visualizations  
- **Seaborn** – for enhancing chart aesthetics  
- **Jupyter Notebook / Google Colab** – for code execution and visualization  

---

## 📂 Dataset
The dataset used is an **open-source CSV file** hosted on GitHub:  
🔗 [2014 US Cities Dataset](https://raw.githubusercontent.com/plotly/datasets/master/2014_us_cities.csv)

This dataset contains information about **US cities**, including details like:
- City name  
- State  
- Population  
- Area  
- Rank  
- Density  

> Note: This dataset is used as a sample. If columns like “Category”, “Sales”, or “Profit” are missing, the code intelligently skips those analysis parts.

---

## 🧾 Steps Performed

### 1️⃣ Importing Libraries
Imported **Pandas**, **Matplotlib**, and **Seaborn** to perform data analysis and visualization.

### 2️⃣ Loading the Dataset
Loaded the CSV file directly from an online URL using:
```python
pd.read_csv(url)
