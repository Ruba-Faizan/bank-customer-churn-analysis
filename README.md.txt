# Task 3 - Customer Churn Prediction

## Project Overview
This project predicts whether a bank customer will churn (exit) using Logistic Regression. The dataset contains customer demographic and financial information. The objective is to identify customers at risk of leaving and help the bank implement retention strategies.

## Dataset
- Source: `data/Churn_Modelling.csv`
- Rows: 10,000 customers
- Columns: 14 features including Age, Credit Score, Balance, Tenure, Gender, Geography, and Exited.

## Steps Performed
1. Data Understanding
2. Data Cleaning (removed irrelevant columns)
3. Encoding Categorical Variables (Gender, Geography)
4. Train-Test Split (80%-20%)
5. Feature Scaling using StandardScaler
6. Logistic Regression Model Training
7. Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
8. Feature Importance Analysis
9. Conclusion

## Key Insights
- Age, Balance, and Customer Activity status significantly affect churn.
- The model achieved satisfactory performance on test data.
- Convergence warning was resolved by using `liblinear` solver and increasing `max_iter`.

## Libraries Required
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Customer-Churn-Prediction.git
Install required libraries:

pip install -r requirements.txt
Open Task3_Customer_Churn.ipynb in Jupyter Notebook and run all cells.

Author
Ruba Faizan