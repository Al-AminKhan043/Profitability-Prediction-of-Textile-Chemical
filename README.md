# Profitability Prediction using Machine Learning

This project focuses on a **binary classification problem** for predicting the profitability of textile chemicals. The dataset is collected from three different companies in the textile industry. Several machine learning classifiers have been tested, and the results have been compared to determine the most effective model for predicting profitability.

## Problem Overview

The goal of this project is to predict whether textile chemicals are profitable or not. The dataset contains various features related to the chemicals, and the task is to classify them into two categories: **profitable** or **non-profitable**. To achieve this, we tested multiple classification algorithms and evaluated their performance.

## Models Used

The following **binary classifiers** were used for analysis:

- **Logistic Regression**
- **Random Forest** (best-performing model)
- **Support Vector Machine (SVM)**
- **XGBoost**
- **AdaBoost**
- **Naive Bayes**

### Key Findings

- **Random Forest** achieved the best results, with an accuracy of up to **95%**.
- The Random Forest model was further improved by implementing **stratified sampling** and **quantile-based splitting** to better handle class imbalance.
- The models were evaluated using various metrics, including accuracy, confusion matrix, ROC curve, and AUC.

## Libraries and Dependencies

The following libraries are required to run this project:

- **NumPy**: For numerical operations and data handling.
- **Matplotlib**: For data visualization.
- **Seaborn**: For enhanced data visualization.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning models and evaluation metrics.
- **XGBoost**: For gradient boosting.
- **Imbalanced-learn**: For handling class imbalance.

### Install the dependencies

You can install all required libraries by using the following command:

```bash
pip install -r requirements.txt
