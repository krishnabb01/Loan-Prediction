# Loan-Prediction

**Customer Financial Data**

*Description:*
    Contains financial information about customers such as income, credit score, and debt levels.
Loan Information Data

*Dataset Column Descriptions*

    Customer_ID: Unique identifier for each customer.
    
    Name: Full name of the customer.
    
    Age: Age of the customer.
    
    Gender: Gender of the customer.
    
    Annual_Income: Annual income of the customer.
    
    Credit_Score: Credit score of the customer.
    
    Total_Debt: Total amount of debt held by the customer.
    
    Employment_Status: Employment status of the customer.

**Loan Information Data**

*Description:* 
  Contains details about loans including loan amount, interest rate, and loan term.
Historical Default Data

*Dataset Column Descriptions*

    Loan_ID: Unique identifier for each loan.
    
    Customer_ID: Unique identifier for the customer who took the loan.
    
    Loan_Amount: Amount of the loan.
    
    Interest_Rate: Interest rate on the loan.
    
    Loan_Term: Duration of the loan.
    
    Loan_Start_Date: Date when the loan was issued.

**Historical Default Data**

*Description:*
  Contains records of past loan defaults to train the predictive model.

*Dataset Column Descriptions*

    Loan_ID: Unique identifier for each loan (matching with Loan_ID in Loan Information Data).
    
    Default: Binary indicator of default (1 if defaulted, 0 if not).
