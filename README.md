# Risk-Scoring-Transaction-Behaviour-Explorer-for-Customer-Review
A small system that:  Scores customers based on multiple weak signals  Compares behavior instead of blindly flagging transactions  Explains why something looks risky
# Risk Scoring & Transaction Behaviour Explorer

## Overview
This project is a learning-focused initiative designed to understand how entry-level analysts review
customer data and transaction behaviour to identify cases that may require further attention.

Instead of relying on a single rule or threshold, the project focuses on combining **multiple weak indicators**
such as transaction amount, frequency, customer profile, and behavioural changes to form a more
context-aware risk perspective.

The objective is not automation or prediction, but **structured analysis, judgment, and explainability** —
key aspects of compliance and financial operations roles.

---

## Problem Statement
In real-world financial operations, suspicious activity is rarely identified through one obvious signal.
Most cases emerge from **small deviations from normal behaviour** that require human review.

This project explores:
- How customer behaviour can be evaluated relative to their own history
- How multiple contextual factors contribute to perceived risk
- How observations can be documented clearly for further review

---

## Data Design
The project uses **dummy datasets created solely for academic and learning purposes**.

### Datasets Used
- `customers.csv`  
  Contains customer profile information such as age, occupation, country, account type, and account age.

- `transactions.csv`  
  Contains transaction history including amount, date, transaction type, and channel.

- `risk_notes.csv` (optional)  
  Contains analyst-style observations to simulate human judgment and documentation.

The datasets are intentionally designed to reflect **realistic customer behaviour**, not extreme or artificial cases.

---

## Approach
The analysis follows a structured and explainable process:

1. **Customer Context Review**  
   Understanding the customer profile before evaluating transaction activity.

2. **Behavioural Analysis**  
   Comparing individual transactions against a customer’s historical patterns rather than global thresholds.

3. **Risk Scoring Logic**  
   Assigning partial scores to multiple indicators (e.g. sudden value spikes, transaction type, profile mismatch).

4. **Explainable Output**

