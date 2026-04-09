# ML Workflow Assignment

## Task 1

**Label (Target Variable):**  
`repeat_purchase_flag`  
This is the label because it indicates whether a customer makes a repeat purchase within 30 days, which is exactly what the model is trying to predict.

**Data Leakage Column:**  
`discount_used_on_repeat_order`  
This column would cause data leakage because it contains information about the repeat purchase itself, which would not be available at the time of prediction.

---

## Task 2

**1. Exploratory Data Analysis (EDA):**  
EDA is important to understand the dataset, identify patterns, check for missing values, and detect outliers before building any model.

**2. Data Preprocessing (Data Cleaning & Feature Engineering):**  
This step ensures the data is properly prepared by handling missing values, encoding variables if needed, and selecting relevant features, which improves model performance and reliability.
