# Sentence-Pair-Similarity

## Goal: 
Given a pair of sentences, determine whether they refer to the same intent or not.



## Data:
“Quora Question Pairs” dataset from kaggle was used. Its train set was used which consisted of 3,63,861 samples. 95:5 train-test split was used over this dataset.



## Data preparation:
- Tokenization
- Padding
- Embedding matrix preparation



## Models:
CNN:
- 1D-CNN

RNN:
- LSTM
- Bidirectional LSTM



## Result:
Best accuracy was obtained with an LSTM model with value 76.00 %.
