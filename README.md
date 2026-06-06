#  Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI to uncover purchasing trends, customer segments, product preferences, and subscription patterns. The objective is to help businesses make data-driven decisions that improve customer engagement, marketing effectiveness, and overall sales performance.

### 🎯 Business Problem

A retail company wants to better understand customer purchasing behavior across demographics, product categories, and shopping channels. The goal is to identify key factors influencing buying decisions and leverage those insights to optimize marketing strategies, customer retention, and product performance.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* PostgreSQL
* SQL
* Power BI
* Jupyter Notebook

---

## 📊 Dataset Summary

| Metric    | Value                          |
| --------- | ------------------------------ |
| Records   | 3,900                          |
| Features  | 18                             |
| Data Type | Customer Shopping Transactions |

### Key Attributes

* Customer Demographics (Age, Gender, Location)
* Subscription Status
* Product Categories
* Purchase Amount
* Discounts & Promotions
* Review Ratings
* Shipping Preferences
* Purchase Frequency

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & Cleaning (Python)

* Imported and explored raw customer shopping data
* Handled missing values in review ratings
* Standardized column names using snake_case
* Created customer age groups
* Engineered additional analytical features
* Validated data consistency
* Loaded cleaned data into PostgreSQL for analysis

### 2️⃣ Exploratory Data Analysis (EDA)

* Analyzed customer spending patterns
* Explored purchasing behavior across demographics
* Evaluated category-level performance
* Identified customer engagement trends

### 3️⃣ Business Analysis (SQL)

Key analyses performed:

* Revenue by Gender
* High-Spending Discount Users
* Top Rated Products
* Shipping Type Performance
* Subscriber vs Non-Subscriber Analysis
* Discount Dependency Analysis
* Customer Segmentation
* Product Popularity by Category
* Repeat Purchase Behavior
* Revenue Contribution by Age Group

### 4️⃣ Dashboard Development (Power BI)

Built an interactive dashboard featuring:

* Revenue KPIs
* Customer Segmentation
* Product Category Performance
* Subscription Analysis
* Discount Impact Analysis
* Purchase Trend Visualizations

---

## 📈 Key Insights

 Subscribers generated higher overall revenue.

 Loyal customers contributed significantly to repeat purchases.

 Certain product categories consistently outperformed others.

 Discounts positively influenced purchasing behavior but require margin optimization.

 Specific age groups represented the largest share of revenue.

 Top-rated products showed strong correlation with customer engagement.

---

## 💡 Business Recommendations

### 🚀 Increase Subscription Adoption

Offer exclusive discounts, loyalty benefits, and personalized promotions.

### 🎁 Strengthen Loyalty Programs

Reward repeat customers to improve retention and long-term value.

### 📢 Optimize Marketing Campaigns

Target high-revenue customer segments with personalized offers.

### ⭐ Promote High-Performing Products

Focus marketing efforts on top-rated and best-selling products.

### 📦 Improve Shipping Strategy

Leverage customer preferences to enhance satisfaction and conversion rates.

---

## 📁 Repository Structure

```text
Customer_Shopping_Behavior_Analysis.ipynb
customer_behavior_sql_queries.sql
customer_behavior_dashboard.pbix
README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Open the Jupyter Notebook and execute the analysis.

3. Run SQL queries in PostgreSQL.

4. Open the Power BI dashboard to explore visual insights.

---

## 📌 Project Outcome

This project demonstrates an end-to-end analytics workflow covering data preparation, exploratory analysis, SQL-based business intelligence, and dashboard reporting. The findings provide actionable insights that can support customer-focused business strategies and improve overall decision-making.
