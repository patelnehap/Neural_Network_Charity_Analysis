# Neural_Network_Charity_Analysis

## Overview:
Beks, an AlphabetSoup Data Analyst has been tasked to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
With her knowledge of machine learning and neural networks, Beks is ready to dive in and apply her skills to help the foundation predict where to make investments.
She has received a dataset of 34,000 organizations from AlphabetSoup business team that have received funding from Alphabet Soup over the years. 
Beks would build her own machine learning model that will be able to predict the success of a venture paid by Alphabet soup.
The trained model will be used to determine the future decisions of the company—only those projects likely to be a success will receive any future funding from Alphabet Soup.

## Results:
The trained model was run successfully and below are the results:

### Data Processing:
- The variable that is considered as the target for our deep learning neural network is the column IS_SUCCESSFUL which contains binary data indicating that it has been successfully funded by AlphabetSoup.
- The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.
- The EIN and NAME columns are Ord ID columns and may impede the accuracy of the model, so they can be removed to improve model efficiency.

### Compiling, Training, and Evaluating the Model
- This deep-learning neural network model is made of four hidden layers with 40,20,10 and 5 neurons respectively.
- The output layer is made of a unique neuron as it is a binary classification.
- To speed up the training process, we are using the activation function ReLU and sigmoid for the hidden layers. As our output is a binary classification, Sigmoid is   used on the output layer.
- For the compilation, the optimizer is adam and the loss function is binary_crossentropy.

## Summary:
The model accuracy is under 75%. This is not a satisfying performance to help predict the outcome of the charity donations.
We increased the number of neurons on one of the hidden layers, then we used a model with three hidden layers.
We also tried a different activation function but none of these steps helped improve the model's performance.
