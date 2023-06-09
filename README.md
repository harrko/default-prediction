# Consumer Loan Default Prediction
The goal of this project is to predict loan default given the characteristics of the borrowers and terms of the loans. The underlying dataset is the LendingClub consumer loan dataset which is available on Kaggle.<br> <br>
As a first step, features are selected, cleaned and preprocessed into dummy variables. A new good / bad ground truth label is created by combining different loan status categories. Then a logistic regression model is fitted to the data and evaluated. Afterwards the same data is used to train and evaluate a XGBoost classifier. <br><br>
Both models yield similar results with AUROC scores of 0.75.
