## Deep Learning
The data is preprocessed and split into training and testing in order to be ready for modeling. In our first trial we are going to use the basic framework same as the one inside of the module.
* **Input Layer**: we set up the input features equal to the number of variables in our feature Data Frame
*	**Hidden Layers**: we had 2 hidden layers and each of them has few neurons. For the hidden layer, we use “relu” for the activation function to identify nonlinear characteristics from the input value.
*	**Output Layers**: Sigmoid for activation function which help to predict the probability of having a good prediction on whether the funding is successful
In our first deep learning model summary, we had 328 weight parameters for input values. This allows us to have great opportunity to find the trends in the dataset. Next we set up the “binary_crossentropy” as our loss function, adam for optimizer and we are looking for accuracy as our metrics. We set up epochs value to be 100 and run the model. The result shows 0.555 for loss and 72.6% accuracy. This value was not consider as low but not ideal at the same time. We are seeking for further change in order to check whether there can be an improvement in accuracy.
Things we can do to change the model:
1.	Add more neurons to hidden layer
2.	Add hidden layer
3.	Change the activation function for hidden layers
4.	Increase the amount of epochs 
In this challenge, we first try to increase the amount of neurons from 8 into 10. This did not really increase the accuracy but makes the accuracy to reach ~73% at early stage. However, this seems to be unnecessary since we are setting up our epochs to be 100 and the accuracy does not seems to vary a lot. Even the basic framework does not require that much epochs to reach that accuracy. 

