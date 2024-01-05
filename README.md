# Spam SMS Classifier

This repository contains code for a Spam SMS Classifier. The classifier is built using Natural Language Processing (NLP) techniques and machine learning algorithms to classify SMS messages into spam or non-spam (ham) categories. The project involves data cleaning, exploratory data analysis (EDA), text preprocessing, model building, evaluation, and deployment.

## Files and Directory Structure
- `spam_sms_classifier.ipynb`: Jupyter Notebook containing the code for the entire project.
- `vectorizer.pkl`: Pickle file containing the trained TF-IDF vectorizer used for text transformation.
- `model.pkl`: Pickle file containing the trained Multinomial Naive Bayes classifier.

## Table of Contents
1. [Data Cleaning](#data-cleaning)
2. [Exploratory Data Analysis (EDA)](#eda)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Building](#model-building)
5. [Evaluation](#evaluation)
6. [Model Improvement](#model-improvement)
7. [Deployment](#deployment)

## Data Cleaning

The initial step includes loading the dataset, inspecting its structure, and performing necessary data cleaning operations. This involves removing unnecessary columns, handling missing values, and dropping duplicate entries.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis is performed to understand the distribution of spam and ham messages, visualize the data, and analyze the length and structure of messages.

## Data Preprocessing

Text preprocessing steps include converting text to lowercase, tokenization, removing special characters, stopwords, and applying stemming.

## Model Building

Several machine learning models are trained, including Naive Bayes (Gaussian, Multinomial, and Bernoulli), Support Vector Classifier (SVC), Decision Tree, Random Forest, AdaBoost, Gradient Boosting, XGBoost, etc.

## Evaluation

Models are evaluated using metrics such as accuracy, precision, and confusion matrix. The performance of each model is compared to identify the best-performing ones.

## Model Improvement

Different techniques to improve the model are explored, including changing parameters such as `max_features` in TF-IDF, scaling features, and considering the number of characters in messages.

## Deployment

The final model is saved using Pickle, and a simple Streamlit web application is created for user interaction. Users can input a message, and the model will predict whether it's spam or not.

## Usage

To use the model, run the Streamlit application locally. Ensure you have the required dependencies installed, and the model and vectorizer files are available.

Feel free to modify the code and experiment with different models or improvements.

Happy coding!





