# Probability of Default (PD) Model — Loan Portfolio

This project develops an end-to-end **PD model** to predict borrower default risk, assign internal **credit rating grades (A–E)**, and visualize portfolio risk via a **dashboard**.

## Project Overview
- Data cleaning & preprocessing (handling missing values, encoding categories, removing outliers)
- Feature engineering (Debt-to-Income ratio, Installment-to-Income ratio, Interest × Leverage interaction)
- Logistic Regression PD model
- Model evaluation (ROC-AUC: 0.887, Gini: 0.775)
- Credit rating assignment (A–E) for portfolio monitoring
- Board-level dashboard for risk visualization

## Tools & Libraries
- Python, Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## How to Run
1. Clone repository:  
   ```bash
   git clone https://github.com/IzaLachinyan/pd-risk-model.git
