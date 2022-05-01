# Neural_Network_Charity_Analysis

## Overview of the analysis:
Bek is expecting help from us to predict if a charity has the potential to be successful if funded by the Alphabet Soup.
With data in hand, along with machine learning and neural networks, the goal is to use features existing in the dataset received. 
The CSV file contains more than 34,000 charities that are already funded over the years and we have a good metadata to work with as listed below.

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

## Results: 
## Data Preprocessing
* What variable(s) are considered the target(s) for your model? <br>
    IS_SUCCESSFUL—Was the money used effectively 

* What variable(s) are considered to be the features for your model?<br>
    - APPLICATION_TYPE—Alphabet Soup application type
    - AFFILIATION—Affiliated sector of industry
    - CLASSIFICATION—Government organization classification
    - USE_CASE—Use case for funding
    - ORGANIZATION—Organization type
    - STATUS—Active status
    - INCOME_AMT—Income classification
    - SPECIAL_CONSIDERATIONS—Special consideration for application
    - ASK_AMT—Funding amount requested
    
    <p>
* What variable(s) are neither targets nor features, and should be removed from the input data?<br>
    - EIN and NAME—Identification columns
    <br>
## Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?<br>
    First hidden layer has five units and second hidden layer has three units along with Relu activation network model. Relu looks into linear relationship(which is a default for the first layer as well). I am only looking into if the charity would be successful or not, so classification model is useful. For the ouput, to see the probability Sigmoid activation is used.
<br>
* Were you able to achieve the target model performance?<br>
    Unfortunately performance has not improved, more time and research is needed.
    <br>
* What steps did you take to try and increase model performance?<br>
    I have added additional hidden layers and changed the number of units; however, results did not improved.
    <br>

## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
<br>
Our machine learning model is as good as our training data, ML model could have improved if we had more and diverse data. There are 9 feature variables in our model, maybe additional features could provide more accuracy and/or with a 'decision forest' model. 
A decision forest model could capture non-linear decision boundaries, can handle more data efficiently in computation and memory use, and it can handle data with varied distribution.