# Customer Transaction Prediction

## Project Overview
This project focuses on predicting whether a customer will make a future transaction using machine learning classification algorithms.

The objective is to identify potential transaction customers, regardless of the transaction amount, using historical customer data.

## Dataset Description
The dataset contains:
- 200,000 customer records
- 200 anonymized numerical features (`var_0` to `var_199`)
- One unique customer identifier (`ID_code`)
- One binary target variable (`target`)

**Target Variable:**
- `0` – Customer will not make a future transaction.
- `1` – Customer will make a future transaction.

**Dataset Source:** [Customer Transaction Prediction Dataset](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1003-CustTransPred.zip)

The dataset is not included in this repository due to its file size.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Project Workflow

1. **Data Loading and Inspection** – Loaded the dataset and examined its structure.
2. **Data Cleaning** – Checked for missing values, duplicate records and data quality issues.
3. **Exploratory Data Analysis** – Examined
