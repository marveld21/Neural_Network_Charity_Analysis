# Neural_Network_Charity_Analysis

## Overview
### We are designing a neural network model to indicate if a applicant will be successful if funded.

## Results
### Data Preprocessing

-IS_SUCCESSFUL is the target variable.

-APPLICATION_TYPE, AFFILIATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONDITIONS, ASK_AMT are all features for the dataset.

-EIN and NAME are identifiers and are neither the target or features

### Compliing, Training and Evaluating the Model

### Model
![model_1](https://github.com/marveld21/Neural_Network_Charity_Analysis/blob/main/resources/model_1.PNG)
### the target of 75% was not achieved we need to look at improving the model.

### Improvement Attempt 1
![improvement_1](https://github.com/marveld21/Neural_Network_Charity_Analysis/blob/main/resources/model_2.PNG)
### To try and improve the model we changed the activation functions from linear to sigmoid the second attempt improved the model quite a bit but is still not at the target 75%

### Improvement Attempt 2
![improv_2](https://github.com/marveld21/Neural_Network_Charity_Analysis/blob/main/resources/model_3.PNG)
### Attempt 2 we tried switching from sigmoid to relu and gained a small % increase but still short of 75%

### Improvement Attempt 3
![improv_3](https://github.com/marveld21/Neural_Network_Charity_Analysis/blob/main/resources/model_4.PNG)
### Attempt 3 we added a hidden layer increased the units and changed to a hybrid of relu and sigmoid. We received the best results but are still short of our 75% target

## Summary
### Even though we did not reach the target of 75% accuaracy we are very close. If we gave the model more epochs and let it run for longer it should get to the target.