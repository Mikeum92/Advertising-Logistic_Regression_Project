# Advertising-Logistic_Regression_Project

This project will be using a fake advertising data set, indicating whether or not a particular internet user clicked on an Advertisement on a company website. It will focus on trying to create a model that will predict whether or not a user will click on an ad based off the features presented.

The data set contains the following features:

      * 'Daily Time Spent on Site': consumer time on site in minutes
      * 'Age': cutomer age in years
      * 'Area Income': Avg. Income of geographical area of consumer
      * 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
      * 'Ad Topic Line': Headline of the advertisement
      * 'City': City of consumer
      * 'Male': Whether or not consumer was male
      * 'Country': Country of consumer
      * 'Timestamp': Time at which consumer clicked on Ad or closed window
      * 'Clicked on Ad': 0 or 1 indicated clicking on Ad
 
 The project is merely an application of skills in data visualization  and machine learning modeling. is focuses on:
 * Exploratory Data Analysis and Visualization using seaborn 
 * Creating a Logistic Regression model to predict users behaviors' boase off their features. 
 
The trained model was able to predict with and accuracy of 94% that a user will click on the ad will visiting the company website.
The classification report for the model can be found in the jupyter project notebook.
            
         precision    recall  f1-score   support

           0       0.91      0.95      0.93       157
           1       0.94      0.90      0.92       143

    accuracy                           0.93       300
