# Loan Prediction Project (Decision Trees & Random Forest)

## Overview

This project applies machine learning classification techniques to predict whether a borrower will fully repay a loan using historical lending data.

The models used:

* Decision Tree Classifier
* Random Forest Classifier

The objective is to compare model performance and determine the most accurate approach.

---

## Dataset

The dataset includes financial and credit-related information such as:

* FICO score
* Interest rate
* Annual income
* Debt-to-income ratio
* Loan purpose
* Credit policy status

### Target Variable

* `not.fully.paid`

  * 1: Loan not fully paid
  * 0: Loan fully paid

---

## Exploratory Data Analysis

The following visualizations were used to understand the data:

* Histograms of FICO score distributions
* Count plot of loan purposes
* Joint plot of FICO score vs interest rate
* Linear model plots comparing trends across credit policy and repayment status

---

## Data Preprocessing

* Converted categorical feature (`purpose`) into numerical variables using one-hot encoding
* Defined feature matrix (X) and target vector (y)
* Split the dataset into training (70%) and testing (30%) sets

---

## Models

### Decision Tree

A simple and interpretable model, but prone to overfitting.

### Random Forest

An ensemble method that combines multiple decision trees to improve performance and reduce overfitting.

---

## Evaluation

Models were evaluated using:

* Confusion matrix
* Classification report (precision, recall, F1-score)

---

## Results

The Random Forest model achieved better performance than the Decision Tree. It produced more accurate predictions and demonstrated improved generalization.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

