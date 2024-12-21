# Music-Recommendation-System
Overview
This project aims to develop a robust music recommendation system using various machine learning models to predict whether a song will be a hit. The models analyze song attributes and labels provided by Spotify, focusing on features like timbre and using techniques such as logistic regression, support vector machines, K-nearest neighbors, Gaussian Naive Bayes, and neural networks.

Data Preparation
The data consists of song timbre attributes, each represented by a list of 120 numbers indicating the strength of the timbre components over time. Each song is also labeled as a hit (1) or not a hit (0). The data preprocessing involves ensuring correct data types, expanding data tables to separate timbre components into distinct columns, and filtering out songs with incomplete data.

Models Implemented
Basic Models: A range of models including logistic regression, support vector classifier, K-nearest neighbors, Gaussian Naive Bayes, and multi-layer perceptron were initially tested.
Recurrent Neural Network (RNN) with LSTM: Given the temporal nature of the data, an RNN with LSTM layers was implemented to capture the time-based progression of song attributes.

Results
The basic models achieved approximately 60% accuracy, which is slightly better than random guessing. However, the RNN model initially showed a promising 97% accuracy but suffered from overfitting, indicating the need for further model refinement.

Real-World Applications
The system's framework can be adapted for various applications such as fitness and travel apps to recommend trails or online food ordering systems to suggest restaurants based on user preferences.
