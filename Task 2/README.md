# Pandas:
## Concepts:
- What Pandas is — Series vs DataFrame
- Creating DataFrames: from dicts, lists, and CSV files
- Reading and writing data: pd.read_csv(), pd.read_excel(), df.to_csv()
- Inspecting data: df.head(), df.tail(), df.info(), df.describe(), df.shape
- Selecting data: column selection, df.loc[], df.iloc[]
- Filtering rows with boolean conditions
- Adding, renaming, and dropping columns
- Sorting: df.sort_values(), df.sort_index()
- Grouping and aggregation: df.groupby(), .agg(), .transform()
- Merging and joining: pd.merge(), pd.concat(), df.join()
- Handling duplicates: df.duplicated(), df.drop_duplicates()
- apply() and map() — applying functions to columns or rows
- pivot_table() — reshaping data for analysis

## Task:
● Sales Data Analyser: Download or create a mock sales CSV with columns for product,
region, date, quantity, and price. Write a Pandas script that loads the file, inspects it, filters for a specific region, adds a revenue column, groups by product to find total
revenue, finds the top 5 products, merges with a mock product metadata table, and
exports the final result to a new CSV
