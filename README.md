# Outlier Detection using Z-Score (Placement Dataset)

## 📌 Project Overview

This project demonstrates how to detect and remove outliers from a dataset using the Z-Score statistical method.
The goal of this project is to understand how statistical techniques can be used in data preprocessing before applying Machine Learning models.
The dataset used in this project is a placement dataset (`placement.csv`).

---

## 🧠 What is Z-Score?

Z-Score measures how many standard deviations a data point is away from the mean.

Formula:

Z = (X - Mean) / Standard Deviation
If the absolute value of Z is greater than a chosen threshold (commonly 3), the data point is considered an outlier.

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib 

---

## 🔄 Workflow

The project follows these steps:

1. Importing required libraries
2. Loading the placement dataset
3. Calculating mean and standard deviation
4. Identifying outliers using a threshold
5. Removing outliers from the dataset
6. Comparing dataset before and after cleaning

---

## 📊 Results

- Outliers were successfully identified using Z-score method.
- The dataset was cleaned by removing extreme values.
- The cleaned dataset is more suitable for further Machine Learning tasks.

---

## 📈 Why Outlier Removal is Important?

Outliers can:
- Distort statistical analysis
- Affect model accuracy
- Bias distance-based algorithms
- Impact mean and variance

Proper preprocessing improves model reliability and performance.

---

## 🚀 Future Improvements

- Compare Z-Score method with IQR method
- Visualize outliers using boxplots
- Apply Machine Learning model before and after outlier removal
- Automate outlier detection for multiple columns

---

## 👨‍💻 Author
Ishaan Sharma  
B.Tech – Artificial Intelligence & Machine Learning  
Currently building practical ML and data preprocessing projects.
Ishaan Sharma  
B.Tech – Artificial Intelligence & Machine Learning  
Currently building practical ML and data preprocessing projects.
