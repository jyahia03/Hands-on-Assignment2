# New York House Price Prediction and Classification

## Overview
This project aims to predict and classify house prices in New York using machine learning techniques. I implemented regression models to estimate house prices and classification models to categorize them as "high" or "low" based on the median price.

## Process
1. Data Preprocessing
   - Loaded and cleaned the dataset.
   - Split the data into training and testing sets for model evaluation.

2. Regression Modeling
   - Built and evaluated five regression models:
     - Linear Regression
     - Random Forest Regressor
     - Gradient Boosting Regressor
     - Ridge Regression
     - Lasso Regression
   - Evaluation metrics included:
     - Mean Squared Error (MSE)
     - R² Score
   - The Gradient Boosting Regressor performed the best in predicting house prices.

3. Classification Modeling
   - Created binary categories for house prices based on the median:
     - "High" (prices above or equal to the median)
     - "Low" (prices below the median)
   - Trained five classifiers:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors
     - Gradient Boosting Classifier
   - Evaluation metrics included:
     - Accuracy
     - Precision
     - Recall
     - F1-score
   - The Gradient Boosting Classifier achieved the best results for classification.

4. Conclusion
   - Gradient Boosting models (both regressor and classifier) outperformed others in this project, making them the most effective methods for predicting and classifying house prices in this dataset.

## Files
- The regression model contains the code for building and evaluating regression models.
- The classification model contains the code for building and evaluating classification models.
- The dataset used for this project.

## Summary
This project demonstrates various techniques for house price prediction and classification. Gradient Boosting models provided the best performance, highlighting their effectiveness with this dataset.
