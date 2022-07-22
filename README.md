# Deep-Learning-Module

## Overview of the analyss
The purpose of this analysis was to create a binary classifier that is capable of predicting whether applicants will be sucessfull if funded by alphabet Soup. 

Dataset:
EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively


## Results
- What variable(s) are considered the target(s) for your model?

Is_SUCCESSFUL column was considered as the target for my model 

- What variable(s) are considered to be the features for your model?

Except the dropped column (EIN, NAME) and IS_SUCCESSFUL, other columns were variables that were considered to be the features for the model.

- What variable(s) are neither targets nor features, and should be removed from the input data?

EIN, NAME!

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

I had 3 hidden layers(9,9,10 neurons respectively) and 2 different activations (relu and sigmoid)
I tried to add more neurons as well as activation functions to increase the accuracy.

- Were you able to achieve the target model performance?

I was not able to acheive the target model performance.

- What steps did you take to try and increase model performance?

First of all, I tried to add more epochs to enhance the accuracy. Then, I added more layers as well as the neurons. Furthermore, I tried to adjust some of columns to see whether the accuracy can go up or not.




## Summary: Summarize the overall results 

Overall, It was fortunate that the accuracy was above 50%. However, I could have adjusted the columns to enhance the accuracy. Since there are other models instead of deep learning model, I could have tried the RandomForestClasssfier and SVM models to check the accuracy. 

