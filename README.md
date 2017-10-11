# Data Analysis and Predictive Modeling on Credit Card Fraud Data

The Jupyter Notebook contains data analysis of credit card fraud data, and a predictive model to detect a fraudulent transaction. The predictive model is a neural network implemented in tensorflow. 

The neural network implemented in tensorflow has three hidden layers and the hidden layer dimensions are: 29, 14, and 7.

Within the model I used the sigmoid cross entropy with logits as the cost function and we use Adam optimization to minimize the cost function.

The model ends up being trained on only a smaller portion of the data set due to computational complexity. I obtained a train and test accuracy of 100%.

I ran the Jupyter Notebook on a Kaggle kernel, which allowed me to utilize the entire data set. Here is a link: https://www.kaggle.com/stochasticats/neural-network-model-implemented-in-tensorflow/notebook
