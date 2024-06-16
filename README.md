# deep-learning-challenge

The purpose of this repository is to use a neural network to predict which organizations will be sucessful if funded by AlphabetSoup, based on historical data. 

*What is the target variable for your model?
The target variable is named "IS_SUCCESSFUL", which is a binary determination of whether or not the historically funded organization used their funding effectively.

*What variables are the features for your model?
The features are as follows: Application Type, Affiliation, Classification, Use Case, Organization, Status, Income Amount, Special Considerations, and Ask Amount.

*What variables should be removed from the input data because they are neither targets nor features?
The variables EIN (tax ID) and Name do not contain any useful information and are removed from the input data. 

*How many neurons, layers, and activation functions did you select for your neural network model
Input Layer: Dense Layer with 80 Neurons and ReLU Activation Function
Hidden Layer: Dense Layer with 30 Neurons and ReLU Activation Function
Output Layer: Dense Layer with 1 Neuron and Sigmoid Activation Function

*Were you able to achieve the target model performance?
I was not able to acheive target model performance of 75% by modifying the dataset or the neural network model. The closest I reached was 73%. 

*What steps did you take in your attempts to increase model performance?
I modified the number of data points within the dataset, the number of neurons, layers, and activation functions, as well as the number of epochs and the learning speed. 

*Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
My application of the deep learning model was unable to achieve over 73% accuracy through multiple optimaztion attempts. This suggests that my neural network model may not be the best model to analyze this dataset. 
A Random Forest model could better analyze this data, as the Random Forest model creates multiple "trees" throughout training of various data points, creating a more robust model. 
Similiarly, a Gradient Boosting model makes multiple decision trees, where each subsequent decision tree attempts to improve upon the errors made in the previous tree.

----
I used the edX XPert Learning Assistant in the completion of this assignment. 
