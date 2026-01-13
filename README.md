# Regression Analysis on California Housing Dataset

## Objective
To evaluate and compare different regression techniques in supervised learning
using the California Housing dataset.

## Dataset
The dataset is obtained from `sklearn.datasets.fetch_california_housing`.
It contains numerical features related to housing demographics and geography
to predict median house value.

## Preprocessing Steps
- Converted dataset into a Pandas DataFrame
- Checked for missing values (none found)
- Applied feature scaling using StandardScaler
- Split data into training and testing sets

## Regression Models Implemented
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)

## Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared Score (R²)

## Results Summary
- Gradient Boosting Regressor performed the best overall.
- Linear Regression showed the weakest performance due to linear assumptions.
- Ensemble models outperformed individual models.

## Tools Used
- Python
- Google Colab
- Scikit-learn
- Pandas, NumPy

## Author
Ansaf_Mhmd

