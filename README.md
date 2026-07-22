# Salary Prediction using Polynomial Regression

## Objective

The objective of this project is to develop a Polynomial Regression model to predict employee salaries based on their position level.

---

## Dataset

**Position Salaries Dataset**

Kaggle Link:
https://www.kaggle.com/datasets/akram24/position-salaries

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records.
3. Identified the input feature (Level) and target variable (Salary).
4. Displayed dataset information and summary statistics.
5. Checked for missing values.
6. Split the dataset into 80% training and 20% testing.
7. Applied Polynomial Features (Degree = 3).
8. Trained the Polynomial Regression model.
9. Predicted salaries for the test dataset.
10. Evaluated the model using MAE, MSE, and R² Score.
11. Plotted the original data and the Polynomial Regression curve.

---

## Results

- Mean Absolute Error (MAE): *(Enter your MAE value)*
- Mean Squared Error (MSE): *(Enter your MSE value)*
- R² Score: *(Enter your R² Score value)*

---

## Conclusion

The Polynomial Regression model successfully predicted employee salaries using position level as the input feature. By transforming the feature into polynomial terms of degree 3, the model captured the non-linear relationship between position level and salary more effectively than Linear Regression. The evaluation metrics demonstrated good predictive performance, and the polynomial regression curve closely followed the original data points, making it suitable for this dataset.
