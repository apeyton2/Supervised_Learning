# Supervised_Learning
In this project we sought to use Logistical regression to classify loans as healthy or high risk to determine if they're worth persuing. This analysis was done on loan atributes like total debt, loan size etc.

# Results
## Model 1: Original Data

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
    macro avg      0.92      0.95      0.94     19384
    weighted avg   0.99      0.99      0.99     19384
On average the model is 95% accurate. It is more accurrate with detecting healthy lones than the high risk loans

## Model 2: Oversampled data

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
    macro avg      0.92      0.99      0.95     19384
    weighted avg   0.99      0.99      0.99     19384
The model trained with the oversampled data preformed much better on the high risk loan in recall but was slightly less precise.
# Summary
The oversampled data performs better than the original data in the macro average. For this problem were mostly looking to accurately classify risky loans, so in Model 2 we see an increase in recall to 99% for the high risk loans.
