# 🛒 Retail Transactions Analysis

This project analyzes **Retail Transactions (2000 rows)** dataset to extract business insights using Python. It includes **data cleaning, one-hot encoding, visualizations, and an optional interactive dashboard**.


## 📂 Project Workflow

### 1. Data Cleaning

* Removed inconsistencies & encoded categorical variables (`Gender`, `City`, `ProductCategory`, `PaymentMode`).
* Saved the cleaned dataset as **`Retail_Cleaned.csv`**.

### 2. Exploratory Data Analysis (EDA)

**Customer Demographics:**

* Age distribution of customers
* Gender distribution
* Top 10 cities by number of customers

**Advanced Insights:**

* Average spend per customer by age group
* City-wise revenue contribution
* Heatmap: Product Category vs Payment Mode

### 3. Interactive Dashboard (Optional)

* Built using **Plotly Dash** in Python.
* KPIs included:

  * Age distribution
  * Gender distribution
  * City-wise revenue (Top 10)
  * ProductCategory × PaymentMode heatmap

---

## 📊 Key Visuals

1. **Age Distribution** (Histogram)
2. **Gender Distribution** (Bar/Pie chart)
3. **City-wise Revenue Contribution** (Bar chart)
4. **Revenue Heatmap**: ProductCategory vs PaymentMode

---

## 📌 Tools & Libraries

* **Python** (pandas, matplotlib, seaborn, plotly, dash)

