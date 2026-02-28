# Instacart Grocery Basket Analysis — Customer Ordering Behavior

**Author:** Saleh Elhady  
**Date:** 2025-04-26  
**Role:** Data Analyst

---

## Project Summary
This project performs Exploratory Data Analysis (EDA) on a modified Instacart grocery orders dataset to uncover customer shopping patterns — including timing, reorder behavior, and product popularity. The goal is to translate raw data into actionable business insights (e.g., recommendation timing, inventory planning).

---

## Business Questions
1. When do customers make the most orders (hour/day)?
2. How often do customers reorder items?
3. What are the most popular and most reordered products?
4. How does shopping behavior differ across customer segments?

---

## Data Overview
The dataset includes:
* **instacart_orders.csv**
* **order_products.csv**
* **products.csv**
* **aisles.csv**
* **departments.csv**

*Note:* Full dataset not included due to size/licensing — sample files are provided.

---

## Key Insights
- 🕒 Peak ordering hours and days.
- 🔁 High reorder proportions for certain products.
- 🛒 Most frequent first-added products indicate preference clusters.

---

## How to Run
1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook in Jupyter
4. Run all cells

---


## Tools & Libraries
Pandas, NumPy, Matplotlib, Seaborn

---

## Future Improvements
* Build predictive model for reorder likelihood.
* Create interactive dashboard (Plotly/Streamlit).
