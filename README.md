# Author-Features-Prediction---NLP
About problem :
Text in the form of blogs, posts, articles, etc. is written every second. It is a challenge to predict the information about the writer without knowing about him/her.
Objective:
The aim is to predicts multiple features of the author of a given text.Multilabel classification problem.

Dataset: 
Blog Authorship Corpus:
    Over 600,000 posts from more than 19 thousand bloggers  
The Blog Authorship Corpus consists of the collected posts of 19,320 bloggers gathered from blogger.com in August 2004. The corpus incorporates a total of 681,288 posts and over 140 million words - or approximately 35 posts and 7250 words per person.

Methods That we followed:
 
Preprocessing:
 * Regular Expresion to clean the text.
 * Stop words.
 * tokenization.
 * Stemming and Lemmatization.
 * As we want to make this into a multi-label classification problem, we are required to merge all the label columns together, so that we have all the labels together for a particular sentence. 
 * Label columns to merge: “gender”, “age”, “topic”, “sign” 
 * Spliting the data

VECTORIZER THE FEATURES:

 BAG OF WORDS USING THE COUNT VECTORIZER.
      i. Use ngram_range=(1, 2)
      ii. Vectorize training and testing features

TERM FREQUENCY AND INVERSE DOCUMENT FREQUENCY - TF-IDF

Convert your train and test labels:
MULTILABEL-BINARIZER

Choose a classifier:
  * ONE VS REST CLASSIFIER
  * LOGISTIC REGRESSION.

EVALUATION METRICS:
i. Accuracy score 
ii. F1 score 
iii. Average precision score 
iv. Average recall score 
v.micro/macro/weighted averaging 

 
