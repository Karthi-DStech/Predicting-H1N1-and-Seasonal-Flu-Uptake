# Predicting-H1N1-and-Seasonal-Flu-Uptake 
<h3> -> Rank 20th out of 6500+ Competitors | Scores : 86.43 </h3>
<h3> -> Driven Data Username : Karthi_DataScience</h3>

<img width="1447" alt="Screenshot 2024-09-24 at 20 44 10" src="https://github.com/user-attachments/assets/fb263607-82e7-43ab-938d-6aa4203e1cb9">

Implemented a machine learning model to predict the likelihood of individuals receiving H1N1 and seasonal flu vaccinations by implementing data analysis and preprocessing techniques, feature engineering, Hyperparameter tuning using Optuna, and advanced classification algorithms to develop the most efficient predictive model and **ranked 20th in the Driven Data out of 6500+ competitors**. 

- The main file of this project is **Predicting H1N1 and Seasonal Flu Uptake - EDA and ML implementation (XGBoost and CatBoost).ipynb.** This file includes ML model implementations of XGBoost and CatBoost. The best scores I got from XGB and CatBoost are 86.25 and 86.22.
  
- The **EDA.py** has all the necessary **Exploratory Data Analysis** and **EDA with labels.py**  has all the necessary **Exploratory Data Analysis with labels**
  
- The **missing value Analysis and imputation.py** includes the analysis of missing values and methods for imputation.
  
- I tried to implement **Sequential Feature Selection**, but unfortunately, I did not get good scores. So I didn’t concentrate much on Feature Selection and Started focusing on models. Feel free to explore the SFS - XGB file for Feature Selection.
  
- XGBoost performed well in the H1N1 Vaccine, and CatBoost performed well in the Seasonal Flu Vaccine. So I came up with the idea to use a Stacking Classifier and implemented it. The guidelines for deploying the Stacking Classifier are mentioned below.

This README file provides information about the Stacking Classifier model used for scoring with an ROC-AUC score of 86.43. The model utilizes a combination of Logistic Regression as the base model and two main models, namely XGBoost and CatBoost.

The Stacking Classifier is a powerful ensemble learning technique that combines the predictions of multiple base models to make final predictions. It leverages the strengths of each base model and creates a meta-model that learns to combine their predictions effectively. **The Stacking Classifier model, using Logistic Regression as the base model and XGBoost and CatBoost as the main models, achieved a score of 86.37.**

<h3>
- Base Model: Logistic Regression
- Main Models: XGBoost and CatBoost
- Score: 86.43 
</h3>


Feel free to modify and experiment with the model to achieve even better results. I tried one basic Feature Engineering combination, and in the beginning, it gave me good results. After increasing the trials in OPTUNA, I achieved the same results. Use the same parameters for the Stacking Classifier’s Main models.

Train a model until it reaches the saturation point and after that, go back to the EDA notebook. Do some analysis for feature engineering and start training. 


