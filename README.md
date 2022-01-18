# CreditRiskLoan_Classification


Methodology Description
The model will be measured using F1 between the predicted results and the original label/class.

True Positive (TP) = your prediction is 1, and the ground truth is also 1
False Positive (FP) = your prediction is 1, and the ground truth is 0
False Negative (FN) = your prediction is 0, and the ground truth is 1

Predict whether the user/customer will default (label = 1) or vice versa (label = 0)
Models with the extension .py
Prediction results in .csv format with the format:
customer_id, default
9365, 0
999, 0
2835, 1
…, …
3190, 1

The score that is filled in during the submission is the F1 Score that is predicted to the training data (training to training).
