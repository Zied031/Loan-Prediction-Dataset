# 🏠 Loan Prediction Dataset - Beginner Project

This project is based on a **Loan Prediction** problem from a challenge hosted on [Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/).

## 🧠 Project Goal

A company called **Dream Housing Finance** provides home loans. They want to **automate the process of deciding whether a loan should be approved** or not, based on information given by customers in their application forms.

By analyzing customer details like gender, income, employment status, loan amount, etc., we aim to **predict whether a loan application will be approved**.

## 🗃️ About the Data

The dataset contains information about previous loan applicants. Each row represents one applicant and includes features such as:

| Feature             | Description                                                         |
| ------------------- | ------------------------------------------------------------------- |
| `Loan_ID`           | Unique ID for the loan                                              |
| `Gender`            | Male or Female                                                      |
| `Married`           | Marital status (Yes/No)                                             |
| `Dependents`        | Number of dependents (children or others)                           |
| `Education`         | Graduate or Not Graduate                                            |
| `Self_Employed`     | Whether the person is self-employed (Yes/No)                        |
| `ApplicantIncome`   | Income of the main applicant                                        |
| `CoapplicantIncome` | Income of the co-applicant (if any)                                 |
| `LoanAmount`        | Requested loan amount (in thousands)                                |
| `Loan_Amount_Term`  | Duration of the loan (in months)                                    |
| `Credit_History`    | Whether the applicant has a good credit history (1 = good, 0 = bad) |
| `Property_Area`     | Urban, Semi-Urban, or Rural area                                    |
| `Loan_Status`       | Whether the loan was approved (Y = Yes, N = No)                     |

The goal is to build a model that uses these features to predict `Loan_Status`.

## 🔍 What I Did

To explore and visualize the data better, I applied a technique called **PCA (Principal Component Analysis)**, which reduces the number of features to **2 dimensions**. This helps in visualizing the data and understanding how different groups (approved vs. not approved loans) are distributed.

I also used some **classification algorithms** to try and predict whether a new loan application would be approved, based on patterns in the data.

## 🛠️ Requirements

If you'd like to run this project yourself, you'll need Python and some common data science libraries, like:

* `pandas`
* `numpy`
* `matplotlib`
* `scikit-learn`

You can install them using:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## 📌 Learn More

* 📘 If you're new to PCA: [PCA explained simply](https://towardsdatascience.com/principal-component-analysis-for-dummies-3e03c568b1b7)
* 📘 Basics of Classification: [Intro to Classification Models](https://scikit-learn.org/stable/supervised_learning.html)
