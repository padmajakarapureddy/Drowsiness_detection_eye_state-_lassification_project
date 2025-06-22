# Drowsiness_detection_eye_state-_lassification_project
** Eye State Detection using DNN**
This project is a computer vision application that classifies eye states (Open or Closed) from grayscale images using a Deep Neural Network (DNN). It demonstrates the complete pipeline from data loading and preprocessing to model training and evaluation.

Model:
  Architecture: Neural Network built using Keras with TensorFlow backend.
  Final layer uses softmax for binary classification (Open = 0, Closed = 1).

Dataset:
  Two classes: Open/ and Closed/ stored in separate folders.
  Each image is converted to grayscale and resized to 64x64 pixels.
  Data is split into training and testing sets.
  
Tools & Libraries:
  OpenCV for image loading and preprocessing.
  NumPy for array operations.
  Keras, TensorFlow for model creation and training.
  Sklearn for dataset splitting.

Results:
  Model trained for 30 epochs with good classification accuracy.
  Saved the trained model as dnn_model.h5.

Potential Applications:
  Drowsiness detection systems
  Eye activity monitoring in medical or security settings

