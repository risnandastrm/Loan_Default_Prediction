# Loan_Default_Prediction

In the banking sector, the Bank get large of income from loan transactions.
But loan transactions comes with a high risk. Sometimes the borrowers fail to pay, it can be called default.
To solve this problem, the bank uses Machine Learning to predict which customers will default based on the past data about loans transactions.

Through machine learning approach, the algorithm used is XGBoost with feature selection with Variance Inflation Factor (VIF). The scores obtained after hyperparameter tuning using RandomizedGridSearchCV is  
- AUC Score: 99.8% 
- Recall Score: 97.8% 
- FPR Score: 1.1%.
