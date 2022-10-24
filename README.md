# Conversion-rate-challenge

My email : 👉baptiste.cournault@gmail.com👈

Video link : 👉https://share.vidyard.com/watch/h6Epca8CNMdVnYu8GcWnit?👈

![image](https://user-images.githubusercontent.com/106257819/197458154-905fe132-749e-4ad6-8833-ef7609a50f02.png)

## Challenge : predict conversions 🏆🏆

In this project, you will participate to a machine learning competition like the ones that are organized by https://www.kaggle.com/. You will be able to work with jupyter notebooks as usual, but in the end you'll have to submit your model's predictions to your teacher/TA, so your model's performances will be evaluated in an independent way. The scores achieved by the different teams will be stored into a leaderboard 🏅🏅

## Description of a machine learning challenge 🚴🚴

In machine learning challenges, the dataset is always separated into to files :
data_train.csv contains labelled data, which means there are both X (explanatory variables) and Y (the target to be predicted). You will use this file to train your model as usual : make the train/test split, preprocessings, assess performances, try different models, fine-tune hyperparameters etc...
data_test.csv contains "new" examples that have not be used to train the model, in the same format as in data_train.csv but it is unlabeled, which means the target Y has been removed from the file. Once you've trained a model, you will use data_test.csv to make some predictions that you will send to the organizing team. They will then be able to assess the performances of your model in an independent way, by preventing cheating 🤸
Your model's predictions will be compared to the true labels and releases a leaderboard where the scores of all the teams around the world are stored
All the participants are informed about the metric that will be used to assess the scores. You have to make sure you're using the same metric to evaluate your train/test performances !

## Company's Description 📇

www.datascienceweekly.org is a famous newsletter curated by independent data scientists. Anyone can register his/her e-mail address on this website to receive weekly news about data science and its applications !

## Project 🚧

The data scientists who created the newsletter would like to understand better the behaviour of the users visiting their website. They would like to know if it's possible to build a model that predicts if a given user will subscribe to the newsletter, by using just a few information about the user. They would like to analyze the parameters of the model to highlight features that are important to explain the behaviour of the users, and maybe discover a new lever for action to improve the newsletter's conversion rate.

They designed a competition aiming at building a model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter). To do so, they open-sourced a dataset containing some data about the traffic on their website. To assess the rankings of the different competing teams, they decided to use the f1-score.

## Goals 🎯

The project can be cut into four steps :

⋅⋅⋅Part 1 : make an EDA and the preprocessings and train a baseline model with the file data_train.csv

⋅⋅⋅Part 2 : improve your model's f1-score on your test set (you can try feature engineering, feature selection, regularization, non-linear models, hyperparameter optimization by grid search, etc...)

⋅⋅⋅Part 3 : Once you're satisfied with your model's score, you can use it to make some predictions with the file data_test.csv. You will have to dump the predictions into a .csv file that will be sent to Kaggle (actually, to your teacher/TA 🤓). You can make as many submissions as you want, feel free to try different models !

⋅⋅⋅Part 4 : Take some time to analyze your best model's parameters. Are there any lever for action that would help to improve the newsletter's conversion rate ? What recommendations would you make to the team ?

## Deliverable 📬

To complete this project, your team should:

⋅⋅⋅Create some relevant figures for EDA

⋅⋅⋅Train at least one model that predicts the conversions and evaluate its performances (f1, confusion matrices)

⋅⋅⋅Make at least one submission to the leaderboard

⋅⋅⋅Analyze your best model's parameters and try to make some recommendations to improve the conversion rate in the future

