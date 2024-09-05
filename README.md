# Car_Price_Pred_using_TF
This code implements a machine learning model using TensorFlow to predict the prices of used cars based on various features.

Data Preparation:

The dataset is split into training, validation, and test sets. The data is shuffled, batched, and prefetched to ensure efficient model training and evaluation.
Model Architecture:

A TensorFlow Keras Sequential model is built. It includes:
An input layer that accepts features of shape (8,).
A normalization layer to standardize the input features.
Three dense layers with 128 neurons each, using ReLU activation functions.
A final dense layer with a single output neuron, predicting the car price.
Visualization:

After training, the model's predictions (y_pred) are compared with the actual prices (y_true) using a bar plot. This helps visualize how well the model's predictions align with the actual car prices.
