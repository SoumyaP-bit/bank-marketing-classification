# Bank Marketing Campaign — Comparing Classifiers

## Business Problem
A bank wants to improve the efficiency of its telephone marketing campaigns. By identifying customers who are more likely to subscribe to a term deposit, the bank can focus outreach efforts more effectively, reduce unnecessary calls, and improve conversion rates.

## Research Question
**Which classification model best predicts whether a customer will subscribe to a term deposit after a phone-based marketing campaign?**

## Dataset
- **Source:** [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Size:** ~41,000 records
- **Target Variable:** `y` — whether the client subscribed to a term deposit (`yes` / `no`)
- **Class Imbalance:** ~89% No / ~11% Yes
- **Note:** `duration` column was excluded per UCI documentation — it causes data leakage as it is only known after the call ends

> The dataset CSV is not included in this repository. Download `bank-additional-full.csv` from the UCI link above and place it in a `data/` folder before running the notebook.

## Repository Structure
