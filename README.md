# bussines_analytics
# 💳 Credit Scoring Model for Loan Applicants

## Predicting Credit Risk Using Demographic, Financial and Behavioral Variables

---

## 📌 Project Overview

The **Credit Scoring Model for Loan Applicants** is a Business Analytics and Machine Learning project designed to analyze loan applicant characteristics and predict their credit risk.

The project uses the **Statlog (German Credit Data)** dataset from the **UCI Machine Learning Repository**.

The system analyzes applicant information such as:

- Credit history
- Checking account status
- Loan duration
- Credit amount
- Savings status
- Employment
- Age
- Housing
- Existing credits
- Loan purpose
- Number of dependents
- Other financial characteristics

The objective is to classify applicants into:

- 🟢 **Good Credit Risk**
- 🔴 **Bad Credit Risk**

The project combines:

**Data Collection → Data Preprocessing → EDA → Statistical Analysis → Data Visualization → Machine Learning → Model Evaluation → Business Insights → Decision Support**

---

# 🎯 Project Objectives

The major objectives of this project are:

1. Analyze the characteristics of loan applicants.
2. Understand the distribution of Good and Bad credit-risk applicants.
3. Identify financial and behavioral factors associated with credit risk.
4. Perform data cleaning and preprocessing.
5. Perform Exploratory Data Analysis (EDA).
6. Conduct statistical analysis.
7. Create meaningful data visualizations.
8. Develop machine-learning models for credit-risk classification.
9. Compare Logistic Regression and Random Forest.
10. Evaluate models using multiple performance metrics.
11. Generate business insights from the analysis.
12. Provide recommendations for credit-risk decision-making.

---

# 🏦 Business Problem

Banks and financial institutions need to determine whether a loan applicant represents a low or high credit risk before approving a loan.

Incorrect decisions can result in:

- Financial losses
- Increased loan defaults
- Poor risk management
- Inefficient manual screening
- Loss of potential good customers

Therefore, this project develops a data-driven credit scoring approach that can help identify applicants who may require additional credit-risk assessment.

---

# 📊 Dataset

## Dataset Name

**Statlog (German Credit Data)**

## Data Source

The dataset is obtained from the:

**UCI Machine Learning Repository**

Dataset page:

https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

---

## Dataset Size

| Property | Value |
|---|---:|
| Total Records | **1,000** |
| Input Variables | **20** |
| Target Variable | **1** |
| Total Columns | **21** |
| Good Credit Risk | **700 (70%)** |
| Bad Credit Risk | **300 (30%)** |
| Missing Values | **0** |

---

# 🎯 Target Variable

The original dataset contains a credit-risk target.

### Original Encoding

| Value | Meaning |
|---:|---|
| `1` | Good Credit Risk |
| `2` | Bad Credit Risk |

For machine-learning modelling, the target is transformed into:

| Value | Meaning |
|---:|---|
| `0` | Good Credit Risk |
| `1` | Bad Credit Risk |

The model therefore predicts whether an applicant belongs to the **Bad Credit Risk** category.

> **Note:** The original UCI dataset contains a Good/Bad credit-risk classification rather than a direct historical default field. Therefore, this project uses "Bad Credit Risk" as the modelling target.

---

# 📋 Dataset Features

| Feature | Type | Description |
|---|---|---|
| Checking Account Status | Categorical | Existing checking-account status |
| Duration | Numerical | Loan duration in months |
| Credit History | Categorical | Previous credit history |
| Purpose | Categorical | Purpose of the credit |
| Credit Amount | Numerical | Amount of credit requested |
| Savings Account/Bonds | Categorical | Savings/bond status |
| Employment | Categorical | Employment duration/status |
| Installment Rate | Numerical | Installment rate as percentage of disposable income |
| Personal Status and Sex | Categorical | Personal status and sex |
| Other Debtors/Guarantors | Categorical | Co-applicant/guarantor information |
| Present Residence Since | Numerical | Years at current residence |
| Property | Categorical | Property ownership/type |
| Age | Numerical | Applicant age |
| Other Installment Plans | Categorical | Other installment plans |
| Housing | Categorical | Housing situation |
| Existing Credits | Numerical | Number of existing credits |
| Job | Categorical | Applicant's job category |
| Number of Dependents | Numerical | Number of dependents |
| Telephone | Categorical | Telephone availability |
| Foreign Worker | Categorical | Foreign-worker indicator |

---

# 🔄 Project Workflow

```text
                    ┌─────────────────────┐
                    │   Credit Dataset    │
                    │  1,000 Applicants   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Collection     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Preprocessing  │
                    │ Cleaning / Encoding │
                    │ Scaling              │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Exploratory Data    │
                    │ Analysis (EDA)      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Statistical         │
                    │ Analysis            │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Visualization  │
                    └──────────┬──────────┘
                               │
                               ▼
              ┌────────────────────────────────┐
              │     Machine Learning Models    │
              ├────────────────┬───────────────┤
              │ Logistic        │ Random        │
              │ Regression      │ Forest        │
              └────────┬────────┴───────┬───────┘
                       │                │
                       └───────┬────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Model Evaluation    │
                    │ Accuracy / Recall   │
                    │ F1 / ROC-AUC        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Business Insights   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Recommendations     │
                    └─────────────────────┘
