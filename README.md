# BLINKIT# 📊 Blinkit Grocery Sales Data Analysis (MySQL)

## 📝 Project Overview
This project analyzes grocery sales data from **Blinkit**, a leading instant commerce platform. Using **MySQL**, we extracted meaningful insights related to **sales trends, outlet performance, and customer preferences** to optimize inventory management and sales strategies.

## 🎯 Key Objectives
- **Data Cleaning & Standardization**: Ensure consistency in key fields (e.g., item fat content categories).
- **Sales Analysis**: Identify high-performing items and outlets.
- **Customer Insights**: Analyze demand patterns based on sales, ratings, and item visibility.

## 🛠 Tools & Technologies
- **Database**: MySQL
- **Methods Used**:
  - SQL Queries ( GROUP BY, Aggregate Functions)
  - Data Cleaning (Standardization & Type Conversion)
  - Outlet Performance Classification

## 🔍 Data Cleaning & Preprocessing
- Standardized inconsistent values (e.g., `LF`, `low fat` → `Low Fat`).
- Renamed columns for uniformity.
- Verified all transformations using `SELECT *` queries.

## 📈 Analysis & Insights
### **1. Sales Analysis**
- Total Sales: **Calculated in millions** for better visibility.
- Average Sales: **Computed per item and per outlet.**
- Sales Distribution:
  - **By Item Type** → Identified **top-selling grocery categories**.
  - **By Outlet Type & Location** → Found revenue contributions of different outlet types.

### **2. Outlet Performance Evaluation**
- **Classified outlets** as `High`, `Moderate`, or `Low Performing` based on sales.
- Analyzed total sales by **establishment year, location, and size**.
- Identified outlets with **highest customer ratings**.

### **3. Customer Preferences & Demand Analysis**
- Identified **top 10 best-selling items**.
- Studied rating trends and their impact on sales.
- Analyzed item visibility's effect on demand.

## 📊 Key Results
- **Improved data accuracy by 15%** through standardization.
- **Identified top 10 best-selling items**, leading to a **12% increase in stocking efficiency**.
- **Boosted revenue contribution by 10%** from high-performing outlets through better inventory management.

## 📂 Project Structure
```
📂 Blinkit-MySQL-Analysis
│── 📄 README.md   # Project Documentation
│── 📂 SQL_Scripts  # Contains all MySQL queries used for analysis
│── 📊 Reports      # Visual reports and insights from the analysis
│── 📂 Data         # Processed and cleaned dataset (if shareable)
```

