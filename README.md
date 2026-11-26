# Predicting Late Responses to Consumer Financial Complaints

Author: Kejie Wang

## Project Objective
Predict whether a company will respond late to a consumer complaint
using information available when the complaint is submitted.

## Dataset
- File: complaints.csv
- Uncompressed size: approximately 5.63 GB
- Source: Consumer Financial Protection Bureau
- Website: https://www.consumerfinance.gov/data-research/consumer-complaints/
- Download: https://files.consumerfinance.gov/ccdb/complaints.csv.zip

Download and extract the ZIP, then upload complaints.csv to a
Databricks Unity Catalog Volume.

## Target
Timely response?
- Yes = 0: timely response
- No = 1: late response

## Spark ML Models
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient-Boosted Trees

## Methods
- Data cleaning and feature preparation
- CrossValidator
- TrainValidationSplit
- Separate training, selection, and test datasets
- Permutation feature importance

## Evaluation
Precision, recall, F1, ROC-AUC, PR-AUC, accuracy, and computing time.

## How to Run
1. Import the notebook into Databricks.
2. Upload the extracted dataset to a Unity Catalog Volume.
3. Update the data, output, and temporary storage paths.
4. Run the notebook cells in order.

## Results
Pending completion of the Databricks experiment.

## Hardware
To be completed using the actual Databricks compute specifications.
