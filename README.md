# Predicting Credit Card Fraud with Deep Learning

This github page consists of iPython notebooks of data analysis and deep learning model development on a credit card fraud data set from Kaggle: [Credit Card Fraud Detection - Anonymized credit card transactions labeled as fraudulent or genuine](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## Data Analysis and Prediction of Credit Card Fraud.ipynb
This notebook contains exploratory data analysis, data preparation and a neural network classification model built in TensorFlow, with thorough documentation.
[Click here to view notebook](https://github.com/stochasticats/credit-card-fraud-detection/blob/master/Data%20Analysis%20and%20Prediction%20of%20Credit%20Card%20Fraud.ipynb).

### Some results
![alt text](https://raw.githubusercontent.com/stochasticats/credit-card-fraud-detection/master/figures/histogram.png "Normal and fraudulent transactions histogram")

![alt text](https://raw.githubusercontent.com/stochasticats/credit-card-fraud-detection/master/figures/transactions_time.png "Normal versus fraudulent transactions over time")

![alt text](https://raw.githubusercontent.com/stochasticats/credit-card-fraud-detection/master/figures/lossfunction.png "Cost function over iterations")

## Prediction of Credit Card Fraud in Keras.ipynb
This notebook contains a neural network classification model built in Keras, along with more in-depth testing and validation. This notebook lacks documentation, something I wish to add in the future.
[Click here to view notebook](https://github.com/stochasticats/credit-card-fraud-detection/blob/master/Prediction%20of%20Credit%20Card%20Fraud%20in%20Keras.ipynb).

### Some results
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_1 (Dense)              (None, 14)                420       
_________________________________________________________________
dense_2 (Dense)              (None, 7)                 105       
_________________________________________________________________
dense_3 (Dense)              (None, 1)                 8         
=================================================================
Total params: 533
Trainable params: 533
Non-trainable params: 0
_________________________________________________________________

![alt text](https://raw.githubusercontent.com/stochasticats/credit-card-fraud-detection/master/figures/confusion_matrix.png "Confusion Matrix")
