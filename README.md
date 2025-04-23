# US-heart-patients-Risk-Prediction-Analysis
Predictive analysis of U.S. heart patient data using Logistic Regression to assess 10-year coronary heart disease r

# Project Overview
This project focuses on analyzing a dataset of U.S. heart patients and predicting the 10-year risk of coronary heart disease (CHD) using Logistic Regression.

# The objective is to understand which factors are most associated with future heart disease and to create a basic risk classification model based on real-world health indicators.

# Tools used
- Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels
- Jupyter Notebook
  
# Steps Performed
1. Data Import & Initial Exploration
   Loaded the dataset US_Heart_Patients.csv
   Displayed the first few rows to understand the structure
   Target variable: TenYearCHD
   1 → Developed CHD within 10 years
   0 → Did not develop CHD

2. Exploratory Data Analysis (EDA)
   Checked data shape and feature types
   Summary statistics for continuous features
   Plotted:
   Count plots for categorical variables (e.g., smoking, gender, education)
   Histograms for continuous features (e.g., age, BMI, glucose)
   Heatmap of correlation matrix

3. Data Preprocessing
   Handled missing or null values
   Selected relevant features for modelling
   
4. Train-Test Split
   Divided data into training and testing sets (typically 70/30 split)
   
5. Logistic Regression Modelling
   Trained a Logistic Regression model using sklearn.linear_model
   Predicted the probability and class of CHD occurrence
   Evaluated model performance using:
   Confusion matrix
   Accuracy score
   ROC-AUC curve and score
   
6. Result Interpretation
   Identified which features (e.g., age, systolic BP, glucose) were most associated with higher CHD risk
   Used ROC curve to visualize
   
# Key Insights
  - Logistic Regression gave a reasonably good fit for predicting CHD risk.
  - Age, blood pressure, and glucose were strong indicators of risk.
  - The model can serve as a starting point for preventive healthcare analytics.
    
# Files in This Repository
  - File Name
  - US_Heart_Patients.csv (The dataset used for modelling) -US Heart Patients Analysis(Unsupervised Learning).ipynb (The notebook containing EDA and logistic regression model)
  - README.md (Project summary and steps)
