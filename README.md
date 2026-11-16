# MNIST
# MNIST Handwritten Digit Recognition Using Neural Networks

## 1. Project Overview
This project focuses on recognizing handwritten digits using Artificial Neural Networks (ANN). The MNIST dataset is used to classify handwritten digits from 0 to 9.

## 2. Problem Statement
Handwritten digit recognition is a common image classification task. This project aims to develop a neural network model that can automatically identify handwritten digits from images.

## 3. Objective
- To load and understand the MNIST dataset.
- To perform exploratory data analysis.
- To preprocess and normalize image data.
- To build different neural network models.
- To compare models using different activation functions, epochs, and batch sizes.
- To evaluate model performance using training and validation accuracy.

## 4. Dataset Description
The MNIST dataset contains handwritten digit images.

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Image Type: Grayscale
- Number of Classes: 10
- Classes: Digits 0 to 9

## 5. Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn

## 6. Data Preprocessing
- Loaded the MNIST dataset.
- Split the training data into training and validation sets.
- Normalized pixel values between 0 and 1.
- Reshaped images into 784 features.
- Converted labels into one-hot encoding.

### Dataset Splitting
- Training Data: 50,000 images
- Validation Data: 10,000 images
- Testing Data: 10,000 images

## 7. Model Development
Different neural network models were developed and compared.

The experiments include:
- Softmax output-only models.
- Single hidden-layer models.
- Multiple hidden-layer models.
- Different activation functions such as Sigmoid, Tanh, and ReLU.
- Different batch sizes such as 32, 64, and 50,000.
- Different epoch values such as 10, 50, and 100.

## 8. Model Evaluation
The models were evaluated using:
- Training Loss
- Training Accuracy
- Validation Loss
- Validation Accuracy
- Training Time

## 9. Best Model Performance
The highest reported validation accuracy in the notebook was achieved by Model 13.

- Training Accuracy: 100%
- Validation Accuracy: 97.55%
- Validation Loss: 0.131
- Epochs: 100
- Batch Size: 32
- Hidden Layers: 3
- Activation Function: ReLU

## 10. Conclusion
This project demonstrates handwritten digit recognition using Artificial Neural Networks. Different neural network architectures, activation functions, batch sizes, and epochs were tested.

The results show that hidden layers, ReLU activation, and mini-batch training improve validation performance. The best validation accuracy achieved was 97.55%.

