# Titanic Survival Prediction using Machine Learning

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.8.5-green.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/framework-Scikit--Learn-orange)](https://scikit-learn.org/)

## Overview
🚢 This project utilizes machine learning techniques to predict the survival status of passengers on the Titanic. The dataset includes information such as passenger class, age, gender, fare, and more.

![Titanic Ship](https://i.ytimg.com/vi/2fExV5KHU9s/maxresdefault.jpg)

## Data Analysis
- Explored the dataset to understand the distribution of missing values.
- Visualized features like age, sex, passenger class, siblings, and fare to gain insights.
- Handled missing data by filling missing ages based on passenger class mean values.
- Removed the 'Cabin' column due to excessive missing values.

## Data Preprocessing
- Encoded categorical variables like 'Sex' and 'Embarked' into binary values.
- Dropped unnecessary columns like 'Name,' 'Sex,' 'Ticket,' and 'Embarked.'
- Created new columns based on encoded values for further analysis.

## Model Building
- Used Logistic Regression to build the predictive model.
- Split the dataset into training and testing sets.
- Trained the model on the training set and made predictions on the test set.

## Analysis and Results
- Evaluated the model using classification metrics like confusion matrix and F1 score.
- The model's performance indicates the accuracy of survival predictions.

![Titanic Survival Infographic](https://static1.squarespace.com/static/5006453fe4b09ef2252ba068/t/5090b249e4b047ba54dfd258/1351660113175/TItanic-Survival-Infographic.jpg?format=1500w)

