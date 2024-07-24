# Lending Club Case Study
> This project aims to analyze factors influencing loan default rates and develop strategies for better lending decisions using Exploratory Data Analysis (EDA).
> It is part of Course 1-Statistics Essentials in the upGrad and IIITB Machine Learning & AI Program - May 2024

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project analyzes loan data to understand the driving factors behind loan defaults.
- **Background:** The analysis is conducted for a consumer finance company specializing in various types of loans to urban customers.
- **Business Problem:** The company needs to minimize financial losses due to loan defaults by identifying risky loan applicants.
- **Dataset:** The dataset includes information about past loan applicants and their repayment status, sourced from the company's loan records.

## Conclusions

### The Primary Factors for Better Decision-Making on Lending:
-  Grade & Sub-Grades: Correlated with the risk of credit loss except for the final risk bucket which should be analysed 
-  Inquiries in Last 6 Months (inq_last_6mths): A surprising metric which shows that multiple credit inquiries may signal credit-seeking behavior and potential risk.
-  Home Ownership: Homeowners may present lower risk.
-  Debt-to-Income Ratio (dti): Higher DTI may indicate potential repayment issues.


### Factors for Better Decision-Making on Loan Monitoring:
-  Delinquencies in Last 2 Years (delinq_2yrs): An increase in the number of delinquencies indicate higher risk.
-  Earliest Credit Line (earliest_cr_line): Regular credit reviews should be made on older accounts to ensure their credit limits are still correct
-  Interest Rate (int_rate): Higher interest rates may correlate with higher risk loans due to the presence of penalty interest clauses
-  Total Recovered Late Fees (total_rec_late_fee): Monitor late fees as an indicator of repayment behavior.


## Technologies Used
- pandas - version 1.3.3
- matplotlib - version 3.4.3
- seaborn - version 0.11.2
- numpy - version 1.21.2

## Acknowledgements
- This project was inspired by the need to enhance risk analytics in the banking and financial services sector.
- References: Based on various EDA techniques and methodologies.
- This project was based on [this tutorial](https://www.example.com).

## Contact
Created by @thomami244 and  Supriyo Roy.
