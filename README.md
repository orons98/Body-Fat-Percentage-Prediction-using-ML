# Body-Fat-Percentage-Prediction-using-ML
## Project Overview  
This project explores the use of machine learning tp estimate body fat percentage using anthropometric measurements. The goal is to devlop an accurate, accessible and non invasive model that overcomes the limitations of BMI and other traditional body fat estimation methods.

## Research Question
To what extent can machine learning models accurately predict body fat percentage using anthropometric measurements, and how do their predictions compare to traditional estimation methods like BMI and DEXA scans?

## Objectives
-	Prepare and clean dataset for anthropometric measurements for modelling.
-	Conduct exploratory data analysis to understand feature relationships.
-	Implement three machine learning models: Linear Regression with backward stepwise feature selection, Random Forest, and XGBoost, for predicting BFP.
-	Evaluate and compare model performance using Mean Squared Error, Mean Absolute Error, Root Mean Squared Error and R2 score metrics.
-	Critically assess how model performance compared to traditional methods such as BMI and DEXA in context of existing literature.
-	Assess the potential for real world application in healthcare and personal wellness contexts.

## Dataset
https://www.kaggle.com/datasets/fedesoriano/body-fat-prediction-dataset
- Contains 15 anthropometric measurements 
- Used for training and testing various ML models

## Technologies and Methods Used
- Python
- Google Colab
- Pandas, NumPy, Scikit-Learn (Data processing and Modeling)
- Matplotlib, Seaborn (Data Visualisation)

## Models
- Methods for training the 3 models: Linear regression, Random Forest, XGBoost
- Models are evaluated based MSE, RMSE, MAE and R2 Score

## Key Results
- XGBoost outperformed other models (R² = 0.67, RMSE = 3.91)
- Abdomen circumference was the most predictive feature
- Demonstrated practical use case for non-invasive body composition analysis
