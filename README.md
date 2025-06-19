# 📊 Telco Customer Churn Analysis

This repository provides an in-depth analysis of customer churn data for a telecom company. The goal is to identify the key factors driving customer churn and offer actionable recommendations for improving customer retention.

---

## 📁 Repository Structure

```
📂 Telco-Customer-Churn-Analysis/
├── Customer Churn.csv                 # The cleaned dataset used for analysis
├── CustomerChurnAnalysis.ipynb       # Jupyter notebook containing full analysis, visualizations & insights
└── Telco_Customer_Analysis.pdf       # Executive summary report with key takeaways
```

---

## 🔍 Objective

- Understand the churn rate across different customer demographics and services.
- Identify behavioral patterns and contract/service types most associated with churn.
- Suggest strategic actions to reduce churn and improve retention.

---

## 🧠 Key Insights

- **Overall Churn Rate:** ~26.54% of customers have churned.
- **Tenure Impact:** Customers with tenure < 12 months are most likely to churn.
- **Contract Type:** Month-to-month contracts see the highest churn (88.5% of churned users).
- **Service Gaps:** Absence of services like Online Security and Tech Support correlates with high churn (70%+).
- **Payment Methods:** Electronic Check users have the highest churn rate (~46%).
- **Demographics:** Senior citizens and customers without partners/dependents churn more frequently.

---

## 📊 Visualizations

The notebook includes:
- Churn distribution (Pie/Bar plots)
- Box plots and distribution plots for Monthly Charges and Total Charges
- Churn breakdown by Contract, Internet Service, and Payment Method
- Heatmaps and correlation matrices

---

## 📄 Report

A concise, stakeholder-friendly summary of the findings and recommendations is available in the PDF:

> **[📥 Telco_Customer_Analysis.pdf](Telco_Customer_Analysis.pdf)**

---

## 💡 Recommendations

1. Promote long-term contracts with attractive discounts.
2. Introduce bundled services with online security, tech support, and backup.
3. Target early-tenure customers with retention offers.
4. Encourage users to switch from Electronic Check to auto-payment.
5. Address dissatisfaction among fiber optic users with customer feedback programs.

---

## 🛠️ Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- FPDF (for generating executive summary)
- CSV for data storage
