# Lending Club Case Study
> Exploratory Data Analysis (EDA) in the context of loans involves a systematic examination of loan-related datasets. Through statistical techniques, visualizations, and summarization methods, analysts explore patterns, trends, and relationships within the data. EDA can provide insights into factors influencing loan approval, repayment behavior, and overall portfolio performance. This data-driven approach aids in making informed decisions, refining risk models, and optimizing lending strategies for better outcomes in the consumer finance industry.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project revolves around a consumer finance company specializing in providing various types of loans to urban customers.
- The primary challenge is to optimize the loan approval process, striking a balance between expanding the customer base and mitigating the risk of financial losses due to defaults.
- The company seeks to improve its ability to identify creditworthy applicants, ensuring it doesn't miss profitable lending opportunities while minimizing the approval of loans to individuals with a high likelihood of default.
- The project utilizes a comprehensive dataset sourced from the consumer finance company's loan records.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Income Impact:
    -   Applicants with an income range of $80,000 or more have lower chances of charged-off loans.
    -   Those with an income range of $0-$40,000 have higher chances of charged-off loans.
    -   Overall, the charged-off proportion decreases with an increase in annual income.  

2.  Interest Rate Influence :    
    -   Interest rates below 10% have significantly lower chances of charged-off loans.
    -   Interest rates above 16% have a higher likelihood of charged-off loans.

3.  Loan Purpose Analysis :    
    -   Small business and debt consolidation loans have higher chances of defaults.
    -   Major purchases have a lower likelihood of loan defaults.

4.  Home Ownership Impact :    
    -   Applicants without homes are more likely to default on loans.

5.  Loan Amount Distribution :    
    -   Small business loans have the highest median, 95th percentile, and 75th percentile of loan amounts.
    -   Debt consolidation and credit card loans follow in terms of loan amount.   

6.  Debt-to-Income (DTI) Ratio :    
    -   Higher DTI values are associated with a higher risk of loan defaults.
    -   Lower DTI values indicate lower chances of loan defaults . 

7.  Loan Issuance by Year and Month :    
    -   Loans issued in 2007 have the highest default rates, while 2009 has the lowest.
    -   Loans issued in May, September, and December have higher default numbers.
    -   February has high default numbers. 

8.  Bankruptcies Record Impact :    
    -   Bankruptcies with a record of 2 have a high impact on loan defaults.
    -   Bankruptcies with a record of 0 have a low impact on loan defaults.   

9.  Regional Differences :    
    -   Northeast (NE) states have the highest number of loan defaults.
    -   Iowa (IA) and Maine (ME) have lower numbers of loan defaults.  

10. Loan Grade Analysis  :    
    -   Applicants with loan Grade G have the highest loan defaults.
    -   Those with loan Grade A have the lowest loan defaults.

11. Experience and Income Source:

    -   Applicants with less or no experience may lack a stable income source, leading to higher loan defaults.
    -   Other applicants show relatively similar chances of getting charged off.

12. Loan Amount and Interest Rate Relationship:
    -   There is a positive correlation between loan amount and interest rates, contributing to higher charged-off ratios.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python: version 3.x
- Pandas: version 1.3.4
- Seaborn: version 0.12.2
- Matplotlib: version 3.5.3
- Plotly: version 5.9.0
- Numpy: version 1.21.6

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
-  This project was inspired by the need to optimize the loan approval process and mitigate financial risks in consumer finance.


## Contact
Created by :
-   Jitesh Rathod 
-   Bala Gorrepati


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->