# House-Price-Prediction-using-Machine-Learning-
House Price Prediction AI
Here is a complete `README.md` for your GitHub repository.

# 🏠 House Price Prediction

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to estimate the price of a house based on various property features such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities.

This project was developed as part of the **XYlofy AI Internship – Week 1 Assignment**.

---

## 🎯 Problem Statement

Real estate buyers and sellers often rely on assumptions and outdated comparisons to determine property prices. The goal of this project is to build regression models that can accurately predict house prices and identify the key factors influencing property values.

---

## 📂 Dataset

**Dataset Source:** Kaggle Housing Prices Dataset

The dataset contains **545 records** and **13 features** related to housing properties.

### Features Included:

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status
* Price (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading and Exploration

* Loaded the dataset using Pandas.
* Displayed the first 10 rows of the dataset.
* Checked the shape of the dataset.
* Identified target and feature variables.
* Checked for missing values.

### 2. Data Cleaning

* Removed duplicate records.
* Converted categorical variables into numerical values.
* Applied one-hot encoding to categorical features.

### 3. Model Building

Two machine learning regression models were implemented:

* Linear Regression
* Random Forest Regressor

The dataset was split into training and testing sets using an **80:20 ratio**.

---

## 📈 Model Evaluation

The models were evaluated using the following metrics:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### Random Forest Regressor Performance

| Metric   | Value      |
| -------- | ---------- |
| MAE      | 1022560.05 |
| RMSE     | 1401496.84 |
| R² Score | 0.6114     |

The Random Forest Regressor outperformed the Linear Regression model and achieved better prediction accuracy.

---

## 📉 Visualizations

The following visualizations were created:

1. House Price Distribution Histogram
2. Correlation Heatmap
3. Actual vs Predicted Price Scatter Plot

---

## 🔍 Key Insights

* House area is one of the most important factors affecting house prices.
* Houses with more bathrooms and stories tend to have higher prices.
* Properties with air conditioning and located in preferred areas are generally more expensive.
* Random Forest provided better prediction performance compared to Linear Regression.

---

## 🚀 Future Enhancements

* Perform hyperparameter tuning to improve model accuracy.
* Implement advanced algorithms such as XGBoost.
* Deploy the model as a web application.
* Build an interactive house price prediction system.

---

## 📁 Project Structure

```text
HousePricePrediction_NitishKumar/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── price_distribution.png
├── correlation_heatmap.png
├── actual_vs_predicted.png
└── README.md
```

## 👨‍💻 Author

**Nitish Kumar**
gmail- nitishkr4web@gmail.com 
LinkedIn - https://www.linkedin.com/in/nitish-kumar-69b32b232

XYlofy AI Internship – Week 1 Project


