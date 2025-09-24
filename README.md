# Credit Risk Modelling – Probability of Default (PD)

A simple project demonstrating **credit risk modelling** with logistic regression on a synthetic dataset. Includes preprocessing, class balancing (SMOTE), model training, and evaluation.

---

## Setup
1) python3 -m pip install --user virtualenv
2) python3 -m virtualenv .venv
3) source .venv/bin/activate
4) pip install -r requirements.txt
5) python -m pip install jupyterlab ipykernel

## Run
python -m jupyterlab

Then open the notebooks in order:

- 01_credit_risk_preprocessing.ipynb
- 02_pd_logistic_regression.ipynb
- 03_pd_logistic_regression_smote.ipynb