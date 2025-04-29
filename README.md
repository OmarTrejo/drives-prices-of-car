# 🧾 Used Car Price Analysis & Prediction

## 📌 Project Overview

This project analyzes used car data to identify the most important features that affect vehicle pricing. The goal is to support used car dealers in making data-driven decisions when acquiring or pricing inventory.

We used a **linear regression model** to quantify the impact of various factors such as year, mileage, condition, and vehicle type on price.

---

## 📊 Summary of Findings

- **Year of the car** is the most influential factor. Newer models significantly increase price.
- **Odometer reading** (mileage) has a strong **negative effect** — the more miles, the lower the price.
- Vehicles in **excellent condition** command much higher prices.
- Surprisingly, variables like **fuel type**, **title status**, and **transmission type** had **little to no predictive power** in this model.
- The model had a **Mean Squared Error (MSE)** of around **88 million**, which suggests it's useful for general trends but not fine-grained predictions.

---

## 🎯 Business Takeaways

- Focus on acquiring **low-mileage, newer vehicles** in **excellent condition**.
- Avoid overpaying for attributes that don't add value (e.g., title type or fuel type).
- A predictive tool based on this model can help dealers estimate vehicle values more consistently.

---

## 🔗 Access the Notebook

👉 [Click here to view the notebook](./prompt_II.ipynb)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- scikit-learn (Linear Regression)
- Matplotlib & Plotly (Visualizations)

---

## 🚀 Future Improvements

- Use non-linear models (e.g., XGBoost, Random Forest) to capture more complex relationships.
- Include brand/model and location data for finer prediction.
- Deploy the model as an API or web app for dealer use.
