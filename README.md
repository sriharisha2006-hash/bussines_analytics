# bussines_analytics
# 💳 Credit Scoring Model for Loan Applicants

## Business Analytics Project Using Microsoft Power BI

---

## 📌 Project Overview

The **Credit Scoring Model for Loan Applicants** is a Business Analytics project developed using **Microsoft Power BI**.

The purpose of this project is to analyze loan applicant information and identify patterns associated with **Good and Bad Credit Risk**.

The project uses the **Statlog (German Credit Data)** dataset obtained from the **UCI Machine Learning Repository**.

The analysis focuses on:

- Applicant financial characteristics
- Credit history
- Checking account status
- Loan duration
- Credit amount
- Employment
- Savings
- Housing
- Age
- Existing credits
- Loan purpose
- Dependents
- Credit risk

The complete analysis is performed using **Power BI without programming or machine-learning coding**.

---

# 🎯 Project Aim

To analyze loan applicant data using **Microsoft Power BI** and identify factors associated with Good and Bad credit risk to support data-driven credit-risk decision-making.

---

# 🎯 Objectives

1. Import the credit-risk dataset into Power BI.
2. Understand the structure of the dataset.
3. Perform data cleaning using Power Query.
4. Analyze Good and Bad credit-risk applicants.
5. Perform descriptive analysis.
6. Identify relationships between applicant characteristics and credit risk.
7. Create interactive visualizations.
8. Develop a Power BI credit-risk dashboard.
9. Identify high-risk applicant groups.
10. Provide business recommendations based on the analysis.

---

# 🏦 Business Problem

Financial institutions need to evaluate loan applicants before approving credit.

Incorrect credit decisions can result in:

- Financial losses
- Higher credit risk
- Poor loan portfolio performance
- Increased manual screening
- Inefficient risk management

This project uses Power BI to analyze historical credit-risk information and identify patterns that can help financial institutions understand applicant risk.

---

# 📊 Dataset

## Dataset Name

**Statlog (German Credit Data)**

## Dataset Source

**UCI Machine Learning Repository**

Dataset:

https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

---

# 📋 Dataset Size

| Property | Value |
|---|---:|
| Total Applicants | **1,000** |
| Input Variables | **20** |
| Target Variable | **1** |
| Total Columns | **21** |
| Good Credit Risk | **700 (70%)** |
| Bad Credit Risk | **300 (30%)** |
| Missing Values | **0** |

---

# 🎯 Target Variable

The dataset contains a **Credit Risk** target.

### Original Target

| Value | Meaning |
|---:|---|
| 1 | Good Credit Risk |
| 2 | Bad Credit Risk |

For Power BI analysis, the target can be displayed as:

| Credit Risk | Meaning |
|---|---|
| Good | Lower observed credit risk |
| Bad | Higher observed credit risk |

> **Important:** The original dataset represents Good/Bad credit risk rather than a direct historical default field.

---

# 📋 Dataset Variables

| Variable | Type | Description |
|---|---|---|
| Checking Account Status | Categorical | Status of checking account |
| Duration | Numeric | Loan duration in months |
| Credit History | Categorical | Previous credit history |
| Purpose | Categorical | Purpose of credit |
| Credit Amount | Numeric | Amount of credit |
| Savings Account/Bonds | Categorical | Savings status |
| Employment | Categorical | Employment status/duration |
| Installment Rate | Numeric | Installment rate |
| Personal Status and Sex | Categorical | Personal status and sex |
| Other Debtors/Guarantors | Categorical | Co-applicant/guarantor information |
| Present Residence Since | Numeric | Years at current residence |
| Property | Categorical | Property type |
| Age | Numeric | Applicant age |
| Other Installment Plans | Categorical | Other installment plans |
| Housing | Categorical | Housing situation |
| Existing Credits | Numeric | Number of existing credits |
| Job | Categorical | Job category |
| Number of Dependents | Numeric | Number of dependents |
| Telephone | Categorical | Telephone availability |
| Foreign Worker | Categorical | Foreign-worker indicator |
| Credit Risk | Categorical | Good/Bad credit-risk target |

---

# 🔄 Power BI Project Workflow

```text
                    CREDIT DATASET
                         │
                         ▼
                ┌──────────────────┐
                │ Import into      │
                │ Power BI Desktop │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Power Query      │
                │ Data Cleaning    │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Data Preparation │
                │ & Transformation │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Exploratory      │
                │ Data Analysis    │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Data             │
                │ Visualization    │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Power BI         │
                │ Dashboard        │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Business         │
                │ Insights         │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Recommendations  │
                └──────────────────┘
