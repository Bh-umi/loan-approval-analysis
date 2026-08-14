# Loan Approval Analysis

## 📌 Project Overview

This project analyzes loan application data to identify factors associated with loan approval decisions and applicant risk.

The analysis focuses on applicant characteristics, financial attributes, CIBIL scores, loan amounts, and approval outcomes to uncover patterns that can support data-driven lending decisions.

---

## 🎯 Business Problem

The objective of this analysis is to understand:

- What factors are associated with loan approval?
- How does CIBIL score relate to approval rates?
- Does applicant income influence loan amount?
- Do education and self-employment status significantly affect approval?
- Which applicant segments have higher or lower approval rates?

---

## 📊 Dataset

The dataset contains **4,269 loan applications** and **13 variables** covering applicant demographics, financial information, asset values, CIBIL scores, loan details, and loan approval status.

### Key Variables

- `income_annum` — Annual income
- `loan_amount` — Requested loan amount
- `loan_term` — Loan term
- `cibil_score` — Applicant CIBIL score
- `education` — Graduate / Not Graduate
- `self_employed` — Yes / No
- `loan_status` — Approved / Rejected
- Asset value variables
- Number of dependents

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 🔍 Analytical Questions

1. What is the overall loan approval rate?
2. How does approval rate vary across CIBIL risk categories?
3. How does approval rate change across CIBIL score bands?
4. What is the relationship between annual income and loan amount?
5. Does education level affect loan approval?
6. Does self-employment status affect loan approval?

---

## 📈 Exploratory Data Analysis

The analysis includes:

- Data understanding and descriptive statistics
- Missing-value checks
- Duplicate-record checks
- Categorical-value validation
- Whitespace removal
- Loan approval analysis
- Loan amount analysis
- Risk categorization
- CIBIL score band analysis
- Education and self-employment analysis
- Income vs. loan amount analysis

---

## 📊 Visualizations

The project includes the following visualizations:

1. **Applicant Distribution by Risk Category**
2. **Average Loan Amount by Risk Category**
3. **Loan Approval Distribution**
4. **Loan Approval Rate by CIBIL Risk Category**
5. **Loan Approval Rate by Education**
6. **Loan Approval Rate by Self-Employment**
7. **Annual Income vs Loan Amount**
8. **Annual Income vs Loan Amount by Loan Status**
9. **Loan Approval Rate Across CIBIL Score Bands**

---

## 💡 Key Findings

### 1. CIBIL score is strongly associated with loan approval

Approval rates are approximately 10–11% for applicants with CIBIL scores below 500, increase to 52.25% for scores between 500–599, and exceed 98% for scores of 600 and above.

### 2. High-risk applicants have substantially lower approval rates

High-risk applicants have an approval rate of approximately **35.09%**, compared with approximately **99.43%** for low-risk applicants and **99.33%** for medium-risk applicants.

### 3. Annual income has a strong positive relationship with loan amount

Annual income and loan amount have a correlation of approximately **0.93**, indicating a strong positive relationship between income and requested loan amount.

### 4. Education has minimal impact on approval rate

Graduate applicants have an approval rate of approximately **62.45%**, compared with **61.98%** for non-graduate applicants.

### 5. Self-employment has minimal impact on approval rate

Approval rates for self-employed and non-self-employed applicants are almost identical, at approximately **62.23%** and **62.20%**, respectively.

### 6. Overall loan approval rate

Approximately **62.2%** of applications were approved, while **37.8%** were rejected.

---

## 💼 Business Recommendations

1. Use CIBIL score as an important component of loan risk assessment.
2. Apply additional scrutiny to applicants with lower CIBIL scores, particularly those below 500.
3. Consider annual income and requested loan amount together when evaluating borrowing requirements and affordability.
4. Avoid using education or self-employment status as standalone approval criteria.
5. Use a combination of credit profile, income, requested loan amount, and other relevant financial attributes when evaluating loan applications.

---

## 📁 Project Structure

```text
loan-approval-analysis/
│
├── data/
│   └── loan_approval_dataset.csv
│
├── Loan_Approval_Analysis.ipynb
│
└── README.md
