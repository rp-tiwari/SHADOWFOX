# House Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts house prices using Machine Learning. A Linear Regression model is trained on housing data to estimate house prices based on various features such as crime rate, number of rooms, tax rate, and other housing-related factors.

The project demonstrates the complete machine learning workflow, including:
- Data preprocessing
- Handling missing values
- Train-test split
- Model training
- Model evaluation
- Data visualization

---

## 🚀 Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## 📂 Dataset
The project uses the **HousingData.csv** dataset.

Features include:
- CRIM (Crime Rate)
- ZN (Residential Land Zone)
- INDUS (Industrial Area Ratio)
- CHAS (Charles River Dummy Variable)
- NOX (Nitric Oxide Concentration)
- RM (Average Number of Rooms)
- AGE (Age of Houses)
- DIS (Distance to Employment Centers)
- TAX (Property Tax Rate)
- PTRATIO (Pupil-Teacher Ratio)
- LSTAT (% Lower Status Population)

Target Variable:
- MEDV (Median House Value)

---

## ⚙️ Project Workflow

### 1. Data Loading
The housing dataset is loaded using Pandas.

### 2. Data Preprocessing
Missing values are handled using the Mean Imputation technique.

### 3. Feature Selection
Input features are separated from the target variable.

### 4. Train-Test Split
The dataset is divided into training and testing sets.

### 5. Model Training
A Linear Regression model is trained on the training data.

### 6. Model Evaluation
The model performance is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 7. Visualization
A scatter plot is generated to compare Actual vs Predicted House Prices.

---

## 📊 Results
The model predicts house prices with reasonable accuracy using Linear Regression.

Evaluation Metrics:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Score

---

## 📷 Output Visualization

The project generates a graph showing:

**Actual House Prices vs Predicted House Prices**

This helps visualize the performance of the model.

