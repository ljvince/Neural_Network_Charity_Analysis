# Module 19 - Neural_Network_Charity_Analysis

## Overview 
#### the purpose of this module is to use the features in the provided dataset to create a binary with machine learning and neural networks, in order to help the foundation predict where to make inversments. in this case we will compare the differences between the traditional machine learning classification and regression models and the neural network models. however, we are using the skill from this module to determind the question following on results.





## Results:
## Data Preprocessing
#### Q1:What variable(s) are considered the target(s) for your model?
#### ---The columns IS_SUCCESSFUL Column

#### Q2:What variable(s) are considered to be the features for your model?
#### ---The columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.

#### Q3:What variable(s) are neither targets nor features, and should be removed from the input data?
#### ---The columns EIN and NAME are identification information and have been removed from the input data.
    
## Compiling, Training, and Evaluating the Model

#### Q1:How many neurons, layers, and activation functions did you select for your neural network model, and why?
#### ---there is 2 hidden layers in my module and the first layer has 80 neurons, the second has 30 neurons. there is an output layer as well. here also have a output layer. the first and second hidden layer have "relu" activation function and the output layer has "sigmoid" activation
<img width="1009" alt="Screen Shot 2022-10-05 at 10 54 32 PM" src="https://user-images.githubusercontent.com/106010498/194226085-1749df91-fa0d-48f4-8725-9e8fbeef30b6.png">


#### Q2:Were you able to achieve the target model performance?
#### ---The model was not able to reach the target 75%. The accuracy for this model is 73%.
<img width="773" alt="Screen Shot 2022-10-05 at 11 05 14 PM" src="https://user-images.githubusercontent.com/106010498/194226746-2178192f-5456-416e-a88b-9727dd0ba697.png">

#### Q3:What steps did you take to try and increase model performance?
#### ---apply a bucketing to the new amt and oeganized the different values is neccessary, inoder to incerased the number of neurons on the one of the hidden layers, as well as use a model with three hidden layers or try a different activation function.

## Summary: 
#### The deep learning neural network model didn't reach the accuracy target of 75%. in the case of binary classification, the supervised machine learning was used, such as random forst classifiers, in order to combination with a large number of decision, to generate classification outputs and evaluate their perfomance against our deep learning model
