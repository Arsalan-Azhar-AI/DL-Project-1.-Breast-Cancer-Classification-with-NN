Breast Cancer Classification Using Neural Networks

Overview:

This project focuses on building a neural network model to classify breast cancer using the popular load_breast_cancer() dataset from Scikit-learn. The model achieves an accuracy of 97%, showcasing its effectiveness in distinguishing between malignant and benign tumors based on clinical features. Key techniques such as Exploratory Data Analysis (EDA), data scaling, and visualization were used throughout the project to ensure the best possible outcomes.

Dataset:

The dataset used in this project is sourced from the Scikit-learn library:
It contains 30 features and 569 samples that describe the characteristics of the cell nuclei present in the breast mass. The classification task is to predict whether the cancer is malignant or benign.

Steps Performed:

  Exploratory Data Analysis (EDA):
  
    Investigated feature distributions and correlations.
    Visualized relationships between key features.
    
  Data Preprocessing:
  
      Applied StandardScaler to normalize the data, which helps improve the performance and convergence of the 
      neural network.
      
  Modeling:
  
    Built a Neural Network using TensorFlow/Keras, consisting of an input layer, hidden layers, and an output      layer for binary classification.
    
  Training:
  
    The model was trained with appropriate metrics, achieving an accuracy of 97% on the test data.
  
  Visualization:
  
    Plotted loss and accuracy curves to visualize model performance over epochs.
    Visualized the results of classification.

  Performance:
  
    The model's performance is summarized below:

Metric --> Value

accuracy: 0.9784,
loss: 0.1198

val_accuracy: 0.9783,
val_loss: 0.1012

test-accuracy: 0.9627,
test-loss: 0.1167 

