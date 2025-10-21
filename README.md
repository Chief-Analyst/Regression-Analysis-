# 🧮 Multiple Linear Regression Analysis

This project demonstrates a **Multiple Linear Regression (MLR)** model built using Python to predict house prices based on factors such as **size**, **year**, and **view (sea view or not)**.

---

## 📊 Project Overview
The goal of this analysis was to understand how different variables affect house prices and to develop a model that can make reliable price predictions.

### Key Objectives:
- Explore and clean the dataset.
- Build a multiple regression model using **scikit-learn** and **statsmodels**.
- Evaluate model performance using **R²**, **Adjusted R²**, and **p-values**.
- Compare results when including and excluding certain variables (like `year`).
- Visualize regression lines for properties with and without sea views.

---

## ⚙️ Tools & Libraries Used
- **Python**
- **pandas** – for data manipulation  
- **numpy** – for numerical calculations  
- **matplotlib** / **seaborn** – for data visualization  
- **statsmodels** – for statistical modeling and p-values  
- **scikit-learn** – for regression modeling and validation  

---

## 📈 Key Findings
- The model achieved an **R² of 0.91**, showing that it explains about **91% of the variation in house prices**.
- The variable **“year”** had a **p-value > 0.05**, suggesting it may not significantly affect price.
- Removing “year” slightly reduced R² to **0.88**, showing moderate impact.
- Properties with a **sea view** consistently had higher predicted prices.

---Author

Chukwuma Samuel
Entry-Level Data Scientist
💼 Tools: Python | MySQL | Excel | Power BI
📧 Email: chukwumasamuel27@gmail.com

