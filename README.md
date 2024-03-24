# credit-risk-classification

## Overview
This project aims to build and evaluate machine learning models to classify the risk associated with loans. Using historical data from a peer-to-peer lending services company, the project focuses on predicting whether a loan will be paid off on time or is at high risk of default. Through logistic regression, I assess the creditworthiness of borrowers based on various financial indicators, including loan size, interest rates, borrower income, and more.

## Objectives
To utilize logistic regression to classify loans into "healthy" or "high-risk" categories.
To evaluate the model's performance using accuracy, precision, recall, and F1-score metrics.
To provide insights and recommendations based on the model's predictive capabilities.

## Dataset
The dataset contains historical lending activity, featuring columns like loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The loan_status column, which indicates whether a loan is healthy (0) or at high risk of defaulting (1), is used as the target variable for model prediction.

## Methodology
Data Preparation: Split the data into features (X) and labels (y). Then, divide the dataset into training and testing sets.
Model Building: Fit a logistic regression model using the training data.
Model Evaluation: Use the testing set to evaluate the model's performance. Generate and analyze the confusion matrix and classification report to assess accuracy, precision, recall, and F1-scores.

## Results
The logistic regression model demonstrated excellent performance, with a high overall accuracy of 99%. The model showed remarkable precision in identifying healthy loans and was highly effective in recalling high-risk loans. Detailed metrics include:

Accuracy: 99%
Precision for Healthy Loans (0): 1.00
Recall for Healthy Loans (0): 0.99
Precision for High-Risk Loans (1): 0.85
Recall for High-Risk Loans (1): 0.91

## Conclusion
The logistic regression model proves to be a robust tool for classifying loans into healthy and high-risk categories. Given its high precision and recall scores, it is recommended for assessing loan applications to enhance the lending company's decision-making process and risk management. The model's ability to accurately predict high-risk loans can significantly mitigate potential defaults, thereby safeguarding the company's financial health.

## Installation
To run this project, ensure you have Python installed along with the following libraries:
- Pandas
- Numpy
- Scikit-learn
- Matplotlib (optional for additional data visualization)
- Clone this repository and navigate to the project directory. Run the Jupyter notebook to replicate the analysis and view the model's performance.

  
