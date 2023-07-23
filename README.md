# Deep-Learning-Challenge

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


# For this challenge I did the following:

## Part 1: Preprocess the Data

* Read in the charity_data.csv to a Pandas DataFrame, and be sure to identify the following in your dataset:
        * What variable(s) are the target(s) for your model?
        * What variable(s) are the feature(s) for your model?
        * Drop the EIN and NAME columns.

* Determined the number of unique values for each column.
* For columns that have more than 10 unique values, determined the number of data points for each unique value.
* Used the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.
* Used pd.get_dummies() to encode categorical variables.
* Split the preprocessed data into a features array, X, and a target array, y. Used these arrays and the train_test_split function to split the data into training and testing datasets.
* Scaled the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.

## Part 2: Compile, Train, and Evaluate the Model

* Created a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
* Created the first hidden layer and choose an appropriate activation function.
* Added a second hidden layer with an appropriate activation function.
* Created an output layer with an appropriate activation function.
* Checked the structure of the model.
* Compiled and trained the model.
* Created a callback that saves the model's weights every five epochs.
* Evaluated the model using the test data to determine the loss and accuracy.
* Saved and exported your results to an HDF5 file.

## Part 3: Optimize the Model

* Adjust the input data to ensure that no variables or outliers are causing confusion in the model, such as:
        * Dropping more or fewer columns.
        * Creating more bins for rare occurrences in columns.
        * Increasing or decreasing the number of values for each bin.
        * Add more neurons to a hidden layer.
        * Add more hidden layers.
        * Use different activation functions for the hidden layers.
        * Add or reduce the number of epochs to the training regimen.

* Imported your dependencies and read in the charity_data.csv to a Pandas DataFrame.
* Preprocessed the dataset as I did in Step 1. Adjusted for any modifications that came out of optimizing the model.
* Designed a neural network model, adjusted for modifications that will optimize the model to achieve higher than 75% accuracy.

## Part 4: Write a Report on the Neural Network Model

* Created a report that contains the following:
        * Overview of the analysis: Explain the purpose of this analysis.
        * Results: Using bulleted lists and images to support your answers, address the following questions:
        * Data Preprocessing
        * What variable(s) are the target(s) for your model?
        * What variable(s) are the features for your model?
        * What variable(s) should be removed from the input data because they are neither targets nor features?

         * Compiling, Training, and Evaluating the Model
                * How many neurons, layers, and activation functions did you select for your neural network model, and why?
                * Were you able to achieve the target model performance?
                * What steps did you take in your attempts to increase model performance?
                * Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.




### Documented Help Received For Assignment
Received Help From Study Groups


