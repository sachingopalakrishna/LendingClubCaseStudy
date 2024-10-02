# Lending Club Case Study
> This project focuses on leveraging the Lending Club dataset to build a predictive model that estimates the probability of loan defaults. By applying data science techniques, the objective is to uncover patterns and key factors that can effectively predict whether a borrower is likely to default on their loan.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Project Overview
This data science project aims to predict loan defaults using the Lending Club dataset. The primary goal is to create a model that assesses the probability of loan default, helping to reduce financial risk for the company.

### Project Background
Lending Club is the largest online marketplace for personal and business loans, including medical financing. It provides borrowers with a simple way to obtain lower-interest loans via an easy-to-navigate online platform. However, like other lending institutions, Lending Club faces significant financial risks, particularly when offering loans to high-risk individuals. The main cause of financial loss, referred to as credit loss, arises when borrowers fail to repay their loans. These defaulted loans, called "charged-off" loans, represent the biggest source of financial loss for the company.

### Project Objective
The goal is to identify the key factors that lead to loan defaults, which significantly affect the company's financial performance.

### Dataset
The dataset, provided in CSV format, contains loan-related information from Lending Club. It will serve as the basis for analyzing and predicting loan defaults.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Loan Grade: Borrowers classified with a loan grade of B or C demonstrate a greater tendency to default.
Loan Term: Loans with a term of 36 months exhibit a slightly higher default rate in comparison to those with a 60-month term.
Home Ownership Status: Renters are more susceptible to default than homeowners, highlighting "RENT" as a significant risk factor.
Employment Length: Borrowers with over 10 years of employment experience show a marginally higher default risk than those with shorter employment durations.
Annual Income: Individuals earning between $30,000 and $60,000 are at an increased risk of default. Furthermore, the analysis reveals that default probability declines as income increases, with lower-income groups facing greater risks.
Loan Amount: Borrowers seeking loans in the range of $4,000 to $6,000, especially for debt consolidation purposes, have a heightened likelihood of default.
Loan Purpose: Loans aimed at debt consolidation and credit card refinancing exhibit higher default rates. Other categories, including small business loans, general loans (classified as "other"), and home improvement loans, also present significant risk.
Credit Inquiries in the Last 6 Months: Borrowers with a greater number of credit inquiries in the preceding six months are more likely to default, suggesting a correlation between recent credit activity and default risk.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- MatplotLib - version 3.8.4
- NumPy - version 1.26.4
- Pandas - version 2.2.2
- Seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is part of the Machine Learning and Artificial Intelligence course within the UpGrad IITB Programme.


## Contact
Created by [@sachingk] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
