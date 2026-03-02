# Outlier Detection and Treatment in Machine Learning

## 📌 Overview
This repository demonstrates practical implementation of statistical techniques used to detect and handle outliers in datasets.
Outlier treatment is a crucial preprocessing step in Machine Learning as extreme values can significantly affect model performance.

---

## 📊 Techniques Implemented

### 1️⃣ IQR (Interquartile Range) Method
- Based on 25th and 75th percentiles
- Detects outliers using:
  
  Upper Limit = Q3 + 1.5 × IQR  
  Lower Limit = Q1 − 1.5 × IQR

- Demonstrates:
  - Outlier detection
  - Trimming
  - Capping

---

### 2️⃣ Percentile Method (Winsorization)
- Uses 1st and 99th percentile
- Effective for large datasets
- Demonstrates:
  - Extreme value filtering
  - Winsorization technique

---

### 3️⃣ Z-Score Method
- Based on standard normal distribution
- Formula:

  Z = (X − μ) / σ

- Uses ±3 standard deviation rule
- Applied only on normally distributed features

---

## 🛠 Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📁 Datasets Used
- placement.csv
- weight-height.csv

---

## 🎯 Key Learning Outcomes
- When to use IQR vs Z-score
- Importance of checking distribution before applying statistical methods
- Difference between trimming and capping
- Practical implementation of winsorization

---

## 🚀 Future Improvements
- Implement robust scaling comparison
- Compare model performance before and after outlier treatment
- Convert code into reusable functions

---

## 👨‍💻 Author
B.Tech AIML Student | Learning Machine Learning Foundations
