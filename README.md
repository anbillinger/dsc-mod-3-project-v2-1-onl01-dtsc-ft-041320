# Module 3 Final Project
By Alex Billinger

## Purpose
* Analyze data about water wells in Tanzania to predict their condition
* Present findings to a non-technical audience

## Contents of Repository:
### Notebooks:
* Student - contains code for cleaning data and initial investigation
* Modeling - initial models for prediction algorithm, and how well they do
* GridSearch for hyperparameters - finding ideal parameters for model, and testing resulting model
* Location_Information - investigating various location factors and mapping data

### Other Important Files:
* cf_matrix_plot.py - python code to create plot for confusion matrices
* Slides.pdf - slideshow used in presentation
* presentation_video_3 - video and audio presentation

### Data Files:
cleaned.csv - data after removing NaNs, dropping duplicate columns, and treating outliers
labels.csv - target data, notably including a column of target values translated from strings to numeric values
ohe.csv - one-hot encoded data, ready for modeling
Test_Values.csv - test data (no target labels) from competition, not used in this repo
Train_Labels.csv - target label data, before cleaning
Train_Values.csv - feature data, before cleaning