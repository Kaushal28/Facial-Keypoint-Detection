# Facial-Keypoint-Detection
15 Facial key-point recognition using Tensorflow from scratch using different neural network models. Used training dataset from this Kaggle challenge: https://www.kaggle.com/c/facial-keypoints-detection

## Approaches
1. Simple Fully Connected Nueral Network with single hidden layer with 100 nuerons. Trained this model with 100 epochs and got training error `0.0065` and validation error `0.0089`.
2. CNN Model with 3 Convolutional layers and 2 fully connected layers, each with 1000 nuerons. Trained this model with 500 epochs and got training error `0.000017` and validation error `0.0005`.
