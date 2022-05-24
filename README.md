# Neural_Network_Charity_Analysis

## Overview:
### Purpose:
The purpose of this module is to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. We will be using our knowledge of machine learning and nueral networks to analze the given dataset.

## Questions:

### Data Preprocessing
- Based on the data provided, it appears the targeted data point will bethe column that shows 'IS_SUCCESSFUL', and will be used for our predictions.

- There are many data points (features) that will be used as input for the models. Included are:
    - AFFILIATION
    - APPLICATION_TYPE
    - ASK_AMT
    - CLASSIFICATION
    - INCOME_AMT
    - ORGANIZATION
    - SPECIAL_CONSIDERATIONS
    - STATUS
    - USE_CASE
    
- The columns for "NAME" and "EIN" have no direct effect on the success/falure rate, and have been dropped from processing.

### Compiling, Training, and evaluating the model
- In order to try and get to 75% accuracy, I used three layers. The first layer started with 80 Nuerons, then second had 30, and last had 10.

- I was not able to achieve the target model performance. Unfortunately, my third attempt caused my accuracy to fall.

## Results:

### Summary:
To further investigate these tests we recommend alternative, non-sequential hyperparameter models. Another means of improving accuracy is to have more datapoints. Although we did not boost success rate to 75%, we have studied additional nueral networks to 
