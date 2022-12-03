# Dataset Description
This data represents the results of a large product testing study. For each product_code you are given a number of product attributes (fixed for the code) as well as a number of measurement values for each individual product, representing various lab testing methods. Each product is used in a simulated real-world environment experiment, and and absorbs a certain amount of fluid (loading) to see whether or not it fails.

Your task is to use the data to predict individual product failures of new codes with their individual lab test results.

# Files
train.csv - the training data, which includes the target failure
test.csv - the test set; your task is to predict the likelihood each id will experience a failure
sample_submission.csv - a sample submission file in the correct format
