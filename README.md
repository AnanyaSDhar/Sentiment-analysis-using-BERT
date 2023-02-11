[![author](https://img.shields.io/badge/author-Ananya-ff69b4.svg?style=flat-square)](https://www.linkedin.com/in/ananya-sutradhar/)
[![GitHub followers](https://img.shields.io/github/followers/Ananya21?style=social)](https://github.com/AnanyaSDhar?tab=followers)
[![GitHub watchers](https://img.shields.io/github/watchers/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?style=social)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/watchers)
[![GitHub stars](https://img.shields.io/github/stars/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?style=social)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?style=social)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/network/members)

![GitHub language count](https://img.shields.io/github/languages/count/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?logoColor=9cf&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?logoColor=important&style=flat-square)

[![GitHub issues](https://img.shields.io/github/issues/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?style=flat-square)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/issues?q=is%3Aopen+is%3Aissue)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?style=flat-square)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?logoColor=yellow&style=flat-square)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/pulls?q=is%3Aopen+is%3Apr)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning?logoColor=yellow&style=flat-square)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/pulls?q=is%3Apr+is%3Aclosed)
[![LICENSE](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](https://github.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning/blob/master/LICENSE)
[![HitCount](http://hits.dwyl.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning.svg)](http://hits.dwyl.com/AnanyaSDhar/Sentiment-analysis-using-Deep-Learning)

# Sentiment-analysis-using-Deep Learning

Dataset:
[IMDB data](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Table of Content
  * [Objective](#objective)
  * [Overview](#overview)
  * [Data Preprocessing](#data-preprocessing)
  * [Modeling](#modeling)
  * [Future Prospects](#future-prospects) 

## Objective

Analysis of sentiment delivered by movie reviews 

## Overview

BERT and LSTM model that is trained on an IMDB movie review dataset, taken from Kaggle, to classify the review as positive or negative. The results should be returned to the user displaying the prediction as either positive or negative.

## Data Preprocessing
Text preprocessing is traditionally an important step for natural language processing (NLP) tasks. It transforms text into a more digestible form so that machine learning algorithms can perform better. In this problem following types of preprocessing is used.
 * Removing all urls from data.
 * Removing all tags from data
 * Decontracting the words
 * Removing special character from data
 * Removing stop words
 * Stemming and Lemmatization
 * Tf-idf vectorization
 
 ##  Modeling
2 deep learning methods are used to train the model
* BERT (Bidirectional Encoder Representations from Transformers)
* LSTM (Long short-term memory)

##  Future prospects 

* Creating a flask app for better user interaction with the model
* Deployment of the model using Heroku.
* Creating a database for storing the input and prediction value



