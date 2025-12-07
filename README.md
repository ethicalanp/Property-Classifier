**Property Address Classification**

This project builds a simple text classification model to categorize property addresses into one of the following classes:

flat

houseorplot

landparcel

commercial unit

others

The goal is to create a clean and reproducible machine learning pipeline using the provided training and validation datasets.

**Future Improvements**

There are several ways this project can be extended to improve classification accuracy:

Traditional ML Improvements

Hyperparameter tuning

Better address cleaning (handling abbreviations, special formats)

Trying other vectorizers or feature engineering

Neural Network Improvements

Replace TF-IDF with word embeddings (Word2Vec, FastText, GloVe)

Build a simple neural network such as:

Feed-forward dense network

1D CNN for text

LSTM/GRU model

Test transformer-based models like DistilBERT or MiniLM for better contextual understanding

Fine-tune a small language model specifically on property address text