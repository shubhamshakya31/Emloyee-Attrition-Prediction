# Employee Attrition Prediction

## Overview

This project focuses on predicting employee attrition, using machine learning techniques to understand and forecast why employees leave a company. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, and the application of various machine learning models, including Logistic Regression, Random Forest Classifier, and a deep learning model using TensorFlow.

### Problem Statement

Employee attrition is a critical issue for organizations, impacting productivity and increasing recruitment costs. Predicting which employees are likely to leave can help organizations take proactive measures to retain valuable talent. This project aims to develop a model that accurately predicts employee attrition based on various features.

## Data Cleaning

Data cleaning was an essential step to ensure the dataset's quality and reliability. The raw dataset included missing values, inconsistencies, and outliers. The following steps were performed:

- **Handling Missing Values**: Missing values were imputed using appropriate strategies such as mean, median, or mode, or by removing records with excessive missing data.
- **Outlier Detection and Removal**: Outliers in continuous variables were identified and removed to prevent distortion in the model.
- **Standardization**: Standardized categorical variables and fixed formatting inconsistencies to ensure uniformity across the dataset.

## Exploratory Data Analysis (EDA)

EDA was conducted to understand the data better and to uncover patterns and relationships. The analysis included:

- **Distribution Analysis**: Examined the distribution of key features such as age, salary, and tenure to understand their spread and central tendencies.
- **Correlation Analysis**: Used heatmaps to visualize correlations between numerical features and the target variable (attrition), identifying influential factors.
- **Feature Relationships**: Explored the relationship between categorical features (e.g., department, job role) and attrition using various visualizations.
- **Insights**: Documented key findings such as the impact of job satisfaction and work environment on attrition to guide feature selection and model development.

## Feature Engineering

Feature engineering was performed to prepare the data for modeling:

- **One-Hot Encoding**: Applied one-hot encoding to categorical variables like department, job role, and marital status to convert them into numerical format.
- **Feature Scaling**: Scaled numerical features to ensure they contributed equally to the model.
- **Feature Selection**: Based on EDA insights, irrelevant or redundant features were dropped to improve model performance.

## Model Building

The dataset was used to build and evaluate several machine learning models for predicting employee attrition:

- **Logistic Regression**: Used as a baseline model due to its interpretability and effectiveness in binary classification problems.
- **Random Forest Classifier**: Applied to capture complex relationships and interactions between features.
- **Deep Learning Model**: Implemented using TensorFlow to explore more advanced modeling techniques.

### Model Evaluation

The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The logistic regression model achieved the highest accuracy, demonstrating its effectiveness in predicting employee attrition compared to other models.

## Results

The results of the model evaluations are as follows:

- **Logistic Regression**: Achieved the highest accuracy of 89%, showing strong performance in predicting employee attrition.
- **Random Forest Classifier**: Provided competitive performance but with slightly lower accuracy compared to logistic regression.
- **Deep Learning Model**: Although more complex, it did not outperform logistic regression in this case.

These results indicate that logistic regression is the most effective model for this particular dataset and problem.

## Conclusion

This project demonstrates the process of developing a predictive model for employee attrition. Logistic regression was identified as the most effective model, offering valuable insights into employee turnover and helping organizations make data-driven decisions to improve retention strategies.


