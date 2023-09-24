# sqlite_database_operations

# SQLite Database Operations Assignment

## Overview

This repository contains code and documentation for the SQLite Database Operations assignment. The assignment involves exploring healthcare pricing transparency datasets and performing various SQLite database operations.

## Datasets

### Dataset 1: Stonybrook
-Description: [The datset contains detailed information about medical procedures, charges, and negotiated rates for various healthcare services. It includes data on procedure codes, descriptions, types of services, and contracted rates with multiple insurance providers]

-Purpose: To provide valuable insights into healthcare charges and insurance-provider relationships


### Dataset 2: st.-joseph-hospital_standardcharges
-Description: [The dataset contains standardized healthcare pricing information for services provided by St. Joseph Hospital. This dataset provides transparency into the charges associated with various medical procedures, treatments, and services offered by the hospital. It includes details such as procedure codes, descriptions, pricing information, and insurance coverage.]

-Purpose: This dataset is used to analyze healthcare pricing trends, insurance coverage, and to ensure pricing transparency for patients and healthcare stakeholders.


## Exploratory Data Analysis (EDA)

In this assignment, we performed an exploratory data analysis (EDA) on the provided datasets. Here are some key observations and insights from our analysis:

- **Dataset 1**:
-The dataset includes a diverse set of descriptions for medical procedures, with 5449 unique values.
-While some descriptions are specific, others are more general, reflecting a range of medical services.
-Procedures are categorized into two types: 'Outpatient' and 'Inpatient.'
-'Outpatient' procedures are more common, with 6041 occurrences, while 'Inpatient' procedures appear 886 times.

- **Dataset 2**:
-A wide range of descriptions, such as 'Box,' 'Blister,' 'Syringe,' among others, underscores the variety in packaging types.
-Some descriptions, like 'Punchcard,' are less common, appearing only once in the dataset.
-'100 each' stands out as the most frequent charge quantity, with 2570 occurrences.
-The dataset includes diverse charge quantities, encompassing counts and milliliter measurements.
-Occasional quantities like 'Punchcard' suggest less conventional billing practices.

## SQLite Database Setup

We created a local SQLite database called `health.db` for this assignment. Below are the steps to replicate the database setup:

1. Clone this repository: `git clone [https://github.com/Jannath19/sqlite_database_operations.git]`
2. Navigate to the repository directory: `cd sqlite_database_operations`
3. Run the Python script to create the database and tables: `python create_database.py`
4. Verify that the `health.db` file has been created and contains the necessary tables.

## Files and Code

- `data/`: Directory containing the dataset files.
- `create_database.py`: Python script to create the SQLite database and tables.
- `explore_data.py`: Python script for exploratory data analysis (EDA).
- `README.md`: This file, providing an overview and instructions.

