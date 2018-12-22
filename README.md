# SB_Capstone2_Code
This repository contains the code for my second Springboard capstone project - building a convolutional neural network to predict Hubble classes from images of galaxies. Both the image data and the CNN model file are too large to host on Github; however, the data used in this project can be found here: https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/data.

There are 4 notebooks contained in this repository:
  1) SB_Capstone2_DataWrangling-Split.ipynb - This contains the code to split the data into training, validation, and test sets and to divide the galaxy image files into directories accordingly.
  2) SB_Capstone2_Explore.ipynb - This contains exploration and analysis of the training data made prior to building and training the CNN.
  3) SB_Capstone2_BuildCNN.ipynb - This contains the code to build and briefly evaluate the CNN for galaxy class prediction. It also saves the predictions made on the test data, as well as the targets associated with the test data, into CSV files for further evaluation.
  4) SB_Capstone2_Evaluate.ipynb - This contains the code performing a more extended evaluation of predictions made by the CNN on the testing data, as well as examples of images corresponding to the primary Hubble classes where prediction certainty was high.
  
 
