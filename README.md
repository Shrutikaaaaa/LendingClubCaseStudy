# LendingClubCaseStudy
This Analysis report shows Online Loan study, where multiple derivations based on Return of Investment,Loan Defaulted, Number of loans issued based on employment, state, loan_puprose and other metrics have been depicted.
Data shape - 39717 rows and 111 columns

Code and Resources used
Python - 3.0 Packages : pandas, numpy, matplotlib, seaborn.

Data Cleaning
After reading the data, following changes were done
Fixing Rows and Columns: DataType changes and column values fixing
Convert string object to date object for below columns: issue_d, last_pymt_date,int_rate
Removal of extra space in column value : term

Missing values
Dropping unnecessary columns and columns with more 70% of missing values and filling missing values.
Let's drop the columns with more than 30% missing values(since the data is already huge).
Since there is no much spread of data and the difference between mean and median is very small, let's impute the missing values with mean for column: revol_util.

