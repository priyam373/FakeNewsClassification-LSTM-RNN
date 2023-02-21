# FakeNewsClassification-LSTM-RNN

# Project Introduction:
This binary classification model aims to identify if a news is fake or not based on the text present in the data set. The data has been gathered from Kaggle.

# Text Pre-Processing:
This involves following steps to deal with the text data

  ## a) Tokenization:
  That is to convert a corpus into words.

  ## b) Stopwords:
  This is to remove words which are meaningless or carry very little meaning.

  ## c) Stemming/Lemmatization
  Stemming and Lemmatization are used for reducing words into their base/root words. Stemming does it by removing suffixes and Lemmatization does it by reducing them into their dictionary base words.

  ## d) One Hot Representation:
  Here after defining the vocabulary size, it assigns indexes to all the unique words in the sentences
  
  ## e) Padding:
  it is to make the length of all the sentences the same before passing them through the embedding layer
  
# Model Building:

  ## a) Embedding Layer:
  this is to convert words into vectors given feature representation.
  
  ## b) LSTM Layer:
  That is to capture long term dependencies in the corpus to exploit relationships between events that occur   far apart in a sequence
  
# Model Training:
  ## a) Train-Test Split
  ## b) Traning the model
  
# Model Evaluation:
