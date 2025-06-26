# 🛒 E-commerce Customer Analysis

This project explores and analyses an e-commerce transactions dataset using Python and SQL. It spans data cleaning, exploratory analysis, customer segmentation, and product affinity insights to support data-driven marketing and sales strategy.

## 📂 Dataset Overview
The dataset contains over **500,000+** rows of customer transactions including:
- Invoice numbers  
- Product details  
- Purchase dates  
- Quantities and prices  
- Customer IDs and country  

## 🔧 Tools & Libraries
- **Python**: pandas, numpy, matplotlib, seaborn  
- **SQL**: sqlite3 for basic queries  
- **Jupyter Notebook** for analysis and presentation  

## 🧪 Project Structure

### 📊 Part 1 – Exploratory Data Analysis (EDA)
- Cleaned missing values and filtered invalid transactions  
- Analysed sales by time, geography, and products  
- Created visualisations for daily sales trends and top products  

### 👥 Part 2 – Customer Segmentation (RFM)
- Calculated **Recency, Frequency, and Monetary (RFM)** scores  
- Performed segmentation based on RFM quantiles  
- Labelled and profiled segments (e.g. Champions, At Risk, Lost)  

### 🛍️ Part 3 – Market Basket Analysis
- Applied association rules using **Apriori algorithm**  
- Identified frequently bought-together product pairs  
- Visualised product linkages to inform cross-selling  

## 💡 Key Insights
- Top 5 products contribute over 25% of sales  
- UK dominates customer base (~80%)  
- ‘Champions’ make up 14% of customers but drive 35% of revenue  
- Most frequent product combinations suggest bundling opportunities  

## 📁 Repository Contents
- `Ecommerce_Analysis_Combined.ipynb`: Full analysis notebook  
- `README.md`: Project documentation and summary  
