# Prescription Drug Sentiment Analysis

<img src="/header/header1.jpg" width="600">

---

## Introduction
Patient reviews for over 3,000 drugs were obtained from online pharmaceutical review sites. Information such as the patients condition, drug name, date, review, and rating were all collected in order to construct the dataset. The main purpose of the data is to be used for sentiment analysis, where the rating determines the classification of the review. However, the data will also be used in exploring select features such as drug name, condition, and rating in order to get a better understanding for the data and its distributions. 

**Citation Requested by UCI**: Felix Gräßer, Surya Kallumadi, Hagen Malberg, and Sebastian Zaunseder. 2018. Aspect-Based Sentiment Analysis of Drug Reviews Applying Cross-Domain and Cross-Data Learning. In Proceedings of the 2018 International Conference on Digital Health (DH '18). ACM, New York, NY, USA, 121-125.

---

## Data
The data for this project was collected from the [UCI Drug Review](https://www.kaggle.com/jessicali9530/kuc-hackathon-winter-2018) on Kaggle, but it originated from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29). Features of the data include:
- *drugName* (categorical): name of drug
- *condition* (categorical): name of condition
- *review* (text): patient review
- *rating* (numerical): 10 star patient rating
- *date* (date): date of review entry
- *usefulCount* (numerical): number of users who found review useful

The data was originally split into a train/test partition of size 75% and 25% (respectively). However, we will further split the training data into both a training and validation set using an 80/20 split (respectively).

#### Data Formatting

---

*To be filled in...*
