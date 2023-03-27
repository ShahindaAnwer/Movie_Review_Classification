# IMDB Dataset
IMDB dataset is one of keras's datasets, `keras.datasets.imdb`.

kaggle link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## The Data
The IMDB dataset consists of 50,000 reviews from the Internet Movie Database.
The dataset has 2 columns; features and targets.

## Feature Variable
Each review is a sequence of words, which is then preprocessed into a sequence of integers, each integer standing for a specific word in the dictionary. Words are indexed according to its frequency in the dataset, thus enabling a quick filteration of opetations. For this projcet I chose the top 30,000 most common words.

## Target Variables
0: `Negative`
1: `Positive`

## Training and Validation

- 25000 reviews for training
- 25000 reviews for testing

Each set contains an equal number (50%) of positive and negative reviews.




# glove.6B.100d.txt
kaggle link: https://www.kaggle.com/datasets/danielwillgeorge/glove6b100dtxt
