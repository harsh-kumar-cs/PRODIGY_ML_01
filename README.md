# PRODIGY_ML_01
# House Price Prediction using Linear Regression

This project implements a baseline machine learning model to predict house prices
using a linear regression approach. The goal of this project is to understand and
demonstrate the fundamental workflow of a regression-based machine learning task.

---

## Objective
To build a linear regression model that predicts house prices based on the following
features:
- Square footage of the house
- Number of bedrooms
- Number of bathrooms

---

## Dataset
The dataset used for this project is sourced from the Kaggle *House Prices* dataset.
For simplicity and interpretability, only a subset of numerical features was selected.

### Selected Features
- `GrLivArea` – Above ground living area (square footage)
- `BedroomAbvGr` – Number of bedrooms above ground
- `FullBath` – Number of full bathrooms

### Target Variable
- `SalePrice` – Final sale price of the house

---

## Methodology
1. Loaded and inspected the dataset.
2. Selected relevant numerical features for the model.
3. Split the data into training and validation sets using a 90–10 ratio.
4. Trained a Linear Regression model on the training data.
5. Evaluated model performance using appropriate regression metrics.

---

## Model & Evaluation
- **Algorithm:** Linear Regression
- **Evaluation Metrics:**
  - Root Mean Squared Error (RMSE)
  - R² Score

### Results
- RMSE ≈ **53,201**
- R² Score ≈ **0.67**

The R² score indicates that the model explains approximately 67% of the variance in
house prices using only three input features.

---

## Conclusion
This project demonstrates how a simple linear regression model can capture meaningful
relationships in housing data. Although the model is intentionally kept simple, it
serves as a strong baseline for further improvements using additional features or
advanced algorithms.

---

## Future Improvements
- Include additional features such as location, house quality, and year built.
- Experiment with regularized models like Ridge and Lasso regression.
- Apply cross-validation for more robust evaluation.
- Explore non-linear models to improve prediction accuracy.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- scikit-learn
- Jupyter Notebook

---

## Author
Harsh Kumar
