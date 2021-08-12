# Uber-Analysis-in-R

#We used the “Uber Pickups in New York City” dataset from Kaggle, which contains data on over 4.5 million Uber pickups in New York City 
from April to September of 2014, and 14.3 million more Uber pickups from January to June 2015. 
Trip-level data on 10 other for-hire vehicle (FHV) companies, as well as aggregated data for 329 FHV companies, is also included.

#Data Preprocessing 
Therefore, we separated the Date.Time column into more specific columns that tells us the the second of the day, minute of the day, 
hour of the day, day of the week, day of the month, as well as the month for better analysis with the number of trips. 
For certain machine learning algorithms, we also subset the data to analyze only a certain month because the datasets were simply 
too big and it takes a very long time to run.


#Modeling 
Three types of supervised classifiers were chosen including Linear Regression, Logistic Regression, 
and Support Vector Machines. Baseline models of all four classifiers were trained and evaluated on the same dataset.
