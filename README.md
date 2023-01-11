# Lending Club Case Study
> This project demonstrates the practical usage of Exploratory Data Analysis for solving real life business problems like identifying the key driving factors behind loan default (for a consumer finance company). 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Business Problem Statement
A consumer finance company is specialised in lending various types of loans to urban customers.When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
-  If the applicant is likely to repay the loan, then   approving the loan results in a loss of business to the company.
-  If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
   
### Business Objective
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment

### Solution Approach
We will use Exploratory Data Analysis to identify the key consumer and loan attributes that influence the tendency of loan default. 

## Conclusions
After performing the Exploratory Data Analysis, we have categorized our results under 2 categories
1. Attributes showing lesser impact to the trend of loan default
2. Attributes showing higher impact to the trend of loan default

#### Lesser impact
-  Lower annual income (below 37000)
-  Higher loan amount (above 16000)
-  Higher debt to income ratio (above 15%)
-  Higher installment amount (above 327)
-  Loan issue month (Dec, May)
-  Applicant’s address state (NV, SD, AK, FL)

#### Higher impact
-  Higher interest rate (above 13%)
-  Repayment term (5 years)
-  Loan purpose (small business, renewable energy, educational)
-  Higher revolving line utilization rate (above 58%)
-  Loan grade & sub-grade (D to G)
-  Public bankruptcy records (1 or 2)
-  Derogatory public records (1 or 2)
-  Missing employment record

In terms of the effects of combined attributes on the tendency of loan default, we observe that the following show higher combined impact

-  High loan amount and interest rate for lower income group
-  High installment and longer repayment term
-  Residential state and loan purpose
-  Income group and loan purpose
-  Home ownership (other) and loan purpose (car, moving or small business)

## Technologies Used
- Python version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@kkcsai1] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
