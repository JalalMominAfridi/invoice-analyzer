# Invoice Analyzer

Detects duplicate and anomalous invoices in a vendor payment dataset.

## Problem
Finance teams risk paying the same invoice twice or approving unusually large amounts by mistake.

## Approach
- Generated a synthetic dataset of 500 invoices (Python, pandas)
- Removed duplicate invoice IDs
- Flagged amounts more than 3 standard deviations from the mean
- Summarized spend by vendor and by month

## Results
- 15 duplicates removed from 515 records
- 8 anomalous invoices flagged
- Gamma Parts had the most anomalies

## Tools
Python, pandas, NumPy, Google Colab

## How to run
Open `invoice_analyzer.ipynb` in Google Colab and run all cells.
