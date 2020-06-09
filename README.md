This project aims at predicting if an online transaction is fraudulent. 
The goal was to keep the false positives to a minimum (high precision)
There were some columns that were highly correlated, so I dropped them if the correlation is 98% or higher. 
I used resampling to generate minority class to handle class imbalance. 
Applied random forest, SVM, AdaBoost and XG boost. XGBoost gave the best precision and recall.
