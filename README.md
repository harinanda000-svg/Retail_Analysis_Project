# 🛒 Retail Demand Analysis

## 📌 Overview

This project focuses on analyzing retail sales data to understand demand patterns, customer behavior, and business performance. The analysis is performed using Python (Pandas, Matplotlib) and SQL (SQLite), simulating a real-world data analytics workflow.

---

## 🎯 Objectives

* Analyze sales trends over time
* Identify high-performing product categories
* Understand purchasing patterns
* Extract meaningful business insights
* Demonstrate Python and SQL integration

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* SQLite (SQL)
* Jupyter Notebook

---

## 📂 Dataset

The dataset consists of retail transaction records with the following key columns:

* CustomerID
* ProductCategory
* Quantity
* Price
* TransactionDate
* DiscountApplied (%)
* Revenue (calculated)

Additional features were derived during analysis:

* Month
* DayOfWeek

---

## ⚙️ Data Processing

* Removed unnecessary columns
* Converted date column to datetime format
* Handled missing values
* Created new features (Month, DayOfWeek, Revenue)
* Cleaned and structured dataset for analysis

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Revenue by Product Category
* Monthly Sales Trends
* Sales Distribution by Day of Week
* Top Performing Categories
* Payment Method Distribution (supporting analysis)

---

## 🗄️ SQL Integration

The cleaned dataset was stored in a SQLite database and queried using SQL.

Example queries include:

* Total revenue by product category
* Monthly revenue trends
* Top categories by quantity sold

SQL was used for aggregation, while Python was used for visualization and further analysis.

---

## 📊 Analysis Approach

This project focuses on exploratory data analysis (EDA) to understand retail demand patterns rather than predictive modeling.

The analysis includes:

* Trend analysis over time
* Category-level performance evaluation
* Distribution-based insights

A machine learning model was not included, as the dataset does not contain sufficient features for reliable demand prediction.

---

## 📈 Key Insights

* Certain product categories consistently generate higher revenue
* Sales show variation across months, indicating possible seasonal trends
* Demand differs across days of the week
* Payment methods show varying customer preferences

---

## ⚠️ Limitations

* No external factors such as promotions, competition, or inventory data
* Limited features for advanced predictive modeling
* Analysis is based only on available transactional data

---

## ✅ Conclusion

This project demonstrates how retail data can be analyzed to extract meaningful business insights. The focus was on data exploration and visualization to understand demand patterns and support decision-making.

---

## 🚀 Future Improvements

* Include external data (holidays, marketing campaigns, etc.)
* Build interactive dashboards
* Apply advanced analytics if richer data is available

---

## 📎 Project Structure

```
data/
notebooks/
sql/
outputs/
README.md
```

---

## 👤 Author

Your Name
Harinand
LH07

---

## ⭐ Note

This project emphasizes **practical data analysis and business insights** rather than complex machine learning models.
