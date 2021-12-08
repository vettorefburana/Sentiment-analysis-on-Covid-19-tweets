# Sentiment-analysis-on-Covid-19-tweets

Objective: 
-----------------------------------------------------------------------------------------------------------------------------------------
Classify 45k tweets on Covid-19 as positive or negative based on the following machine learning and deep learning models: 

* Multinomial Naive Bayes Model
* Random Forests 
* ADABoost
* XGBoost
* Simple RNN
* LSTM 
* GRU
* Bidirectional LSTM
* BERT 

For machine learning models, the tweets are preprocessed using the following NLP methods: 

* Bag-of-words model
* Bag-of-POS model
* Pre-trained Spacy word embeddings

For neural networks, we use the following preprocessing methods: 

* Pre-trained Spacy word embeddings
* Keras embedding layers

Results:
--------------------------------------------------------------------------------------------------------------------------------------
* Among the machine learning classificators, XGBoost trained on a Bag-of-words model has the best performance in terms of accuracy (85%) and AUC ROC (92%)
* Among the deeplearning models, the GRU network with no preprocessing has the best performance (accuracy = 87% and AUC ROC = 95%)

References: 
----------------------------------------------------------------------------------------------------------------------------------------
* https://www.kaggle.com/andreshg/nlp-glove-bert-tf-idf-lstm-explained
* https://www.kaggle.com/tanulsingh077/deep-learning-for-nlp-zero-to-transformers-bert#Bi-Directional-RNN's
* Azunre, P. (2021). Transfer learning for natural language processing. Simon and Schuster.
* Ferrario, A., & Nägelin, M. (2020). The art of natural language processing: classical, modern and contemporary approaches to text document classification. Modern and Contemporary Approaches to Text Document Classification (March 1, 2020).

Data source: 
----------------------------------------------------------------------------------------------------------------------------------------
https://www.kaggle.com/datatattle/covid-19-nlp-text-classification
