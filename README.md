# Starbucks Capstone Challenge:
Understanding our customers is the key providing them a good service and sustain a profitable business. To understand them well, we need to pay attention on their purchase behaviour. One way we can collect and analyse their purchasing behaviour through an app, then identify their needs based on demographics.

## Table of Contents:
1. [Project Overview](https://github.com/Aditya-Kashyap/starbucks-capstone-challenge#Project-Overview)
2. [Problem Statement / Metrics](https://github.com/Aditya-Kashyap/starbucks-capstone-challenge#Problem-Statement-/-Metrics)
3. [Installation](https://github.com/Aditya-Kashyap/starbucks-capstone-challenge#Installation)
4. [Project Motivation](https://github.com/Aditya-Kashyap/starbucks-capstone-challenge#Project-Motivation)
5. [File Descriptions](https://github.com/Aditya-Kashyap/starbucks-capstone-challenge#File-Descriptions)

## Project Overview:

Starbucks has provided a dataset that emulates the behavior of customers using the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app.  An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.
                
This project is focused on analysis the promotional offers for customers based on their responses to the previous offers and find out which of them are most likely to respond to an offer. 

This will improve the conversion rate of the offers and increase the overall profit for Starbucks. Will create and compare different predictive models to evaluate which features contribute most to a successful offer.
 

## Problem Statement

The goal is to predict whether or not a user will response an offer that is sent to him.  


## Installation:
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter-Notbook](https://jupyter.org/install.html)

Or you could install [Anaconda](https://www.anaconda.com/products/individual), a pre-packaged Python distribution that contains all 
of the necessary libraries and software for this project.

## Project Motivation:
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, 
Starbucks sends out an offer to users of the mobile app. Using this dataset I have built a model that predict whether customers will respond to 
offers or not.

The Starbucks Udacity Data Scientist Nanodegree Capstone challenge data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Periodically, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). However, some users might not receive any offer during certain weeks. Using the data, I aim to :

    1. Gain understanding what types of customer characteristics and demographics are there.
    2. What offer should be sent to each customer ?
    3. How well can we predict customer response to offer ?

## File Descriptions:

The data is contained in three files:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.).
* profile.json - demographic data for each customer.
* transcript.json - records for transactions, offers received, offers viewed, and offers completed.

Here is the schema and explanation of each variable in the files:

### portfolio.json:
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

### profile.json:
* age (int) - age of the customer
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

### transcript.json:
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

## Solution Statementv:

*	Preprocessing—merging all the data, cleaning up data
*	EDA – performing a deep dive analysis on each element
*	Build Model – using learning techniques namely Support Vector Machines, Random Forest, KNN, Naive Bayes, Light GBM and Logistic Regression and compare the performance of each model  
*	Compare the performance of each model accuracy and F1-score
  
