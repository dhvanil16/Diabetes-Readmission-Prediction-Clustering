# C07093_CW_Classification-Clustering

# Exploratory Data Analysis and Preprocessing

## Load and Shape the Dataset
- Loaded the 'diabetic_data.csv' dataset into a Pandas DataFrame.
- Displayed the shape of the data.

## Drop Unnecessary Column
- Removed the 'encounter_id' column from the DataFrame.

## Handle Missing Values
- Identified and replaced missing values represented by '?' with NaN.
- Displayed summaries of missing values before and after replacement.

## Transform 'readmitted' Column
- Replaced values in the 'readmitted' column: '<30' with 1, '>30' and 'NO' with 0.
- Displayed the updated 'readmitted' column value counts.

## Data Types and Missing Percentage
- Displayed data types of each column.
- Calculated and displayed the percentage of missing values for each column.

## Drop Columns with High Missing Values
- Dropped columns with more than 90% missing values.
- Displayed the updated DataFrame after dropping columns.

## Drop Near Zero-Variance Columns
- Dropped columns with near-zero variance.
- Displayed the updated DataFrame after dropping near zero-variance columns.

## Drop Rows with Null Values
- Dropped rows containing null values.
- Displayed the updated DataFrame after dropping rows.

## Outlier Removal using IQR
- Calculated outliers using the Interquartile Range (IQR) method.
- Removed outliers from the DataFrame.
- Displayed the updated DataFrame after removing outliers.

## Feature Normalization
- Identified numerical columns for normalization.
- Used MinMaxScaler to normalize numerical columns.
- Displayed the updated DataFrame after feature normalization.

## Summary
- Created a comprehensive README.md file to explain the code and its steps.
- Documented the entire process for better understanding and reproducibility.

