# 📊 Multiple Linear Regression Analysis – Housing Prices

## 📌 Project Objective

This project implements a Multiple Linear Regression model to estimate housing prices based on structural property characteristics.

The goal is to quantify how housing features influence market price using Ordinary Least Squares (OLS).

---

## 🧠 Dataset Overview

**Dependent Variable:**
- `Price`

**Independent Variables:**
- `Area`
- `Bedrooms`
- `Bathrooms`
- `Stories`

Total observations: 545  
Training set: 381  
Test set: 164  

---

## 📐 Estimated Regression Equation

The fitted model is:

\[
Price = -15,222.75 
+ 356.04(Area)
+ 119,297.18(Bedrooms)
+ 1,246,895.69(Bathrooms)
+ 536,079.09(Stories)
\]

---

## 📊 Estimated Coefficients

| Variable   | Coefficient |
|------------|-------------|
| Intercept  | -15,222.75 |
| Area       | 356.04 |
| Bedrooms   | 119,297.18 |
| Bathrooms  | 1,246,895.69 |
| Stories    | 536,079.09 |

---

## 📈 Model Performance Metrics

- **R²:** 0.5243  
- **Mean Squared Error (MSE):** 1,936,272,230,125.76  
- **Root Mean Squared Error (RMSE):** 1,391,499.99  
- **Relative RMSE:** 29.31%

---

## 🔎 Interpretation of Results

- **Bathrooms** have the strongest effect on housing price.  
  Adding one bathroom increases price by approximately **1,246,896** (currency units), holding other variables constant.

- Each additional **story** increases price by approximately **536,079**.

- Each additional **bedroom** increases price by approximately **119,297**.

- Each additional unit increase in **area** increases price by approximately **356**.

---

## 📊 Model Evaluation

The model explains approximately **52.4% of the variance** in housing prices, indicating moderate explanatory power.

However:

- Nearly half of price variation remains unexplained.
- Additional predictors (e.g., location, amenities, age of property) may improve model fit.
- Residual diagnostics and multicollinearity checks are recommended.

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

```bash
git clone https://github.com/stephen-adebisi/multiple-variable-linear-regression.git
pip install -r requirements.txt
jupyter notebook
```

---

## 👤 Author

Stephen Adebisi  
Graduate Student – Geospatial Science  
Machine Learning | Data Science | Statistical Modeling
