# Credit-Card-Default-Detection

This notebook aims to classify clients of a credit card company based on default. It  is a **Binary Classification Problem** where based on every clients details like History of Past payments, Amount of bill statement, Limit balance thery are classified is they will be in default category or not.


**In this notebook i have focused on following parts:**

**1. Feature understanding , Feature Selection based on target variable** 

**2. Different Imputaion Stratergies**


## This notebook has following workflow:

**1. Understand, Clean and Format Data (Cleaning data and EDA)**

**2. Examining the Relationships between Features and the Response (Feature Engineering)**

	2.1. Feature Selection based on EDA.
    
    2.2. Optimum Features based on using F-test
    
        2.2.1.  Fitting model on Features selected using F-test.
	
        2.2.2.  Plotting ROC-AUC Curve
        
**3.  Cross Validation and Feature Engineering**

	3.1. Cross Validation on Logistic Regression model.
    
   	3.2. Using Polynomial features to create new interaction features
    
**4. Decision Tree Algorithm**

    4.1. Fitting model with inbuilt default parameters.
    
    4.2. Grid-Search CV for decision tree.
    
**5. Random Forest Model**

    5.1. Fitting model with inbuilt default parameters.
    
    5.2. Grid-Search CV for decision tree.
    
    5.3. Checkerboard Graph for visualisation of GridSearchCV

**6. Dealing with Missing Data: Imputation Strategies**

    6.1. Method 1: Mode and Random Imputation of PAY_1
    
    6.2. Method 2: A Predictive Model for PAY_1 (model based imputation)
    
    6.3. Using the imputation model for PAY_1
    
    6.5. Confirming Model Performance on the Unseen Test Set.
    

