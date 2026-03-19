# 📌 Customer Segmentation using K-Means Clustering

## 📊 Project Overview

This project focuses on segmenting customers based on their purchasing behavior using **K-Means clustering**.
The goal is to identify different types of customers so businesses can target them effectively.

---

## ⚙️ Workflow

### 1. Data Cleaning

* Removed duplicate records
* Removed cancelled transactions
* Removed negative quantities and zero prices
* Handled missing values

---

### 2. Feature Engineering

* Created **TotalAmount = Quantity × UnitPrice**
* Extracted **Month** and **Hour** from InvoiceDate

---

### 3. Customer Aggregation

Grouped data by **CustomerID** to create:

* Total Spending
* Total Orders

---

### 4. Feature Scaling

* Applied **StandardScaler** to normalize numerical features

---

### 5. Clustering (K-Means)

* Used **Elbow Method** to find optimal clusters
* Applied **K-Means clustering**
* Segmented customers into 3 groups

---

## 🧠 Customer Segments

* **High Value Customers**

  * High spending and high purchase frequency
  * Major contributors to revenue

* **Regular Customers**

  * Moderate spending and engagement
  * Potential for growth

* **Low Value Customers**

  * Low spending and low purchase frequency
  * Minimal engagement

---

## 📈 Key Insights

* A small group of customers contributes to most of the revenue
* Regular customers can be converted into high-value customers
* Low-value customers require targeted engagement strategies

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📁 Files in Repository

* `customer_segmentation.ipynb` → Complete analysis and model
* `customer_segmentation.csv` → Final segmented dataset

---

## 📌 Conclusion

Customer segmentation helps businesses understand customer behavior and design better marketing strategies, leading to improved revenue and customer retention.
