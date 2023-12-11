# credit-risk-classification
# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis is to develop and evaluate machine learning models for credit risk classification. The dataset used includes financial information related to loan applications, and the goal is to predict whether a loan is healthy (`0`) or high-risk (`1`). The variables of interest include features such as credit scores, loan amounts, and employment lengths. The analysis follows standard machine learning processes, including data preprocessing, feature selection, and model training.

**Stages of the machine learning process:**

1. **Data Preprocessing:** Checked for missing values, encoded categorical variables, and scaled numerical features.
2. **Data Splitting:** Split the data into training and testing sets.
3. **Model Training:** Utilized logistic regression for credit risk classification.
4. **Model Evaluation:** Evaluated model performance using balanced accuracy, precision, recall, confusion matrix, and classification report.

## Results

* **Logistic Regression Model:**
  * Balanced Accuracy Score: 0.952
  * Precision (Healthy Loan - `0`): 1.00
  * Recall (Healthy Loan - `0`): 0.99
  * F1-Score (Healthy Loan - `0`): 1.00
  * Precision (High-Risk Loan - `1`): 0.85
  * Recall (High-Risk Loan - `1`): 0.91
  * F1-Score (High-Risk Loan - `1`): 0.88

## Summary

The logistic regression model demonstrates exceptional performance in credit risk classification. It achieves a high balanced accuracy score of 95.2%, indicating effectiveness in handling imbalanced datasets. The precision and recall scores for both healthy and high-risk loans are commendable, with a perfect precision score for healthy loans. This model is recommended for use by the company due to its overall robustness and ability to accurately predict credit risk.

Performance may depend on the specific business goals. If the focus is on minimizing false negatives (misclassifying a high-risk loan as healthy), the model performs well with a recall of 0.91 for high-risk loans. Conversely, if precision is crucial (avoiding false positives), the model excels with a precision of 1.00 for healthy loans. Ultimately, the choice depends on the company's risk tolerance and specific objectives.

The logistic regression model is recommended for its well-rounded performance and interpretability. It strikes a balance between precision and recall, making it a reliable tool for credit risk assessment.
