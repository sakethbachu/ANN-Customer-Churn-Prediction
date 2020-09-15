# ANN - Customer-Churn-Prediction

![alt text](https://github.com/sakethbachu/ANN-Customer-Churn-Prediction/blob/master/ANN%20main/img/churnrate.png "Logo Title Text 1")

## Description
The aim of the project is to predict the customer churn rate in a bank. This is done based on some given factors about a customer also called as the features, for ex credit score, age of the customer, geography etc.

## Method 
* The Prediction engine is built over a deep Artificial Neural Network backed with Keras.
* I have achieved an accuracy of around ~85% on both training and testing data.
* The ANN is trained over K-fold cross validation testing over 10 rounds to find if it was underfit or overfit over the data based on the variance betweent the accuracies of the     10 rotations.
* The model is Tuned over the Hyerparametes to find the best batch_size, epoch and optimizer for generating the best possible combination for best fit model.

## Training
![alt text](https://github.com/sakethbachu/ANN-Customer-Churn-Prediction/blob/master/ANN%20main/img/1accuracy_console.PNG "Logo Title Text 1")

## Contents of this repository
* img folder : Which contains the image data.
* Churn_modelling : This is the dataset that we have used.
* model.py : This contains all the code for the base model, hyper parameter tuning, Kfold-cross validation.
* prediction_classifier.pkl : The saved model.

## Requirements
* Tensorflow
* Keras
* Sci-kit learn
* Scipy
* Matplotlib
* Pandas
* Numpy


