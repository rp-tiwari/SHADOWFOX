# House Price Prediction using Linear Regression

## Overview
This project aims to predict house prices using the Boston Housing Dataset. A Linear Regression model is trained on various housing features to estimate the median value of homes.

## Objective
To build a machine learning model that can accurately predict house prices based on housing characteristics.

## Dataset
The dataset used is the Boston Housing Dataset containing 506 records and 14 attributes.

## Features
- CRIM – Per capita crime rate by town
- ZN – Proportion of residential land zoned for lots
- INDUS – Proportion of non-retail business acres per town
- CHAS – Charles River dummy variable
- NOX – Nitric oxide concentration
- RM – Average number of rooms per dwelling
- AGE – Proportion of owner-occupied units built before 1940
- DIS – Weighted distances to employment centres
- RAD – Accessibility to radial highways
- TAX – Property tax rate
- PTRATIO – Pupil-teacher ratio
- B – Proportion of Black population
- LSTAT – Percentage of lower status population

## Target Variable
- MEDV – Median value of owner-occupied homes (in $1000s)

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

## Methodology

## 1. Data Loading
The dataset is loaded using Pandas.

## 2. Data Preprocessing
The target variable (MEDV) is separated from the input features.

## 3. Train-Test Split
The dataset is split into:
- 80% Training Data
- 20% Testing Data

## 4. Model Training
A Linear Regression model is trained using the training dataset.

## 5. Prediction
The trained model predicts house prices on the testing dataset.

## 6. Evaluation
Model performance is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## Results
The Linear Regression model successfully predicts house prices and provides evaluation metrics to measure prediction accuracy.

## Project Structure

House-Price-Prediction/
│
├── BostonHousing.csv
├── house_price_prediction.ipynb
└── README.md

## How to Run

1. Open Google Colab.
2. Upload the notebook file.
3. Upload BostonHousing.csv.
4. Run all cells.
5. View predictions and evaluation metrics.

## Future Improvements

- Implement Random Forest Regressor
- Implement XGBoost Regressor
- Hyperparameter tuning
- Feature engineering
- Model comparison

## Author

Ram Prasad Tiwari

## License

This project is developed for educational and internship purposes.
