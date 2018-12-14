# CS229-Zestimate-Bazinga-Project
This repository contains the code used for the CS229 project models built for predicting selling price for condos in downtown Vancouver.

*Data import and cleansing.ipynb* : script for data import (*df_775feat.csv*). It does data processing, cleansing, standardization and feature engineering; produces the *df_48feat.csv* file used for further data exploration and modeling.

*48_features_LR_CV.ipynb*: script for benchmarking Linear Regression implementation on 48 features. Uses 5-fold cross validation for MSE reporting.

*48_features_lasso_LR.ipynb*: Lasso regularization implementation on 48 features, uses 5-fold CV.

*48_features_RegressionTree_CV.ipynb*: Regression tree implementation on 48 features, uses 5-fold CV. Max tree depth is set to 10.

*48_features_Random Forest_CV.ipynb*: Random forest implementation on 48 features, uses 5-fold CV. Max tree depth is set to 10.

*48_features_CVsetup_Gradient Boosting.ipynb*: Gradient boosting implementation on 48 features, uses 5-fold CV. Gradient search is used to optimize the parameters.

All scripts above produce learning curve plots.

*48_features_neural_network.ipynb*: Google collab notebook, neural network implementation with Tensorflow.
