# capstone-project-on-yes-bank-stock-prices

Project Summary -
Introduction

This is Almabetter's capstone project on ML-Regression problem. In this project we are going to work on Yes bank’s stock price dataset. Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in news because of the fraud case involving Rana Kapoor. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest and lowest stock prices of every month. The main objective is to predict the stock's closing price of the month.

Objective

The objective of this project is to predict the stock's closing price of the month.

To Do List

To achieve the objective of the project we need to do perform exploratory data analysis, Hypothesis testing, some data manipulation and feature engineering, data preprocessing, model implementation and several other things mentioned below.

1. Import Libraries

Main libraries to be used:

Pandas for data manipulation and aggregation.
Matplotlib and Seaborn for visualization.
Numpy for computationally efficient operations.
Scikit learn for model training, model optimization and metrics calculation.
2. Know Your Data

Load Dataset
Dataset first look
Rows & Columns count
Check for duplicate and null values
3. Understanding Your Variables

Variables description
Check Unique Values for each variable
4. Data Cleaning

Fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. Dataset can contain missing data, numerical string value, various cues. If we can clean them, It will make our analyzing process easy.

5. Exploratory Data Analysis

Data wrangling
Visualization
Storytelling and experimenting with charts
Understand the relationships between variables
6. Hypothesis Testing

Based on our EDA, we will define 3 hypothetical statements from the dataset and peform hypothesis testing to obtain final conclusion about the statements.

7. Feature Engineering & Data Pre-processing

Handling missing values
Handling Outliers
Categorical encoding
Textual data preprocessing
Feature manipulation and selection
Data transformation
Data scaling
Dimensionality reduction
Data splitting
Handling imbalanced data
8. ML Model Implementation

Implementation
Explain the ML Model used and it's performance using Evaluation metric Score Chart.
Cross- Validation & Hyperparameter Tuning
ML models we are going to use:

Linear regression
Ridge, Lasso and ElasticNet for Regularization
Random Forest Regressor
XGboost Regressor
9. Explain the model using SHAP model explainability tool.

SHAP(SHapley Additive exPlanations) is a model explainability tool to explain the predictions of machine learning models. It is based on the concepts of game theory and can be used to explain the predictions of any machine learning model by calculating the contribution of each feature to the prediction.




Conclusion

Let's see what we did and what we got in this project in a nutshell.
What We Did :-
The objective of this project was to predict the stock's closing price of the month and to achieve the objective,
we started with importing required libraries and load the dataset. than performed EDA(exploartory data analysis) analyze outliers did some data manipulation hypothesis testing feature engineering and data preprocessing Ml model implementation and record the evaluation metric scores and in the end explain the model using SHAP model explainability tool. ML models we used:
Linear regression Ridge, Lasso and ElasticNet for Regularization Random Forest Regressor XGboost Regressor
What We Got :-
*important Instances & Observations we discovered after analyzing the yes bank's stock price datasets
*Given dataset has neither missing values and nor outliers.
*In year of 2017 and 2018 stock prices were at their peak.
*All time high was 404, it was in 2018.
*All time low was 5.55, it was in 2020.
*From 2016 to 2018, price is increased at high rate.
*After 2018 price is decreased at very high rate.
*In 2019 and 2020 also, price is continuously decreasing.
*All open, high, low and close price has positively skewed distribution.
*All open, high, low and close has strong correlation with eachother.
*All Open , high and low has strong linear relationship with dependent variable.
Observations while model implementation
Our first and base model was Linearregression, and got a decent training and testing score of 0.82 and 0.76 respectively with high MSE and MAE metric score.
Than we implemented Ridge, lasso and ElasticNet regulization models and Lasso model found out as a better model with 0.83 r2-score and MSE and MAE was also very low as compared to base model.
than we tried Polyfit model which was giving a pretty good result but was performing very bad in cross-validation.
Than we implemented Random Forest Regressor and XGboost Regressor, both of them were performing far better than other previous models at every metric.
