# project-09

# Paddy Yield Prediction and Classification Using Machine Learning

## Project Overview

This project analyzes a paddy farming dataset to predict paddy yield and classify farms into high-yield and low-yield groups using machine learning techniques. The dataset includes information on agricultural management, fertilizer application, irrigation, weather conditions, soil characteristics, and farming practices.

The project also applies multiple feature selection methods to identify the most informative variables and evaluates their impact on classification performance.

---

## Research Questions

1. Can machine learning accurately predict paddy yield?
2. Can farms be classified into high-yield and low-yield groups?
3. Which agricultural and environmental factors contribute most to paddy yield?
4. Does feature selection improve classification performance?

---

## Dataset

The dataset contains **2,789 observations** and **45 original variables**, including:

* Farm information
* Land preparation
* Nursery management
* Fertilizer application
* Weed and pest control
* Irrigation
* Rainfall
* Temperature
* Wind speed and direction
* Relative humidity
* Paddy yield (target variable)

A new variable, **Yield per Hectare**, was calculated to classify farms into **High Yield** and **Low Yield** using the median yield per hectare.

---

## Data Preprocessing

* Loaded and explored the dataset
* Checked data types and summary statistics
* Created Yield per Hectare
* Generated a balanced binary classification target
* Standardized numerical features
* One-hot encoded categorical variables
* Split data into training and testing datasets

---

## Machine Learning Models

### Regression Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Classification Models

* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes

---

## Feature Selection Methods

Five feature selection techniques were applied:

* Backward Elimination
* Stepwise Forward Selection
* Random Forest Feature Importance
* Exhaustive Feature Selection
* Gradient Boosting Feature Importance

The selected features were merged using Poincaré's formula (set union) to create a refined dataset for the final classification models.

---

## Model Evaluation

### Regression Metrics

* MAE
* RMSE
* R² Score

### Classification Metrics

* Accuracy
* ROC AUC
* Precision
* Recall
* F1-score
* Confusion Matrix


---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* MLxtend

---

## Project Structure

* Data Loading and Exploration
* Data Preprocessing
* Regression Modeling
* Classification Modeling
* Feature Selection
* Refined Feature Construction
* Final Model Evaluation
* Conclusions

---
