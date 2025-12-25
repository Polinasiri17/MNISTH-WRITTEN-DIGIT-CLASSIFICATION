Handwritten Digit Classification (MNIST)

 📌 Overview
This project implements a **Handwritten Digit Classification** system using the **MNIST dataset**.  
The goal is to correctly classify grayscale images of handwritten digits (0–9) using a machine learning / deep learning model.

The MNIST dataset is a standard benchmark dataset widely used in computer vision and machine learning research.



 🧠 Dataset
Name: MNIST (Modified National Institute of Standards and Technology)
Total images: 70,000
Training images: 60,000
Test images: 10,000
Image size: 28 × 28 pixels
Classes: 10 (digits 0 to 9)



 ⚙️ Technologies Used
- Python  
- NumPy  
- Matplotlib  
- TensorFlow / Keras *(or PyTorch / Scikit-learn – adjust if needed)*  
- Jupyter Notebook  



 🏗️ Model Architecture
- Input layer (28×28 flattened)
- Hidden layers (Dense / CNN layers depending on implementation)
- Activation functions: ReLU, Softmax
- Output layer with 10 neurons (one for each digit)



 🚀 Features
- Loads and preprocesses MNIST dataset
- Normalizes image pixel values
- Trains a digit classification model
- Evaluates model accuracy on test data
- Predicts handwritten digits
- Visualizes sample predictions



 📊 Results
- Achieved high accuracy on the MNIST test dataset
- Model successfully classifies handwritten digits from 0 to 9


