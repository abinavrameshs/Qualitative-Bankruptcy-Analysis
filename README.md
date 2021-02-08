# Qualitative-Bankruptcy-Analysis

Analysis of Qualitative Bankruptcy data from UCI ML Database

# Aim
To predict `Class` variable (Which indicates if a firm will go Bankrupt or not)

# Link of the data Source 
http://archive.ics.uci.edu/ml/datasets/Qualitative_Bankruptcy

# Tasks performed
Peformed the following activities in the IPYTHON notebook using Qualitative Bankruptcy dataset  : 
1. Profiling report and Correlations
2. Pandas profiling report
3. Correlation Plot (Cramer's V test)
4. Phik (φk) correlations
5. Exploratory Data Analysis
    - Industrial Risk vs Class
    - Management_Risk vs Class
    - Financial_Flexibility vs Class
    - Credibility vs Class
    - Competitiveness vs Class
    - Operating_Risk vs Class
    - Industrial Risk and Management risk
6. Classification Model to predict Bankruptcy
    - Setting up the Pre-processing pipeline
    - Modelling for Bankruptcy indicator
        - Building top 10 models
        - Tuning Hyperparameters of top 10 models
    - Feature importances
    - AUC Plot
    - Confusion Matrix
    - Using SHAP values to explain the model

# Process for modelling  
Used PyCaret (Low code ML library) to build classification models, tune and select a Champion model
