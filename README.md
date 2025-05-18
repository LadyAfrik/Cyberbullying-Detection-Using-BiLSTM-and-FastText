# Cyberbullying Detection Using BiLSTM  

## Overview  
This repository contains an implementation of **Bidirectional Long Short-Term Memory (BiLSTM)** for cyberbullying detection. The model leverages **FastText embeddings**, **tokenization**, and **deep learning** techniques to classify tweets into different cyberbullying categories.  

## Features  
- **Data Cleaning & Preprocessing**: Removes stopwords, performs stemming, and processes emojis.  
- **FastText Word Embeddings**: Generates word vectors to improve text representation.  
- **Bidirectional LSTM Model**: Captures both past and future context for accurate classification.  
- **Overfitting Prevention**: Implements dropout regularization and early stopping.  
- **Performance Evaluation**: Includes confusion matrix and classification metrics.  

## Installation  
To set up the environment, install the required libraries:  

```bash
pip install tensorflow gensim nltk pandas seaborn plotly imbalanced-learn
