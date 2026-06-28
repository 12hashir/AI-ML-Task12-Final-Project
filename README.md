# AI & ML Course - Task 12: Final Project Deployment and Presentation

## 1. Problem Statement
Predict customer churn for a telecom company. Goal: Identify customers likely to leave.

## 2. Dataset Description
*Dataset:* churn_data.csv - 500 synthetic customer records.
*Features:* tenure, monthly_charges, total_charges, contract_type, internet_service, senior_citizen
*Target:* churn - 0 = No, 1 = Yes.

## 3. Methodology & EDA
*Preprocessing:* One-Hot Encoding + StandardScaler.
*EDA - 5 Charts:* Churn Count, Tenure Histogram, Charges Boxplot, Correlation Heatmap, Contract vs Churn.
*Models:* RandomForestClassifier and LogisticRegression.

## 4. Evaluation Results
- *RandomForest Accuracy:* 0.92
- *LogisticRegression Accuracy:* 0.85
- *Best Model:* RandomForestClassifier

## 5. Insights
1. Month-to-month contracts have highest churn.
2. Churn highest in first 12 months tenure.
3. Higher monthly_charges = higher churn.

## 6. Recommendations
1. Convert month-to-month users to 1-Year contracts.
2. Retention campaigns for first-year customers.
3. Use Streamlit app for real-time scoring.

## 7. Deployment
*Streamlit App:* streamlit run App.py
*Demo Video Link:* [Yahan apna YouTube/Unlisted link paste karo]

## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Streamlit, Joblib
