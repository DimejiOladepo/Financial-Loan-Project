# Pre-deliquency Loan Model

This dataset was wrangled using Bigquery to develop two loan pre-delinquency models and comprehensively juxtapose the two models.

A pre-delinquency model is a model that is triggered after a loan is disbursed. 

The model uses features developed after loan disbursement to predict whether or not a loan will be defaulted on or paid back.  

A random forest classifier and a neural network were built with both models trained and tested on the same data to perform binary classification. 

The models were also compared. 

The data used for training and testing the models were transformed and manipulated. It was subsequently extracted for pre-processing and EDA was performed.

The features and Target were derived after which models were built. 

The classification is whether or not a loan will be defaulted on (1) or not (0). 

The models were built in Google Colab and written in Python and commented for understanding. 
 
This model handles missing values, one-hot-encode categorical data, balancing the classes and spliting the data into a training and testing set . 

Hyper parameters were also tuned for both models using GridSearchCV.
