# 🧠 Brain Tumor Analysis Using Machine Learning Algorithms

## 📌 Project Overview

Brain tumors are among the most serious neurological disorders, and their early diagnosis is essential for effective treatment. Manual analysis of Magnetic Resonance Imaging (MRI) scans is time-consuming and depends heavily on the expertise of radiologists. This project presents an intelligent approach for automated brain tumor classification using Machine Learning and Deep Learning techniques.

The project compares several traditional Machine Learning algorithms with a Convolutional Neural Network (CNN) to classify MRI images into different tumor categories. The comparative analysis demonstrates that CNN achieves the highest classification performance due to its ability to automatically learn spatial and textural features from medical images.

---

## 🎯 Objectives

- Develop an automated brain tumor classification system.
- Compare the performance of multiple Machine Learning algorithms.
- Design and implement a Convolutional Neural Network (CNN).
- Evaluate models using Accuracy, Precision, Recall, and F1-Score.
- Identify the most reliable model for MRI-based brain tumor diagnosis.

---

## 🧬 Dataset

The project uses an MRI Brain Tumor Dataset consisting of **3,788 MRI images** classified into four categories:

- No Tumor
- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor

The dataset contains MRI scans from different orientations including:

- Axial
- Coronal
- Sagittal

Data Split:

- Training Set: 80%
- Testing Set: 20%

---

## 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- TensorFlow
- Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

### Development Environment

- Jupyter Notebook

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied before model training:

- Image Resizing (224 × 224)
- Pixel Normalization
- Grayscale Conversion
- Image Flattening (for ML models)
- Data Augmentation
  - Rotation
  - Horizontal Flip
  - Vertical Flip
  - Zoom
  - Width Shift
  - Height Shift

---

## 🤖 Machine Learning Models

The following algorithms were implemented and compared:

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

The CNN model consists of:

- Conv2D Layer (32 Filters)
- MaxPooling Layer
- Conv2D Layer (64 Filters)
- MaxPooling Layer
- Flatten Layer
- Dense Layer (128 Units)
- Softmax Output Layer

Training Configuration:

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 100
- Batch Size: 32

---

## 📊 Performance Summary

| Model | Performance |
|--------|-------------|
| Naive Bayes | Poor |
| KNN | Moderate |
| Decision Tree | Good |
| Logistic Regression | Good |
| SVM | Very Good |
| MLP | Very Good |
| Random Forest | Excellent |
| XGBoost | Outstanding |
| CNN | Best Overall (93% Accuracy) |

---

## 📈 Results

The comparative study shows that:

- CNN achieved approximately **93% validation accuracy**.
- Random Forest and XGBoost were the best traditional Machine Learning models.
- CNN successfully learned hierarchical spatial features directly from MRI images.
- Deep Learning significantly outperformed traditional Machine Learning methods.

---

## 🔍 Key Features

- Automated Brain Tumor Detection
- MRI Image Classification
- Deep Learning Based Diagnosis
- Machine Learning Performance Comparison
- CNN Architecture Implementation
- Medical Image Analysis
- Performance Evaluation
- Multi-Class Classification

---

## 🚀 Future Enhancements

Potential improvements include:

- Larger MRI datasets
- Transfer Learning (ResNet, EfficientNet)
- Attention Mechanisms
- Explainable AI (Grad-CAM)
- Web-based Diagnostic System
- Real-time Clinical Deployment

---


```

---

## 👨‍💻 Authors

**Snehil Raj**  
B.Tech – Electrical and Electronics Engineering  
Vellore Institute of Technology (VIT), Vellore



---

## 📄 Project Report

The complete project report, methodology, experimental setup, comparative analysis, and results are included in the repository.

---

## ⭐ Conclusion

This project demonstrates that Convolutional Neural Networks (CNNs) provide superior performance for automated brain tumor classification from MRI images compared to traditional Machine Learning algorithms. The results highlight the potential of Deep Learning in assisting radiologists with accurate and efficient medical diagnosis, paving the way for future intelligent healthcare systems.

---

## 📜 License

This repository is intended for educational and academic purposes only.
