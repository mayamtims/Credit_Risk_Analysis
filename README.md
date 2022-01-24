# Overview
The purpose of this analysis was to predict how different factors collectively predict whether a loan will be considered high risk or low risk. Credit risk is hard to predict because low risk loans greatly outweigh high risk loans. Multiple different models were trained and evaluated to see whether they are viable tools for predicting credit risk. 

# Results
- Random Oversampling: The balance accuracy score is 64%, the precision is 1% and the recall is 72% for high risk loans
![oversampling](https://github.com/mayamtims/Credit_Risk_Analysis/blob/main/images/oversampling.png)

- SMOTE Oversampling: The balance accuracy score is 66%, the precision is 1% and the recall is 62% for high risk loans
![SMOTE](https://github.com/mayamtims/Credit_Risk_Analysis/blob/main/images/SMOTE.png)

- Undersampling: The balance accuracy score is 60%, the precision is 1% and the recall is 69% for high risk loans
![Undersampling](https://github.com/mayamtims/Credit_Risk_Analysis/blob/main/images/Undersampling.png)

- Combination Sampling: The balance accuracy score is 54%, the precision is 1% and the recall is 72% for high risk loans
![Combination](https://github.com/mayamtims/Credit_Risk_Analysis/blob/main/images/Combination.png)

- Balanced Random Forest Classifier: The balance accuracy score is 78%, the precision is 3% and the recall is 67% for high risk loans
![Forest](https://github.com/mayamtims/Credit_Risk_Analysis/blob/main/images/Forest.png)

- Easy Ensemble AdaBoost Classifier: The balance accuracy score is 93%, the precision is 9% and the recall is 92% for high risk loans
![early](https://github.com/mayamtims/Credit_Risk_Analysis/blob/main/images/early.png)


# Summary
In the first four models we used oversampling, undersampling and a combination of both to try and predict credit risk. In the last two ensemble classifiers were used instead. I would reccomend using ensemble classifier models over over/under sampling models because the balance accuracy score and recall are higher. Out of the ensemble classifier models the Easy Ensemble AdaBoost Classifier model predicts credit risk the best, though its precision is still relatively low at 9%. 