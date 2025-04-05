# 🚢 Titanic EDA Analysis

This repository contains a comprehensive **Exploratory Data Analysis (EDA)** of the Titanic dataset, one of the most well-known datasets used in data science and machine learning.

---

## 📊 Project Overview

The objective of this project is to explore and analyze the Titanic dataset, identify patterns related to survival, clean and transform the data, and engineer meaningful features for further machine learning modeling.

---

## 🧰 Tools & Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📝 Key Tasks Performed

- Dataset inspection (shape, types, null values, etc.)
- Handling missing data (e.g., `age`, `fare`, `cabin`)
- Feature engineering:
  - `fare_per_person`: Adjusted fare based on family size
  - `family_size`: Sum of `sibsp` and `parch`
  - `family_type`: Categorized as "alone", "small", or "large"
- Column drops: Removed `sibsp` and `parch` after combining
- Visualizations for understanding survival rates based on:
  - Gender
  - Passenger class
  - Family size
  - Embarked port
- Data cleaning for modeling readiness

---

## 📁 Dataset Information

- Dataset used: Titanic Passenger Dataset  
- Source: https://docs.google.com/spreadsheets/d/1RU2NGI86jOOHs6p80uBcghdU70i8R2NX/edit?gid=967308879#gid=967308879

---

## 📌 Project Status

✅ Completed EDA  
✅ Cleaned dataset  
✅ Feature engineered  
🔜 Future Work: Apply ML models for survival prediction (coming soon!)

---

## 🧠 Author

**Muhammad Fahad Qazi**  
📧 fahadqazi2027@gmail.com 
🔗 www.linkedin.com/in/muhammadfahadqazi27
