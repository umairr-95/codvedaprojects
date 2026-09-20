# Level 1 Task 1: Data Cleaning and Preprocessing

This project demonstrates basic data cleaning and preprocessing using the Iris dataset.

## Tools Used

- **Python** — Programming language
- **Pandas** — Data loading, inspection, and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization support
- **Jupyter Notebook** — Interactive development environment

## Steps Completed

1. Imported the required Python libraries.
2. Loaded the Iris dataset using Pandas.
3. Inspected the dataset using:
   - `df.info()`
   - `df.shape`
   - `df.head()`
   - `df.dtypes`
4. Checked for missing values and calculated their percentages.
5. Identified duplicate rows.
6. Removed duplicate records.
7. Rechecked the dataset shape and duplicate count.
8. Inspected unique categorical values in the `species` column.
9. Standardized species values by:
   - Removing leading and trailing spaces
   - Converting text to lowercase
10. Converted the `species` column to a categorical data type.
11. Verified the cleaned values, category counts, and final data types.

## Result

The dataset was cleaned by removing duplicate rows, standardizing categorical values, and converting the species column to an appropriate categorical data type.