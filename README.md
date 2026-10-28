# Tehran House Price Prediction

## Overview
This project uses machine learning regression techniques to predict residential property prices in Tehran based on housing data. The project covers data exploration, data preprocessing, feature analysis, model development, and performance evaluation.

---

## Objectives
* Explore and understand the housing dataset.
* Identify missing values and investigate data quality.
* Prepare features for machine learning.
* Train and evaluate regression models.
* Analyze prediction errors and model performance.

---

## Project Workflow
1. Load and inspect the dataset.
2. Perform exploratory data analysis.
3. Clean and preprocess the data.
4. Prepare features and the target variable.
5. Split the data into training and testing sets.
6. Train regression models.
7. Evaluate model performance.
8. Interpret results and discuss limitations.

---

## Technologies
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset

The project uses a residential property dataset from Tehran. You can access and download the original dataset on Kaggle:

Kaggle Dataset Link: [Tehran House Price Dataset] 
[https://www.kaggle.com/datasets/valakhorasani/tehran-house-prices-dataset?select=TehranHouse.csv]

---

## Model Evaluation

The regression models were evaluated on unseen test data using three primary metrics: **R² Score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**. 

### Performance Comparison

| Model | R² Score | MAE (Tomans) | RMSE (Tomans) |
| :--- | :---: | :---: | :---: |
| **Ridge Regression** | 0.8641 | 1,303,514,000 | 2,890,779,000 |
| **Random Forest Regressor** | 0.8384 | 1,235,602,000 | 2,603,479,000 |
| **K-Nearest Neighbors Regressor** | 0.7932 | 1,404,327,000 | 2,942,084,000 |
| **Linear Regression** | -4.49 × 10^19 | 1,315,151,000 | 2,899,028,000 |

### Results and Discussion

* **Ridge Regression** achieved the highest R² score of **0.8641**, indicating the strongest overall fit in explaining variance according to this metric among the evaluated models.
* **Random Forest Regressor** achieved the lowest **MAE** and **RMSE**, suggesting that it produced the smallest absolute prediction errors in terms of real-world scale (Tomans) among the reported models.
* **K-Nearest Neighbors Regressor** showed a lower R² score and higher prediction errors compared with Ridge Regression and Random Forest Regressor.
* **Linear Regression** exhibited a severely negative R² score (due to numerical instability or extreme outlier predictions without regularization), highlighting the necessity of regularization techniques like Ridge in this dataset.

---

## Limitations
* Housing prices can vary with location, market conditions, and time.

---

## Author
* **مهرداد راست‌گفتار (Mehrdad Rastgoftar)**
* GitHub:[https://github.com/merco13]
