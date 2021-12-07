# Sentiment-analysis-on-Covid-19-tweets

Objective: 
-----------------------------------------------------------------------------------------------------------------------------------------
Classify 45k tweets on Covid-19 as positive or negative based on the following machine learning and deep learning models: 

* Multinomial Naive Bayes Model
* Random Forests 
* ADABoost
* XGBoost
* LSTM neural network
* BERT transformers model

The tweets are preprocessed using the following NLP methods: 

* Bag-of-words model
* Bag-of-POS model
* Glove word embeddings

Results:
--------------------------------------------------------------------------------------------------------------------------------------
* Among the machine learning classificators, XGBoost trained on a Bag-of-words model has the best performance in terms of accuracy (85%) and AOC ROC (92%)

References: 
----------------------------------------------------------------------------------------------------------------------------------------
* https://www.kaggle.com/andreshg/nlp-glove-bert-tf-idf-lstm-explained
* Ferrario, A., & Nägelin, M. (2020). The art of natural language processing: classical, modern and contemporary approaches to text document classification. Modern and Contemporary Approaches to Text Document Classification (March 1, 2020).

Data source: 
----------------------------------------------------------------------------------------------------------------------------------------
https://www.kaggle.com/datatattle/covid-19-nlp-text-classification
