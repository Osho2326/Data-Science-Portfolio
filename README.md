# Data-Science-Portfolio
Portfolio of data science projects completed by me for Data Scientist position, self learning and enthusiasm for Artificial Intelligence. All the projects are presented in the form of iPython Notebooks.

## Motivation : 
I have been working in the field of Data Science for the last 18-20 months. I first learned about Data Science when I was in my 3rd year of my graduation and came to know about how we are in the midst of a new global revolution, one that is driven by and centred on data that surrounds us and infuses everything we do, from making a toast to driving cars across the country and establishing new paradigms of social interaction and the key to all that is Data Science. My interest grew more and more as I learned what Artificial Intelligence can bring to the future. I am motivated towards my role as a Data Scientist.

Looking forward to advance my career as a Data Scientist since what matters in Data Science is the richness of our analysis not the quantity of code. The analysis is more important for me than code if I ought to pick one. I believe that I am passionate, intellectually capable, and prepared to set out on this exhilarating path.

For a more visually pleasant experience for browsing the portfolio, check out 
https://osho2326.github.io/portfolio/

Note: Data used in the projects (accessed under data directory) is for demonstration purposes only.

## Instructions for Running Python Notebooks Locally:

- Install dependencies using requirements.txt.
- Run notebooks as usual by using a jupyter notebook server, Google Colab, Vscode etc.

## Contents

### Machine Learning:

- **Social network Graph Link Prediction - Facebook - Supervised Learning** :- Given a directed social graph, Created a machine learning model to predict missing links to recommend users. Mapped the problem into supervised learning problem. Tried to support connections which were most likely to connect and not to miss any possible connection. No low-latency were required.
- **Taxi Demand Prediction in New York City : Time-series forecasting : Regression** :-  Created a ML Model to find the number of pickups in the given location coordinates(latitude and longitude) and time, in the query region. Data of the famous NYC yellow taxis that provide transportation exclusively through street-hails were used.
- **Quora Question Pair: Identify question pair that have the same intention : Binary Classification problem** :- Created a machine learning model that identified which questions asked on Quora are duplicates of questions that have already been asked. This is used to instantly provide answers to questions that have already been answered. Task was to predict whether a pair of questions are duplicates or not.
- **Stack Overflow: Tag Prediction : Multi-label classification** :- Created a ML model to suggest the tags based on the content that was there in the question posted on Stackoverflow. Model predict as many tags as possible with high precision and recall because incorrect tags could impact customer experience on StackOverflow.
- **Personalized Cancer Diagnosis : NIPS Competition : Multi class classification problem** :- Created a ML model which classify the given genetic variations/mutations based on evidence from text-based clinical literature. Two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations. Classified the given genetic variations/mutations based on evidence from text-based clinical literature.
- **Microsoft Malware detection : Multi class classification problem** :- Created a machine learning model to identify whether a given piece of file/software is a malware. In order to be effective in analyzing and classifying such large amounts of data, we need to be able to group them into groups and identify their respective families. Dataset provided by Microsoft contains about 9 classes of malware.

### Recommendation System:

- **Amazon Fashion Discovery Engine : Content Based Recommendation** :- Created a system to recommend similar apparel items/products in e-commerce. Collected the data from amazon API accessed under data directory. Used both text pre-processing and image pre-processing. Best results were taken into consideration.
- **Netflix Movie Recommendation : Collaborative Based Recommendation : Regression problem** :- Predicted the rating that a user would give to a movie that he had not yet rated. Minimize the difference between predicted and actual rating (RMSE and MAPE). For a given movie and user model predicted the rating would be given by him/her to the movie.

### Natural Language Processing:

- **Amazon Fine Food Review : Text pre-processing : Feature Engineering : Binary Classification** :- Created a machine learning model that determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2). A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review. Used the SQLITE dataset as it easier to query the data and visualise the data efficiently.
- **Customer Support on Twitter : Text pre-processing** :- Objective of this kernel was to understand the various text preprocessing steps. Cleaning or preprocessing the data is as important as model building if not more. And when it comes to unstructured data like text, this process is even more important. Carefully choose the preprocessing steps based on our use case since that also play an important role.
- **SMS Spam Collection : Text pre-processing : Binary classification** :- Created a prediction model that can accurately classify which texts were spam
or not.files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

### Data Analysis and Visualisation : Python

- **Indian Start-ups Ecosystem**:- Objective was to find investors and increase the chances of funding opportunities. Data had details about 3009 funding deals and data was available from January 2015 till September 2019.
- **Zomato Bangalore Restaurants**:- Objective was to analyze the Zomato dataset to get a fair idea about the factors affecting the establishment of restaurant and boost sale for beverages at different places in Bengaluru.

### Algorithms and Performance Matrics Used:

- **Social network Graph Link Prediction - Facebook** :- 
    1. Algorithm : Random Forest Classifier and RandomSearchCV to find the optimal hyper-parameter.
    2. Performance matrics : F1 Score and Confusion matrics.
- **Taxi Demand Prediction in New York City : Time-series forecasting** :- 
    1. Algorithm : Linear Regression, Random Forest Regression and XgBoost regression.
    2. Performance matrics : Mean Absolute percentage error, Mean Squared error.
- **Quora Question Pair: Identify question pair that have the same intention** :- 
    1. Algorithm : Logistic Regression, Linear SVM, and XgBoost
    2. Performance Matrics : Log-loss, Confusion matrics, Precision and Recall
- **Stack Overflow: Tag Prediction** :- 
    1. Algorithms : 
    2. Performance Matrics :
- **Personalized Cancer Diagnosis : NIPS Competition** :- 
    1. Algorithms : Naive Bayes, Logistic Regression
    2. Performance matrics : Multi-class log-loss, confusion matrics
- **Microsoft Malware detection** :- 
- **Netflix Movie Recommendation** :- 
    1. Algorithm :
        - For regression problem : Xgboost
        - For recommendation problem : Surprised library
            - Baseline
            - XgBoost
            - Baseline + XGBoost
            - KNN-baseline
            - Baseline + XgBoost + knn_bsl_m
            - Matrix factorization techniques such as SVD
            - Baseline + XgBoost + KNN + MF SVD
    2. Performance Matrics : Mean Absolute Percentage Error, Root Mean Square Error
- **Amazon Fine Food Review** :- 
    1. Algorithms : Naive Bayes, Logistic Regression 
    2. Performance Matrics : Confusion matrics, AUC

If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot an email at oshokumar97@gmail.com.

## Support My Work
If these projects inspired you, gave you ideas for your own portfolio or helped you, please consider buying me a coffee ❤️.
















 




   



