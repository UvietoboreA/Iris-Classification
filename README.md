# Task 1: Iris Species Classification with Decision Tree Classifier
This project focuses on classifying the species of the Iris dataset using a Decision Tree Classifier. It includes data preprocessing, model training, evaluation, and visualization of results.

## Features
Exploratory Data Analysis (EDA) of the Iris dataset.
Preprocessing: Handling missing values, dropping unnecessary columns, and encoding categorical labels.
Model training and evaluation using a Decision Tree Classifier.
Visualization of the Confusion Matrix and correlation map.

## Dataset
The project uses the Iris.csv dataset. Ensure the dataset is in the same directory as the code.

## Code Workflow

### Load and Inspect Data
The dataset is loaded using pandas.
Basic inspection, such as dataset info, shape, and missing values, is performed.

### Data Preprocessing
Dropped unnecessary columns like Id.
Label encoded the Species column to numeric values for visualization.

### Split Data
Features (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm) are separated from the target (Species).
The dataset is split into training (75%) and testing (25%) sets.

### Model Training
A Decision Tree Classifier is trained on the training data.

### Model Evaluation
Accuracy is calculated for the test set.
Predictions are evaluated using a confusion matrix and classification report.

### Visualizations
A confusion matrix heatmap to show prediction accuracy.
A correlation map for feature relationships.

## Results
The accuracy of the Decision Tree Classifier is printed.
A confusion matrix heatmap visualizes the model's predictions.
A correlation map identifies relationships between features.
