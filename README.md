# 🚗 Used Car Price Prediction

This repository contains a complete data science project designed to model and predict used car prices using regression techniques. The analysis is based on a cleaned dataset of 426K used car listings and follows the CRISP-DM framework.

---

## 📌 Objective
To help used car dealerships:
- Understand what drives used car prices
- Predict prices with strong accuracy
- Use data insights to optimize pricing and inventory strategies

---

## 🧰 Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📈 Model Summary
| Model              | R² Score | RMSE (log-scale) | Notes                                     |
|-------------------|----------|------------------|-------------------------------------------|
| Linear Regression | 0.7456   | 0.31             | Simple and interpretable baseline         |
| Ridge Regression  | 0.7455   | 0.31             | Regularized for multicollinearity         |
| Lasso Regression  | 0.7136   | 0.33             | Useful for feature reduction              |

✅ Models predict prices within ±30% for most listings.

---

## 🔍 Key Feature Insights
| Feature           | Insight |
|------------------|---------|
| Car Age          | Newer vehicles command higher prices |
| Odometer         | Lower mileage is positively correlated with price |
| Transmission     | Automatics tend to be more valuable |
| Brand/Model      | Toyota, Ford, Honda retain better resale value |
| Vehicle Type     | Trucks and SUVs are priced higher than sedans |
| Drive Type       | AWD/4WD adds value especially in colder regions |
| Condition        | "Excellent" and "Like New" cars are priced at a premium |

---

## 💼 Business Recommendations
- Focus inventory on low-mileage, newer vehicles with clean titles
- Prioritize popular brands and good condition listings
- Avoid or deeply discount salvage/manual/old vehicles
- Use model predictions to benchmark and reprice inventory

---

## 📘 License
This project is licensed under the MIT License.

---

## 🙌 Acknowledgments
- Dataset source: kaggle
