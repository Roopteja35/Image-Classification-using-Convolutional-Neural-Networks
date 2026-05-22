Image Classification using CNN:
This project focuses on image classification using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The model is trained on image datasets to classify images into different categories and evaluate performance using accuracy and loss metrics.

Project Overview:
  Image Classification is one of the most important applications of Deep Learning and Computer Vision. 
  In this project, a CNN model is developed and trained to automatically identify and classify images from a dataset.

  The project includes:
    Data preprocessing
    CNN model building
    Model training and testing
    Accuracy and loss visualization
    Prediction on sample images

Objectives:
  Build a CNN model for image classification
  Train the model using TensorFlow/Keras
  Evaluate model performance using accuracy and loss
  Predict classes for test images
  Visualize training results

Dataset used: CIFAR-10 -> Color image dataset consisting of 10 object categories.
  The CIFAR-10 dataset contains:
    60,000 color images
    10 image classes
    32x32 image size
  Dataset contains these classes:
    0. Airplane
    1. Automobile
    2. Bird
    3. Cat
    4. Deer
    5. Dog
    6. Frog
    7. Horse
    8. Ship
    9. Truck

Technologies Used:
  Python
  TensorFlow / Keras
  NumPy
  Matplotlib
  Scikit-learn

CNN Model Architecture:
  The CNN model includes:
    Convolution Layers
    Max Pooling Layers
    Flatten Layer
    Dense Layers
    Dropout Layer
    Softmax Output Layer
  The model is trained using the Adam optimizer and categorical/sparse categorical crossentropy loss function.

Model Evaluation:
  The model performance is evaluated using:
    Training Accuracy
    Validation Accuracy
    Training Loss
    Validation Loss

Output Visualizations:
  The project generates:
    Accuracy vs Epoch graph
    Loss vs Epoch graph
    Sample image predictions
    Predicted class outputs
