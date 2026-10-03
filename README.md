# Loan Repayment Prediction

Python / scikit-learn notebooks from UTS 32130 Fundamentals of Data Analytics. They work with a loan applicant dataset and predict whether a borrower pays back the loan (`loan_paid_back`).

## Ass2 — Data exploration & preprocessing

| Notebook | What it does |
| --- | --- |
| `Ass2_A.ipynb` | Initial exploration: distributions, correlation matrix, K-Means clustering |
| `Ass2_B1_Binning.ipynb` | Equal-width / equal-depth binning and smoothing (`debt_to_income_ratio`, `credit_score`) |
| `Ass2_B2_normalise.ipynb` | Min-Max and Z-Score normalisation |
| `Ass2_B3_discretise.ipynb` | Discretisation |
| `Ass2_B4_binarise.ipynb` | Binarisation |

## Ass3 — Classification

`Ass3.ipynb` preprocesses the data, then trains and compares three classifiers using 5-fold cross-validation and F1 score:

- K-Nearest Neighbours
- Decision Tree
- Multi-layer Perceptron

## Tech

Python · pandas · NumPy · scikit-learn · matplotlib · seaborn · Jupyter / Google Colab

Datasets are not included in this repo.
