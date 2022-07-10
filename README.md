# Nerual_network
# Analysis Overview
The purpose of this project is to use neural networks in Python to analyze and classify the success of charitable donations.
We use the following methods for the analysis:
-preprocessing the data for the neural network model,
-compile, train and evaluate the model,
-optimize the model.
# Results
#Data Preprocessing
- The EIN and name where dropped from data input
= Is successful to determine whether charity was recieved 
- Added colums Application types, Affiliation, classification, use_case, organization, status, income amt, special consideation, and ask amt. 

#Compiling and Training
- This deep-learning neural network model is made of two hidden layers with 80 and 20 neurons.
- The input data has 43 features and 25,724 samples.
- The output layer is made of a unique neuron as it is a binary classification.
- To speed up the process we used Relu for activation, then the second hidden layer we continued to use Relu, as for output we used Linear. 
- The Models accuracy was 72 percent which is less than 75 pecercent. 
- To increase performance I tired to change the way Ask amnt was bucketed 
- We also changed begining activation to tanh 
# Summary 
The unfortuantly the deep learning neural network model did not reach the target of 75% accuracy. It is safe to say put model are not performing because of the fact we considering we couldnt hit 75 percent any of the optomizers.
We could use instead of a neural network is a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model. This may work better because we are looking for a specfic result. 
