# Predicting-H1N1-and-Seasonal-Flu-Uptake
Implemented a machine learning model to predict the likelihood of individuals receiving H1N1 and seasonal flu vaccinations by implementing data analysis techniques, feature engineering, Hyperparameter tuning using Optuna and classification algorithms to develop the most efficient predictive model and ranked 72 in the Driven Data out of 5500+ competitors. The Stacking Classifier model, using Logistic Regression as the base model and XGBoost and CatBoost as main models, achieved a score of 86.33.

- The main file of this project is **Predicting H1N1 and Seasonal Flu Uptake - EDA and ML implementation (XGBoost and CatBoost).ipynb.** This file included EDA and ML model implementations of XGBoost and CatBoost. The best scores which I got is from XGB and CatBoost is 86.25. ****
- I tried to implement Sequential Feature Selection, but unfortunately, I did not get good scores. So I didn’t concentrate much on Feature Selection and Started focusing on models. Feel free to explore the SFS - XGB file for Feature Selection and Feature Engineering files to get an idea of Feature Engineering.
- XGBoost performed well in H1N1 Vaccine, and CatBoost performed well in Seasonal Flu Vaccine. So I came up with the idea to use Stacking Classifier and implemented it. The guidelines for deploying Stacking Classifier are mentioned below.

This README file provides information about the Stacking Classifier model used for scoring with a score of 86.33. The model utilizes a combination of Logistic Regression as the base model and two main models, namely XGBoost and CatBoost.

The Stacking Classifier is a powerful ensemble learning technique that combines the predictions of multiple base models to make final predictions. It leverages the strengths of each base model and creates a meta-model that learns to combine their predictions effectively.

- Base Model: Logistic Regression
- Main Models: XGBoost and CatBoost
- Score: 86.33

Feel free to modify and experiment with the model to achieve even better results. I tried one basic Feature Engineering combination, and in the beginning, it gave me good results. After increasing the trials in OPTUNA, I achieved the same results. Use the same parameters for Stacking Classifier’s Main models.

Deploy a model and test the model. After that, go back to the EDA and ML notebook and do some analysis for feature engineering.


