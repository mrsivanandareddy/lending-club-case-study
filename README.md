# Lending Club Case Study

The primary objective of the Lending Club case study is to mitigate the credit loss while approving or denying the loans to their customers. 
This challenge arises from two potential scenarios
1. Rejecting the loans to the applicants who has the capability to repay the loans will result in a loss of business to the company
2. Approving the loans to the customers who are likely to default may lead to financial loss for the company

The objective is to determine the applicants at risk of defaulting on loans, enabling a reduction in credit losses. This case study aims to achieve this goal through Exploratory Data Analysis (EDA) using the provided dataset.


## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Objectives

The primary objective of the Lending Club case study is to mitigate the credit loss while approving or denying the loans to their customers. 
This challenge arises from two potential scenarios
1. Rejecting the loans to the applicants who has the capability to repay the loans will result in a loss of business to the company
2. Approving the loans to the customers who are likely to default may lead to financial loss for the company

The objective is to determine the applicants at risk of defaulting on loans, enabling a reduction in credit losses. This case study aims to achieve this goal through Exploratory Data Analysis (EDA) using the provided dataset.

## Conclusions

### Univariant Analysis
1. Applicants who are employed for more than 10 years a for are accountable for the highest number of "Charged off" loans. 
2. The majority of defaulted loan members are individuals, living in rented houses. 
3. "Charged off" loans are mostly that are taken during the 4th quarter(December, November and October) primarily in December. This 	might be the reason for loan application during the holiday season.
4. The trend says, the Charged Off loans are increasing year by year.
5. Most of the Charged off loans are due to Debt Consolidation. 
6. California state had the highest number of Charged off loan applicants. 
7. Short term loans with a duration of 3 years or 36 months are popular among Charged Off loan applicants.
8. The following combinations are some of the reasons for Charged Off loans
   - Loan amounts between 5k to 10k
   - Installment amount between 150$ to 270$
   - Interest rate between 13% to 17%
   - Debt to Payments ratio between 12 to 24.

### Bivariant Analysis
1. Applicants with annual income more than 60k and applying for either home or home improvement or small business has higher chances 	of defaulting. 
2. Applicants with Grade E, F, G and applying for 15k or more loan amount 
3. Applicants applying for over 12k loan amount for the purpose of credit card, debt consolidation or house are prone to default
4. “Charged Off” loans are likely to happen if the applicants annual income is over 70k and interest rate is between 21-24%
5. “Charged Off” loans are likely to happen if the Loan amount is over 15k and interest rate is between 21-24%
6. “Charged Off” loans are likely to happen with F & G grades if the interest rate is over 20%

### Correlation Analysis
1. Installment and loan amount has a strong correlation
2. Term and interest rate has strong correlation
3. Annual income and loan amount has a strong correlation
4. dti has weak correlation with other fields
5. emp_length has weak correlation with other fields
6. pub_rec_bankrupticies has weak correlation with every field
7. dti and annual income has negative correlation


## Technologies Used

- [Python](https://www.python.org/) - version 3.11.7
- [Pandas](https://pandas.pydata.org/) - version 2.1.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Matplotlib](https://matplotlib.org/) - version 3.8.0
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2


## Acknowledgements

- UpGrad material and tutorials on Exploratory Data Analysis (EDA) on the UpGrad learning platform

## Collaborators

Created by [@ShivaMylarapu](https://github.com/mrsivanandareddy) and [@SunithaSaraf](https://github.com/shravaniwani)
