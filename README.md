# Task-1_Elivate_Labs_DA_Internship
This task involved cleaning and preprocessing the Marketing Campaign Dataset to prepare it for analysis. Missing values were handled, duplicates removed, and text columns standardized. Column names were formatted uniformly, and date and numeric data types were corrected. The cleaned dataset was then saved as a new CSV file for further analysis.



In this task, I worked on cleaning and preparing the Marketing Campaign Dataset for analysis using Python in Google Colab. First, I loaded the dataset and checked its basic structure, column names, and data types to understand the information it contained. Then, I identified missing values and filled the missing income values with the median to keep the data balanced. I removed duplicate rows to ensure there were no repeated records. Next, I cleaned and standardized the column names by converting them to lowercase and replacing spaces with underscores for consistency. I also standardized text columns like Education and Marital_Status to make them uniform. The Dt_Customer column was converted into a proper datetime format, and I fixed the data types of numerical columns by converting them to integers where needed. Finally, I saved the cleaned dataset as a new CSV file, making it ready for further analysis or visualization.



Interview Questions Related To Task 1:

1. What are missing values and how do you handle them?
Ans: Missing values are empty or blank entries in a dataset where information is not recorded. To handle them, we can either remove the rows if they are very few or fill them using methods like mean, median, mode, or a fixed value. The choice depends on how important the missing data is and how much of it exists.

2. How do you treat duplicate records?
Ans: Duplicate records are repeated rows in a dataset. They can cause wrong analysis, so we identify them using functions like duplicated() and remove them using drop_duplicates(). This keeps the dataset clean and ensures the results are accurate.

3. Difference between dropna() and fillna() in Pandas?
Ans: dropna() removes the rows or columns that contain missing values.
fillna() fills the missing values with a given value, such as the mean, median, or zero.
So, in simple words, dropna deletes, while fillna replaces.

4. What is outlier treatment and why is it important?
Ans:Outlier treatment means identifying and handling data points that are extremely different from the rest. These unusual values can distort averages and lead to incorrect conclusions. Outliers are treated by removing them or transforming them so that analysis becomes more reliable.

5. Explain the process of standardizing data.
Ans: Standardizing data means making the format of the values consistent. This includes fixing text formats (like “single” vs “Single”), converting all column names into a uniform style, scaling numbers, or keeping similar units. This ensures that the data is clean, readable, and ready for analysis or modeling.

6. How do you handle inconsistent data formats (e.g., date/time)?
Ans: Inconsistent data formats like mixed date formats are fixed by converting them to one standard format using functions like pd.to_datetime(). This helps avoid errors and makes calculations involving dates easy and accurate.

7. What are common data cleaning challenges?
Ans: Some common challenges include dealing with missing values, removing duplicates, fixing wrong data types, handling inconsistent formatting, identifying outliers, and cleaning messy text data. These issues take time and careful checking to fix properly.

8. How can you check data quality?
Ans: Data quality can be checked by looking for missing values, verifying data types, checking unique values, reviewing summary statistics, identifying duplicates, and visualizing patterns. Good quality data is complete, consistent, accurate, and ready for analysis.
