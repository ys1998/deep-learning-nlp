# Deep Learning for Natural Language Processing
This repository contains the solutions to course assignments for [CS224n](http://web.stanford.edu/class/cs224n/) offered by Stanford University.
## Assignment 1
Explored the following topics through this assignment :
* wrote efficient, vectorized numpy code for basic components
* developed a vanilla neural network from scratch
* implemented the following `word2vec` models -
  1. **Skip-gram** model : Used both *Softmax-Cross-Entropy* and *Negative-Sampling* (as proposed by Mikolov et al.) loss functions to train word vectors so as to predict context words for a given central word
  2. **Continuous Bag Of Words (CBOW)** model : Used similar loss functions as above to train word vectors to predict the central word, given a collection of context words
* Sentiment Analysis:
  * implemented a logistic regression based sentiment classifier to predict one-of-five classes best  describing a sentence's sentiment
  * used average operation for procuring feature vectors
  * used random search in logarithmic space for finding optimal regularization parameter
  * used self-trained word vectors for classification and attained `30.31%` test accuracy as compared to `36.51%` obtained by using GloVe vectors
  * compared and analyzed the performance of my word vectors with GloVe
