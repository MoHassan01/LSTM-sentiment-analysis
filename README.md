# LSTM sentiment analysis
Dataset link: https://www.kaggle.com/datasets/bittlingmayer/amazonreviews
In this project, amazon text reviews are given along with the rating.
After performing text preprocessing including tokenizaion, lemmatization and padding.
GloVe pretrained model is then used to get pretrained word embeddings on our dataset
Then using LSTM along with Tensorflow Deep Neural Network, the model is trained on a portion of the data.
(Further model running on the whole data couldn't be done due to hardware limitations)
