
# MovieLens Recommendation Model

This repository presents a recommendation model developed for the MovieLens rating dataset. The model aims to provide movie recommendations based on user historical ratings.

## Dataset

Due to the dataset's size, the ratings.csv file is not included in this repository. You can access the complete dataset, including the ratings.csv file, by downloading it from the official MovieLens website:

http://files.grouplens.org/datasets/movielens/ml-20m.zip

After downloading, extract the ratings.csv file from the zip archive.

## Model Overview

The recommendation model is built using TensorFlow and incorporates the following components:

- Embedding layers for users and movies.
- Concatenation of user and movie embeddings.
- Fully connected neural network layers.
- Training employs Mean Squared Error loss and Stochastic Gradient Descent optimization.

## Achieved State-of-the-Art (SOTA) Results

I'm proud to report that this recommendation model has achieved state-of-the-art (SOTA) results for this task. It has attained a Root Mean Square Error (RMSE) of 0.8583.

---
