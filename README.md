# Deep_Learning_Challenge
This repository covers the work done with deep learning, neural networks.

## Overview of the analysis: 
This challenge is analysing data that is received on the funding projects of AlphabetSoup charity with parameters of each project and each ones success or failure and correponding data that may or maynot have affected this result.

## Results: 

Data Preprocessing

* What variable(s) are the target(s) for your model?
  Target variable is whether or not it was Successful (Is_Successful)
* What variable(s) are the features for your model?
  Application Type, Affiliation, Classification, Use_Case, Organization, Status, Income_Amount, Special_Considerations and Ask_Amount.
* What variable(s) should be removed from the input data because they are neither targets nor features?
  I have tried removing Application Type from input data, however, the data provided all are features for the success or faliure of the organization, hence all variables should be kept.


Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  The best accuracy of 74% was acheived by a 3 hidden layer approach with neurons as below with activation function as 'relu'.
  hidden_nodes_layer1 = 200
  hidden_nodes_layer2 = 100
  hidden_nodes_layer3 = 50
* Were you able to achieve the target model performance?
  Only upto 74%
* What steps did you take in your attempts to increase model performance?
  Increased the layers and neurons of the layers.

## Summary: 

