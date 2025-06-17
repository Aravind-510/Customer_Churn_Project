Customer_churn Dataset: 
The details regarding this ‘customer_churn’ dataset are present in the data dictionary 
Lab Environment: Anaconda 
Domain – Telecom 
Tasks to be done:
 A) Data Manipulation: 
a. Extract the 5th column & store it in ‘customer_5’ 
b. Extract the 15th column & store it in ‘customer_15’ 
c. Extract all the male senior citizens whose Payment Method is Electronic check & 
store the result in ‘senior_male_electronic’ 
d. Extract all those customers whose tenure is greater than 70 months or their 
Monthly charges is more than 100$ & store the result in ‘customer_total_tenure’ 
e. Extract all the customers whose Contract is of two years, payment method is Mailed 
check & the value of Churn is ‘Yes’ & store the result in ‘two_mail_yes’ 
f. 
Extract 333 random records from the customer_churndataframe& store the result in 
‘customer_333’ 
g. Get the count of different levels from the ‘Churn’ column  

B) Data Visualization: 
a. Build a bar-plot for the ’InternetService’ column: 
i. 
Set x-axis label to ‘Categories of Internet Service’ 
ii. 
iii. 
Set y-axis label to ‘Count of Categories’ 
Set the title of plot to be ‘Distribution of Internet Service’ 
iv. Set the color of the bars to be ‘orange’ 
b. Build a histogram for the ‘tenure’ column: 
i. 
Set the number of bins to be 30 
ii. 
iii. 
Set the color of the bins  to be ‘green’ 
Assign the title ‘Distribution of tenure’ 
c. Build a scatter-plot between ‘MonthlyCharges’ & ‘tenure’. Map ‘MonthlyCharges’ to 
the y-axis & ‘tenure’ to the ‘x-axis’: 
i. 
ii. 
iii. 
Assign the points a color of ‘brown’ 
Set the x-axis label to ‘Tenure of customer’ 
Set the y-axis label to ‘Monthly Charges of customer’ 
iv. Set the title to ‘Tenure vs Monthly Charges’ 
d. Build a box-plot between ‘tenure’ & ‘Contract’. Map ‘tenure’ on the y-axis & 
‘Contract’ on the x-axis.  

C) Linear Regression: 
a. Build a simple linear model where dependent variable is ‘MonthlyCharges’ and 
independent variable is ‘tenure’ 
i. 
ii. 
iii. 
Divide the dataset into train and test sets in 70:30 ratio.  
Build the model on train set and predict the values on test set 
After predicting the values, find the root mean square error 
iv. Find out the error in prediction & store the result in ‘error’ 
v. Find the root mean square error 

D) Logistic Regression: 
a. Build a simple logistic regression modelwhere dependent variable is ‘Churn’ & 
independent variable is ‘MonthlyCharges’ 
i. 
Divide the dataset in 65:35 ratio 
ii. 
iii. 
Build the model on train set and predict the values on test set 
Build the confusion matrix and get the accuracy score 
b. Build a multiple logistic regression model where dependent variable is ‘Churn’ & 
independent variables are ‘tenure’ & ‘MonthlyCharges’ 
i. 
Divide the dataset in 80:20 ratio 
ii. 
iii. 
Build the model on train set and predict the values on test set 
Build the confusion matrix and get the accuracy score 

E) Decision Tree: 
a. Build a decision tree model where dependent variable is ‘Churn’ & independent 
variable is ‘tenure’ 
i. 
ii. 
iii. 
Divide the dataset in 80:20 ratio 
Build the model on train set and predict the values on test set 
Build the confusion matrix and calculate the accuracy 

F) Random Forest: 
a. Build a Random Forest model where dependent variable is ‘Churn’ & independent 
variables are ‘tenure’ and ‘MonthlyCharges’ 
i. 
Divide the dataset in 70:30 ratio 
ii. 
iii. 
Build the model on train set and predict the values on test set 
Build the confusion matrix and calculate the accuracy 
