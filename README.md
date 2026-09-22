# Data_Quality
A short data quality review notebook, built as follow-up work after a technical interview.

The notebook checks a dataset of customers, customer snapshots, and transactions for common data quality issues before any feature engineering or modeling:

Missing values, duplicates, and data types across all tables
Consistency of customer IDs between tables
Date validity and logical checks (for example, join date after snapshot date)
Time coverage across the transaction history
Numeric ranges and business rule checks
Transaction amount outliers
Missing merchant categories, with a short appendix exploring merchant-name matching 

Tools: Python, pandas, matplotlib
