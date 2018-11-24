# Recurrent Neural Network for Sentiment Analysis

We train a Recurrent Neural Network(LSTM network) about two layers of bidirectional LSTMs with Dropout regularization to classify movie reviews from the 50k IMDb review dataset that has been collected by Maas et. al.

Default parameters:

    * learning_rate    = 0.01
    * batch_size       = 600
    * training_steps   = 10
    * emb_size         = 32 (dimension of word embeddings)
    * num_hidden_units = 16
    * number_of_layers = 2
    * seq_max_len      = 600