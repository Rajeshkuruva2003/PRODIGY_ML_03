# 🖼️ Image Classification using SVM

This project demonstrates how to build an image classification system using Support Vector Machines (SVM). The goal is to train a model that can classify images into predefined categories based on extracted features.

## 📌 Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Project Structure](#project-structure)
- [License](#license)

---

## 📖 Overview

In this project, we use image data to train a Support Vector Machine (SVM) classifier. Images are preprocessed and converted into a format suitable for classification. Features are extracted using simple techniques (e.g., pixel intensities, HOG), and an SVM model is trained on the extracted data.

### Features:
- Image loading and preprocessing (grayscale, resize)
- Feature extraction using raw pixels or HOG
- Training and evaluating an SVM classifier
- Accuracy and confusion matrix reporting

---

## 🛠️ Technologies Used

- Python 3.8+
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib (for visualization)
- joblib (for saving models)

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/image-classification-svm.git
cd image-classification-svm
image-classification-svm/
│
├── data/                     # Contains image dataset (organized in class folders)
├── models/                   # Trained model files
├── svm.py                    # Main training script
├── requirements.txt
└── README.md

