# 🛒 Sales Data Analysis & Customer Segmentation

## 📌 Project Overview

This project explores **sales data analysis** and applies **K-Means clustering** to identify profitable customer segments. The goal is to help businesses understand **which products and customer groups generate the most profit**, enabling data-driven decision making.

---

## 📊 Dataset Information

* **Columns:** Date, Day, Month, Year, Customer Age, Gender, Country, Product Category, Sub-Category, Order Quantity, Unit Cost, Unit Price, Profit, Cost, Revenue
* **Categories:** Accessories, Clothing, Bikes
* **Customers:** Male & Female across multiple countries

---

## 🔍 Key Insights

### 1️⃣ Product Category Analysis

* **Bikes → ₹20,519,276 (Highest Profit 💰)**
* Accessories → ₹8,862,377
* Clothing → ₹2,839,447

✅ **Bikes are the most profitable product category.**

### 2️⃣ Customer Segmentation (K-Means, k=3)

Cluster-wise averages:

| Cluster | Avg. Customer Age | Avg. Revenue | Avg. Profit |
| ------- | ----------------: | -----------: | ----------: |
| 0       |          \~47 yrs |          406 |         169 |
| 1       |          \~35 yrs |     **3697** |    **1294** |
| 2       |          \~28 yrs |          395 |         159 |

✅ **Cluster 1 (Adults \~35 years old) has the highest revenue & profit.**

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas, NumPy
* Scikit-Learn (K-Means, StandardScaler)
* Matplotlib

---

## 📈 Visualizations

* Profit comparison across product categories
* Revenue distribution by age groups
* K-Means clustering results (Customer Age vs Revenue)

---

## 🚀 Business Recommendations

* Focus on **Bikes category** for maximum profit.
* Target **Cluster 1 (Adults \~35 years old)** with premium offers & loyalty programs.
* Design marketing campaigns that combine **Bikes + Cluster 1** to maximize ROI.

---

## 📂 Files

* `sales_data.csv` → Dataset
* `analysis.ipynb` → Data exploration & visualization
* `clustering.ipynb` → K-Means clustering & insights
* `README.md` → Project documentation

---

✨ **Final Answer:**

* **Most Profitable Category → Bikes**
* **Most Profitable Customer Group → Cluster 1 (Adults \~35 yrs, high spenders)**


