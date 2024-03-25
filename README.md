# credit-risk-classification

Attached please find the documents for the Module 20 Challenge within the 'Credit_Risk' folder:
  - The 'credit_risk_classification.ipynb' file which features the code for the Logistic Regression Model.
  - The 'Resources' folder which includes the 'lending_data.csv' file that was loaded in for analysis.

**Credit Risk Analysis Report**
Overview of the Analysis

The purpose of this project was to train and evaluate a model based on loan risk. The financial information at our disposal included loan size, interest rate, borrower income, a debt-to-income ratio, the number of accounts, any derogatory marks, and total debt. We used this information to predict a loan status of either 0 (healthy) or 1 (high-risk).

In order to complete this process, I first seperated the existing 'loan_status' column (as the y variable) from the rest of the DataFrame (and made that the X variable). Next, I used the train_test_split module to create 'X_train', 'X_test', 'y_train' and 'y_test' values for the rest of the analysis. I then used the LogisticRegression module to create a 'classifier' variable that I used to fit the model using the training data. I made predicitons using the 'X-test' variable and then I evaluated the model's performance by generating a confusion matrix and a classification report.

Results

Machine Learning Model 1:

