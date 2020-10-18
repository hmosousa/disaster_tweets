# Disaster Tweets

Can a recurrent autoencoder improve the preformace of a recurrent neural network?

I used the data from ["Real or Not? NLP with Disaster Tweets"](https://www.kaggle.com/c/nlp-getting-started/data) competition on Kaggle to test this hypothesis. 

First I built up a deep recurrent neural network (RNN) and trained it as usual. Then I trained an autoencoder and used the encoder to build a similar RNN.

To improve performance, the [GloVe embeddings](https://www.kaggle.com/joshkyh/glove-twitter) trained on tweets were used.
