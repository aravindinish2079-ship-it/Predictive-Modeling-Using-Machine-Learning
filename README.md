# Predictive-Modeling-Using-Machine-Learning
# Laptop Price Prediction Using Machine Learning

## Project Overview

This project focuses on building a machine learning model to predict laptop prices based on hardware specifications and system configurations. The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization.

The main objective is to transform raw laptop specification data into a predictive machine learning system capable of estimating laptop prices with high accuracy.

---

## Objectives

* Clean and preprocess raw laptop data
* Handle missing and invalid values
* Perform exploratory data analysis (EDA)
* Encode categorical variables for machine learning
* Train multiple regression models
* Compare model performance
* Visualize prediction accuracy and model evaluation metrics

---

## Dataset Features

The dataset contains information about laptops including:

* Company
* TypeName
* Inches
* ScreenResolution
* CPU
* RAM
* Memory
* GPU
* Operating System
* Weight
* Price

Additional engineered features:

* CPU Brand
* GPU Brand

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Data Preprocessing

The following preprocessing techniques were applied:

* Removed duplicates
* Handled missing values
* Replaced invalid symbols such as `?`
* Converted datatypes into numerical formats
* Encoded categorical variables using Label Encoding
* Cleaned RAM and Weight columns
* Removed outliers using statistical methods

---

## Exploratory Data Analysis

The project includes several visual analyses such as:

* Laptop brand distribution
* Price distribution analysis
* RAM vs Price analysis
* Correlation heatmaps
* Average price by company
* Laptop type analysis

---

## Machine Learning Models Used

### 1. Linear Regression

A baseline regression model used to establish initial prediction performance.

### 2. Decision Tree Regressor

A tree-based regression model capable of learning non-linear relationships.

### 3. Random Forest Regressor

An ensemble learning model that improves prediction accuracy using multiple decision trees.

---

## Model Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Visualization techniques:

* Actual vs Predicted Price Scatter Plot
* Model Performance Comparison Graph
* Residual Error Distribution

---

## Key Insights

* RAM strongly influences laptop pricing
* Premium laptop brands generally have higher average prices
* Gaming laptops are significantly more expensive
* Higher-end GPUs increase laptop prices considerably
* Random Forest achieved the best overall prediction performance

---

## Project Structure

```text
laptop-price-prediction/
│
├── README.md
├── laptop_price_prediction.ipynb
├── laptopData.csv
├── cleaned_laptop_data.csv
│
└── images/
    ├── heatmap.png
    ├── model_comparison.png
    ├── actual_vs_predicted.png
    └── price_distribution.png
```

---

## Future Improvements

* Hyperparameter tuning
* Advanced feature engineering
* Deploying the model using Streamlit or Flask
* Creating an interactive dashboard
* Using advanced boosting algorithms such as XGBoost

---

## Conclusion

This project demonstrates a complete machine learning workflow starting from raw data preprocessing to predictive model evaluation. It highlights practical data science techniques including data cleaning, feature engineering, exploratory analysis, regression modeling, and performance visualization.
