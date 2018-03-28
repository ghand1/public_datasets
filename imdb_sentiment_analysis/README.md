# IMDB Movie Review Sentiment Analysis

The [Keras](https://keras.io/) library comes with a preloaded dataset from [IMDB moview reviews](https://keras.io/datasets/#imdb-movie-reviews-sentiment-classification). The dataset is preprocessed, and each review is encoded as a sequence of word indexes (integers). This makes it an excellent dataset to explore the power of Keras on sentiment analysis using convolutional neural networks, which is what I do in this notebook.

Additional preprocessing is conducted by tokenizing the word indexes and converting to binary. Model parameters are explored using GridSearchCV and additional exploration into model architectural development is conducted.

The following libraries are required for this notebook written in *Python 3.6*:

> NumPy
> Keras
> MatPlotLib.Pyplot
> scikit-learn

Once Keras is installed, the IMDB is immediately available using the following commands in Python script:

```python
## import the dataset
from keras.datasets import imdb

## num_words is a parameter for how many words we want to look at
(X_train, y_train), (X_test, y_test) = imdb.load_data(num_words=1000)
```


