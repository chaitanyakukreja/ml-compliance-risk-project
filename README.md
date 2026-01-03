# Explainable Transaction Risk Scoring for Compliance

## Problem
Financial platforms must detect potentially risky transactions while minimizing false positives that negatively impact legitimate users and customer trust.

## Compliance Context
In AML and regulatory environments, model decisions must balance risk detection with explainability, fairness, and operational impact. Accuracy alone is insufficient.

## Data
Public transaction dataset used to simulate AML-style transaction risk detection under extreme class imbalance.  
No real financial institution data is used.

## Approach
- Binary classification under imbalanced data
- Baseline model: Logistic Regression
- Advanced model: Tree-based classifier
- Evaluation focused on precision, recall, and false positive rates
- Threshold analysis to demonstrate compliance-driven tradeoffs

## Explainability & Governance
Model behavior is analyzed using feature importance to support transparent, regulator-friendly explanations of flagged transactions.

## Disclaimer
This project is for educational purposes only and does not reflect PayPal systems, data, or internal models.
