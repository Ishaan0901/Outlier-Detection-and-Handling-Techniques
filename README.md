# Outlier Detection & Handling using Statistical Method (Z-Score Approach)

## 📌 Project Overview

This project demonstrates how to detect and handle outliers using statistical techniques on a placement dataset.
Instead of only identifying outliers, this project explores multiple strategies to handle extreme values and prepare the dataset for Machine Learning tasks.

---

## 🧠 Statistical Approach Used

Outliers were detected using the 3-sigma rule:

Upper Limit = Mean + 3 × Standard Deviation  
Lower Limit = Mean - 3 × Standard Deviation  

Any data point outside this range was considered an outlier.
This approach is mathematically equivalent to using a Z-score threshold of ±3.

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
4. Defining upper and lower boundaries using 3-sigma rule
5. Detecting outliers outside the defined range
6. Applying two outlier handling techniques:
   - Trimming (removing extreme values)
   - Capping (replacing extreme values with boundary limits)
7. Comparing dataset before and after preprocessing

---

## 🛠 Outlier Handling Techniques Implemented

### 1️⃣ Trimming
All values outside the defined range were removed from the dataset.

✔ Reduces dataset size  
✔ Removes extreme influence completely  

### 2️⃣ Capping
Extreme values were replaced with the upper or lower boundary limit.

✔ Preserves dataset size  
✔ Reduces extreme value impact  

---

## 📊 Key Learnings

- How to detect outliers using statistical boundaries
- Practical difference between trimming and capping
- Impact of extreme values on dataset distribution
- Importance of preprocessing before applying ML models

---

## 🚀 Future Improvements

- Compare Z-score method with IQR method
- Visualize distribution before and after handling
- Train ML model before and after outlier handling
- Automate preprocessing for multiple numerical features

---

## 👨‍💻 Author
Ishaan Sharma  
B.Tech – Artificial Intelligence & Machine Learning  
Focused on building strong fundamentals in Data Preprocessing and Machine Learning workflows.
Ishaan Sharma  
B.Tech – Artificial Intelligence & Machine Learning  
Focused on building strong fundamentals in Data Preprocessing and Machine Learning workflows.
