🧹 Data Cleaning in Excel
📌 Project Overview

This project demonstrates the complete process of cleaning and preparing raw data in Microsoft Excel before analysis.

The dataset originally contained:

Duplicate records
Inconsistent formatting
Spelling mistakes
Extra spaces
Incorrect date formats
Text-formatted numerical values
Unnecessary columns

The goal of this project was to transform messy raw data into a clean, structured, and analysis-ready dataset that can later be used in:

SQL
Python
Power BI
Tableau
Excel Dashboards
❓ Problem Statement

Raw datasets often contain inconsistencies that make analysis difficult and unreliable.

The original dataset included:

Different naming formats
Duplicate records
Incorrect data types
Formatting inconsistencies
Additional spaces
Mixed date formats

Without proper cleaning, these issues can lead to:

Incorrect insights
Broken visualizations
SQL import problems
Inaccurate analysis

🎯 Project Objectives
Clean and standardize raw Excel data
Remove duplicate records
Correct spelling and formatting inconsistencies
Convert data into proper formats
Prepare numerical and date columns for analysis
Create a reliable and analysis-ready dataset
Learn real-world data preparation techniques used by analysts

🧠 Data Cleaning Process
1️⃣ Created a Backup of Raw Data

Before making any changes, a separate copy of the original raw dataset was saved.

Why this is important:
Prevents accidental data loss
Keeps original data available for auditing
Follows real-world data cleaning practices

2️⃣ Removed Duplicate Records

To identify and remove duplicate rows:

Steps:
Selected all data using:
CMD + A
Added filters using:
CMD + SHIFT + L
Used:
Data → Highlight Duplicates → Remove Duplicates
Result:

Removed repeated records and improved data accuracy.

3️⃣ Standardized Text Formatting

Some titles and names were written inconsistently.

Example:

president
PRESIDENT
President

To fix this, the PROPER() function was used.

Formula Used
=PROPER(A2)
Process:
Created a new column
Applied the formula
Copied the corrected values
Used Paste Values to permanently save cleaned text
Deleted unnecessary original columns
Why:

Improves readability and consistency across the dataset.

4️⃣ Removed Unnecessary Columns

Columns that were not useful for analysis were deleted to simplify the dataset and improve workflow efficiency.

Benefits:
Cleaner dataset
Better performance
Easier analysis
5️⃣ Corrected Spelling Errors

Spelling mistakes and inconsistent labels were updated manually to ensure accurate categorization and filtering.

6️⃣ Removed Extra Spaces Using TRIM()

Some cells contained unnecessary spaces before or after text values.

To clean this:

Formula Used
=TRIM(A2)
Why TRIM() is Important:
Prevents filter issues
Improves SQL compatibility
Ensures consistent text matching
Removes hidden spacing errors

This process was applied across multiple columns.

7️⃣ Cleaned Numerical Data

Some numerical columns were stored as text and included unnecessary trailing zeros (00).

Process:
Copied the column
Changed format from:
Text → Number
Result:
Proper numerical formatting
Easier calculations
Better compatibility with SQL and Python

8️⃣ Standardized Date Formats

The dataset originally contained inconsistent date formats.

Cleaning Process:
Selected the date column
Changed format to:
General → Short Date
Ensured all dates followed the same structure
Why this matters:

Consistent dates are critical when:

Uploading data into SQL databases
Performing time-series analysis
Using Python/Pandas
Building dashboards
🔎 Filter Validation

After cleaning each column, filters were checked carefully to ensure:

No broken categories
No hidden formatting issues
Correct sorting and grouping

This helped validate data consistency across the entire dataset.

🛠️ Skills Demonstrated

This project demonstrates practical skills in:

Microsoft Excel
Data Cleaning
Data Preparation
Data Formatting
Duplicate Removal
Text Standardization
Data Validation
Numerical Formatting
Date Formatting
Spreadsheet Best Practices

💡 What I Learned

Through this project, I learned:

The importance of cleaning data before analysis
How inconsistent formatting affects reporting
Real-world Excel data preparation techniques
How to standardize text and dates efficiently
Why backup copies are essential before transformations
How to prepare datasets for SQL, Python, and dashboards
🚀 Conclusion

This project reflects the real-world process of transforming raw, messy datasets into clean and analysis-ready data.

It demonstrates attention to detail, structured data preparation, and foundational data analytics skills that are essential in business intelligence and analytics workflows.





