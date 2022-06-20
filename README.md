# Heart-Failure-Prediction-with-Machine-Learning
Creating ML model using "Heart Failure Prediction Dataset" (from kaggle.com) to predict Heart failure of patients.


The data is downloaded from https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

Here I created two different model that both can predict heart failure with 0.88 F1-score. 

The steps:

- Cleaning the data
- Exploratory data analysis
- Scale the features (StandardScaler)
- Model selection, tested models were:
  *   RandomForest
  *   Logistic Regression
  *   Support Vector
  *   KNeighbors
  *   xgboost
  *   Gaussian Naive Bytes Classifier
- Hyperparameter tuning for Support Vector classifier.
- Build another model with Deep learning.
- Identify the importance of the features using SHAP.
