## Interview Questions – Data Cleaning & Preprocessing
## Marketing Campaign Dataset – Task 1
**Author: Anjali Gupta**

1. What are missing values and how do you handle them?
- Missing values are empty or unavailable data in a dataset. They occur when information was not recorded, entered incorrectly, or lost.
- To handle them, we first identify missing values using methods like .isnull() in Pandas. Then, we treat them based on the situation, for example, filling numerical columns with the median/mean, filling categorical columns with the mode, or removing rows if they contain too many missing values.

2. How do you treat duplicate records?
- Duplicate records are repeated rows that provide no new information and can affect analysis.
- We detect them using .duplicated() and remove them using .drop_duplicates().
- This helps make the dataset cleaner and prevents biased results.

3. What is the difference between dropna() and fillna() in Pandas?
- dropna() removes rows or columns that contain missing values.
- Useful when there are very few missing entries.
- fillna() replaces missing values with something meaningful like the mean, median, mode, or a custom value.
- Useful when removing rows may cause loss of important data.

4. What is outlier treatment and why is it important?
- Outlier treatment involves detecting and handling extreme values that do not follow normal patterns.
- Outliers can distort averages, mislead visualizations, and affect model accuracy.
- Common methods include removing them, capping them, or transforming the data.

5. Explain the process of standardizing data.
- Standardizing data means making values consistent in format.
- Examples include:
      - Making all text lowercase or title case
      - Removing trailing spaces
      - Converting dates into the same format
      - Aligning categories (e.g., “married” and “Married” to “Married”)
      - Standardization helps avoid confusion and ensures accurate grouping and analysis.

6. How do you handle inconsistent data formats (e.g., date/time)?
- We convert inconsistent formats into a single standard format.
- For dates, we use pd.to_datetime() to convert strings into proper datetime objects.
- This ensures all dates are readable, comparable, and suitable for sorting, filtering, and time-based analysis.

7. What are common data cleaning challenges?
- Some common challenges are:
      - Missing values
      - Duplicate records
      - Inconsistent formats (text, dates, numbers)
      - Incorrect data types
      - Outliers
      - Spelling mistakes
      - Extra spaces or unusual characters
- These issues must be fixed before performing analysis.

8. How can you check data quality?
- Data quality can be checked by:
      - Viewing dataset shape (rows & columns)
      - Checking missing values (.isnull().sum())
      - Checking data types (.dtypes)
      - Using .describe() for statistical summary
      - Checking unique values in categories
      - Identifying duplicates
      - Looking for inconsistencies in text, formats, and ranges
- Good data quality ensures accurate and trustworthy analysis.
