# Complete Deep Learning Course Created by Hesham Asem

These Notebooks are the practical part of a comprehensive deep learning course consisting of 25 lectures with a total duration of approximately 50 hours. It covers everything you need to know about:

- Deep Learning
- Computer Vision
- Natural Language Processing (NLP)
- Practical Applications

The course provides a solid foundation and hands-on experience in these key areas of artificial intelligence.


# What are these notebooks?

## DNN
### Deep Neural Network for Airline Delay Classification

This notebook implements a Deep Neural Network (DNN) using Keras and TensorFlow to analyze and predict various aspects of airline delay data. It begins by preprocessing the dataset to clean missing values and drop irrelevant columns. For binary classification, a target variable `weather_delay_Case` is derived by labeling delays over 100 minutes as significant. Additionally, the notebook includes a multiclass classification version of `weather_delay_Case`, showing how to categorize different delay severity levels. It also performs a regression task to predict the number of arriving flights (`arr_flights`) using continuous input features. The DNN models are built with multiple dense layers using activation functions like `tanh`, `sigmoid`, and `softmax`, and trained with the `AdamW` optimizer. Loss functions such as `binary_crossentropy`, `categorical_crossentropy`, and `mean_squared_error` are used appropriately based on the task. Model performance is evaluated through validation accuracy, loss metrics, and training history plots, making this notebook a comprehensive and flexible tool for tackling a range of supervised learning problems.

