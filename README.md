# Lending Club Case Study
## Goals of data analysis:  

``` 
Lending loans to ‘risky’ applicants is the largest source of financial loss
(called credit loss). The credit loss is the amount of money lost by the lender 
when the borrower refusesto pay or runs away with the money owed.  

The main objective is to be able to identify these risky loan applicants, 
then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study.   

Perform an analysis to understand the driving factors (or driver variables)
behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment. 

## Table of Contents
*Dataset-provided to us of past loan applicants-Loan Dataset and Data dictionary for finance jargons
* [Technologies Used]-Python 3*(Libraries used-numpy,panda,seaborn,matplotlib)
* [Conclusions]- conclusions are derived on the basis of credit history, 
   annual income, int rates, loan amount, grades etc(descritive conclusions are provided in the PPT)


## General Information.
Project is about a consumer finance company LendingClub company which specializes in lending various types of
loans to urban customers. When the company receives a loan application, the company has to make a decision 
for loan approval based on the applicant’s profile.

- What is the background of your project?
-Business Loss-in events of not approving loan to an applicant who can repay the loan
-Credit Loss-If the applicant is not likely to repay the loan, i.e. he/she is likely 
to default, then approving the loan may lead to a financial loss for the company

- What is the business probem that your project is trying to solve?
The aim is to identify patterns which indicate if a person is likely to default, 
which may be used for taking actions such as denying the loan, reducing the amount of loan, 
lending (to risky applicants) at a higher interest rate, etc.

- What is the dataset that is being used?
Loan.csv dataset is being used which has data of past loan applications and applicants, 
along with another data file which has finance jargons explanation.



## Conclusions

- Loans for Small Business(Loan Purpose) Applicants should be checked properly.
- Loan approval should be avoided for those who already have Derogatory Public Records.
- Loan approval should be avoided for those who already have Public Bankruptcy Records.
- Loan approval for Low quality loans should be avoided or given for smaller loan repayment term.
- Lower annual income applicants should be avoided for big loan amounts with higher interest Rates.
- Loan approval should be avoided for applicants who don’t have a source of income or adequate income against the loan amount applied for.
- Loan approved for people who wish to have a long repayment term should be scrutinized from time to time as long repay term also indicates applicant’s inclination to have EMIs of lower amount or some kind of collateral should be kept in such cases.
- Loans with high amount should be avoided for applicants who don’t have significant work experience as it affects their compensation, eventually impacting their liability to lender. 


## Technologies Used
- library - Python numpy 1.23.5
- library - Python Pandas 1.5.3
- library - Python Matplotlib
- library - Python Seaborn 0.12.2


## Acknowledgements
This case study has been completed with equal collaboration from Garvit Minocha(Group Facitilator) and Shivendu Sharma.
-Developed as part of the Exloratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
https://learn.upgrad.com/course/4653/segment/40028/233888/714354/3605983


## Contact
Created by [@githubusername] - feel free to contact me!
