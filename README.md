# House-Price-Estimation

Estimating House Price by applying variety of ensemble models :

This is very simple, however very good estimator for proprty price.

The Data for property has 110 features, but not all the features have impact on the price.

I have implemented an autotune technique on 4 different regressor ensembles(Random Forest, XGBoost, Catboost and LGBM) and by finding the best hyperparameters through autotune, I have combined the results by using Stacking Regressor.

At the end, you can see the predicted and actual price for the first 20 properties on a plot to appreciate the accuracy of this model. 

Please run __main__.ipynb to see the model.

