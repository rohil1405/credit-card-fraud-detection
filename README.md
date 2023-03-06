# Credit-Card-Fraud-Detection
Credit Card Fraud Detection using logistric regression, XGBoost Classifier and Random Forest.

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Dataset
- The dataset used for this research is collected from Kaggle at https://www.kaggle.com/mlg-ulb/creditcardfraud.

- The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

- It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Introduction

- 'Fraud' in credit card transactions is unauthorized and unwanted usage of an account by someone other than the owner of that account.
- Necessary prevention measures can be taken to stop this abuse and the behavior of such fraudulent practices can be studied to minimize it and protect against similar occurrences in the future.
- Fraud detection involves monitoring the activities of populations of users in order to estimate, perceive or avoid objectionable behaviour, which consist of fraud, intrusion, and defaulting.

## Problem Statement and Proposed system

- The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. 
- This model is then used to identify whether a new transaction is fraudulent or not. 
- The approach that this project proposes, uses the latest machine learning algorithms to detect anomalous activities, called outliers. 
- Our aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.
- Our Project’s main purpose is making Credit Card Fraud Detection, awaring to people from credit card online frauds. the main reason of credit card fraud detection system is necessary to safe our transactions & security.

## Requirements

#### Hardware Requirement
- Laptop/PC
- Memory : 4 GB Ram
- Processor : i3
- Operating System : Windows 10
- Internal Hard disk : 256 GB
#### Software Requirement
- Python

## Detection

Some of the currently used approaches to detection of suchfraud are:
- Artificial Neural Network
- Fuzzy Logic
- Genetic Algorithm
- Logistic Regression
- Decision tree
- upport Vector Machines
- Bayesian Networks
- Hidden Markov Model
- K-Nearest Neighbor

## This Project

In this project we have compared three algorithms according to their accuracy.
- Logisitc Regression
- Random Forest Classifier
- XGBoost Classifier

#### Logistic regression

- Logistic regression is an example of supervised learning.
- It is used to calculate or predict the probability of a binary (yes/no) event occurring. 
- The f-1 score is lowest hence this is not a preferred algorithm.

#### Random Forest Classifier

- Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset.
- It has the highest f-1 score so this is selected for prediction.
- Another advantages of random forest are that it is faster and takes less training time while also giving high accuracy.

#### XGBoost Classifier

- In this algorithm, decision trees are created in sequential form. Weights play an important role in XGBoost. Weights are assigned to all the independent variables which are then fed into the decision tree which predicts results. 
- The weight of variables predicted wrong by the tree is increased and these variables are then fed to the second decision tree. These individual classifiers/predictors then ensemble to give a strong and more precise model. It can work on regression, classification, ranking, and user-defined prediction problems.
- It’s accuracy is high but because of higher recall value it is discarded 

## Heap Map

<img width="275" alt="image" src="https://user-images.githubusercontent.com/103554765/223153905-0c3cd780-0c5d-444c-9142-1219e17295fb.png">

## FlowChart

<img width="443" alt="image" src="https://user-images.githubusercontent.com/103554765/223154066-914eceef-024b-43c7-aa0c-37c1bd297148.png">



