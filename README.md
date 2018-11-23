# Recurrent Neural Network for Sentiment Analysis

We train a Recurrent Neural Network(LSTM network) with Dropout regularization to classify movie reviews from the 50k IMDb review dataset that has been collected by Maas et. al.

Default parameters:

    * learning_rate    = 0.005
    * batch_size       = 1000
    * training_steps   = 20
    * emb_size         = 100 (dimension of word embeddings)
    * num_hidden_units = 10
    * number_of_layers = 2
    * seq_max_len      = 400