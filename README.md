# Credit Card Churn Analysis
**Tools:** Python · Pandas · NumPy · Seaborn · Tableau  
**Dataset:** [Credit Card Customers – Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

---

## 📌 Project Overview

This project investigates why customers are leaving a fictional credit card company by analyzing behavioral and demographic patterns across active and churned customers. The goal was to surface actionable insights that could inform targeted retention strategies — translating raw data into stakeholder-ready findings.

---

## 🗂️ Dataset

The dataset contains credit card customer records with the following key fields:

| Column | Description |
|---|---|
| Attrition Flag | Whether the customer churned or remained active |
| Customer Age | Age of the cardholder |
| Gender | Customer gender |
| Dependent Count | Number of dependents |
| Education Level | Highest education attained |
| Marital Status | Marital status of the customer |
| Income Category | Annual income bracket |
| Card Category | Type of card held (Blue, Silver, Gold, Platinum) |
| Months on Book | Duration of customer relationship |
| Total Transaction Amount | Total spend over the period |
| Total Transaction Count | Number of transactions |
| Contacts Count (12 months) | Number of times customer contacted support |

---

## 🧹 Data Cleaning & Preparation

- Loaded and preprocessed the dataset using **Pandas** and **NumPy**
- Handled missing values and standardized categorical fields
- Engineered features to isolate attrition signals across behavioral and demographic dimensions

---

## 🔍 Analysis Approach

The analysis focused on identifying the strongest predictors of customer churn:

- **Transaction behavior** — Compared total transaction amounts and counts between churned and active customers
- **Customer engagement** — Analyzed contact frequency and its relationship to attrition
- **Demographic profiling** — Explored churn rates by income category, education level, and card type
- **Tenure analysis** — Examined how customer relationship length correlates with attrition likelihood

---

## 📊 Visualizations

Data was visualized using **Seaborn** in Python for exploratory analysis and a fully interactive **Tableau KPI Dashboard** for stakeholder-facing reporting.

🔗 **[View Live Tableau Dashboard](https://mahaderzeru.github.io/Credit-Card-Churn-Analysis/)**

The dashboard includes:
- Churn rate by demographic segment
- Transaction behavior comparison (churned vs. active)
- Customer engagement trends
- Income and card category breakdowns

---

## 💡 Key Findings

- Churned customers showed significantly lower transaction counts and amounts in the months prior to leaving
- Customers who contacted support more frequently were more likely to churn, suggesting unresolved service issues
- Certain income brackets and card categories had disproportionately higher attrition rates
- Customers with shorter tenure showed higher churn vulnerability

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `BankChurnAnalysis.ipynb` | Full Python analysis notebook (cleaning, EDA, visualizations) |
| `CreditCardChurnPresentation.pdf` | Stakeholder presentation summarizing findings and recommendations |

---

## 👤 Author

**Mahader Zeru**  
BS Data Science, UNC Charlotte · MBA Candidate, Data Analytics — Indiana Wesleyan University  
[LinkedIn](https://linkedin.com/in/mahaderzeru) · [GitHub](https://github.com/mahaderzeru)
