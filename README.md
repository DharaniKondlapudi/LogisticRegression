# LogisticRegression
# 📊 LoanTap - Logistic Regression Case Study

## 🏦 Overview

**LoanTap** is a fintech platform offering flexible, customized loan products for millennials. This case study focuses on building an **underwriting model** using **Logistic Regression** to determine the **creditworthiness** of individuals applying for a **Personal Loan**.

---

## 📌 Problem Statement

> Given a set of borrower attributes, **predict whether a personal loan should be granted** (loan status) and provide **repayment recommendations** based on model insights.

---

## 📾 Dataset Information

📁 **Download Link**: [LoanTap Dataset (Google Drive)](https://drive.google.com/file/d/18BpwHHqquP6OVHOcAOuyd7b_v8yHQovb/view?usp=drive_link)

### 📂 Key Features

| Column                                    | Description                              |
| ----------------------------------------- | ---------------------------------------- |
| `loan_amnt`                               | Loan amount requested                    |
| `term`                                    | Duration of loan (36 or 60 months)       |
| `int_rate`                                | Interest rate on the loan                |
| `installment`                             | Monthly EMI payment                      |
| `grade`, `sub_grade`                      | LoanTap assigned loan grade and subgrade |
| `emp_title`, `emp_length`                 | Employment title and years of experience |
| `home_ownership`                          | Home ownership status                    |
| `annual_inc`                              | Annual income of borrower                |
| `verification_status`                     | Income verification status               |
| `issue_d`                                 | Loan issued date                         |
| `loan_status`                             | **Target variable** - status of the loan |
| `purpose`, `title`                        | Purpose and title of the loan            |
| `dti`                                     | Debt-to-income ratio                     |
| `earliest_cr_line`                        | Oldest credit line date                  |
| `open_acc`, `total_acc`                   | Number of open and total credit accounts |
| `pub_rec`, `pub_rec_bankruptcies`         | Public records and bankruptcies          |
| `revol_bal`, `revol_util`                 | Revolving credit balance and utilization |
| `mort_acc`                                | Mortgage accounts                        |
| `initial_list_status`, `application_type` | Listing and application type             |
| `Address`                                 | Address of the borrower                  |

---

## 🧠 Concepts Used

* 📌 **Exploratory Data Analysis (EDA)**
* ⚙️ **Feature Engineering**
* 📈 **Logistic Regression Modeling**
* 🎯 **Precision vs Recall Tradeoff**

---

## ⚒️ Tools & Libraries

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📍 Objectives

* Build a **binary classification model** using Logistic Regression
* **Evaluate performance** using precision, recall, F1-score
* Analyze the impact of **credit-related features** on loan decisions
* Provide **business recommendations** based on model insights

---

## 📝 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/LoanTap-Logistic-Regression.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook LoanTap_Logistic_Regression.ipynb
```

---

## 📌 Business Impact

A robust underwriting model will:

* Improve **loan approval accuracy**
* Reduce **default risks**
* Support better **credit product design**

---

## 📬 Contact

For questions or collaboration, feel free to reach out at: **[kondlapudidharani@gmail.com](mailto:kondlapudidharani@gmail.com)**
