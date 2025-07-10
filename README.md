# Superstore Sales Analysis and Visualization

## Project Overview  
This project performs an exploratory data analysis (EDA) on the Superstore Sales dataset. The goal is to understand sales patterns, profit margins, and customer behaviors through statistical summaries and visualizations. This analysis provides actionable insights to improve business performance and decision-making.

---

## Dataset  
- Source: Publicly available “Superstore Sales” dataset (CSV format)  
- Contents: Sales transactions including order IDs, product categories, sales amounts, profits, shipping costs, discounts, dates, and customer regions.

---

## Objectives  
- Load and clean the data  
- Explore key metrics: total sales, profits, discounts, and order quantities  
- Visualize sales trends over time (monthly)  
- Analyze profit and sales relationships  
- Identify best-performing regions and product categories  
- Summarize key insights to guide business decisions

---

## Tools & Libraries Used  
- Python 3.x  
- Pandas (Data manipulation)  
- Matplotlib & Seaborn (Data visualization)

---

## Project Steps

### 1. Data Loading and Cleaning  
- Imported CSV file into a Pandas DataFrame  
- Converted date columns to datetime format  
- Dropped irrelevant columns like `Postal Code`

### 2. Exploratory Data Analysis  
- Summarized dataset info and checked for missing values  
- Calculated aggregate sales and profit by region and category  
- Visualized monthly sales trends using resampling  
- Examined correlations between sales, profit, discounts, and other variables

### 3. Visualization  
- Bar charts for sales and profit by region and category  
- Line charts for monthly sales trends  
- Scatter plots to study the relation between sales and profit  
- Heatmaps for correlation matrix

### 4. Insights  
- Sales and profit generally show a positive correlation, but exceptions exist  
- Some regions show higher sales but lower profit margins  
- Discounts tend to decrease profit  
- Shipping costs have a small negative impact on profitability

---

## How to Run  
1. Clone or download this repository  
2. Ensure you have Python 3 and required libraries installed (`pandas`, `matplotlib`, `seaborn`)  
3. Place the `Superstore.csv` file in the project directory  
4. Run the provided Jupyter Notebook or Python script to reproduce analysis and plots

---

## Future Work  
- Build an interactive dashboard (e.g., Streamlit, Power BI) for dynamic data exploration  
- Extend analysis to customer segmentation and sales forecasting  
- Incorporate machine learning models for predictive analytics

---

## Author  
Yasin Asadi –  Data Scientist | AI/ML Researcher | Data Analyst  

