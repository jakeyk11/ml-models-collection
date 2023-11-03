# Collection of Machine Learning Models
This repository contains a collection of Machine learning models that I have constructed to solve a range of problems, including [Kaggle competitions](https://www.kaggle.com/jakekolliari).

## Contents

<details open="open">
  <summary>Problems</summary>
  <ol>
    <li><a href="#kaggle---titanic-disaster"> ➤ Kaggle - Titanic Disaster</a></li>
    <li><a href="#kaggle---restaurant-recommender-system"> ➤ Kaggle - Restaurant Recommender System</a></li>
    <li><a href="#football-pass-clustering"> ➤ Football Pass Clustering</a></li>
  </ol>
</details>

## Kaggle - Titanic Disaster

### Motivation
I have included this popular machine learning challenge purely to demonstrate the approach I typically take to tackle simple machine learning problems. 

### Description
Using Titanic passenger data, I have constructed a classification model to determine what sorts of people were more likely to survive the disaster. This work involves the construction of a machine learning pipeline and testing of a variety of classification algorithms. The chosen model uses a gradient-boosted decision tree algorithm with tuned hyperparameters to predict whether a given passenger was likely to survive or not given their passenger information.

### Files
Steps taken to develop the machine learning model are found within [Kaggle - Titanic Disaster/ml_model.ipynb](https://github.com/jakeyk11/ml-models-collection/blob/main/Kaggle%20-%20Titanic%20Disaster/ml_model.ipynb)

    Kaggle - Titanic Disaster
    │
    ├── data
    │   ├── train.csv
    │   ├── test.csv
    │ 
    ├── output
    │   ├── submission.csv
    │ 
    ├── ml_model.ipynb


## Kaggle - Restaurant Recommender System

### Motivation
Development of a Restaurant Recommender System to consolidate learning of Neural Network driven collaborative filtering algorithms.

### Description
This project makes use of user, item and rating data extracted from the University of California Machine Learning repository. The objective being to develop collaborative filtering algorithm that is able to make restaurant rating predictions for a new or existing user. Work undertaken on Google Collab.

### Files
Steps taken to develop the machine learning model are found within [Kaggle - Restaurant Recommender System/restaurant-recommender-system.ipynb](https://github.com/jakeyk11/ml-models-collection/blob/main/Restaurant%20Recommender%20System/restaurant_recommender_system.ipynb)

    Kaggle - Restaurant Recommender System
    │
    ├── data [not included in this repository]
    │   ├── chefmozaccepts.csv
    │   ├── chefmozcuisine.csv
    │   ├── chefmozhours4.csv
    │   ├── chefmozparking.csv
    │   ├── geoplaces2.csv
    │   ├── rating_final.csv
    │   ├── usercuisine.csv
    │   ├── userpayment.csv
    │   ├── userprofile.csv
    │    
    ├── restaurant_recommender_system.ipynb


## Football Pass Clustering

### Motivation
I regularly use football event data (second-by-second logs of actions and locations within a match) to undertake and share football analytics projects. The ability to assign a team's passes to specific pass clusters presents the opportunity to perform deeper analysis on how a team tends to move the ball throughout the pitch. I therefore decided to develop and implement my own pass clustering algorithm.

### Description
Using 5,000,000+ passes withn Europe's "Big 5" leagues (Opta data, 2019/20 - 2022/23), I have constructed a clustering model that is able to assign successful passes to one of 65 clusters. This work involves the construction of a machine learning pipeline and testing of a variety of classification algorithms. The chosen model uses a k Means clustering algorithm to assign passes, which I have then packaged up within a clustering function to support many of my football analytics projects.

### Files
Steps taken to develop the machine learning model are found within [Football Pass Clustering/ml_model.ipynb](https://github.com/jakeyk11/ml-models-collection/blob/main/Football%20Pass%20Clustering/ml_model.ipynb)

    Football Pass Clustering
    │
    ├── data
    │   ├── pass_data.pbz2 [not included in this repository]
    │ 
    ├── images
    │   ├── birch_t015.png
    │   ├── bisecting_k_means.png
    │   ├── ...
    |
    ├── output
    │   ├── PassClusterModel65.joblib
    │ 
    ├── ml_model.ipynb
