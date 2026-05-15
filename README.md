# Financial-risk-analysis
This project builds a financial transaction monitoring system designed to detect abnormal customer behaviour amd access fraud risk.
It combines statistical anoamlly detection with behavioural analysis to identify high risk transactions and support decision making.

## Problem Statement
Detection of fradulent transactions is essential for Financial institutions. 
This project aims to design a transparent and interpretable system for identifying risky transactions.

## Approach
The system is built in layers:

1. Data Preparation  
   - Cleaned and structured transaction data  
   - Created time-based and behavioral features  
2. Feature Engineering  
   - Transaction frequency  
   - Spending volatility  
   - Time-of-day activity  
   - Customer-level aggregation  
3. Anomaly Detection  
   - Used A-score to measure deviation from customer behavior  
4. Risk Scoring  
   - Combined anomaly score, transaction timing, and frequency  
   - Built a weighted risk scoring system
5. Visualization  
   - Developed an interactive Power BI dashboard
   - Enabled real-time investigation of high-risk transactions


## Key Insights

- Fraud does not always occur in highly abnormal transactions  
- Some fraudulent activities occur within normal behavioral patterns  
- Anomaly detection alone produces false positives  
- Combining multiple signals improves risk detection  

##
Dashboard

<img width="741" height="480" alt="risk analysis power bi" src="https://github.com/user-attachments/assets/5dff875e-bbe9-4e01-9f13-e427feb3b7ad" />















 
   - Enabled real-time investigation of high-risk transactions
  
