# Starbucks Capstone project

This project is a part of Udacity Data Science Nanodegree

Project Overview
Data Set
Installation
File Descriptions
Acknowledgements
Results

## 1. Project Overview
This is a capstone project of the Data Scientist Nanodegree Program of Udacity. In this project, the given dataset contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offers during certain weeks. Not all users receive the same offer, and that is the challenge to solve with this dataset.

## 2. Data sets
The data is contained in three files:

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed
Following is the schema and explanation of each variable in the files:

portfolio.json

id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)
profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income
transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record

## 3. Installation
No extra besides the built-in libraries from Anaconda needed to run this project
Data Processing & Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
Data Visualization: Matplotlib, Seaborn


## 4. File Descriptions
This repo contains 4 files.There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

## 5. Acknowledgements
This project was completed as part of the [Udacity Data Science Nanodegree]. The dataset used in this project contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Starbucks® Rewards program: Starbucks Coffee Company.

## 6. Results 
The main observations of the code are published on medium [here](https://medium.com/@sara_96045/starbucks-capstone-challenge-b894bc313e8b )
