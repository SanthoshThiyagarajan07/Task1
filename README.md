# Task1
this is first step of data analysis
in this project  i have done the following 
To ensure data quality and consistency, the following preprocessing steps were performed on the Mall_Customers.csv dataset:

Missing Values Handling
Checked for missing data using .isnull().sum(). No missing values were found in any column, so no imputation was necessary.

Duplicate Removal
Used .drop_duplicates() to eliminate any repeated rows, ensuring the dataset contains only unique records.

Standardizing Text Values
Standardized the Gender column by removing leading/trailing spaces and capitalizing the values for uniformity (e.g., "male", " FEMALE " → "Male", "Female").

Date Format Conversion
This dataset does not contain date columns, so this step was not applicable.

Renaming Column Headers
Cleaned and standardized column names by converting them to lowercase and replacing spaces with underscores.
Example: "Annual Income (k$)" → "annual_income_(k$)"

Fixing Data Types
Ensured that each column has the appropriate data type:

age: converted to int

annual_income_(k$): converted to int

spending_score_(1-100): converted to int
This cleaning process ensures the dataset is tidy, consistent, and ready for further analysis or machine learning tasks.
