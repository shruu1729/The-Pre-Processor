## Context
Machine Learning is a subset of the larger field of artificial intelligence (AI) that focuses on teaching computers how to learn without the need to be programmed for specific tasks. In fact, the key idea behind ML is that it is possible to create algorithms that learn from and make predictions on the data.

But before applying Machine Learning on any dataset, you need to convert it in such a way that the algorithms could understand the dataset. These steps are preprocessing steps.

## What is Data Pre-Processing ??
Data preprocessing is a data mining technique that involves transforming raw data into an understandable format. Real-world data is often incomplete, inconsistent, and/or lacking in certain behaviors or trends, and is likely to contain many errors. Data preprocessing is a proven method of resolving such issues.

In the real world data are generally incomplete: lacking attribute values, lacking certain attributes of interest, or containing only aggregate data. Noisy: containing errors or outliers. Inconsistent: containing discrepancies in codes or names.

## So what is the Project About ?
It is a simple CLI tool will save your time so that you can utilize it in applying different machine learning algorithms.
I will apply the following preprocessing steps:

--> Handling NULL values
--> Encoding Categorical Data
--> Feature Scaling

## Project Includes the following Process : 
1. Input the Dataset
2. Data Description
3. Handling NULL Values
4. Encoding Categorical Data
5. Feature Scaling
6. Download the preprocessed Dataset

Pandas and scikit learn will be used throughout the project to perform the preprocessig steps.

## Step-1: Input the Dataset
There are several types of Machine Learning such as Supervised learning, Unsupervised learning etc. Here, you are writing python scripts to make preprocessed dataset for performing supervised learning.
--> For simultaneously testing I will be performing the preprocessing on a very popular ML dataset - Titanic survival Dataset available on Kaggle.

Make a main class for the Project where all below functions will be defined -
1. A function that only takes a ‘.csv’ input from the command line.
2. A function that chooses a target (dependent) variable and removes it from the dataset, so that you can start preprocessing on all the independent variables.
3. Each task will have a separate class and will be called by their respective object.
4. Handle all the exceptions in the input.

## Step-2: Data Description
Make a separate class for Data Description where all below functions will be defined -
1. A function that shows properties (mean, standard deviation, percentiles, total number of values, maximum, minimum) of each numeric column. This function should        also show the datatypes along with the null value count of each column.
2. A function that shows the property of any specific column.
3. A numeric column should show properties like mean, standard deviation, percentiles, total number of values, maximum and minimum.
4. A string column should show properties like total number of values and number of distinct values.
5. A function that takes a number of rows ‘n’ as input and prints the dataset.
6. Handle all the exceptions in the input.

