# RSNA_Resnet
Kaggle competition, RSNA Breast Cancer Detection - Image Classification using ResNet50

Files used to participate in Kaggle competition. 

---------
src 
---------

maintrainrsna.ipynb : This is the main file that creates the dataframe and executes training loops. Currently, the paths in this file for the input data set and configuration files is set to what I used while participating in the Kaggle competition.   

preprocessrsna.ipynb: Includes function to create the clean data frame from the input data. Imputes missing values and removes columns that are not useful from the data. 

resnetrsna.ipynb: Includes function to create model with ResNet50 followed by a fully connected layer to handle images as well as meta data about the patient.

trainrsna.ipynb: Includes functions to format data into a form readable by the model, read the configuration file and the function to train folds. 


--------
config
--------

This folder contains configuration files for training the model. 
