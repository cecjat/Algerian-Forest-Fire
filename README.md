## Algerian Forest Fire Cleaned Data Analysis

### Overview
This repository contains the analysis of the Algerian Forest Fire Cleaned Data. The dataset has been explored using various regression techniques including Linear Regression, Ridge Regression, Lasso Regression, and Elastic Net Regression. Additionally, hyperparameter tuning has been performed using RandomizedSearchCV to optimize model performance.

### Analysis Steps
 1. Exploratory Data Analysis (EDA): Initial exploration of the dataset to understand its structure, distributions, and relationships between variables.
 2. Linear Regression: Utilized Linear Regression to model the relationship between independent and dependent variables.
 3. Ridge Regression: Applied Ridge Regression to handle multicollinearity and prevent overfitting.
 4. Lasso Regression: Utilized Lasso Regression for feature selection and regularization.
 5. Elastic Net Regression: Implemented Elastic Net Regression to combine the strengths of Ridge and Lasso regression.
 6. Hyperparameter Tuning: Employed RandomizedSearchCV to optimize hyperparameters for better model performance.
 7. Feature Engineering: Added more features to the dataset to improve model accuracy.
 8. Model Evaluation: Evaluated model performance using various metrics including Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
 9. Model Deployment: Saved the optimized model using Pickle for future use.

### Files
- Algerian_forest_fires_cleaned.csv: The cleaned dataset used for analysis.
- README.md: This file provides an overview of the project.
- Main File: This file contains the end-to-end code for the Analysis of the Algerian Forest Fire. 
- CLJ1 and Scaler1: This is a pickled file of the Tunned Ridge Regression Model using the 3 features. 
- CLJ2 and Scaler2: This is a pickled file of the Tunned Ridge Regression Model using the 7 features. 

### Requirements
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Usage
 1. Clone the repository: git clone https://github.com/your-username/algerian-forest-fire-cleaned.git
 2. Navigate to the project directory: cd algerian-forest-fire-cleaned
 3. Open and run the Jupyter notebooks to explore the analyses.

### Future Work
- Further exploration of feature engineering techniques to enhance model performance.
- Experimentation with other regression algorithms and ensemble methods.
- Deployment of the optimized model in production environments.

