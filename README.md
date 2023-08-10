- In this project, we built All Classifier models on one bank data: default_credit_card_data. First, we did pre-processing. 
Note: Before the conversion part, we created three data,because we will use two different conversion methods and check which one is better for model prediction :
1) data_w = going to convert with woe transformation
2) data_d = going to convert with the dummies method
3) data_cb = for the Catboost model with categoric columns include.
   
After that, we built Logistic Regression, Random Forest Classifier, SVM, Catboost, XGBM and Stacking models. We built the Catboost model first with categoric columns included. And also, after conversion with the dummies method. We also, use hyperparameters to optimize our models. 
