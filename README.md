# Neural_Network_Charityy_Analysis

## Overview

The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.. Python's TensorFlow library was used to create, train, and evaluate data gathered from previous loans.

## Results

The model accuracy is under 75%. This is not a satisfying performance to predict the outcome of the charity donations.
In an attempt to increase the performance of the model, bucketing was applied to the feature ASK_AMT and the different values we organized by intervals.
The number of neurons was increased on one of the hidden layers, then a model with three hidden layers was applied.
A different activation function (tanh) was also used, but none of these steps helped improve the model's performance.

## Summary

The deep learning neural network model did not reach the target of 75% accuracy. 
