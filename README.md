# Horse Health Prediction

This project aims to predict health outcomes of horses based on various features using machine learning techniques. Below is a comprehensive overview of the steps involved in the project:

## Initial Setup and Data Exploration
Importing Libraries: All necessary libraries for data manipulation, visualization, preprocessing, model training, and evaluation are imported.

Reading Data: The training and test datasets are loaded, concatenated, and explored for initial insights including shape, first few rows, and missing values.

Target Variable Distribution: Visualizing the distribution of the target variable (outcome) using a pie chart to observe class imbalances.

## Exploratory Data Analysis (EDA)
Exploring Feature Types: Analyzing the types of features, separating them into categorical and numerical, and displaying summary statistics for each type.

Numerical Data Exploration: Visualizing the distribution of numerical features using histograms and analyzing specific features like lesion_1.

Categorical Data Exploration: Visualizing the distribution of categorical features using bar plots and examining the relationship between categorical features and the target variable using heatmaps.

Encoding: Encoding categorical features using one-hot encoding for nominal features and ordinal encoding for ordinal features.

## Preprocessing
Imputation and Normalization: Imputing missing values using KNN imputation and normalizing numerical features using StandardScaler.

## Feature Engineering:
Performing feature engineering by creating new features based on existing ones and translating codes into meaningful labels.

## Modeling and Evaluation
Decision Tree, Logistic Regression, Random Forest: Training these classifiers and evaluating their performance using metrics like precision, recall, F1-score, and accuracy.

## Over-sampling:
Dealing with class imbalances by over-sampling the minority classes.

## Feature Selection
Using Feature Importances and PCA: Performing feature selection using feature importances from Decision Trees and Random Forests, as well as Principal Component Analysis (PCA).
Advanced Modeling and Evaluation
Model Evaluation: Calculating evaluation metrics like precision, recall, F1 score, and accuracy for models like CatBoost, XGBoost, and LightGBM.

## Hyperparameter Tuning: 
Applying RandomizedSearchCV to find the best hyperparameters for classifiers.

## Preparing Test Data:
Preprocessing the test data using techniques like imputation, one-hot encoding, and label encoding.

## Applying Best Models: 
Applying the best-performing models (CatBoost, XGBoost, Random Forest) on the entire dataset and making predictions on the test set.

## Learning Curves: 
Generating learning curves to visualize how the models' performance changes with training examples.

## Results: 
Saving the predictions to CSV files and reporting cross-validation scores for each model.

This project provides a detailed approach to building and evaluating machine learning models for the classification task of predicting horse health outcomes. If there are any further questions or need for assistance, feel free to ask!





