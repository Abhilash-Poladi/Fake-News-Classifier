# Fake-News-Classifier
This is a classifier that predicts if a news is real or fake

dataset : https://www.kaggle.com/competitions/fake-news/data 

As part of data preprocessing, we 
1) Remove stop words
2) Apply stemming to extract the root word

After preprocessing the data, we tranform the text data to numerical data using TFIDF. we then use the numerical data as an input to the Logistic regression model.

Metrics to evaluate the model:
1) Accuracy score
2) Confusion matrix
3) Recall
4) Precision
5) F1 score
