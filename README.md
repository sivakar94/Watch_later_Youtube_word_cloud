# Topic_modelling
Topic_Modelling_Youtube

## Task:
Finding the Best To video to watch out of 200 videos in terms of Topic out of my list of my Youtube watch later list 

Using:
WordCloud to visualize the topics and
SVD-Single Value Decomposition 

## Methods

-Got data from my perosonal Watch later JSON file
-Preprocessing with NLTK
-Filter stopwords, punctuations, and lowercase
-Tokenize
-Stem words
-Visualization with TSNE (a tool to visualize high-dimensional data)
-Model training
-Support Vector Machine with variety of embeddings, including:
-Bag of words from scratch
-Tf-Idf Vectorizer
-Word2Vec
-Combination of Tf-Idf and Word2Vec
-BERT
-Neural Network with BERT and PyTorch

## Results

Using Tf-Idf achieves the highes f1-score. The result is shown in the table below:

## I published an article on medium talking about this mini project:
https://towardsdatascience.com/what-does-your-word-cloud-say-about-your-youtube-watch-later-playlist-e75e262c4e26
