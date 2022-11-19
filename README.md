# Neural Network Charity Analysis

Using machine learning and neural networks, create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Overview of the Loan Prediction Risk Analysis:

Using Pandas and the Scikit-Learn’s StandardScaler(), the dataset was preprocessed. This was done in order to compile, train, and evaluate the neural network model later in the analysis.

The CSV contained more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

TensorFlow was used to design a neural network, or deep learning model. This was in order to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. The number of inputs had to be considered before determining the number of neurons and layers in the model. Finally, the binary classification model was ready to compile, train, and evaluate in order to calculate the model’s loss and accuracy. 

Using TensorFlow, the model was optimized in order to achieve a target predictive accuracy higher than 75%.

## Results:

### Data Preprocessing:

The variable that was considered the target for the model was the IS_SUCCESSFUL column. 
The variables that were considered the features for the model were the rest of the columns (ie: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, etc)
The variables that were neither targets nor features for the model were EIN and NAME because we removed them.

### Compiling, Training, and Evaluating the Model:

To optimize the model to achieve a target predictive accuracy higher than 75%, I attempted the following:

Adjusting the input data to ensure that there are no variables or outliers that are causing confusion in the model, such as:
Decreasing the number of values for each bin.
Adding more neurons to a hidden layer.
Adding more hidden layers.
Using different activation functions for the hidden layers.

Despite my dest efforts, the target model performance was not achieved.

## Summary:

The overall results of the deep learning model are as follows:

A different model could potentially solve this classification problem. Because neural network models are so nuanced and intricate, it would take many different iterations to find the perfect fit.
