# Telecom-Churn-Case-Study

# Overview
This case study focuses on predicting customer churn in the telecommunications industry using customer usage data from a leading telecom firm. The objective is to build predictive models to identify customers at high risk of churn and identify the main indicators of churn. The analysis considers high-value customers only, as they contribute significantly to the revenue.

# Business Objective
Predict customer churn in the ninth month using data from the first three months. The goal is to reduce churn of high-value customers and prevent revenue leakage.

# Dataset
The dataset contains customer-level information for four consecutive months - June, July, August, and September (encoded as 6, 7, 8, and 9, respectively).
# Analysis steps
** Data Cleaning and EDA (Exploratory Data Analysis) **

** Import Necessary Packages and Libraries:**  Loaded the dataset into a dataframe.

** Check Data Types and Null Values:** Identified columns with incorrect data types and checked for missing values.

**Handle Duplicates and Unique Identifiers:** Checked for duplicate records and set 'mobile_number' as the unique identifier.

**Column Renaming and Data Type Conversion:** Renamed columns for consistency and converted columns to appropriate data types.

**Filter High-Value Customers:** Selected customers whose 'Average_rech_amt' in months 6 and 7 are greater than or equal to the 70th percentile.

**Handle Missing Values:** Dropped columns with more than 50% missing values and imputed meaningful columns.

**Drop Irrelevant Columns:** Removed columns with only one unique value and those related to the churn phase (month 9).

**Tag Churn Variable:** Labeled the target variable for churn prediction.

**Final Dataset:** Retained 30,011 rows and 126 columns.

# Exploratory Data Analysis (EDA)
 . Analyzed customer usage patterns and identified key indicators of churn.

 . Performed correlation analysis and created derived variables.

 . Handled outliers by capping them at the 99th percentile.

 . Created dummy variables for categorical data.
# Contributer
* Shravan Madipelly
   email id: shravan.madipelly@gmail.com 
* Shilpa

## Contact
Created by [@https://github.com/Madipelly] - +91-9618188869
