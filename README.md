# 🧠 Brain Tumor Analysis Using Machine Learning Algorithms

## 📌 Project Overview

Brain tumors are among the most critical neurological disorders, where early diagnosis is essential for effective treatment. Manual analysis of Magnetic Resonance Imaging (MRI) scans is time-consuming and depends on expert radiologists. This project presents an automated brain tumor classification system using Machine Learning and Deep Learning techniques to improve diagnostic accuracy and efficiency.

The study compares several traditional Machine Learning algorithms with a Convolutional Neural Network (CNN) to classify MRI images into different tumor categories. Experimental results demonstrate that CNN achieves superior performance by automatically learning complex spatial and texture-based features from MRI images.

---

## 🎯 Objectives

- Develop an automated brain tumor classification system.
- Compare multiple Machine Learning algorithms.
- Design and implement a Convolutional Neural Network (CNN).
- Evaluate model performance using Accuracy, Precision, Recall, and F1-Score.
- Identify the best-performing model for MRI-based brain tumor diagnosis.

---

## 📊 Dataset

The project uses **3,788 MRI brain images** categorized into four classes:

- No Tumor
- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor

### Dataset Split

- **Training Data:** 80%
- **Testing Data:** 20%

### MRI Views

- Axial
- Coronal
- Sagittal

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied before model training:

- Image Resizing (224 × 224 pixels)
- Pixel Normalization
- Grayscale Conversion
- Image Flattening
- Data Augmentation
  - Rotation
  - Horizontal Flip
  - Vertical Flip
  - Zoom
  - Width Shift
  - Height Shift

---

## 🛠️ Technologies Used

### Programming Language

- Python

### Libraries & Frameworks

- TensorFlow
- Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

### Development Environment

- Jupyter Notebook

---

## 🤖 Machine Learning Models

The following Machine Learning and Deep Learning models were implemented and compared:

- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree
- Logistic Regression
- Support Vector Machine (SVM)
- Multilayer Perceptron (MLP)
- Random Forest
- XGBoost
- Convolutional Neural Network (CNN)

---

## 🧠 CNN Architecture

The proposed CNN architecture consists of:

- Conv2D Layer (32 Filters)
- MaxPooling Layer
- Conv2D Layer (64 Filters)
- MaxPooling Layer
- Flatten Layer
- Dense Layer (128 Neurons)
- Softmax Output Layer

### Training Configuration

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Batch Size: 32
- Epochs: 100

---

## 📈 Performance Summary

| Model | Performance |
|--------|-------------|
| Naive Bayes | Poor |
| K-Nearest Neighbors | Moderate |
| Decision Tree | Good |
| Logistic Regression | Good |
| Support Vector Machine | Very Good |
| Multilayer Perceptron | Very Good |
| Random Forest | Excellent |
| XGBoost | Outstanding |
| CNN | ⭐ Best Overall (93% Validation Accuracy) |

---

## 🚀 Results

The comparative analysis demonstrates that:

- CNN achieved approximately **93% validation accuracy**.
- Random Forest and XGBoost were the strongest traditional Machine Learning models.
- CNN automatically extracted hierarchical spatial and texture features from MRI images.
- Deep Learning significantly outperformed conventional Machine Learning algorithms in terms of classification accuracy and generalization.

---

## ✨ Key Features

- Automated Brain Tumor Detection
- MRI Image Classification
- Machine Learning vs Deep Learning Comparison
- CNN-Based Medical Image Analysis
- Multi-Class Classification
- Performance Evaluation
- Medical Image Processing

---

## 🔮 Future Scope

Future enhancements may include:

- Larger MRI datasets
- Transfer Learning using ResNet, EfficientNet, and DenseNet
- Explainable AI using Grad-CAM
- Cloud-based deployment
- Real-time clinical decision support system

---

## 👨‍💻 Author

**Snehil Raj**

B.Tech – Electrical and Electronics Engineering  
School of Electrical Engineering  
Vellore Institute of Technology (VIT), Vellore

---

## 📄 Project Report

This repository contains the complete project report covering the project methodology, literature review, system architecture, implementation details, experimental setup, comparative analysis, results, discussion, and conclusion for automated brain tumor classification using Machine Learning and Deep Learning techniques.

---

## ⭐ Conclusion

This project demonstrates that Convolutional Neural Networks (CNNs) provide significantly better performance than traditional Machine Learning algorithms for MRI-based brain tumor classification. By automatically learning meaningful spatial features from medical images, CNN achieves higher classification accuracy and better generalization. The study highlights the growing importance of Artificial Intelligence in modern healthcare and its potential to support radiologists through accurate and efficient computer-aided diagnosis.

---

## 📜 License

This repository is intended for **educational, academic, and research purposes only**.
