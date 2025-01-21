# Diabetes Readmission Prediction

## Problem Statement
This coursework aims to create a classification model that predicts whether a patient will be readmitted to the hospital within 30 days using the Diabetes dataset from 130 US hospitals. The dataset consists of 47 features and 101766 instances spanning ten years (1999-2008) of clinical care.

## Data Cleaning and Transformation
- Loaded the dataset and performed initial data exploration.
- Deleted the 'encounter_id' column and replaced missing values represented as '?' with NaN.
- Converted the 'readmitted' feature to a binary variable, where '<30' represents early readmission (1) and '>30'/'NO' represent no early readmission (0).
- Checked the datatype of each column and dropped columns with more than 90% missing values.
- Deleted near-zero variance columns and dropped rows with null values.
- Removed outliers from numerical columns and performed feature normalization if required.

## Data Visualization
- Plotted the distribution of unique classes of the target variable ('readmitted').
- Visualized the count of readmitted cases against age and number of medications.
- Generated scatter matrix plot and correlation matrix to identify highly correlated feature pairs.
- Added additional plots to further understand the data using Seaborn library.

## Model Building
- Selected predictors impacting readmission and built a linear model.
- Split the data into training and test sets and evaluated the model using cross-validation.
- Used different performance metrics to evaluate model performance and balanced data using undersampling or oversampling techniques.
  
## Improved Model
- Developed an improved classification model by treating missing values differently, retaining near-zero variance columns, and optimizing model performance.
- Utilized K-Means algorithm to cluster the dataset and compared obtained clusters with the distribution found in the data.
- Built local classifiers based on clustering and compared with the original model obtained.

## Instructions
To reproduce the results, run the provided Python code files and follow the instructions in the Jupyter Notebook.

## Group Details

**Group ID:** 26

| Sr. | Name of Student               | Student ID no. |
|-----|-------------------------------|----------------|
| 1.  | Shubham S. Sonawane          | 239062846      |
| 2.  | Dhvanil Alpeshkumar Patel    | 239064467      |
| 3.  | Vivek Prakash Shah           | 239062179      |
| 4.  | Ritika Ritika Karthikeyan    | 239057165      |
| 5.  | Om Vilas Shimpi              | 239063265     |


