# Face & Image Classification using Convolutional Neural Networks (CNN)

## 📌 Project Overview
This project focuses on **image classification using Convolutional Neural Networks (CNNs)**. A deep learning model was built and trained to classify images from the **CIFAR-10 dataset**, which consists of multiple object categories commonly used for benchmarking computer vision models.

The project demonstrates the complete deep learning workflow including data preprocessing, CNN architecture design, model training, evaluation, and performance analysis using Python and TensorFlow/Keras.

---

## 🎯 Problem Statement
Image classification is a fundamental task in computer vision with applications in face recognition, object detection, and automated image tagging.  
The objective of this project is to design a CNN model capable of accurately classifying images into predefined categories by learning spatial features from raw pixel data.

---

## 📊 Dataset
- **Dataset:** CIFAR-10
- **Total Images:** 60,000 color images (32×32 pixels)
- **Training Images:** 50,000
- **Test Images:** 10,000
- **Number of Classes:** 10

### Classes:
- Airplane  
- Automobile  
- Bird  
- Cat  
- Deer  
- Dog  
- Frog  
- Horse  
- Ship  
- Truck  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Normalized pixel values to improve convergence
- Reshaped input images to match CNN input requirements
- One-hot encoded class labels

### 2. Model Architecture
- Convolutional layers for feature extraction
- ReLU activation functions
- MaxPooling layers to reduce spatial dimensions
- Fully connected (Dense) layers for classification
- Softmax activation for multi-class output

### 3. Model Training
- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy
- Training performed over multiple epochs
- Validation split used to monitor generalization

---

## 📈 Model Evaluation
The trained CNN model was evaluated using:
- Training and validation accuracy
- Training and validation loss
- Test set performance

Visualization of accuracy and loss curves was used to analyze learning behavior and detect overfitting.

---

## 🧠 Key Learnings & Insights
- CNNs effectively learn spatial hierarchies from image data
- Data normalization significantly improves training stability
- Increasing model depth improves accuracy but may lead to overfitting
- Regularization and validation monitoring are crucial for generalization
