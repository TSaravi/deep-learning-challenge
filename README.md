# deep-learning-challenge

Alphabet Soup Charity Funding Tool

# Overview: 

A binary classifier was created to help the non-profit foundation Alphabet Soup predit and select the applicants for funding with the best chance of success in their ventures. 

Using a CSV data file containing more than 34,000 organizations that have recieved funding previously from Alphabet Soup the model was created based off the following metadata about each organizations. A target of 75% accuracy was set for the model. 

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

# Results 

Data Preprocessing

The target variable used for this model was IS_SUCCESSFUL and the featured variable used for the model were APPLICATION_TYPE, AFFLIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and lastly ASK_AMT. The variables that were removed were EIN and NAME columns because they are neither target nor features.

Compiling, Training, and Evaluating the Model

The first model that were built to process the data were 2 hidden layers with 80 and 30 neurons respectively and with activation layer of relu. The output node used was an output layer activation of sigmoid. This model was give us the target model performance at 72%. In order to increase the models performace a third hidden layer was added to the model with neurons set to 80, 30, 20 respectively. This model increased our models accurancy level to 72.7%. The third model created to was to change the neurons in the three hidden layers to 8,15,22. With this third model the performance level did increase to 73%.

# Summary

In summary, we were not able to reach the 75% tagert with the models used.The third model came closest to the target with a 0.55 loss and accurancy of 73%. Another type of prediction model must be used to reach the 75% target and different target variable can be incorperated as well to increase the accurancy. 

