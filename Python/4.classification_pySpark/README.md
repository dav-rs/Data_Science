# Classification using Gradient Boosted tree model

This Jupyter notebook contains a classification model for predicting hacking attacks on a dataset containing memory and process activity from Linux systems. (https://ieee-dataport.org/documents/toniot-datasets). The notebook covers the following sections:

## EDA
After creating the spark session, the data is loaded and an analysis on the class imbalance is performed. At the end of this section, additional visualizations are provided to have an idea of the relationship between some of the variables. 

## Feature extraction
In this section, the data is rebalanced to improve the performance of the models to be trained later. Feature selection is explained and the one-hot encoding is applied to the selected categorical variables. At the end, the correspondent pipeline is built using Gradient boosted tree model (and decision tree for comparison).

## Training and evaluation of model
Here, after the model is trained, the correspondent evaluation is done, analyzing the AUC curve, accuracy, recall and precision. 
