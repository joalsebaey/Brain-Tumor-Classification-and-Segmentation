# 🧠 Brain Tumor Detection and Classification

## Overview
Brain tumors are among the most aggressive diseases, affecting both children and adults. Accounting for 85–90% of all primary Central Nervous System (CNS) tumors, early and accurate diagnosis is critical for improving patient outcomes. However, manual diagnosis through Magnetic Resonance Imaging (MRI) can be error-prone due to the complexities involved in interpreting tumor properties.

This project leverages **Deep Learning** techniques to automate the detection, classification, and segmentation of brain tumors. Using state-of-the-art models like **Convolutional Neural Networks (CNNs)** for classification and **YOLO (You Only Look Once)** for segmentation, the system achieves remarkable performance, significantly aiding radiologists in accurate and efficient diagnoses.

---

## Key Features
- **Classification Model**:
  - Built using a CNN architecture.
  - Achieves an accuracy of **87%**.
  - Classifies tumors into 4 categories:
    1. **Benign Tumor**
    2. **Malignant Tumor**
    3. **Pituitary Tumor**
    4. **Other Tumors**

- **Segmentation Model**:
  - Uses the YOLO algorithm for precise tumor localization.
  - Achieves an accuracy of **95%** for segmenting tumor regions.

- **Dataset**:
  - MRI dataset with over **5300 images**.
  - Covers 4 tumor classes with diverse and complex tumor characteristics.

---

## Deep Learning Models
1. **Convolutional Neural Network (CNN)**:
   - Designed to classify brain tumor types based on MRI scans.
   - Optimized with techniques like data augmentation and regularization for high accuracy.

2. **YOLO (You Only Look Once)**:
   - Implements tumor segmentation by detecting and localizing the affected regions in the MRI scans.
   - Ensures real-time performance and high precision, making it suitable for clinical use.

---

## Applications
- **Automated Diagnostics**: Assists radiologists by providing fast and reliable tumor classification and segmentation.
- **Treatment Planning**: Helps medical professionals understand the tumor's location and type, enabling precise treatment strategies.
- **Research**: Facilitates the study of brain tumor patterns and properties using large datasets.

---

## Results
- **CNN Accuracy**: **87%** for tumor classification.
- **YOLO Accuracy**: **95%** for tumor segmentation.
- **Dataset Size**: **5300 MRI images**, ensuring robustness and reliability.

---

## Getting Started

### Prerequisites
Ensure the following are installed:
- Python (>= 3.8)
- TensorFlow/Keras
- PyTorch (for YOLO implementation)
- OpenCV
- NumPy
- Matplotlib
- Seaborn

###Results Visualization
- Classification: View tumor predictions for MRI scans.
- Segmentation: Visualize segmented regions using bounding boxes.
##Future Work
- Expand dataset size and diversity for improved generalization.
- Incorporate additional tumor types and conditions.
- Develop a user-friendly interface for clinical use.
