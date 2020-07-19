Project:-
   Credit Card Fraud Detection

Abstract:-
  The credit card fraud detection features uses user behavior and location scanning to check for unusual 
  patterns. These patterns include user characteristics such as user spending patterns as well as usual user
  geographic locations to verify his identity. If any unusual pattern is detected, the system requires 
  revivification.
  The system analyses user credit card data for various characteristics. These characteristics include user 
  country, usual spending procedures. Based upon previous data of that user the system recognizes unusual
  patterns in the payment procedure. So now the system may require the user to login again or even block the
  user for more than 3 invalid attempts.

Process:-

  Collecting Data: - Took data set from Kaggle.
  Analyzing Data: - Explore our data as much as possible like what are the important variables for this model.
                    For e.g Location and time can be used to make a pattern.This can be better understand by
                    ploting various graphs.
  Data wrangling: - Clean that data which is not useful Ticket-id or null values in data set etc.
  Train & Test: - Build the model using train data set and test the model on test data set.
  Accuracy check: - checked that how much accurate our value are.

What I have done:-
  Import various libraries 
    • Pandas 
    • Numpy 
    • Seaborn 
    • Matplotlib
    • Sklearn
  Read the csv file using pandas.
  Compress the data size because the data file contain large number of data.
  Plot the various graph using seaborn to check whether the data is balanced or not.
  Split the data into Train data and Test data so that we can check the model.
  Import Confusion matrix and then check the model on test data.
  Use Logistic Regression Algorithm to get accuracy.

In this model I got the accuracy 0.998495 which is much much better. So no need to check other algorithms.
  
