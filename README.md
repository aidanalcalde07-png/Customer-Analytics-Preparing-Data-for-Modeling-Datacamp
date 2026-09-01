# Customer Analytics: Preparing Data for Modeling

A data cleaning and preprocessing project completed as part of DataCamp's Customer Analytics: Preparing Data for Modeling project.

## Project Overview

This project focuses on preparing a dataset of job candidates for downstream analysis and machine learning. The dataset contains 19,158 records describing candidates' education, work experience, company characteristics, training, and job-search activity.

The primary goal was to clean the dataset and ensure that each variable was represented using an appropriate data type while preserving meaningful categorical relationships.

## Data Cleaning and Preprocessing

The dataset was cleaned and transformed by:

- Handling missing categorical values by representing them as `"Unknown"`
- Converting binary variables to Boolean (`bool`) data types
- Converting nominal categorical variables to the `category` data type
- Converting ordinal variables to ordered categorical data types
- Preserving the natural ordering of variables such as education level, experience, company size, and time since the previous job
- Converting integer variables to `int32`
- Converting the city development index to `float16`
- Validating the resulting data types and categorical transformations

## Business Requirement

The final dataset was filtered to identify candidates who:

- Have at least 10 years of professional experience
- Work at companies with at least 1,000 employees

This filtering reflects a recruiting requirement focused on more experienced professionals working at enterprise-sized companies.

## Validation

After preprocessing, the dataset was validated to confirm:

- Missing values were handled appropriately
- Binary variables contained the expected Boolean values
- Categorical variables contained the expected categories
- Ordinal categorical variables retained their intended ordering
- Required data types were correctly applied
- The final dataset satisfied the specified recruiting criteria

## Tools

- Python
- Pandas
- Jupyter Notebook

## Project Files

- `customer_analytics.ipynb` — Data cleaning and preprocessing workflow
- `customer_train.csv` — Original dataset used in the project

## Source

This project was completed as part of a guided DataCamp project.
