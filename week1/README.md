# Week 1 Homework

The data used can be download from the link in the text file. The data used are collected from NYC taxi dataset ([link](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)), specifically for the yellow tripdata 2022-01 and 2022-02 (the link could also be found in the data folder).

Homework questions:
Q1. Downloading the data
Read the data for January. How many columns are there?

Q2. Computing duration
What's the standard deviation of the trips duration in January?

Q3. Dropping outliers
There are some outliers. Let's remove them and keep only the records where the duration was between 1 and 60 minutes (inclusive). What fraction of the records left after you dropped the outliers?

Q4. One-hot encoding
Apply one-hot encoding to the pickup and dropoff location IDs. We'll use only these two features for our model.
Turn the dataframe into a list of dictionaries, fit a dictionary vectorizer, and get a feature matrix from it. What's the dimensionality of this matrix (number of columns)?

Q5. Training a model
Using the feature matrix from the previous step to train a model, train a plain linear regression model with default parameters, and calculate the RMSE of the model on the training data.
What's the RMSE on train?

Q6. Evaluating the model
Apply the model to the validation dataset (February 2022). What's the RMSE on validation?