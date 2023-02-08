# UBER-FARE-PREDICTION

This code is based on the Machine learning project for the Uber Fare Prediction.

The project is about on world's largest taxi company Uber inc. 
In this project, we're looking to predict the fare for their future transactional cases. 
Uber delivers service to lakhs of customers daily. Now it becomes really important to manage their data properly to come up with new business ideas to get best results. Eventually, it becomes really important to estimate the fare prices accurately.

The dataset was taken from kaggle.

The datset contains the following fields:

key - a unique identifier for each trip
fare_amount - the cost of each trip in usd
pickup_datetime - date and time when the meter was engaged
passenger_count - the number of passengers in the vehicle (driver entered value)
pickup_longitude - the longitude where the meter was engaged
pickup_latitude - the latitude where the meter was engaged
dropoff_longitude - the longitude where the meter was disengaged
dropoff_latitude - the latitude where the meter was disengaged

We have used pandas, numpy, matplotlib, seaborn, calendar functions for the data cleaning and visualization purposes.

We used Linear Regression algorithm, Random Forest Algorithm, Decision Tree Algorithm andn XGBoost Algorithm for the predictive analysis.

As a conclusion, the XGBoost algorithm gives us a reliable score and thus used for further prediction process.
