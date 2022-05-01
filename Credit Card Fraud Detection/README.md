# Goal:
Implementtion of different algorithms like random forest, SVM logistic regression, XGBoost and Artificial Neural Network  to see which gives better accuracy.

# Dataset:
https://www.kaggle.com/mlg-ulb/creditcardfraud

# Description: 
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# What I have done:
Analyzed the data and found insights such as correlation, missing values etc.
Selected the columns that have high correlation than other columns to be used as features.
As the dataset was imbalanced, I have balanced the data set and uses different algo for each type of balance
Trained model with algorithms with default parameters:
Logistic Regression
SVM
Random Forest
XGBoost
ANN


# LIBRARIES NEEDED
->Numpy
->Pandas
->Matplotlib
->scikit-learn
->xgboost
->seaborn
-> Tensorflow
-> Tensorflow addons

