# Credit_card_response_model
Predict which customers has high probabilities to respond to the campaign of buying a loan/credit card
🚀 Machine Learning Project: Bank Marketing Response Prediction | EDA to Model Optimization

🎯 Problem Statement

How can banks predict which customers are most likely to subscribe to a term deposit and improve the efficiency of their marketing campaigns?

My objective was to build a classification model that predicts customer subscription outcomes using historical campaign and customer data.

🔍 EDA Highlights

Analyzed 4,119 records and 21 features.

Identified significant target-class imbalance.

Explored customer characteristics, campaign activity, and previous outcomes.

Prepared the data for classification and addressed class imbalance using SMOTE.

🤖 Model Comparison: Test Accuracy

I evaluated multiple classification algorithms and compared their performance on the test set.

Algorithm

Test Accuracy

K-Nearest Neighbors (KNN)

90%

Naive Bayes

85%

Decision Tree

89%

Decision Tree — GridSearchCV

85%

Bagging Classifier

90%

🏆 Bagging Classifier — GridSearchCV

92%

Random Forest

91%

Random Forest — GridSearchCV

85%

AdaBoost

90%

AdaBoost — GridSearchCV

90%

🏆 Best-Performing Model: Tuned Bagging Classifier

The tuned Bagging Classifier achieved 92% test accuracy, with the following subscription-class metrics:

✅ Precision: 65%
✅ Recall: 60%
✅ F1-score: 62%

💡 Key Learning

A high accuracy score doesn't always mean a model is best for a business problem. With imbalanced data, evaluating precision, recall, and F1-score is equally important.

This project strengthened my practical understanding of EDA, feature preprocessing, SMOTE, ensemble learning, hyperparameter tuning, and model evaluation.

I'm continuing to build end-to-end machine learning projects that turn data into actionable business insights. 🚀
