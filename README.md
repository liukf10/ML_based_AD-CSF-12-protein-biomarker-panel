# Machine-learning based strategy identifies a robust protein biomarker panel for Alzheimer’s disease in cerebrospinal fluid
___
Code and data for guided auto AD omics data data analysis.

This is a python package that is distributed with the aim on ensuring reproducibility. The code was designed and tested to work specifically with the data in the package

developer: Hou Xiaosen https://github.com/beijingsenlin


# Requirements 
___
The main requirements are listed below:
* python 3.6
* Numpy
* Scikit-Learn
* Pandas
* matplotlib
# The description of Main scripts
___
* model_train_test_from_articl.ipynb  
  * The code is used to train models and make predictions.  
  * The data used for training and prediction come from recent articl.
  * In the CSF data, the training set uniformly uses 297_CSF, while the test set uses CSF data from other articles.
  * In the DLPFC data, the 182_DLPFC dataset is divided into training and test sets.  
  * Running this script produces the AUC value, accuracy value, ROC curve, confusion matrix, and PCA scatter plot.
* model_train_test_from_elisa.ipynb
  * the training set uniformly uses 297_CSF, while the test set uses CSF data from ELISA test.
  * Running this script produces the accuracy value.
