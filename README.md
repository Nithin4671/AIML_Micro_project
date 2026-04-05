# AIML Micro Project

##  Title

Student Career Prediction using Artificial Neural Network (ANN)

##  Description

This project predicts a student's potential career path based on academic performance and behavioral attributes using an Artificial Neural Network.

##  Dataset

* Source: Kaggle (Student Performance Dataset)
* Features used:

  * G1, G2, G3 (grades)
  * Failures
  * Absences

##  Model

* ANN (Sequential Model)
* Hidden Layers: 16, 12 neurons (ReLU activation)
* Output Layer: 3 neurons (Softmax)

##  Training

* Optimizer: Adam
* Loss: Sparse Categorical Crossentropy
* Epochs: 100

##  Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

##  Result

The model achieved high accuracy with minimal misclassification across all classes.

##  Conclusion

The ANN model successfully predicts career paths based on student data. Future improvements include using real-world labeled datasets for better generalization.
