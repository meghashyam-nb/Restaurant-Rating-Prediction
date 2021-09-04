# Restaurant-Rating-Prediction
The main goal of this project is to perform extensive Exploratory Data Analysis(EDA) on the Zomato Dataset and build an appropriate Machine Learning Model that will help various Zomato Restaurants to predict their respective Ratings based on certain features.

# Approach

  Data Exploration     : I started exploring dataset using pandas,numpy,matplotlib and seaborn. 

  Data visualization   : Ploted graphs to get insights about dependend and independed variables. 

  Feature Engineering  :  Removed missing values and created new features as per insights.

  Model Selection I    :  1. Tested all base models to check the base accuracy.
  
                          2. Also ploted residual plot to check whether a model is a good fit or not.

  Model Selection II   :  Performed Hyperparameter tuning using gridsearchCV and randomizedSearchCV.

  Pickle File          :  Selected model as per best accuracy and created pickle file using joblib .

  Webpage & deployment :  Created a webform that takes all the necessary inputs from user and shows output.
  
                           After that I have deployed project on heroku.
