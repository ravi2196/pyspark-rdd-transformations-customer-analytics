# 🚀 PySpark RDD Transformations – Customer Analytics Project

## 📌 Overview

This project demonstrates **PySpark RDD Transformations** using a real-world **customer analytics dataset**.
It covers **beginner to advanced transformations** and simulates real data engineering workflows.

---

## 🚀 Project Highlights

- Processed **18,000+ customer records**
- Implemented **15+ RDD transformations**
- Covered **beginner to advanced PySpark concepts**
- Demonstrated **lazy evaluation and DAG execution**
- Built a **customer analytics pipeline using RDD API**

---

## 🎯 Objectives

* Understand **RDD transformations**
* Learn **lazy evaluation & DAG execution**
* Perform **customer behavior analysis**
* Apply **real-world data engineering logic**

---

## 📂 Dataset: `customers_report`

The dataset contains **18,000+ customer records** with the following features:

* Customer demographics (age, age_group)
* Transaction data (total_sales, total_orders, total_quantity)
* Behavioral metrics (recency, lifespan)
* Derived metrics (avg_order_value, avg_monthly_spend)

---

## 🛠️ Technologies Used

* Python 🐍
* Apache Spark (PySpark)
* RDD API

---

## 🔥 RDD Transformations Covered

### 🟢 Beginner

* `map()`
* `filter()`
* `flatMap()`
* `distinct()`
* `union()`

---

### 🟡 Intermediate

* `reduceByKey()`
* `groupByKey()`
* `sortBy()`
* `mapValues()`
* `keys()` / `values()`
* `sortByKey()`
* `intersection()`
* `subtract()`

---

### 🔴 Advanced

* `combineByKey()`
* `mapPartitions()`
* `repartition()`
* `coalesce()`
* `cartesian()`
* `sample()`

---

## 📊 Key Use Cases Implemented

* Customer segmentation
* Sales aggregation by age group
* High-value customer identification
* Recency-based analysis
* Average order value calculation

---

## ⚡ Key Learnings

* RDD transformations are **lazy**
* DAG execution improves performance
* `reduceByKey()` is more efficient than `groupByKey()`
* Partitioning impacts performance
* `combineByKey()` enables custom aggregations

---

## 📁 Project Structure

```
├── customers_report.csv
├── rdd_transformations.py   # Main PySpark code
└── README.md
```

---

## 🎯 Future Improvements

* Convert RDD → DataFrame API
* Add Spark SQL queries
* Implement performance optimization
* Deploy on cloud (GCP / AWS)

---

## 👨‍💻 Author

**Ravi Shankar Kumar**
Aspiring Data Engineer | Machine Learning Enthusiast

---

## ⭐ If you found this useful

Give this repo a ⭐ and connect with me!

---

## 📜 License
This project is licensed under the MIT License.
