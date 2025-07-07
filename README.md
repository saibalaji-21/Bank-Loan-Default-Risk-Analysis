# 📊 EDA: Bank Loan Default Risk Analysis

## 📝 Overview
This project performs Exploratory Data Analysis (EDA) on banking data to understand patterns related to loan default. The goal is to help financial institutions identify high-risk customers and make informed lending decisions.

## 📁 Dataset
- Clone and see it in the code itself 

## 🎯 Objective
Identify key factors that influence loan default, helping banks:
- Approve loans to reliable customers.
- Reject or apply higher interest rates to high-risk applicants.

## ⚙️ Tools & Technologies
- Python
- Jupyter Notebook / Google Colab
- Libraries: Pandas, NumPy, Matplotlib, Seaborn

## 🔍 Key Insights

### ✅ Low-Risk Applicants
- Income > ₹700K  
- Age > 50  
- Employment > 40 years  
- No or few children  
- Higher education  
- Safe regions (Rating = 1)

### ❌ High-Risk Applicants
- Income < ₹300K  
- Young age (< 40)  
- Large families (children ≥ 4, family members ≥ 8)  
- Unstable employment  
- Risky loan purposes (e.g., repairs)  
- Risky regions (Rating = 3)

### ⚠️ Medium-Risk (Consider Higher Interest Rates)
- Loan amount ₹300K–₹600K  
- Applicants with risky occupations or housing type

## 📌 Conclusion
EDA revealed important trends in customer behavior that can help banks reduce risk and increase profitability.

## 🚀 How to Run
```bash
git clone https://github.com/saibalaji-21/Bank-Loan-Default-Risk-Analysis
cd Bank-Loan-Default-Risk-Analysis
```
