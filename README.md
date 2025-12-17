Rice Type Classification with PyTorch
Project Overview
This project demonstrates a simple Artificial Neural Network (ANN) built with PyTorch for binary classification of rice types. The model predicts the class of rice based on various physical attributes.

Dataset
The project uses the Rice Type Classification dataset from Kaggle, which includes features like Area, Axis Lengths, Eccentricity, etc., and a binary 'Class' label.

Source: https://www.kaggle.com/datasets/mssmartypants/rice-type-classification

Methodology
Data Preprocessing: Data is loaded, cleaned (missing values and 'id' column removed), and numerical features are normalized.
Model: A PyTorch-based ANN with one hidden layer and ReLU activation, followed by a sigmoid output for binary classification.
Training: The model is trained using nn.BCELoss and Adam optimizer, tracking training and validation performance.
Evaluation: Performance is assessed using accuracy, precision, recall, F1-score, and a confusion matrix on a dedicated test set.
Key Results
Test Accuracy: 98.53%
Precision: 0.9893
Recall: 0.9841
F1-Score: 0.9867
The model achieved high accuracy and balanced performance metrics, indicating strong generalization capabilities.

Usage
To run the notebook, install dependencies via pip install torch torchvision scikit-learn pandas numpy matplotlib opendatasets torchsummary and execute the cells sequentially. You can interactively test the model with new input values.
