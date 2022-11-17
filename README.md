# Charity Funding Predictor

Author: Rosie Gianan, gianr00@gmail.com

Build With: Python, Pandas, Machine Learning, scikit-learn, TensorFlow, Keras, jupyter notebook 

## Objective:

The nonprofit foundation Alphabet Soup wants a tool to help select the applicants for funding with the best chance of success in their ventures. Their business team provided a [charity_data.csv](Resources/charity_data.csv) dataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The dataset has a number of columns that capture metadata about each organization, such as:

* **EIN** and **NAME**—Identification columns
* **APPLICATION_TYPE**—Alphabet Soup application type
* **AFFILIATION**—Affiliated sector of industry
* **CLASSIFICATION**—Government organization classification
* **USE_CASE**—Use case for funding
* **ORGANIZATION**—Organization type
* **STATUS**—Active status
* **INCOME_AMT**—Income classification
* **SPECIAL_CONSIDERATIONS**—Special consideration for application
* **ASK_AMT**—Funding amount requested
* **IS_SUCCESSFUL**—Was the money used effectively

## Solution:
1.    Preprocess the data
Determine the number of unique values for each column and determine the number of data points for each unique value. Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, `Other`, and then check if the binning was successful.
 
2.  Compile, Train, and Evaluate the Model
Using TensorFlow and Keras, you’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. Create an output layer with an appropriate activation function. Compile and train the model. Evaluate the model using the test data to determine the loss and accuracy.

3.  Optimize the Model
Using TensorFlow, optimize your model to achieve a target predictive accuracy higher than 75%.

Adjust the input data to ensure that no variables or outliers are causing confusion in the model, such as:
-    Dropping more or fewer columns.
-    Creating more bins for rare occurrences in columns.
-    Increasing or decreasing the number of values for each bin.
-    Add more neurons to a hidden layer.
-    Add more hidden layers.
-    Use different activation functions for the hidden layers.
-    Add or reduce the number of epochs to the training regimen.

4. Create a summary report. 
    Note: See the [Report_Charity_Funding_Predictor.pdf](Report_Charity_Funding_Predictor.pdf) for the results and summary.

