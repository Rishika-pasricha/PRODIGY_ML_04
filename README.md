# ✋ Hand Gesture Recognition Model

This project presents a **Hand Gesture Recognition System** capable of accurately identifying and classifying different hand gestures from image data. The goal is to enable **intuitive human-computer interaction** and **gesture-based control systems** using deep learning techniques.

## 📁 Dataset

The model uses the **leapGestRecog** dataset, which consists of grayscale images of hand gestures captured using a Leap Motion Controller. The dataset includes 10 gesture classes across multiple subjects and is ideal for training gesture classification models.

📌 **Dataset Link:**  
[leapGestRecog Dataset on Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog)

## 🧠 Model Overview

- Type: **Convolutional Neural Network (CNN)**
- Framework: **TensorFlow / Keras**
- Input: Grayscale images (320x240)
- Output: One of 10 gesture class labels
- Data Augmentation: Used to increase generalization and robustness
- Evaluation: Accuracy, Confusion Matrix

## 📌 Features

- Real-time or image-based gesture classification
- Simple, lightweight CNN model suitable for deployment
- Preprocessing pipeline includes resizing, normalization, and augmentation
- Supports further integration with GUI or control systems

## 🛠️ Installation

1. Clone the repository
2. Install required libraries:
    ```bash
    pip install tensorflow opencv-python numpy matplotlib scikit-learn
    ```
3. Download and extract the dataset from Kaggle


## 📊 Results

- Training Accuracy: ~XX%
- Validation Accuracy: ~XX%
- Confusion Matrix and classification report for detailed performance analysis

*(Update the percentages after model training)*

## 📌 Future Enhancements

- Integrate with webcam for real-time gesture control
- Expand gesture vocabulary
- Build a web or desktop interface for interaction

## 🤝 Acknowledgements

- Dataset provided by: [GTI-UPM Leap Gesture Dataset](https://www.kaggle.com/gti-upm/leapgestrecog)

---

