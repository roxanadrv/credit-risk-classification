# Module 20- Credit Risk Classification Report

## Overview of the Analysis

The purpose of this analysis was to leverage machine learning to improve the process of assessing loan risk. Utilizing a dataset of historical lending activity from a peer-to-peer lending services company, I aimed to build a model that could accurately predict the creditworthiness of borrowers. This involved distinguishing between loans likely to be paid off on time and those with a high risk of default (as indicated by the loan_status variable).

The dataset encompassed various financial indicators, such as loan size, interest rates, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The challenge lay in predicting the binary outcome reflected in loan_status, where 0 denotes a healthy loan and 1 signifies a high-risk loan.

The machine learning process unfolded in several stages, starting with data preparation where I split the data into features (X) and labels (y). Subsequently, I divided the dataset into training and testing sets to evaluate the model's performance on unseen data. I employed logistic regression, a robust algorithm suitable for binary classification tasks, to fit the model using the training data and then tested its accuracy and predictive power on the testing set.

## Results

The performance metrics for the logistic regression model are as follows:

Logistic Regression Model:
- Accuracy: The model achieved an overall accuracy of 99%, indicating a high level of reliability in its predictions across both categories of loans.
- Precision for Healthy Loans (0): Precision was 1.00, meaning the model correctly identified 100% of the loans it predicted as healthy.
- Recall for Healthy Loans (0): Recall was 0.99, suggesting the model successfully captured 99% of all actual healthy loans.
- F1-Score for Healthy Loans (0): The F1-score was 1.00, reflecting the excellent balance between precision and recall for healthy loans.
- Precision for High-Risk Loans (1): Precision was 0.85, indicating 85% correctness for high-risk loan predictions.
- Recall for High-Risk Loans (1): Recall stood at 0.91, showing the model identified 91% of all actual high-risk loans.
- F1-Score for High-Risk Loans (1): The F1-score was 0.88, denoting a solid balance between precision and recall for high-risk loans.

## Summary

The logistic regression model exhibited well performance metrics, demonstrating its efficacy in classifying loans into healthy and high-risk categories. The high accuracy, precision, and recall scores across both loan statuses underscore the model's ability to serve as a reliable tool for assessing borrower creditworthiness.

Given the stakes involved in loan issuance decisions, the precision and recall scores are particularly noteworthy. The model's high precision for healthy loans ensures minimal false positives, which is crucial for avoiding undue denial of loans. Meanwhile, its high recall for high-risk loans means it is adept at identifying loans that are likely to default, allowing lenders to take preemptive action to mitigate risk.

Considering these factors, I recommend the deployment of this logistic regression model for evaluating loan applications in the peer-to-peer lending services company. Its robust performance, particularly in identifying high-risk loans, could significantly enhance the company's risk management capabilities. While no model is infallible, the strengths of this logistic regression approach—reflected in its precision, recall, and overall accuracy—make it a valuable asset for making informed lending decisions.
