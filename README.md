# Spam SMS Classifier

This project is a machine learning-based spam SMS classifier. It involves data cleaning, exploratory data analysis (EDA), text preprocessing, model building, and evaluation. The goal is to build a classifier that can differentiate between spam and ham (non-spam) SMS messages.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis (EDA)](#eda)
5. [Text Preprocessing](#text-preprocessing)
6. [Model Building](#model-building)
7. [Evaluation](#evaluation)
8. [Model Improvement](#model-improvement)
9. [Deployment](#deployment)

## Introduction
This project focuses on building a spam SMS classifier using machine learning techniques. The steps include data cleaning, EDA, text preprocessing, model building, and evaluation. The classifier is trained on a dataset of SMS messages labeled as spam or ham.

## Dataset
The dataset used in this project is a CSV file (`spam.csv`) containing SMS messages labeled as spam or ham. It includes information about the type of message and additional columns that were cleaned during the data cleaning process.

## Data Cleaning
The initial dataset contained some unnecessary columns (`Unnamed: 2`, `Unnamed: 3`, `Unnamed: 4`), which were removed. Duplicate values were also removed to ensure the quality of the dataset.

## Exploratory Data Analysis (EDA)
EDA involves analyzing the distribution of spam and ham messages, visualizing the dataset, and exploring key statistics. Imbalance in the dataset is addressed through visualizations.

## Text Preprocessing
Text preprocessing includes converting text to lowercase, tokenization, removing special characters, stopwords, and applying stemming. The processed text is then used for model training.

## Model Building
The project uses various classifiers such as Gaussian Naive Bayes, Multinomial Naive Bayes, Bernoulli Naive Bayes, Support Vector Machine, K-Nearest Neighbors, Random Forest, AdaBoost, Bagging, Extra Trees, Gradient Boosting, and XGBoost. The models are trained, and their performances are evaluated.

## Evaluation
The models are evaluated based on accuracy, precision, and other relevant metrics. The performance of each model is discussed, and the best-performing model is chosen.

## Model Improvement
To enhance the model's performance, different strategies can be employed, such as adjusting hyperparameters, changing vectorizer parameters, or trying different algorithms. The README discusses the options considered for improving the model.

## Deployment
The final trained model is saved using `pickle` for future use. If applicable, information about deploying the model to a website or other platforms is provided.

Feel free to contribute, report issues, or suggest improvements!


