Project Name:-
   Predicting the Survival of Titanic Passenger.
   
Abstract:-
  As we all know about Titanic Ship. Sinking of the Titanic caused the deaths of   thousands of passengers and that is the deadliest disaster in the history. A lot of reasons     was there for not surviving of passengers but one of the main reason was that there was not enough boats on the crew. From that a most interesting observation which comes out   from the sinking is that some people were more likely to survive than the others like women, children were the one who got the priority to rescue. The objective is to first     explore the unknown information by applying exploratory data analytics on available data set and then apply ML models to complete the analysis of what sorts of people were       likely to survive. And then the results of applying ML models are compared and analyzed on the basis of accuracy. 

Process:-
  1.	Collecting Data: - Took data set from Kaggle.
  2.	Analyzing Data: - Explore our data as much as possible like check that the females or children survive better than males or did the rich passengers survived more than the       poor passengers etc.
  3.	Data wrangling: - Clean that data which is not useful Ticket-id or null values in data set etc.
  4.	Train & Test: - Build the model using train data set and test the model on test data set.
  5.	Accuracy check: - checked that how much accurate our value are.

What I have done:-
  1.	Import various libraries
    •	Pandas
    •	Numpy
    •	Seaborn
    •	Matplotlib
    •	Sklearn
  2.	Read the csv file using pandas.
  3.	Plot the various graph using seaborn to check whether the data is balanced or not.
  4.	Removed/drop the null data using drop function.
  5.	Covert the string data into integer values using get_dummies function.
  6.	Split my data into two parts: - Train data and Test data.
  7.	Used two ML algorithm: -
     •	Logistic Regression: - Accuracy got 0.77128
     •	Random Forest: - Accuracy got 0.82601


  

  

