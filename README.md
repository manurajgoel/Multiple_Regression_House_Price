# Multiple_Regression_House_Price

# Multiple Linear Regression: House Price Prediction

## Project Overview
This project demonstrates a **Multiple Linear Regression model** built using **scikit-learn** 
to predict **house prices** based on multiple input features
such as **area, number of bedrooms, age of the house, and location score**.


## Problem Statement
Predict the price of a house using multiple real-world features with the help of a Multiple Linear Regression model.


## Dataset Description
### Input Features (X)

1. Area of the house in square feet
2. Number of bedrooms
3. Age of the house (in years)
4. Numeric score representing location quality

### Target Variable (y)
House price (numeric value)


## Tech Stack & Libraries Used
- **Programming Language:** Python  
- **Libraries:**
  - NumPy
  - Pandas
  - scikit-learn
- **Tools:**
  - Jupyter Notebook / Python Script
 

## Machine Learning Concepts Covered
- Multiple Linear Regression
- Supervised Learning
- Feature Selection
- Feature Scaling using StandardScaler
- Train–Test Split
- Model Training using scikit-learn
- Model Evaluation
  - Root Mean Squared Error (RMSE)
  - R² Score
- Making predictions on new/unseen data
  

## Project Workflow
1. Import required libraries  
2. Load and inspect the dataset  
3. Separate input features and target variable  
4. Split the dataset into training and testing sets  
5. Apply feature scaling using StandardScaler 
6. Train the Multiple Linear Regression model  
7. Evaluate model performance using RMSE and R² score  
8. Test the model using custom input values  


## Output & Results
The project produces the following outputs:

- Learned feature coefficients (weights)
- Bias (intercept)
- RMSE (prediction error)
- R² Score (model accuracy)
- Predicted house price for user-defined inputs


## Model Equation
Price = w₁×Area + w₂×Bedrooms + w₃×Age + w₄×Location_Score + b
