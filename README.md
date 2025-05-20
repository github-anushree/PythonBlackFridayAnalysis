# 🛍️ Black Friday Sales Analysis with Python

Welcome to the **Black Friday Sales Analysis** project!  
In this case study, we dive deep into a real-world retail dataset consisting of over **550,000+ transactions** to uncover insights about customer behavior, purchasing patterns, and product trends—all using **Python and Pandas**.

---

## 📊 Project Overview

This project uses a dataset sourced from **Kaggle**, which captures sales transactions during a Black Friday event at a retail store. It includes demographic data (age, gender, occupation), product information, and purchase amounts.

### 🎯 Objective

The main objective is to perform **exploratory data analysis (EDA)** and **feature engineering** to:

- Understand purchasing behavior by gender, age, and city.
- Handle missing values in product categories.
- Identify top-selling products and high-value customers.
- Perform data filtering, grouping, and aggregation.
- Tag transactions into "High Focused" and "General" categories based on purchase amounts.

---

## 🧰 Tools & Libraries Used

- **Python 3.9+**
- **Pandas** – data manipulation and analysis
- **NumPy** – numerical operations
- **Jupyter Notebook** – for analysis and step-by-step exploration

---

## 🗂️ Dataset Summary

- 📁 File: `blackfriday.csv`
- 🧾 Rows: `550,069`
- 🧾 Columns: `12`
- 📌 Target: `Purchase Amount`

| Column Name                | Description                                 |
|---------------------------|---------------------------------------------|
| User_ID                   | Unique ID of the user                       |
| Product_ID                | Unique ID of the product                    |
| Gender                    | Gender of the user                          |
| Age                       | Age group of the user                       |
| Occupation                | Masked occupation code                      |
| City_Category             | A/B/C - City tier                          |
| Stay_In_Current_City_Years| Number of years in current city             |
| Marital_Status            | Marital status                              |
| Product_Category_1, 2, 3  | Product category (masked)                   |
| Purchase                  | Purchase amount (target variable)           |

---

## ✅ Key Highlights

- Displayed and explored dataset shape, structure, and data types.
- Identified and handled missing values using both **dropping** and **imputation** techniques.
- Performed **indexing and slicing** using `.iloc` and `.loc`.
- Created new features such as "High Focused" transactions.
- Conducted group-by analysis to study gender and age-wise purchase behavior.
- Generated statistical summaries and performed sorting to identify **top 20 high-revenue customers**.

---

## 📈 Results in a Nutshell

- **Total Purchase Value:** ₹5+ Billion
- **Most Purchased Product ID:** `P00265242`
- **Most Active Age Group:** `26-35`
- **High Focused Transactions:** Purchases over ₹5000
- **Top Customers:** Identified based on total spend

---

## 🧠 What You’ll Learn

- Real-world data exploration with Pandas
- Handling missing values and data cleaning
- Feature extraction and filtering techniques
- Aggregation and group-wise analysis
- Boolean indexing and advanced selection
- Applying lambda and custom transformations

---

## Final Notes
This project serves as a great hands-on exercise for anyone looking to improve their skills in:

Exploratory Data Analysis (EDA)

Pandas data manipulation

Handling real-world messy data

Retail customer insights

Dataset Source
Kaggle - [Black Friday Sales Dataset](https://www.kaggle.com/datasets/syedhaideralizaidi/black-friday-dataset)

 Let’s Connect
If you enjoyed this project or have suggestions to improve it, feel free to connect!

🌐 LinkedIn: [Anushree Kashyap](www.linkedin.com/in/anushreekashyap)

🧠 Medium Blog: [Read Full Blog](https://medium.com/@anushreekashyap03/black-friday-sales-analysis-with-python-a-simple-yet-insightful-case-study-f55a0ee2fe6d)
