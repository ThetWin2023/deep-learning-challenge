# deep-learning-challenge

# Data Analytics and Visualization Bootcamp 
## University of Toronto
### Name: Thet Win
### Date: October 1, 2024
### Challenge 21 - Deep Learning 


## Overview of the analysis: 
 - The purpose of this project is to develope a deep learning model to help a non-profit organization select applicats for funding with the best chance of success in their ventures.

## Results: Using bulleted lists and images to support your answers, address the following questions:

## Data Preprocessing

#### Target Variable
 - IS_SUCCESSFUL

#### Feature Variables
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS
- ASK_AMT

#### Variables removed:
- EIN
- NAME

## Compiling, Training, and Evaluating the Model

### Number of Neurons and Layers:
  - 80 and 30 Neurons
  - Hidden Layer 1: Relu
  - Hidden Layer 2: Relu
  - Output Layer: Sigmoid

Several trials were conducted and the number of newrons were chosen to ensure that the model's performance is at optimum. 

### Model Performance
  - 73% Accuracy attained
  
### Steps Taken to increase model performance
  - Increased neorons 
  - Increased epochs

## Summary
  - Random forrest algorithm is recommended for this classification as it is a better option for non-linear relationships. It can also identify outliers and it performs better on larger datasets.
