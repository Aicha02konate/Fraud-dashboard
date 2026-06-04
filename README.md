# Credit Card Fraud Detection Dashboard 

## Overview
This project analyzes credit card fraud transactions using a dataset of 284,807 real transactions. It explores fraud patterns including transaction amounts, and peak hours when fraud occurs most frequently.

## Tools & Technologies
- streamlit
- pandas
- kaggle
- python 
- plotly

## Results
- Fraud transactions represent only 0.17% of all transactions - a classic class imbalance problem that makes detection difficult
- The average fraud transaction amount ($122) is not significantly higher than normal transaction ($88), making amount alone an unreliable fraud indicator
- Fraud peaks around 7-8pm and 3-4 am, suggesting two distinct fraud patterns

## How to run
pip install streamlit pandas plotly kaggle
streamlit run app.py
# Fraud-dashboard
# Fraud-dashboard
