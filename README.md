# Rec_System_Project_JJ_DC


## Introduction:

Used the dataset from MovieLens from the GroupLens research lab at the University of Minnesota. 
https://grouplens.org/datasets/movielens/latest/

## Objective:
 
To provide a director(Steven Spielberg) with specific criteria of a movie; on a model that outputs the top 5 movie recommendations based on their ratings of other movies using collaborative filtering & EDA.

## The Dataset:

* MovieLens
* TMDB

## Skills Required to Complete:

The skills used to complete this project consisted of:

* Working with Python to make visualizations using Matplotlib & Seaborn
* Using Pandas to collect and clean the dataset
* Building & interpreting various algorithmic models based on RMSE scores & hyperparameter tuning
* Using Scikit Suprise to cross validate our algorithms to reach the lowest RMSE score

## What Was Posted on GitHub:

Two separate notebooks were posted on GitHub. One was the Final Project notebook which consisted of the Data Cleaning, Collection & Modeling components of the project and the ReadMe notebook which is a layout of how our project was presented.

## Questions That Were Posed:

* How does the budget of a movie impact the overall rating it receives? (Which genres have the highest budget?)
* Does the movie genre impact the overall rating it receives? (Which genres had the most ratings?)
* Does the length of a movie impact the overall rating it receives? (Which genre has the longest run times?)
* What kinds of movies should be produced to achieve the highest user ratings?

## How the Data Was Put Together:

The data was gathered from about 100,000 different movie ratings from the MovieLens website. Following that, the data was run through various grid searches & cross validations in order to determine the best model to predict user ratings for movies. In addition, an API call was pulled from TMDB.com to merge with the MovieLens dataset to incorporate additional features. After the data was gathered & cleaned, EDA was performed to see which features had any statistical relationships with one another.

## Future Steps:

* To use the hybrid approach in order to include content filtering as opposed to just collaborative.
* Utilizing PySpark in order to incorporate a larger rating dataset to perform more accurate predictions.

## Recommendation Based on Analysis:

The following recommendations can be made for our director Steven Spielberg:

* Higher rated movies require a smaller budget, therefore recommending that it's unnecessary to overspend on a movie. Comedy movies on average have 80% less of the budget compared to Action & Adventure movies that Spielberg is known for making.
* On average, comedy movies are rated around a 3.4 which is essentially the target Spielberg has to surpass. Based off of our recommendation model, we provided five of the top rated comedy movies as guidance from the user who was accounted for the most comedy reviews in our dataset.
* Based off of our data, we believe that comedy is a strong genre to enter into because it encompasses the most reviews compared to the other genres.
* The average comedy movie run time is just over 100 minutes, therefore we believe that a 1-2 hour parameter is appropriate for this genre.

## Presentation Link:

https://docs.google.com/presentation/d/1OIJDNvcoEDuJCeSGipIy4YrRNlaxd546SrWxLWBvg3k/edit#slide=id.p

## Visual:

![](http://localhost:8888/view/Count_of_Ratings.png)








