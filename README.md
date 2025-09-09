 House Prices — Advanced Regression Techniques

A Kaggle-style machine learning project focused on predicting house prices using a variety of regression models including Ridge Regression, Neural Networks.

 Overview

This project tackles the classic House Prices: Advanced Regression Techniques problem using real-world housing data. The goal is to predict final sale prices of homes based on various features, testing multiple model pipelines and comparing their performance.

 Contents

train.csv, test.csv: Original dataset

House prices advanced Regression (3).ipynb: Main notebook with preprocessing, modeling, and evaluation

predicted_results_ridge_log.csv: Final predictions using best-performing model

sample_submission.csv: Sample format for submissions

model_results.csv: Summary of evaluation metrics for all models

README.md: You're here!

LICENSE: MIT License

 Models Tried

 Ridge Regression (Best overall performance)

 Neural Networks (Baseline & tuned)

 Unlogged predictions (worse performance)

 Feature scaling + OneHotEncoding for preprocessing

 Best Model

Model: ridge_log

Val RMSE ($): ~25,863

Val MAE ($): ~16,647

Reason: Low error, fast training, no overfitting

 Evaluation Strategy

Models were compared using:

RMSE and MAE in log space

RMSE and MAE in dollar space (converted via np.expm1)

Average rank across metrics to find the overall best model

 Results Visualization

Model leaderboard generated using matplotlib to compare RMSE ($) and ranks.

 Tools & Libraries

Python 3.10+

NumPy, Pandas, Matplotlib

scikit-learn

TensorFlow / Keras



 Related Links

 Kaggle Competition Page : https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

 
