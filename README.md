# Task-3-Iris-Flower-Classification
Steps to Run the Project
1)Open Google Colab and create a new notebook.
2)Upload the dataset (IRIS.csv) using the file upload option.
3)Run all the cells in order to:
4)Load and preprocess the data
5)Encode categorical target variable (species) using LabelEncoder()
6)Split the dataset into training and testing sets (70%-30%)
7)Evaluate the model using accuracy, classification report, and confusion matrix

Code Structure
Data Loading & Preprocessing:
1)Reads IRIS.csv, checks for missing values.
2)Encodes species column into numerical labels.

Model Training:
1)Splits data into train and test sets (train_test_split()).
2)Uses Random Forest Classifier for training.

Evaluation:
1)Computes accuracy, classification report, and confusion matrix.

Feature Importance Analysis:
1)Extracts and prints feature importance values.
2)Plots a bar chart to visualize feature importance.
