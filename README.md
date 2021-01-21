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
1. samplesubmission.csv:
    - This is a sample file to show the output format. Wrong format will lead to unknown result.
	
2. evaluate_2.macOS:
    - This is a command line tool to evaluate your result. We will use F1-measure to measure your result. 
    - Usage: Press "command + space" to open spotlight search and type in "terminal", then type in the following command in the terminal. You should replace
	```./submission_2.csv``` with your own path to the submission_2.csv.  Please note that ```./```denote the current position of the command line and ```submission_2.csv``` denote your submission file name.
```bash
./evaluate_2.macOS ./submission_2.csv
```

3. evaluate_2.linux:
    - Usage: Press "ctrl + alt + t" to launch a terminal and input the following command.
    - Other  notification details are as introduced in the "macOS setting".
```bash
./evaluate_2.linux ./submission_2.csv
```

4. evaluate_2.exe:
    - Usage: Press "command + r" and then type in "cmd" in the dialog box to launch a terminal. Then type in the command:
    - Other notification details are as introduced in the "macOS setting".
```bash
./evaluate_2.exe ./submission_2.csv
```

5. submission_2_tree.csv: 
    - result from decision tree

6. submission_2_xgb.csv: 
    - result from XGBoost
  
7. customer_churn.ipynb

Remarks: This is one of my school projects
