# Loan Approval Prediction

This project predicts whether a loan application will be approved based on applicant details such as income, employment type, credit score, and loan amount.  
It uses **Python** for data processing, **Pandas/Seaborn** for data analysis, and **Scikit-learn** for machine learning modeling.

## 📌 Features
- Load and explore the `loan_approval_dataset.csv` dataset
- Data cleaning: handle missing values, duplicates, and irrelevant columns
- Visualize relationships between features and loan approval status
- Train and evaluate classification models for prediction
- Provide insights into the most important factors affecting loan approval

## 🛠 Tech Stack
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📂 Dataset
The dataset contains columns such as:
- `loan_id`
- `applicant_income`
- `loan_amount`
- `credit_score`
- `loan_status` *(target variable)*

*(Ensure the dataset is in the same folder as the notebook before running.)*

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-approval-prediction.git
   cd loan-approval-prediction
 2.  Install dependencies:
    pip install -r requirements.txt
3.Run the Jupyter Notebook:
jupyter notebook "Loan Approval Prediction.ipynb"

