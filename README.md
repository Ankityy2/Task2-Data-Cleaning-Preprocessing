# Task 2: Data Cleaning & Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the Titanic dataset to improve data quality and prepare it for machine learning applications.

## Dataset

- Titanic Dataset (train.csv)
- Total Records: 891
- Original Features: 12

## Objectives

- Handle missing values
- Remove duplicate records
- Verify data types
- Detect and handle outliers
- Normalize numerical features
- Export cleaned dataset

## Data Cleaning Steps

### Missing Value Handling

- Age missing values filled using Median
- Embarked missing values filled using Mode
- Cabin column removed due to excessive missing values

### Duplicate Record Check

- Duplicate records identified and removed

### Data Type Verification

- Verified all columns have appropriate data types

### Outlier Detection & Treatment

- IQR (Interquartile Range) method used
- 116 Fare outliers identified
- Outliers removed from dataset

### Feature Scaling

Applied MinMaxScaler on:

- Age
- Fare
- SibSp
- Parch

Scaled values range between 0 and 1.

## Final Dataset Summary

- Final Rows: 775
- Final Columns: 11
- Missing Values: 0

## Files Included

- Task2_DataCleaning_Preprocessing.ipynb
- train.csv
- clean_titanic.csv
- README.md

## Conclusion

The Titanic dataset was successfully cleaned and preprocessed. The resulting dataset is free from missing values, contains normalized numerical features, and is ready for exploratory data analysis and machine learning tasks.

## Author

Ankit Yadav
