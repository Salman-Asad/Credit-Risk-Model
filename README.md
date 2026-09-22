# Credit Risk Model: PD, LGD & Expected Loss

A credit risk project on the German Credit dataset (1,000 loan applications), predicting Probability of Default (PD) and combining it with standard LGD/EAD assumptions to estimate portfolio-level Expected Loss.

## What it does
- Predicts default probability using Logistic Regression (AUC 0.67)
- Applies a Basel-style LGD assumption (45%) for unsecured retail exposures
- Calculates Expected Loss = PD x LGD x EAD at loan and portfolio level
- Segments loans into risk groups, showing Expected Loss concentrated ~7x
  more heavily in the highest-risk group vs. the lowest

## Tools
Python, pandas, scikit-learn (Logistic Regression), matplotlib

## Note
This is a learning/portfolio project on public data, using simplified assumptions (e.g. LGD as a fixed rate rather than modeled from collateral data) rather than a production credit model.
