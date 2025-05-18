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
To set up the environment, install the necessary libraries in the `cyberbullying_Using_BiLSTM.ipynb` file.


## Dataset  
The dataset consists of tweets labeled with different cyberbullying categories. The dataset can be accessed via Kaggle using this link: [Cyberbullying Classification Dataset](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification). The preprocessing script cleans the text and prepares it for training.  

## Model Architecture  
The BiLSTM model consists of:  
- **Embedding Layer** – Uses FastText word embeddings  
- **Bidirectional LSTM Layers** – Captures sequential patterns  
- **Dropout Layers** – Prevents overfitting  
- **Fully Connected Dense Layers** – Learns classification patterns  
- **Softmax Output** – Predicts the cyberbullying class  

## Training  
Run the `cyberbullying_Using_BiLSTM.ipynb` file from beginning to end. The model is trained over **10 epochs** using the **Adam optimizer** with a learning rate of **0.005**.  

## Evaluation  
After training, the model is evaluated using:  
- **Accuracy**  
- **F1-score**  
- **Confusion Matrix Visualization**  

## Results  
- Achieved **92% accuracy** and **92% macro-averaged F1-score** after 10 epochs.  
- Outperforms previous BiLSTM implementations with **higher efficiency** and **performance**.  

## Citation  
If you use this repository in your work, please consider citing it accordingly.  
