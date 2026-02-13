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

## How to Run the Project

1.Clone the repository to your local machine using:

```git clone https://github.com/YourUsername/Customer-Churn-Prediction.git```

2.Navigate to the project directory.

3.Install the required libraries by running:

```pip install -r requirements.txt```

4.Open the Jupyter Notebook named Task3_Customer_Churn.ipynb.

5.Run all the cells in the notebook sequentially to execute the analysis.

Author
Ruba Faizan
