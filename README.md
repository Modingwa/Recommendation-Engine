# Recommendation Engine
> 
The main motivation behind this project is to build a recommendation engine that analyses the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles that they may find useful or of interest.

## Table of contents
* [Data and Code](#data-and-code)
* [Project Recommendation Models](#project-recommendation-models)
* [Prerequisites](#prerequisites)

## Data and Code
* The main project file is the Recommendations_with_IBM.ipynb jupyter notebook. This contains the code for exploratory data analysis as well various models for recommendations. The models used are Collaborative filtering, Rank-based recommendation and SVD - Matrix Factorization Recommendations.
* The html file is generated from the notebook. 

## Project Recommendation Models
* Collaborative Filtering
    * Takes into account the similarity of users and recommends the most popular articles read by similar users.
* Rank Based Recommendations
    * Recommends the highest ranked articles by choosing similar users that have the most total article interactions as well as choosing articles with the most total interactions.
* SVD - Matrix Factorization Recommendations
    * Makes use of singular value decomposition to make recommendations based on accuracy and f1 score performance metrics.
## Prerequisites
* Pandas
* Numpy
* Seaborn
* Sklearn
* Matplotlib
Jupyter notebook and python 3.6 are needed to run the notebook.

