
# Loan Defaulter Prediction:  
## Project at Infosys (No code due to restrictions)
### Keywords : R, SQL ,Logistic Regression, Random Forests
### The Goal of this project is to predict whether a customer of the bank will default or not in near future, and help the bank to make a decision in the approval process of loan.
* Identified the key variables for analysis by working together with banking domain Subject Matter Expert (SME) and documented the requirements
* Studied the schema of database and wrote SQL queries to pull data from several tables in order to compile data set for the analysis
* Performed data cleaning and manipulation such as deleting records with majority missing columns,created new variables from existing variables like maximum transaction amount,discretized income etc.,
* Hand annotated response classes "Default","Non Default" for a sample of customer records using the business rules to create training labels
* Explored several attributes of customer such as age,income,number of loans,sex,credit score  etc., w.r.to response variable
* Modeled logistic regression for the classification to interpret the variable importance based on odds ratio and decision tree model to interpret variables ,derive decision rules based on tree structure
* Evaluated model performance based on F1-Score and tree model outperformed logistic model ,hence as a next step Random Forest model was trained to achieve better results
* Tested the model performance on future loan data, both logistic regression and Random forest achieved better F1 score than expert judgement by 0.15 this is because existing expert judgement over looked some dynamic variables like late fee
