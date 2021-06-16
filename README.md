# Featurization-Model-Selection-Tuning
Read the csv file and check shape, info, and statistical summary of the data
Select columns having data type as object and save it in a new data frame
Check the shape and info of the data frame having only object columns
Check for correlation among the predictors in the original dataset.
Drop irrelevant columns.
Encode above categorical data using get dummiesand drop first.
Separated target column from the features.
Applied Random forest model.
Evaluated above model using accuracy and confusion matrix.
Checked feature importance.
Applied Grid Search to tune important hyperparameters like,n_estimators,criterion, max_depth, and  min_samples_leaf.
K-fold cross validation and check score for random forest model with the best parameters from grid search
