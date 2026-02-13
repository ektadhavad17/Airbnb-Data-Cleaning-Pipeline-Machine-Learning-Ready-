## Airbnb Data Cleaning Pipeline (Machine Learning Ready)
#### Overview

This repository contains a structured data cleaning and preprocessing workflow built using Python and Pandas.

The dataset is sourced from Kaggle and contains listing-level data from Airbnb, including pricing, host details, location attributes, booking policies, and review metrics.

The purpose of this project is to transform a raw, inconsistent dataset into a machine-learning-ready format through systematic preprocessing and validation.

This project focuses strictly on data preparation — not modeling.

#### Problem Context

Real-world datasets are rarely usable in their raw form. Common issues include:

Missing values

Inconsistent column formatting

Currency symbols embedded in numeric fields

Incorrect data types

Redundant or irrelevant features

Logical inconsistencies

Before any ML model can be built, these issues must be resolved.

This repository demonstrates that preprocessing stage.

#### Data Cleaning Workflow

The following transformations were applied:

##### 1. Structural Standardization

Renamed inconsistent column headers

Removed unnecessary index columns

Standardized column naming conventions

##### 2. Missing Value Treatment

Identified null-heavy columns

Dropped or handled missing values where appropriate

Ensured critical ML features contain no null values

##### 3. Data Type Corrections

Removed currency symbols from price column

Converted pricing columns to numeric format

Enforced correct integer and float types

##### 4. Data Validation

Checked for unrealistic or invalid values

Ensured logical consistency (e.g., minimum nights ≥ 0)

Removed duplicate or redundant columns

##### 5. Output Generation

Produced cleaned, ML-ready dataset files:

Cleaned_data_airbnb.csv

Excel_cleaned_data_airbnb.xlsx

Tech Stack

Python 3.x

Pandas

NumPy

Jupyter Notebookcleaning pipeline.
