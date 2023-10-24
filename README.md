OVERVIEWED ANALYSIS

The purpose of this analysis is to compare two models exercises one with normal data set and the second with "re-trained" data in order to see if there any differences between them. The data set is from historical lending activity to evaluate loan risk. For this task it is presented a large data set of loans that we need to size in mind and coding, also LinearRegression models needed to be fitted to achive results and visualization of them.


MODEL #1

precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384


MODEL #2

    precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384

As you can see, "0" for model #1 and model #2 didn't change much or any at all, but by retraining data for model #2, we can notice that "1" precision and recall are diferent; precision decreased and recall increase, meaning that the precision of calling a loan "high risk" is minor but more positive about it by being more sure of it.

Personally, I would trust by comparing both models and deciding due to balancing precision/recall between data. If you had me choose, ill chose model #1 because results are good without risking any of it, if this wouldn't be this way ill run the second model and compare for reassurance.