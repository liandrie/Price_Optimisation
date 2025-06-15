# Online Course Price Optimization Project

This project explores how different pricing strategies affect enrollments and profitability for an online course. The goal was to determine the optimal price points to either maximize user acquisition or profit using both statistical and machine learning models.

---

## Objectives

- Understand how price impacts student sign-ups
- Predict demand using both linear regression and machine learning
- Simulate outcomes across price points
- Identify optimal pricing for different business goals

---

## Methods

### Part 1: Price Elasticity Modeling (Linear Regression)
- Modeled enrollments using price and ad spend
- Simulated enrollments and profit across a range of prices
- Identified the price points that maximize enrollments and profit

### Part 2: Machine Learning Comparison (Random Forest, XGBoost, Gradient Boosting)
- Trained three models to predict enrollments
- Compared performance using MAE, RMSE, and R²
- Selected the best model for final simulation

---

## Model Performance

| Model              | MAE       | RMSE      | R²        |
|--------------------|-----------|-----------|-----------|
| Random Forest      | 27.26     | 51.94     | **0.4728** |
| Gradient Boosting  | 27.98     | 53.45     | 0.4418    |
| XGBoost            | 29.56     | 58.83     | 0.3238    |

**Best Model: Random Forest**

---

## Final Insights & Recommendations

- **Price and enrollments are negatively correlated**
- **Profit peaks at a higher price** than where enrollments peak
- Max enrollments: **R50**
- Max profit: **R67**
- Balanced trade-off: **R60**

If the goal is to maximize **profit**, **R67** is ideal.  
If the goal is to increase **sign-ups**, **R50** is recommended.

---

## Tools Used

- **Python** (Pandas, NumPy)
- **Statsmodels** for linear regression
- **Scikit-learn** for Random Forest and Gradient Boosting
- **XGBoost**
- **Seaborn & Matplotlib** for visualizations

---

## Files

- `notebook.ipynb`: Full code, analysis, and visualizations
- `README.md`: Project summary and results

---
