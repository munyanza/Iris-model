Notebook Summary
This notebook demonstrates a basic machine learning workflow using the Iris dataset.

Steps:

Import necessary libraries: Imports pandas for data manipulation, train_test_split for splitting data, LogisticRegression for the model, load_iris (although the data is loaded from a CSV), and accuracy_score for evaluation.

Load the dataset: Loads the Iris dataset from a CSV file into a pandas DataFrame.
Data Preprocessing:

Converts the 'Species' column to numerical representations using one-hot encoding.

Splits the data into features (X) and target (y), converting the 'Species' column to numerical labels (0, 1, 2).
Splits the data into training and testing sets.
Model Training:
Initializes a Logistic Regression model.
Trains the model using the training data.
Model Evaluation:
Evaluates the model's accuracy on the testing data.# Iris-model
