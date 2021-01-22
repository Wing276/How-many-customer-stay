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
    - Usage: Press "command + r" and then type in "cmd" in the dialog box to launch a terminal. Then type in the command:
    - Other notification details are as introduced in the "macOS setting".
```bash
./evaluate_2.exe ./submission_2.csv
```
2. submission_2_tree.csv: 
    - result from decision tree

3. submission_2_xgb.csv: 
    - result from XGBoost
  
4. customer_churn.ipynb

Remark: This is one of my school projects. You can download my script and play around my code :)
