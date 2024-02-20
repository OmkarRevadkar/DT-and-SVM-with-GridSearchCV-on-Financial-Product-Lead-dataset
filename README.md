DT (Decision Tree) & SVM (Support Vector Machine) are supervised machine learning classification algorithms and both the algorithms have been used individually to build the model. The dataset used here is regarding Financial Product Lead.
Keeping in view the target variable for this dataset i.e customers, precision score (an evaluation parameter) becomes our top most priority and we need to ensure its highest value as per the problem statement.
GridSearchCV() has been used to perform suitable hyperparameter tuning so that we get the best model built on both the algorithms.
Adequate care has also been taken off during data cleaning process by maintaining the order of the ordinal data so that the machine generates meaningful productive insights and does not give false insights/impressions. 

Following basic steps are executed as usual:

1. Understand the problem statement/requirement.
2. Import the necessary libraries.
3. Load the dataset.
4. Data pre-processing.
5. Random Sampling with train test split.
6. Build the model on train data.
7. Use Tradeoff/GridSearchCV to perform the best hyperparameter tuning.
8. Test the model on test data.
9. Build the confusion matrix and evaluate the model using various evaluation parameters.
10. Re-run the model from some previous steps if required.
