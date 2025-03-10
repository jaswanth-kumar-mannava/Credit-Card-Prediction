# Credit-Card-Prediction
EM589 Project

README

This repository contains a Python script for a credit risk assessment project. The script includes data reading, cleaning, preprocessing, merging, feature engineering, model training, evaluation, and visualization steps. Below is a brief overview of each section:

Data Reading, Cleaning, Preprocessing, and Merging:
Reads data from CSV files (application_record.csv and credit_record.csv).
Performs data cleaning and preprocessing tasks such as handling duplicates, missing values, and transforming categorical variables.
Merges the cleaned dataframes based on the ID column.
Feature Engineering:
Calculates new features such as age and years employed.
Selects relevant features for model training.
Model Training and Evaluation:
Utilizes various machine learning algorithms including Random Forest, Gradient Boosting, XGBoost, AdaBoost, Decision Tree, and Logistic Regression.
Performs feature selection using Recursive Feature Elimination (RFE) with Random Forest.
Evaluates model performance using accuracy, F1 score, precision, recall, and confusion matrix.
Applies techniques like Standardization, SMOTE (Synthetic Minority Over-sampling Technique), and cross-validation.
Data Analysis and Visualization:
Conducts exploratory data analysis (EDA) through histograms, bar plots, box plots, pair plots, and correlation heatmaps.
Visualizes the distribution of numeric and categorical variables, and their relationship with the target variable.
Usage:

Ensure that Python and required libraries are installed (including scikit-learn, imbalanced-learn, pandas, numpy, matplotlib, seaborn, xgboost).
The first line of code provides a method to install imbalanced learn using pip install command which has been commented out in the code. Just uncomment it to install it into the environment


Download the CSV files (application_record.csv and credit_record.csv) and place them in the same directory as the Python script.
Run the Python script. Make sure to review and modify paths or parameters as necessary.
The script will perform data processing, model training, evaluation, and visualization. Results will be displayed in the console
Note: Ensure to review and customize the script according to specific requirements and data characteristics. Adjust hyperparameters, feature engineering techniques, and model selection based on the dataset and project objectives.

Feel free to reach out for any further assistance or clarification!
