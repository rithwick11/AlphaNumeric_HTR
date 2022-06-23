# AlphaNumeric_HTR

This project is my own AlphaNumeric Handwritten Text Recognizer or as I call it, an HTR.

In this project, I used two datasets:

  1. A_Z Handwritten.csv
  2. MNIST Digits (both train and test)

Using pandas i merged them together so i could form my own new collection of alphanumerics. The dataset is too large and hence couldn't be uploaded. 

The main model i built and trained for this text recognition was a Convolutional Neural Network Model comprising of 2 convolution layers with 32 filters & kernel size 5X5, 2 pooling layers with pooling size 2x2, 1 dropout layer with rate 0.1, 2 dense layers with relu activation and output layer with softmax activation. This was done in Keras with TensorFlow as backend from scratch to predict the alphanumeric it received. Matplotlib was used for data visualization. Data preprocessing was carried out using tensorflow 2.0. Metrics chosen for model evaluation were Training Set and Test/Validation Set accuracy. Adam optimizer was chosen for gradient descent.

**Results of the model were following:

Training Set Accuracy : **97.07 %**

Training Set Loss : **0.12190**

Validation Set Accuracy : **96.56 %**

Validation Set Loss: **0.15200**

Test Set Accuracy or CNN Score : **96.56 % or 0.9656** 

Test Set Loss : **0.15199**
