# Customer Churn Prediction System

This project explores how to predict customer churn from behavioral data using a clean end to end machine learning workflow.  
The focus is on understanding churn drivers and making practical modeling decisions.

## Project Overview

Customer churn is costly and often difficult to detect early.  
This project builds a churn prediction pipeline that analyzes customer usage patterns and estimates churn risk before customers leave.

The notebook emphasizes clarity, evaluation and decision making rather than model complexity.

## Data

The dataset contains customer account information and usage behavior such as call minutes, charges, service plans, and customer service interactions.

The target variable indicates whether a customer eventually churned.

## Modeling Approach

The project follows a simple and interpretable workflow:

- Exploratory data analysis to understand usage patterns
- Feature preparation and basic preprocessing
- Supervised classification to predict churn probability
- Model evaluation using standard metrics
- Decision threshold selection based on tradeoffs between false positives and false negatives

Rather than optimizing for a single metric, the notebook treats threshold choice as a business decision.

## Evaluation

Model performance is evaluated using classification metrics and probability outputs.  
Different decision thresholds are explored to understand how sensitivity and precision change depending on business priorities.


## How to Run

Create a Python environment  
Install common ML libraries such as pandas and scikit learn  
Open the notebook in the notebooks folder and run it top to bottom

## Notes

This project is intended as a clear and readable example of applied machine learning.  
The focus is on understanding the model’s behavior and making sensible decisions rather than building overly complex models.


## Project Structure

## Project Structure

```
churn-prediction-system/
├── notebooks/
│   └── 01_churn_modeling_with_threshold_selection.ipynb
│
├── data/
│   └── telecom_churn_raw.csv
│
├── README.md
└── .gitignore
```
