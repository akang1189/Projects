# Project 3: Web APIs & NLP

Description:
1. Using Pushshift's API, you'll collect posts from two subreddits of your choosing.
2. You'll then use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem.

## Executive Summary


### Subreddits
(https://www.reddit.com/r/nfl) vs (https://www.reddit.com/r/baseball)

### Problem Statement

We are an analytics firm hired by one of the largest sports gambling platforms in the country. While we will be eventually building a sports gambling prediction model, today we will start by building the foundation, training a classifer using data from two of the most popular sports subreddits, football and baseball.

What are the key words helpful to the model in predicting which subreddit a post came from? 


Workflow

We will be comparing a random tree classifier to a logistic regression model to see which model best predict which subreddit a post came from.

- Importing data from reddit
- Data Collection and Cleaning
- EDA
- Preprocessing for Modeling
  - Tokenization
  - Lemmatization
  - Stemming
  - CountVectorizer
  - Tf-idf
- Modeling
- Results 
-Evaluation

### Conclusions

I had some issues with this model, I will revist my mistakes after discussing with my instructors. Fixed the issue with the amounts of posts being grabbed but not sure why all my models are producing the same output.

Ran the models multiple times with multiple different outputs. Could keep a random state however was working on fixing other breaks.

## The model correctly predicted: CountVectorizer/Logistic Regression
Our first model scored the best, rhe accuracy score was 100.0% on training data and about 96-100% on testing/new data. We are confident in our model with such a high accuracy however there is no such thing as a perfect model. We will revisit our models to see if there were any parameters we could refine.


Model 1: 0.9689
Model 2: 0.9688
Model 3: 0.9649
Model 4: 0.9611

Second time around:
 Model 2- TF-IDF Vectorizer Logistic Regression achieved a better testing score for a logistic regression model and produced the best accuracy on testing data.

Train/Test: 1.0/0.9804
Gridsearch  Model 2: 0.9871
Specificity Model 2: 0.9615384615384616


### Recommendations

There is no such thing as the perfect model however this model is predicting perfect accuracy, is this correct? What could be causing this and why?
Is this our best model or can we make it better?
Improve our model by collecting more data, better data refining, and including more models ie. boosting, SVM.
Sentiment analysis could also be helpful to better determine negative sentiment for betting odds.

