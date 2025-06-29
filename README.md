# Bias Detection & Debiasing in Recommender Systems

## Project Overview
This project implements causal inference and fairness metrics to detect and quantify bias in a movie recommendation dataset. The primary focus is on understanding if user attributes like **gender** introduce systematic bias in predicted ratings.

## Key Steps
- Data Preprocessing
- Causal Graph Definition
- Estimand Identification
- Effect Estimation using Regression
- Refutation Tests (Random Common Cause, Subset Data, Placebo Treatment)
- Fairness Metrics Evaluation using `fairlearn`

## Fairness Metrics Used
- **Demographic Parity Difference**
- **Equalized Odds Difference**

## Final Fairness Results
- **Demographic Parity Difference**: ~0.0093
- **Equalized Odds Difference**: ~0.0000

## Requirements
Install dependencies with:

```bash
pip install -r requirements.txt
