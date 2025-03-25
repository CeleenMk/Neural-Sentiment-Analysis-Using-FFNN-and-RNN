This project implements two neural network models to perform sentiment analysis on Yelp reviews:

- Feedforward Neural Network (FFNN) with Bag-of-Words input
- Recurrent Neural Network (RNN) with pre-trained word embeddings
  
The goal is to predict the review rating (1–5 stars) given the text.

How to run:
python ffnn.py --hidden_dim [hparam] --epochs [hparam] --train_data [train data path] --val_data [val data path]
