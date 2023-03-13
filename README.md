# Neural_Network_Charity_Analysis

# I Learned
By the end of this module, you will be able to:

Compare the differences between the traditional machine learning classification and regression models and the neural network models.

Describe the perceptron model and its components.

Implement neural network models using TensorFlow.

Explain how different neural network structures change algorithm performance.

Preprocess and construct datasets for neural network models.

Compare the differences between neural network models and deep neural networks.

Implement deep neural network models using TensorFlow.

Save trained TensorFlow models for later use.
________________________________________________________________________________________________________________________________________________________________

# Summary

Finally it can be said that the model does not meet the necessary requirements to be used to predict the effectiveness of money invested in organizations as it only predicts between 72% and 74% of the ones that are succesful. 

Another model is reccomended to keep testing this dataset as to prove two things:

The dataset is enough to convey a good predcition.

The deep learning model can still be modified as to get a better result without overfitting the data.

Random Forest Classifier is reccomended as it has as good of precision as deep learning and also it is faster to implement and it could be useful to better conclude about the datset, if maybe the data is not enough or maybe if neural network does not adjust itself to this case. Any case it is good to have comparissons for future reference.
_____________________________________________________________________________________________________________________________________________________________

# Overview

The purpose of this analysis was to help develop a machine learning algorithm for a client to help predict in what organizations to invest as to minimize the risk of not having anything to show for it.
_____________________________________________________________________________________________________________________________________________________________

Data Preprocessing

For the model the variable considered as the target variable was the column named "IS_SUCCESFUL" which as described by the client answers the question: Was the money used effectively? So in other words the model will use the information provided to predict if the money that might be invested will be used effectively.

For the features of the model it was decided to use all but 4 columns, this was decided after deep consideration of what the variable describes and by trial and error through multiple optimizations options. 

The columns considered as features were:

APPLICATION_TYPE—Alphabet Soup application type
LIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
