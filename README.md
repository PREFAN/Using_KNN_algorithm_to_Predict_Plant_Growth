# Using_KNN_algorithm_to_Predict_Plant_Growth
This project uses the K-Nearest Neighbors (KNN) machine learning algorithm to predict plant growth milestones based on environmental and treatment-related factors such as soil type, watering frequency, and fertilizer type.

The project demonstrates a complete machine learning workflow, including data preprocessing, categorical feature encoding, feature scaling, model training, and performance evaluation.

Project Overview

The goal of this project is to classify whether a plant reaches a specific growth milestone using structured plant growth data. Since the dataset contains categorical variables, preprocessing steps such as one-hot encoding and feature scaling are applied before training the KNN classifier.

This project is ideal for learning how to apply supervised machine learning to agricultural or biological datasets.

Features
Load and inspect plant growth dataset
Perform exploratory data analysis (EDA)
Check for:
Missing values
Data types
Dataset dimensions
Encode categorical variables using One-Hot Encoding
Split data into training and testing sets
Scale features using MinMaxScaler
Train a K-Nearest Neighbors (KNN) classifier
Make predictions on unseen test data
Evaluate model performance using:
Accuracy score
Confusion matrix
Classification report (Precision, Recall, F1-score)
Visualize confusion matrix using Seaborn heatmap
Technologies Used
Python
Pandas – data handling and preprocessing
NumPy – numerical operations
Scikit-learn
MinMaxScaler
train_test_split
KNeighborsClassifier
confusion_matrix
classification_report
Matplotlib – visualization
Seaborn – confusion matrix heatmap
Dataset
File: plant_growth_data.csv
The dataset includes plant growth-related features such as:
Soil Type
Water Frequency
Fertilizer Type
Other numerical growth-related variables
Target variable: Growth_Milestone
Machine Learning Workflow
Load the dataset
Explore dataset structure and statistics
Check for missing values and data types
Apply one-hot encoding to categorical features:
Soil_Type
Water_Frequency
Fertilizer_Type
Separate features (X) and target (y)
Split the dataset into training and testing sets
Scale features using MinMaxScaler
Train the KNN classifier with n_neighbors=3
Predict plant growth milestone outcomes
Evaluate model performance using classification metrics
Model Evaluation

The model is evaluated using:

Accuracy Score – measures overall prediction correctness
Confusion Matrix – compares actual vs predicted classes
Classification Report – provides:
Precision
Recall
F1-score
Support
Visualization

The project includes a heatmap of the confusion matrix to visually interpret classification performance and identify prediction errors.

Use Cases

This project can be useful for:

Agricultural data analysis,
Plant growth monitoring,
Predictive modeling in farming,
Machine learning practice with categorical data, and 
Educational demonstrations of KNN classification.
