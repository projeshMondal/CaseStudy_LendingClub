# Project Name
Leanding Club is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

This case study aims to achieve this goal through Exploratory Data Analysis (EDA).

### Dataset
The dataset used for thr analysis: [dataset](./loan.csv)
The given data contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## Conclusions
- Customer living in Rent and loan amount less than 15K are highly like to default
- Debt consolidation has the highest number of defaulters. But percentage of defaulters are highest for small businesses.
- Customer opting loan for Credit card and debt consolidation has higher dti value, hence more porbable to default.
- Different loan purpose had different interest date distribution. The interest rate of small businesses being the maximum
- Not verified customers are actually more likely to default.
- Customer opting for 60 months term are more likely to default.
- Percentage of defaulters increase with increase in debt to income ratio (dti)
- Higher dti value customers have probublity of defaulting more even if customer has good Grades
- Percentage of defaulters decreases with increasing annual income.
- Customers with employment period more than 10 years are taking most of the loans for Debt consolidation and are also the highest contributer in small business by a good margin
- Percentage of defaulters increase with increase in interest rate.
- Customer living in Rent and loan amount less than 15K are highly like to default





## Technologies Used
- Python - version 3.7.6
- NumPy - version 1.18.1
- Pandas - version 1.2.3
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was created as a case study required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore
- This project was based on UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform [this tutorial](https://www.example.com).

Prepared by:

Projesh Kumar Mondal
Rajesh Kumar Nakka


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->