# Customer Churn Prediction

## Project Overview
This project predicts whether a telecom customer will churn using machine learning techniques.

## Dataset
The dataset contains customer information such as:
- Tenure
- Contract type
- Internet service
- Payment method
- Monthly charges
- Total charges

## Project Pipeline
1. Exploratory Data Analysis (EDA)
2. Data Cleaning & Preprocessing
3. Feature Encoding
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Feature Importance Analysis
8. Model Saving
9. Prediction Example

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest

## Final Model Performance
Random Forest achieved the best performance:

- Accuracy: ~79%
- ROC-AUC: ~0.83

## Key Features Influencing Churn
- Tenure
- Total Charges
- Internet Service Type
- Contract Type
- Payment Method

## Model Saving
The trained model is saved as: models/churn_model.pk1

This allows the model to be reused for predictions without retraining.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
