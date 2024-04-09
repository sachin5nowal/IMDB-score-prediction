# IMDB-score-prediction

IMDB Movie Prediction
Data description
The dataset (movie-review-data.csv) contains 28 variables for 5043 movies, spanning across 100 years in 66 countries. There are 2399 unique director names, and thousands of actors/actresses. “imdb_score” is the response variable while the other 27 variables are possible predictors.

Problem Statement:
Build Model to predict what kind of movies are more successful. Take imdb scores as response variable and focus on operating predictions by analyzing the rest of variables in the movie data.

Date:-07/04/2021


### Contents
1. Importing libraries and loading data
2. Exploratory data analysis:looking what's in data :Statistics
    1. Basic observations, feature statistics
    2. Visual representations
3. Modelling
    1. Data cleaning (Missing value replacement)
    2. Feature Engineering(Creating new features)
    3. Feature selection (Correlation , Eliminating features)
    4. Machine learning algorithms with hyperparameter tuning
4. Conclusion



IMDB Movie Prediction (Modelling and conclusion)
About: This notebook is continuation of 'imdb_score_prediction_cleaned.ipynb'.

Author:- Sachin Nowal
Date:-11/04/2021
3.4 Modelling : Machine learning algorithms with hyperparameter tuning
Algorithm: We are using a regression model here
Experiments with classification model can also we done but balancing techniques should be used
Also as binning/bucketing imdb_score might result in loss in precision{ability to predict in precise decimal values}
