# Lab : Classification Multi-Classes avec scikit-learn MLPClassifier sur le Dataset Forest Cover Type 🌲   

[Notebook](https://albanecoiffe.github.io/MLP_Dataset_Forest_Cover_Type/)   

## 🎯 Objective
In this lab, you will implement a `Multi-Layer Perceptron (MLP)` model using scikit-learn to classify different forest cover types.
The data profiling and preprocessing steps have already been completed in a previous lab.

## 🛠️ Steps    
1. Data Preprocessing (Completed in a Previous Lab)     
  - Normalization of data using StandardScaler.
  - Encoding target labels with One-Hot Encoding.
  - Splitting the dataset into training (80%) and testing (20%) sets.

2. MLP Model Construction
  - Using MLPClassifier from scikit-learn.
  - Architecture:
      - 2 hidden layers with 128 and 64 neurons respectively.
      - Activation function: ReLU.
      - Optimizer: Adam.

4. Model Training     
  - Training the model on the training dataset (no need for one-hot encoding of labels).

5. Model Evaluation
  - Predicting labels on the test set.
  - Generating evaluation metrics:
  - Accuracy
  - Confusion matrix
  - Classification report

6. Confusion Matrix Visualization
  - Displaying the confusion matrix as a heatmap to better understand model performance.

7. Hyperparameter Tuning
  - Exploring the impact of hyperparameters such as:
      - Number of hidden layers
      - Learning rate
      - Regularization
      - Evaluating their effect on model performance.
