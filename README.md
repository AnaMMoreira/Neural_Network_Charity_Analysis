# Neural_Network_Charity_Analysis

## Analysis Overview


The purpose of this exercize is to use neural networks in order to help a charity foundation predict where to make investments based on historical data provided by Alphabet Soup’s business team.  Based on this data a binary classifier hopefully can be developed that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
Using deep-learning neural networks with the TensorFlow platform in Python, an atempt to create a model that would automate the investment process in the future.

The following methods were used for the analysis:

1. Preprocessing the data for the neural network model
2. Compilation, trainning and evaluation the model
3. Optimization of the model


## Preprocessing the data for the neural network model

Cleaning up of the data included removing identification information from the input data because it did not have any influence and this also reduced data volume.
The column IS_SUCCESSFUL contains binary data refering to weither or not the charity donation was used effectively. This variable is then considered as the target for our deep learning neural network.
identification of data columns that influences for our model.
Encoding of the categorical variables, spliting into training and testing datasets and standardization were applied.


## Compilation, trainning and evaluation the model

After running multiple iterations in order to optimize the model performance the following describes the best performing version of the model;

  *  the deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.
  *  The input data has 43 features and 25,724 samples.
  *  The output layer is made of a simple neuron.
  *  During the training process multiple combinations of the ReLU, Sigmoid, and Linear              functions were utilized.
  
 ## Optimization of the model
 
  However, the best performing version of the training process uses the activation function ReLU    for the hidden layers and a Sigmoid for the last layer the output layer. 
  
  * For the compilation, the optimizer is adam and the loss function is binary_crossentropy.
  * Additional internatal layers were also maximized in order to improve the model's              performance and minimize loss.
  * Avalidation of the model demonstrated consistent results for performance and loss.
  
  * The model accuracy is under 75% and is therefore not considered a satisfactory performance in order to be used as a predictive tool maximize the outcome of the charity donations.
  
## Summary
The deep learning neural network model did not reach the necessary target of 75% accuracy in order to be considered a reliable tool.
In order to improve the development of a more reliable predictive model, suggestions for the development of a supervised machine learning model such as the Random Forest Classifier might be most appropriate.
