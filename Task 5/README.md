# Data Cleaning: Concepts:
- Why raw data is always messy — sources of data quality issue
- Types of missing data: MCAR, MAR, MNAR
- Detecting missing values: df.isnull(), df.isna(), df.isnull().sum()
- Strategies for handling missing data: drop, mean/median/mode imputation, forward fill, backward fill
- Detecting and removing duplicates
- Fixing incorrect data types: pd.to_datetime(), pd.to_numeric(), astype()
- Handling inconsistent string values: .str.strip(), .str.lower(), .str.replace()
- Detecting and treating outliers: capping, flooring, removal
- Fixing structural errors: inconsistent category names, typos, extra whitespace
- Validating cleaned data — sanity checks before moving on

## Task:
● Dirty Data Cleaner: Download or create a deliberately messy CSV with missing values, duplicate rows, inconsistent casing, wrong dtypes, and outliers. Write a cleaning pipeline that detects and reports every issue, applies an appropriate fix for each, and outputs a fully clean version of the file alongside a printed cleaning log showing what was changed and how many rows were affected at each step.
