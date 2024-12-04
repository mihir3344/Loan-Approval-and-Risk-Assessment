# Project Overview

This project develops a machine learning model to predict loan approval outcomes and assess the risk associated with each loan application. Using a dataset of 20,000 loan applications with 36 features, the model evaluates financial, demographic, and credit factors to predict loan approval and classify applicants based on risk.

## Features of the Dataset
The dataset contains the following 36 features:

- **Demographic Information**: Age, Marital Status, Education Level, Number of Dependents  
- **Financial Information**: Annual Income, Loan Amount, Credit Score, Monthly Debt Payments  
- **Credit History**: Bankruptcy History, Previous Loan Defaults, Payment History, Credit Card Utilization  
- **Other Factors**: Home Ownership Status, Job Tenure, Length of Credit History, etc.

## Model Used
**Machine Learning Models**:
- Logistic Regression
- Random Forest
- Decision Tree
- Gradient Boosting
- AdaBoost
- Multi-layer Perceptron (MLP)

**Evaluation Metrics**:
- Accuracy
- Precision
- Recall
- F1-score

## Results
The project achieved an accuracy of up to **99%** in predicting loan approvals and assessing risk, with detailed classification reports available for each model used.
| Model                        | Accuracy | Precision | Recall | F1 Score |
|------------------------------|----------|-----------|--------|----------|
| Logistic Regression L2        | 0.9640   | 0.99      | 0.97   | 0.98     |
| Logistic Regression L1        | 0.9640   | 0.99      | 0.97   | 0.98     |
| Support Vector Classifier     | 0.9865   | 0.99      | 0.99   | 0.99     |
| Linear SVC                    | 0.9635   | 0.99      | 0.97   | 0.98     |
| Random Forest                 | 0.9487   | 0.97      | 0.96   | 0.97     |
| Decision Tree                 | 0.9170   | 0.95      | 0.93   | 0.94     |
| Gradient Boosting             | 0.9557   | 0.99      | 0.95   | 0.97     |
| AdaBoost                      | 0.9595   | 0.99      | 0.96   | 0.97     |
| Gaussian Naive Bayes          | 0.8922   | 0.96      | 0.89   | 0.93     |
| Multi-layer Perceptron (MLP)  | 0.9950   | 1.00      | 1.00   | 1.00     |


## Conclusion
This project demonstrates the effectiveness of machine learning in financial risk assessment and loan approval prediction, aiding in data-driven decision-making for financial institutions.
