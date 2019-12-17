# Bank_Marketing_Supervised_Capstone_Project

## Objective:
* find out if a client will subscribed the term deposit service or not base on their information
## Methods:
* Algrithms: Knn, random forest, gradient boost, SVM, DecisionTree and logistic regression
* Dimension reduction: PCA
* Prediction measurement: Cross_validation_score, accuracy_score, and confusion matrix
## Conclusion:
* Overall, gradient boosting is the best for both train and test accuracy and consistency. due to the low performance, support vector and decision tree are not suggested. Knn, random forest and logistic regression perform fairly good. There is no significant overfitting problem was found.
* From the explainatory aspect, we should choose KNN.
* There are 26 premary components were used and only represent 80% of the total variance, so a better feature selection may needed.
* For the data exploration, a box plot may needed for removing some potential outliers which will lead an overfit or inaccurate prediction.
* Also, for all the models, it will be worth to pass different functions to tune algorithms.
