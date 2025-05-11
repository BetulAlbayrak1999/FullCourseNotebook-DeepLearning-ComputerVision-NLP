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

## RNN
### LSTM and GRU
This notebook implements Recurrent Neural Network (RNN) architectures—specifically Simple RNN, Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU)—using Keras and TensorFlow to model and predict IBM stock prices based on historical time series data. The dataset is first preprocessed by extracting the `High` price feature and applying Min-Max scaling to normalize the values. For each model, the input data is transformed into sequences of 60 timesteps to capture temporal dependencies.

The RNN, LSTM, and GRU models are constructed with multiple recurrent layers followed by dropout for regularization and a dense output layer to predict future stock prices. Models are trained using the `rmsprop` optimizer and the `mean_squared_error` loss function. After training, predictions are inverse-transformed to the original scale and compared against actual stock prices.

## CNN
### Image Preprocessing & CNN Model for Binary Classification
This part of the notebook handles image loading, preprocessing, and building a Convolutional Neural Network (CNN) for binary image classification. It starts by reading grayscale images from a directory, resizing them to 100×120 pixels, and reshaping them into a format suitable for CNN input. The processed images are then split into training and testing sets using `train_test_split`.

A CNN model is built using Keras, consisting of two convolutional layers with max pooling and batch normalization to extract features and reduce overfitting. The network ends with fully connected dense layers, including dropout for regularization, and a `sigmoid` activation function to output binary predictions. The model is designed to efficiently learn patterns from image data for classification tasks.

