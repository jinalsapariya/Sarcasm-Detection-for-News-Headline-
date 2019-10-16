# Sarcasm Detection for News Headline based data


Humor detection is an important problem in the field of Natural Language Processing. Famous voice assistants such
as Alexa, google voice assistant, Siri lack the opportunity of detecting sarcasm or humor in general. For example, if we
say, Alexa hit me with a truck, it does not understand the sarcasm involved in the sentence. The ability to detect humor
is important as it becomes an important feature when it comes to voice assistants and chatbots and we are trying to address
the same problem with this project which can help in the field of natural language processing. In this project I have used kaggle dataset for news headlines which is collected from HuffPost and The Onion to train RNN based models to classify headlines as sarcastic or non sarcastic.

## Dataset

https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection


## Data Preprocessing

* Checking class imbalance
* Removing punctuations and digits
* Fixing maximum sentence length
* Tokenizing sentences
* Visualizing Part of Speech Tags of sarcastic and non sarcastic data
* Lementization of senteces
* Stop word removal from data
* Use glove embeddings for data

## Classification Models used

* RNN/LSTM
* Naive Bayes Classifier
* Random Forest
* Linear Support Vector Classifier
* Logistic regression


## Evaluation Metric

* Accuracy


## Requirements

* nltk
* keras
* pandas
* tensorflow
* matplotlib


### Incase you are not able to see the notebook on github please goto https://colab.research.google.com/drive/12WlM_KUFDF33uHtSqHv6jl4BPMtpa7bH

