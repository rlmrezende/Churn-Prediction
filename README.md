# Customer Churn Prediction for a Bank

## Introduction

This project focuses on predicting customer churn for a bank using machine learning techniques. Churn prediction is an essential task for any business as it can help identify potential churners in time for the business to provide proactive responses.

## Dataset

The dataset used in this project contains information about a bank's customers and whether they churned or not. The features include customer ID, credit score, geography, gender, age, tenure, balance, number of products, whether they have a credit card, whether they are an active member, estimated salary, and whether or not they exited (churned).

## Methodology

The project is implemented in Python using data science and machine learning libraries, including pandas, numpy, seaborn, matplotlib, scikit-learn, and keras.

The steps followed in the project are:

1. **Data Cleaning and Preprocessing**: The dataset was first cleaned and preprocessed, including dealing with missing values, removing unnecessary columns, and encoding categorical variables.

2. **Exploratory Data Analysis**: Conducted an exploratory analysis on the dataset, including distributions, correlations, and visualizations.

3. **Feature Selection and Engineering**: Identified important features and created new features to improve model performance.

4. **Model Training and Evaluation**: Trained and evaluated multiple machine learning models, including Logistic Regression, SVC, K-Nearest Neighbors, Decision Tree, Random Forest, LGBM, and Neural Network. The models were evaluated using accuracy and AUC-ROC.

5. **Hyperparameter Optimization**: Conducted hyperparameter optimization to enhance model performance.

6. **Neural Network**: Trained a Neural Network to improve the prediction performance.

7. **Final Evaluation**: Selected the best model based on performance and used it for the final churn prediction.

## Results

The model achieved good performance in predicting customer churn, with an AUC-ROC of 0.86. However, there is room for improvement, especially in reducing the number of false negatives.

## Future Developments

Future work on this project will focus on improving the neural network model and finding ways to reduce the number of false negatives.