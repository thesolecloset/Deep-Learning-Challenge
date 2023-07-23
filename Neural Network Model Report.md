# Deep-Learning-Challenge

## Overview:

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With the knowledge of machine learning and neural networks, I used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, I have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.  Within this dataset are a number of columns that capture metadata about each organization, such as:

        * EIN and NAME—Identification columns
        * APPLICATION_TYPE—Alphabet Soup application type
        * AFFILIATION—Affiliated sector of industry
        * CLASSIFICATION—Government organization classification
        * USE_CASE—Use case for funding
        * ORGANIZATION—Organization type
        * STATUS—Active status
        * INCOME_AMT—Income classification
        * SPECIAL_CONSIDERATIONS—Special considerations for application
        * ASK_AMT—Funding amount requested
        * IS_SUCCESSFUL—Was the money used effectively

## Results:

* Data Preprocessing:

        * What variable(s) are the target(s) for your model?
                The target variable is - IS_SUCCESSFUL
        * What variable(s) are the features for your model?
                The feature variables for this model are - EIN and NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS,INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
        * What variable(s) should be removed from the input data because they are neither targets nor features?
                The variables that should be removed are - EIN & NAME

* Compiling, Training, and Evaluating the Model

        * How many neurons, layers, and activation functions did you select for your neural network model, and why?
                I did 80 hiddennodes1, 30 hiddennodes2, and 1 hiddennodes3
        * Were you able to achieve the target model performance?
                No I did not achieve the target model performance as I only got 72% - 73% accuracy
        * What steps did you take in your attempts to increase model performance?
                I put the cutoff value of the application types to <100 and the cutoff value for the classifications to <200 for the first optimization test.
                Optimization Test #2 I put put the cutoff value of the application types to <500 and the cutoff value for the classifications to <500 for the first optimization test.
                Optimization Test #3 I put put the cutoff value of the application types to <10x`00 and the cutoff value for the classifications to <1000 for the first optimization test.


## Summary:

Using the data that was provided I was only about to get an accuracy rate around 72% - 73%.  I was seeking to get a accuracy rate around 75% and realized that in order to get higher preduction accuracy rates I would need to take the csv file and do more with the data and clean it up better than currently presented to me.


### Documented Help Received For Assignment
Received Help From Study Groups


