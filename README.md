# Credit_Card_Defaulter_Classifier

### Problem Statement : 
A bad loan for the bank can lead to a huge financial loss in the event of a defaulter and requires heavy risk-mitigation regarding this issue. Furthermore, the bank loaning process can be quite a manual and tiresome task in identifying who might be a potential defaulter. The loaning process is also quite dependent on the loan processors themselves, leaving a lot of it to subjectivity which might possibly turn into a bad loan in the future.  
  
On the other side, banks can also earn a lot from people who actually pay back their loans. Additionally, they don’t want to be turning people away who could really use that money to get their lives back on track or achieve their dreams (i.e. setting up a business or higher education etc.).

This project aims to bridge this gap of uncertainty by utilizing a data-driven approach by using past data of credit card customers in conjunction with machine learning to predict whether a consumer will default on their credit cards.


### Objective :
The goal behind using this model is to achieve two things:  
•	Bring more consistency to the loaning process.  
•	Investigate what the key drivers are behind a potential defaulter.

### Problem Solving  Approach :
---

---
### Attribute Information :
This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.  
There are 25 variables in the dataset :  

|Column Name|Meaning|
|:---|:---|
|ID | ID of each client  |
|LIMIT_BAL | Amount of given credit in NT dollars (includes individual and family/supplementary credit)  |
|SEX | Gender (1=male, 2=female)  |
|EDUCATION | (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)  |
|MARRIAGE | Marital status (1=married, 2=single, 3=others)  |
|AGE | Age in years  |
|PAY_0 | Repayment status in September, 2005 (-2: No consumption or advance payment;  -1: Paid in full; 0: The use of   revolving credit (partial payment); 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment   delay for eight months; 9 = payment delay for nine months and above.)    |
|PAY_2 | Repayment status in August, 2005 (scale same as above)  |
|PAY_3 | Repayment status in July, 2005 (scale same as above)  |
|PAY_4 | Repayment status in June, 2005 (scale same as above)  |
|PAY_5 | Repayment status in May, 2005 (scale same as above)  |
|PAY_6 | Repayment status in April, 2005 (scale same as above)  |
|BILL_AMT1 | Amount of bill statement in September, 2005 (NT dollar) | 
|BILL_AMT2 | Amount of bill statement in August, 2005 (NT dollar)  |
|BILL_AMT3 | Amount of bill statement in July, 2005 (NT dollar)  |
|BILL_AMT4 | Amount of bill statement in June, 2005 (NT dollar)  |
|BILL_AMT5 | Amount of bill statement in May, 2005 (NT dollar)  |
|BILL_AMT6 | Amount of bill statement in April, 2005 (NT dollar)  |
|PAY_AMT1 | Amount of previous payment in September, 2005 (NT dollar)  |
|PAY_AMT2 | Amount of previous payment in August, 2005 (NT dollar)  |
|PAY_AMT3 | Amount of previous payment in July, 2005 (NT dollar)  |
|PAY_AMT4 | Amount of previous payment in June, 2005 (NT dollar)   |
|PAY_AMT5 | Amount of previous payment in May, 2005 (NT dollar)  |
|PAY_AMT6 | Amount of previous payment in April, 2005 (NT dollar)  |
|default payment next month | Default payment (1=yes, 0=no)  |
