# Neural Network Charity Analysis

## Overview Of the Analysis
The purpose of this analysis is to assist Bek in creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The CSV provided has 34,000 organizations that Alphabet Soup has funding in the past several years and will be used when conducting this analysis.

## Results: 

###	Data Preprocessing

What variable(s) are considered the target(s) for your model?

-	The variable ‘IS_SUCCESSFUL’ was used as the target for the  model. 

What variable(s) are considered to be the features for your model?

-	The variables 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION' and 'INCOME_AMT' were the features of the model.

What variable(s) are neither targets nor features, and should be removed from the input data?

-	'EIN', 'NAME' , 'STATUS' and 'SPECIAL_CONSIDERATIONS' were not applicable features and were dropped from the input data.

###	Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

-	Four layers were used for the neural network model, an input layer, two hidden layers and an output layer. The activation function ‘Linear’ was used for the input layer, ‘Relu’ was used for the 1st hidden layer, ‘Linear’ was used for the 2nd hidden layer and ‘Sigmoid’ was used for the output layer.

Were you able to achieve the target model performance?

-	Unfortunately, I was not able to achieve the target model performance of 75%. 

What steps did you take to try and increase model performance?

- To  achieve the higher accuracy score I removed the additional columns 'STATUS' and 'SPECIAL_CONSIDERATIONS', and added an additional hidden layer with an increase in neurons.

## Summary: 

After the adjustments, the model was not able to achieve the target model performance score of 75%. However, it did achieve the model performance of 63% which is 10% higher than the initial result from Deliverable 1 of 53%. I would recommend using Random Forest Classifier as it combines the predictions of many decision trees and will likely produce a better result.
