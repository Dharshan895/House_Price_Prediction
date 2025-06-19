# 🏠 Housing Price Prediction

This project focuses on predicting house prices using machine learning regression models. It includes data preprocessing, outlier handling, feature scaling, and performance evaluation.

## 📌 Project Overview

* Predicts housing prices based on various features
* Compares performance of four regression models:

  * Linear Regression
  * Random Forest Regressor
  * K-Nearest Neighbors (KNN)
  * Decision Tree Regressor
* Evaluates models using:

  * Mean Squared Error (MSE)
  * Mean Absolute Error (MAE)
  * R-squared Score (R²)

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* SciPy

## 🚀 Workflow

1. Load and inspect dataset
2. Remove outliers using Z-score
3. Scale features with StandardScaler
4. Split data into training and testing sets
5. Train and evaluate multiple regression models
6. Compare performance and identify the best model

## 📊 Model Performance (R² Score)

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.447    |
| Random Forest     | 0.406    |
| KNN Regressor     | 0.359    |
| Decision Tree     | 0.016    |

## 📁 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/housing-price-prediction.git
   cd housing-price-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook housing_price_prediction.ipynb
   ```


