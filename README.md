# credit-risk-classification


Comprehensive Analysis Overview

The purpose of this analysis is to create a supervised machine learning model that predicts if a loan is healthy (class 0) or high-risk (class 1). We used logistic regression as a binary classifier.  
The goal was to predict loan status — either a healthy loan (0) or a high-risk loan (1).


Steps of the machine learning process:

    •    Split the data into labels and features (loan status as the label).
    •    Split the data into training and testing sets.
    •    Built a Logistic Regression model using sklearn.
    •    Fit the model with the training data.
    •    Made predictions with the test data.
    •    Evaluated model performance using accuracy, precision, recall, and f1-score.

Results

Model Performance
    •    Accuracy:
The model’s overall accuracy is 0.99, meaning it correctly classified 99% of the loans.
    •    Precision:
    •    High-Risk Loan (class 1): 1.00
    •    Low-Risk Loan (class 0): 0.87
    •    Recall:
    •    High-Risk Loan (class 1): 1.00
    •    Low-Risk Loan (class 0): 0.95

Summary

The logistic regression model does an excellent job predicting high-risk loans (class 1), with precision and recall both at 1.00, meaning it almost perfectly identifies high-risk loans. For healthy loans (class 0), the model also performs very well, with a precision of 0.87 and a recall of 0.95.
The slightly lower precision for healthy loans could be because of the imbalanced dataset. There were many more high-risk loan examples than healthy ones to train on, which could have affected the model’s performance slightly. However, overall the model is very strong.
