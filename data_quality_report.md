Data Quality Report
1. Missing Values

Example:

sentiment_score missing → impacts churn-driver analysis



2. Duplicates

Observed in:

orders/support data



3. Invalid Values

Negative sentiment OK
Check resolution hours extremes

4. Outliers

Very high order values
Long resolution times

5. Join Issues

Some customer_ids missing across datasets

6. Date Issues

Ensure all < snapshot date

7. Leakage Risk
⚠️ Critical:

Any data after snapshot date (2025‑09‑30)
intervention after churn window
