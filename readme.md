
# Lending Club Default Analysis

## The analysis is divided into four main parts:
1. Data understanding
2. Data cleaning (cleaning missing values, removing redundant columns etc.)
3. Data Analysis 
4. Recommendations

# Data understanding
1. Basic study of each column entry to know how the different customer profile looks.
   Some of the important columns in the dataset are loan amount, term, interest rate, 
   grade, sub grade, annual income, purpose of the loan etc.

2. Identified the target variable, which we want to compare across the independent 
   variables, is loan status. The strategy is to figure out compare the average 
   default rates across various independent variables and identify the ones that 
   affect default rate the most.
   
# Data cleaning 

Below approach is followed to clean/remove the redundant ineffective data. 

1. Looked for redundant information and empty (NA) values then removed them as it is not going to impact the data analysis
   After this process removed around 111 columns were removed and retained only 57 columns
2. Filtered the data those are not available for all the customers with limit of >70%
   Because the data that are available for only limited customers not be correlated with other customers to find any inferences.

# Data Analysis   

## Univariate analysis  
1. Studied the no of loan approvals happened year wise
2. Studied loan amount approved year wise
3. Studied count of loan approved loan tenure wise
4. Studied customer's purpose of loan to know their emotional motivation that will make them to repay the loan committedly
5. Studied loan amount, funded amount and investment of funded amount
6. Studies customer nature based their grade category, also studied their population.
7. Studied customers employment duration to know their repaying capacity based on their job stability.
8. Studied customer verification status to filter out the non-verified customer.

## Bivariate analysis 
1. Studied customer's Annual income v/s Funded amount to check their re-paying capacity.
2. Studied customer's Funded amount v/s home ownership to check their re-paying capacity.
3. Studied the last payment histories to check the recent financial status of customers.
4. Studied customer's number of derogatory public records count to know their social background details

## Derived variables analysis
1. Binned/Segmented the customer based on interest rate.
2. Binned/Segmented the customer based on loan amount wise.

## Below the data analysis outcomes
1. Higher grade customer have good record re-paying the load, only < 10% customers defaulted the load, F grade have 
   higher ono repayment count
2. Higher non re-payment rate is found in higher interest rate loans.
3. Both Higer and lower income customer loan re-payment commitment is at similar proportion
4. More loan defaulters are seen in the lower loan amount groups.
5. More loan defaulters are seen in verified customer category.

# Recommendations 
1. Higher interest rate loans needs to monitored. Close engagement with the customer is needed.
2. More loan defaulters are seen in verified customer category, so verification process needs to be strengthened
