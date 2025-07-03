# 📊 Day 3: Interactive Charts & Time Series Analysis

Welcome to **Day 3** of the Data Analytics & Visualization Workshop!  
This session focuses on building **interactive data visualizations** using **Plotly**, and performing **time series analysis** including rolling statistics and forecasting using **ARIMA**. 
We will also cover how to interpret these visualizations and insights effectively. 

## 📂 Contents

- 🔗 [Presentation Slides](https://docs.google.com/presentation/d/1Xdzmk3HUkLBct3FdukY2FQRTuz7MloJ9jZdVLL96J_M/edit?usp=sharing)   
- 📁 [Dataset for Practice](./datasets/retail_sales.csv)  
- 🧰 [Installation Guide for Tools](./installation-guide.md)  
- 📑 [Case Study Template](#case-study-template)  
- 💻 [Hands-on Tasks](#hands-on-tasks)  

---

## 🧰 Installation Guide

### 📦 Required Tools

1. **Python 3.8+**
2. **Jupyter Notebook or VS Code**
3. **Power BI Desktop** (for Windows users)
4. Python Libraries:
   
   ```bash
   pip install matplotlib seaborn plotly pandas statsmodels
    ```

## 📊 Dataset Information

**File:** `retail_sales.csv`
**Description:** A sample dataset showing weekly sales data across multiple regions and product categories.
* **Columns Include:**

  * `Date` (YYYY-MM-DD)
  * `Product_Category`
  * `Region`
  * `Weekly_Sales`
  * `Discount`


## 📑 Case Study Template

Please use the following structure to guide your **faculty-evaluated case study analysis**:

### 📝 Title: \[e.g. Regional Sales Trend Forecasting]

#### 1. **Objective**

> State the aim of your analysis (e.g., detect sales trends, forecast next 4 weeks, analyze discount effects).

#### 2. **Dataset Overview**

> Brief description of dataset, number of rows/columns, missing values handled, key variables selected.

#### 3. **Visualization Insights**

* Sales trend over time (line plot)
* Regional comparison (bar chart)
* Category-wise analysis (pie/donut chart or stacked bar)
* Discount vs. sales (scatter plot)

#### 4. **Time Series Analysis**

* Convert date column to datetime
* Resample by month/week
* Rolling average (20-day, 50-day)
* Decomposition (trend, seasonality)
* ARIMA forecast plot

#### 5. **Interpretation**

> Write 4–5 lines interpreting your visualizations and forecasts.

#### 6. **Conclusion**

> Summarize business impact or potential actions from the insights.


## 💻 Hands-On Tasks

### 🔹 Interactive Visualizations using Plotly

* Convert a Seaborn chart to interactive Plotly
* Add hover info (e.g. product name, region)
* Add dropdown to filter by year/category

### 🔹 Time Series Forecasting

* Load historical data
* Apply rolling mean (20-day, 50-day)
* Plot decomposition (statsmodels)
* Fit ARIMA and predict next 4 weeks


## 👨‍🏫 Evaluation Checklist

* ✅ Clean code structure (Jupyter or script)
* ✅ Use of Plotly and matplotlib
* ✅ Time Series forecasting with ARIMA
* ✅ Report (PDF or Markdown) summarizing insights
* ✅ Final interpretation based on charts and predictions


📩 **Submit your notebook + report** to the submission form provided by the volunteers.

Happy Visualizing! 🎨📈
