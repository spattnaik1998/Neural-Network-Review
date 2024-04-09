# Neural-Network-Review

This repository contains a sample TensorFlow tutorial demonstrating the usage of TensorFlow and Keras for two different tasks: Fashion MNIST classification and IMDB movie review sentiment analysis.


# Fashion MNIST Classification

In this part of the tutorial, we train a neural network to classify images of clothing items from the Fashion MNIST dataset. The code loads the dataset, preprocesses the images, builds and trains a neural network model, evaluates its performance on a test set, and makes predictions.


# Usage

Run Fashion_MNIST_Classification.ipynb to execute the code in a Jupyter notebook environment.
Make sure to have TensorFlow and matplotlib installed in your Python environment.


# Key Components

Data Loading: Utilizes the Fashion MNIST dataset provided by Keras.
Data Preprocessing: Normalizes pixel values of images to the range [0, 1].
Model Definition: Defines a simple neural network architecture using Keras Sequential API.
Model Training: Compiles and fits the model to the training data.
Model Evaluation: Evaluates the trained model on the test data and computes accuracy.
Visualization: Displays sample images from the test set along with their predicted and actual labels.


# IMDB Movie Review Sentiment Analysis

In this part of the tutorial, we perform sentiment analysis on IMDB movie reviews. The code loads the IMDB dataset, preprocesses the text data, builds and trains a neural network model for sentiment classification, evaluates its performance, and provides a function to classify user-provided movie reviews.


# Usage

Run IMDB_Sentiment_Analysis.ipynb to execute the code in a Jupyter notebook environment.
Ensure TensorFlow and numpy are installed in your Python environment.


# Key Components

Data Loading: Loads the IMDB dataset provided by Keras.
Data Preprocessing: Tokenizes and pads input sequences to a fixed length.
Model Definition: Defines a neural network architecture for sentiment classification.
Model Training: Compiles and fits the model to the training data.
Model Evaluation: Evaluates the trained model on the test data and reports accuracy.
Review Classification: Provides a function to classify user-provided movie reviews.
