# Task 1 – Data Cleaning & Preprocessing
### Data Analyst Internship – Marketing Campaign Dataset
**Created by: Anjali Gupta**

## Project Overview
This project is part of Task 1 of the Data Analyst Internship, where the main objective was to clean and preprocess a real-world dataset to make it ready for analysis.
I worked with the **Marketing Campaign Dataset**, which contains customer demographics, spending behavior, campaign responses, and purchase activity. The goal was to identify and correct common data issues such as missing values, duplicates, messy column names, inconsistent text formatting, incorrect date formats, and wrong data types.

## Task Objective
The purpose of this task was to:
- Identify missing values and fix them appropriately
- Remove duplicate records
- Clean and standardize column names
- Format text fields for consistency
- Convert date columns into a readable format
- Correct and validate numerical data types
- Produce a clean, structured dataset ready for analysis or modeling

## What I Did in This Task
1️. Loaded and Inspected the Dataset
- Imported the dataset into Google Colab
- Displayed initial rows to understand structure
- Checked column names, data types, and dataset dimensions
- Identified initial data quality issues

2️. Identified & Handled Missing Values
- Used .isnull().sum() to detect missing entries
- Found missing values mainly in the Income column
- Filled missing Income values using the median, keeping distribution stable

3️. Removed Duplicate Records
- Detected duplicates using .duplicated()
-  Safely removed duplicate rows using .drop_duplicates()

4️. Cleaned & Standardized Column Names
Transformed all column names to:
- lowercase
- no special characters
- no spaces
- This ensures consistency across analysis tools.

5️. Standardized Text Values
Fixed inconsistent formatting in:
- Education
- Marital_Status
- Converted to consistent title-case for cleaner grouping during analysis.

6️. Converted Date Columns to Proper Format
- Converted Dt_Customer to proper datetime format
- Used dayfirst=True to correctly parse European-style dates

7️. Corrected Data Types
- Converted numerical fields (year, kids, purchases, web visits, etc.) to integer
- Ensured accurate computation and analysis

8️. Saved the Cleaned Dataset
- Exported final cleaned dataset as **marketing_campaign_cleaned.csv**
- Stored in the task folder for final submission

## Summary of Data Cleaning
This task successfully transformed a raw dataset into a clean, structured, and analysis-ready format.
Key achievements include:
- Missing values cleaned
- Duplicate rows removed
- Columns standardized
- Dates formatted correctly
- Numeric data types fixed
- Dataset saved and documented

## Key Learning Outcomes

Through this task, I gained hands-on experience with:
- Pandas for real-world data cleaning
- Handling missing data responsibly
- Detecting and removing duplicates
- Standardizing messy text data
- Working with dates and data types
- Preparing datasets for analysis or machine learning models
- This task greatly improved my understanding of data preprocessing, a crucial step before any meaningful analysis or visualization.

## Submission Content
- Task1.ipynb – Google Colab Notebook
- marketing_campaign.csv – Original Dataset
- marketing_campaign_cleaned.csv – Final Cleaned Dataset
- README.md – Documentation of the entire process

## Final Insights & Readiness
The cleaned Marketing Campaign dataset is now ready for:
- Exploratory Data Analysis
- Customer segmentation
- Campaign performance evaluation
- Modeling and prediction
- Dashboard creation
- The preprocessing phase ensures all future analysis is accurate and reliable.


## Task 1 – Data Cleaning & Preprocessing - a short Summary
Marketing Campaign Dataset | Data Analyst Internship

In this task, I cleaned and prepared the Marketing Campaign Dataset using Python (Pandas) in Google Colab. I began by inspecting the data structure, checking column names, data types, and identifying issues such as missing values, duplicates, and inconsistent formatting. I handled missing values by filling Income gaps with the median, removed duplicate records, and standardized column names using a consistent lowercase snake_case format. Text fields like Education and Marital_Status were cleaned for uniformity, and the Dt_Customer column was converted into proper datetime format. Numerical columns were also corrected to their appropriate data types. After completing the cleaning steps, I exported the final dataset as marketing_campaign_cleaned.csv, making it fully ready for further analysis, visualization, or modeling.

## Author
**Anjali Gupta**  
Data Analyst Intern
