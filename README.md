# Neural_Network_Charity_Analysis

## Overview
Use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The dataset contains more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Results

### Data Preprocessing
    1. What variable(s) are considered the target(s) for your model?
        * IS_SUCCESSFUL
    2. What variable(s) are considered to be the features for your model?
        * NAME
        * APPLICATION_TYPE
        * AFFILIATION
        * CLASSIFICATION
        * USE_CASE
        * ORGANIZATION
        * STATUS
        * INCOME_AMT
        * SPECIAL_CONSIDERATIONS
        * ASK_AMT
    3. What variable(s) are neither targets nor features, and should be removed from the input data?
        * EIN

### Compiling, Training, and Evaluating the Model
    4. How many neurons, layers, and activation functions did you select for your neural network model, and why?
        * 3 Hidden Layers - For increased Accuracy
        * Activation Functions - For increased Accuracy
            * 1st Layer = 'relu'
            * 2nd Layer = 'sigmoid'
            * 3rd Layer = 'sigmoid' 
    5. Were you able to achieve the target model performance?
        * Yes, 77% Accurate
    6. What steps did you take to try and increase model performance?
        * Did not drop "Name" column
        * Added an additional layer
        * Second and Thrid layer activation changed to 'sigmoid' 

