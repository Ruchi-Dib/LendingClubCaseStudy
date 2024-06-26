## Lending Club Case Study
Case study refers to a consumer finance company which specialises in lending various types of loans to urban customers. It incurrs financial losses due to loan default from risky loan applicants. Our objective is to identify driver variables for loan default and help the company utilize our findings/analysis for its portfolio and risk assessment.


## Table of Contents
### About the Company - General Information:
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of
medical procedures Borrowers can easily access lower interest rate loans through a fast online interface It faces
significant financial losses due to credit loss from ' loan applicants who default on their loans.
Key Objectives / Problem Statement:
 - Identify Risky Loan Applicants Determine the driving factors driver variables of loan default by borrowers,
i. e. the variables which are strong indicators of default.
 - Reduce Credit Loss by making use of driving factors Minimize the financial losses due to defaults, by
identifying and potentially rejecting high risk loan applications based on different driver variables which are
strong indicators of default.
Our objective is to identify driver variables for loan default and help the company utilize our findings/analysis for
its portfolio and risk assessment.
### Analysis Approach & Technologies used:
 - Performed Exploratory Data Analysis ( to investigate the dataset and identify patterns or trends associated
with loan defaults
 - While performing EDA, data cleaning activities have been performed and some major steps taken were
removal of columns with all null values, removal of columns not contributing in analysis and removal of ‘loan
status’ as current and keeping only the Fully Paid and Charged off loan status
 - As per the problem statement, analysis is more focused on loan default as count rather in monetary terms Few
places (as needed in the analysis), monetary term has also been considered
 - Examined company’s historical record report trend on loan and derived outcomes based on Univariate and
Bivariate analysis
 - Identified all key variables that are strong predictors of loan default
 - Develop a comprehensive understanding of the borrower profiles and loan characteristics that contribute to
higher default rates
 - Made extensive use of python and it’s libraries like pandas, matplotlib and seaborn
### Conclusion:
After analysing multiple driver variables using EDA, there are several observations and conclusions drawn (as listed below) which leads to higher loan default rates among loan
borrowers
Key Outcomes from Univariate & Bivariate Analysis:
1. Sanctioned Loan Amount Loan sanction volume being higher at lower disbursement values and thus, loan default volume is higher at same level Bivariate analysis leads to
the conclusion that Special due diligence is needed for loan sanction in the disbursement bucket of 20 K to 25 K” and 30 K to 35 K” due to higher loan default percentage
2. Loan Tenure Loan with higher tenure 60 months) has the higher loan default percentage 25 based on total loan sanctioned at same tenure
3. Interest Rates Loan default increases with increase in intertest rate and highest loan default is between 20 to 23 interest rate Interest rate should be maintained at
market standards mean level Issuing risky loans at higher interest rate would make the loan more risky
4. Loan Grades Loan grades assigned by the LC seems to be working fine with higher loan defaults at lower grade sub grade level Loan sanctions to lower grades should be
minimized and more scrutinized
5. Employee Experience There isn’t much variance in loan default at different employee service length and loan default percentage at each employee service length ranges
between 12 to 15 Loan disbursed to employee with service length of 7 and 10 years need better scrutiny since loan default percentage at these length are 15
6. Loan Purpose Loan disbursed for the purpose of “Small Business” need better scrutiny since it has the highest loan default percentage of 27 Also, since major loan
business volume comes from loan purpose of “Debt Consolidation”, loan for this purpose need to be better scrutinized
7. Geographical Factors Loans sanctioned to borrowers in the states of NV and NE show higher default rates NV is more relevant since there are very few borrowers in state of
NE wit h 60 loan default rate
8. Seasonal Periodical factor Maximum loan default happens in the quarter end months (month 3 and year end (i e Dec) This could be because, sales team grant more
number of loans to applicants at liberal terms to achieve their sales targets
9. Borrower Income Source of income for low annual income groups should be scrutinized to minimize loan defaults Also, employees with instalment of 20 to 25 of annual
income need better scrutiny since the loan default is highest at this level
### Overall Conclusion:
The analysis highlights that loan defaults are influenced by a combination of factors related to multiple loan driver variables By focusing on these key indicators, the company can
further process its risk assessment and lending strategies to mitigate the risk of loan defaults, thereby reducing financial losses Specifically, loans with lower amounts, specific
interest rate ranges,


## Contact & Contributors
Created by [@Ruchi-Dib] - feel free to contact me!
 - Ruchi Agarwal
 - Abirami Manickam
