# bank-marketing-classification

Comparing Classifiers: Bank Marketing Campaign
Overview
This project compares four classification models:
K-Nearest Neighbors (KNN)
Logistic Regression
Decision Tree
Support Vector Machine (SVM)
The goal is to predict whether a customer will subscribe to a term deposit after a phone-based marketing campaign.
Business Problem
A bank wants to improve the efficiency of its telephone marketing campaigns. By identifying customers who are more likely to subscribe, the bank can focus outreach efforts more effectively, reduce unnecessary calls, and improve conversion rates.
Dataset
The data comes from the UCI Bank Marketing dataset, based on direct marketing campaigns from a Portuguese banking institution.
Models Compared
Logistic Regression
KNN
Decision Tree
SVM
Evaluation Metric
Because the dataset is imbalanced, accuracy alone is not enough. This project emphasizes:
Recall
F1-score
ROC-AUC
Recall is especially important because missing likely subscribers means lost business opportunities.
Summary of Findings
Logistic Regression performed well and was highly interpretable.
Decision Tree was easy to explain but more prone to overfitting.
KNN was computationally heavier and less practical on larger data.
SVM performed competitively but required more computation and tuning.
Overall, the best model should be selected based on a balance of predictive performance and business interpretability.
Business Recommendations
Use the top-performing model to prioritize likely subscribers.
Focus campaign resources on high-probability customers.
Continue testing more advanced ensemble methods in future work.
