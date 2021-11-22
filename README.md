# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis was to create a deep learning model for AlphabetSoup to predict whether applicants will be successful if funded.

## Results:

### Data Preprocessing
 - The target variable for this model was Is_Succesful, which stated whether an applicant was successful after funding
 - The variables considered as features were classification and application type
 - Name and EIN should be removed as they are neither target nor feature variables

### Compiling, Training, and Evaluationing the Model
 - 130 neurons, 2 hidden layers, and 1 activation function were used in this model.  
 - The closest acheived accuracy was 66%, not acheiving the goal of 75% or greater
 - The number of nerons were adjusted in the 2 different layers to atempt to increase performance

## Summary
In summary, the goal of 75% accuracy was not acheived by the model.  Future iterations of the model should look at the number of layers, and binning of data at a higher level to increase performace.
