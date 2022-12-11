# DATA606 - Capstone Project

## Fake News Detection Using NLP [Website](https://sites.google.com/umbc.edu/data-606-hk-website/home)

## Resources:

- Data collected from 'Politifact' [website](https://www.politifact.com/factchecks/list/)

- **Python Libraries** : pandas, numpy, beautifulsoup, matplotlib, seaborn, sklearn, scipy, textblob
- **NLP Libraries** : NLTK, TF-IDF, VADER

## Introduction:

Fake news can be defined as a set of elaborate lies or hoaxes that are deliberately fabricated to mislead or defame an individual, a community or an organization. With the widespread reliance on social media for information and unchecked growth of such platforms, false news reaches millions of people in a matter of few seconds which can lead to devastating consequences for the society. In recent years, reluctance of social media executives to proactively identify and censor false information on their platforms to promote free speech has led to several civic unrests like the Rohingya genocide, healthcare nightmares like unverified COVID treatments and threats to national security. Additionally, an increase in the circulation of False information has also seen an increase in Cyberbullying, public shaming, mental health crisis and in extreme cases suicide and wrongful convictions. Given this dangerous nature of false information it is necessary to identify this information and remove it from social media platforms as soon as possible. 

## Overview of the project:

Data Collection: 

We extract labeled data from the section’s of crime, guns, and marijuana of the PolitiFact website. 

Data Cleaning: 

We clean the data so that we can derive insights from it and then convert it into a format suitable for classification algorithms.

Exploratory Data Analysis (EDA):

We use statistics and visualizations to analyze and identify trends in data set.

Statistical Analysis:

We use in-built python libraries to perform Hypothesis testing and derive insights from the data

Feature extraction: 

We make use of various natural language processing methodologies to transform the text data into data suitable for machine learning models to process.

Prediction:

We build and evaluate various traditional machine learning algorithms as well as a few deep learning algorithms to classify if the given statement is true information or not. The best model is selected and deployed for further use.


## Models
- Naive Bayes
- SVM
- Logistic Regression
- XGBoost
- Bi-LSTM
- GRU

## Procedure:
- Web scrapping
- Data Cleaning
- Exploratory Data Analysis
- Statistical Analysis
- Natural Language Processing
- Train the Model
- Model Evaluation
