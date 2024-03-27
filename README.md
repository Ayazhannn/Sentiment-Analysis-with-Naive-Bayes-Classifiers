# Sentiment-Analysis-with-Naive-Bayes-Classifiers
This repository contains code for performing sentiment analysis on movie reviews using Naive-Bayes classifiers. Three variants of Naive-Bayes classifiers - Multinomial NB, Bernoulli NB, and Complement NB - are explored, and their performance is evaluated on the IMDb 50k film dataset. This project are done on Google Colab. The server is running on Python version 3.10.12.

## Overview
Sentiment analysis, also known as opinion mining, is a natural language processing task aimed at determining the sentiment expressed in text data. This project focuses on sentiment analysis of movie reviews, a common application of text classification.

## Dataset
The IMDb 50k film dataset, comprising 50,000 movie reviews labeled as positive or negative, is utilized. Each review provides valuable insights into the sentiment of the reviewer towards the movie.

## Naive-Bayes Classifiers
* Multinomial NB: Suitable for text classification tasks with discrete features, such as word counts.
* Bernoulli NB: Designed for binary feature vectors, making it ideal for tasks where only the presence or absence of features matters.
* Complement NB: A variant of Multinomial NB that addresses class imbalance by adjusting for the frequency of each term in the dataset.

## Required Libraries

To run the code in this repository, you'll need the following Python libraries:

- `numpy`: Library for numerical computations.
- `pandas`: Library for data manipulation and analysis.
- `scikit-learn`: Library for machine learning algorithms and tools.
- `matplotlib`: Library for creating visualizations.
- `seaborn`: Library for statistical data visualization.
- `nltk`: Library for natural language processing tasks.
- `wordcloud`: Library for generating word clouds.
- `re`: Library for regular expressions and pattern matching.
