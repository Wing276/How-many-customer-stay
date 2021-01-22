# How many Customers Stay
## 1. Background
- This data comes from clients of a bank. The bank wants to model whether they will stay or not in the future. The task is to do the binary classification based on the given information.
## 2. Data Set Information
- The data are attributes of customers' basic information. 
- train.csv
  - The training set with 13 input attributes and 1 output attribute (i.e. class attribute)
- test.csv
  - The testing set with 13 input attributes. You need to identify the class of each item. 

#### Other files
1. evaluate_2.exe:
    - Let me know if you are using another operating system
    - This is a command line tool to evaluate your result. F1-measure is used to measure your result.
    - Usage: Press "command + r" and then type in "cmd" in the dialog box to launch a terminal. Then type in the command:
```bash
evaluate_2.exe submission_2.csv
``` 
2. submission_2_tree.csv: 
    - result from decision tree

3. submission_2_xgb.csv: 
    - result from XGBoost
  
4. customer_churn.ipynb

5. samplesubmission.csv:
    - This is a sample file to show the output format. Wrong format will lead to unknown result.
    
## 3. Goal

- The classification goal is to predict if the customer will leave this bank and choose other competitors in the future (i.e, Identify the value of feature 'Exited', 1 for yes and 0 otherwise).

## 4. Attribute Information
#### a) Input variables

**customers' basic information**

- RowNumber: the number of rows
- CustomerId: the id of the customer in this bank.
- Surname: the surname of the customer
- CreditScore: personal credit score for an account.
- Geography: the location of the customer.
- Gender: the gender of the customer.
- Age: the age of the customer.
- Tenure: the valid time of the account.
- Balance: the amount of money in the account.
- NumOfProducts: the number of products the customer buys.
- HasCrCard: The number of Credit Card the customer owns.
- IsActiveMember: whether active in the recent period.
- EstimatedSalary: the estimated salary of the custome

#### b) Output variable

- Exited: whether this customer will leave in the future.

Remark: This is one of my school projects. You can download my script and play around my code :)
