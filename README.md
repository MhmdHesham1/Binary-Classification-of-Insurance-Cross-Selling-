Binary Classification of Insurance Cross-Selling

This project aims to build and evaluate models for binary classification in the context of insurance cross-selling. The objective is to predict whether a customer will buy a product or not, based on the given features.
Table of Contents

    Installation
    Data
    Data Cleaning
    Feature Selection
    Model Training and Evaluation
    Results
    Contributing
    License

Installation

Ensure you have the following Python libraries installed:

    pandas
    scikit-learn
    xgboost
    catboost

Data

The dataset used in this project is provided in a CSV file. The data includes various features related to customers and the target variable Response, which indicates whether the customer bought the product (1) or not (0).
Data Cleaning

Data cleaning involves handling missing values and encoding categorical variables.
Feature Selection

Features are selected by dropping irrelevant columns such as id and the target variable Response. The dataset is then split into training and testing sets.
Model Training and Evaluation
XGBoost

An XGBoost classifier is trained on the training data.
CatBoost

A CatBoost classifier is trained and used for predictions.
Results

Evaluate the model performance using appropriate metrics like accuracy, precision, recall, and F1-score.
Contributing

If you would like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.
License

This project is open-source and available under the MIT License.
