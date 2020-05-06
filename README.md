Notebooks for the HousePricing (https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

Trying the fastai __TabularLearner__ with some manual preprocessing, which results in a RMLSE of 0.1326. __XGBoost__  performs way better on that (preproced) data with a RMLSE of 0.11775. 

When ensembled (80/20,xgboost/nn) it reaches 0.11675. 

To imporve: finetune the NN to reach a similar performance as the GradientBoost model.
