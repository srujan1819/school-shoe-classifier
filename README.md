# School Shoe Classifier 👟🎓

A comprehensive computer vision and deep learning project designed to automatically classify standardized student footwear. This project implements, trains, and evaluates multiple state-of-the-art Deep Convolutional Neural Network (CNN) architectures to identify compliance with strict school uniform color and gender specification standards.

---

## ## Project Overview
In many educational institutions, maintaining strict uniform compliance is part of daily discipline. This project leverages computer vision to automate the classification and inspection of student footwear into specific uniform categories:
* **Boys Black Shoes** (Standard formal black uniform shoes)
* **Boys White Shoes** (Standard white uniform shoes)
* **Girls Black Shoes** (Standard formal black uniform shoes/ballerinas)
* **Girls White Shoes** (Standard white uniform shoes)

The project explores a comparative study between a custom-built CNN architecture and various state-of-the-art pre-trained deep learning models via transfer learning to determine the most efficient and accurate option for uniform monitoring.

---

## ## Features & Functionality
* **Targeted Multi-Class Classification:** Dedicated sorting focused entirely on black and white uniform shoe variants for boys and girls.
* **Comprehensive Benchmarking:** Evaluation pipelines across more than 10 different deep learning architectures.
* **Pre-processing & Data Augmentation:** Built-in pipelines for resizing, normalization, and robust data augmentation to handle varied lighting conditions and angles.
* **Performance Analysis:** Automated generation of evaluation metrics, loss/accuracy curves, and classification reports.

---

## ## Deep Learning Architectures Evaluated
To find the optimal balance between classification accuracy and computational efficiency, the following models were systematically trained and evaluated:

* **Custom CNN Architecture:** A lightweight, baseline convolutional network built from scratch.
* **Standard Deep Networks:** AlexNet, VGG16, ResNet50, SE-ResNet50, DenseNet121, Xception.
* **Lightweight / Mobile-Optimized:** MobileNetV2, MobileNetV3-Small, MobileNetV3-Large, NASNetMobile.
* **High-Efficiency Networks:** InceptionV3, EfficientNetB0.

Detailed performance analysis and evaluation summaries for each model are saved as standalone verification documents in the repository.

---

## ## Model Performance & Evaluation

The training logs and metrics for each tested architecture are documented inside individual evaluation sheets. Below is a summary highlight of the models:

| Model Architecture | Accuracy | Precision | Recall | F1-Score | Status |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **ResNet50** | *[Insert %]* | *[Insert]* | *[Insert]* | *[Insert]* | 🏆 Best Accuracy |
| **MobileNetV2** | *[Insert %]* | *[Insert]* | *[Insert]* | *[Insert]* | ⚡ Best for Mobile/Edge |
| **Custom CNN** | *[Insert %]* | *[Insert]* | *[Insert]* | *[Insert]* | 📉 Baseline Model |

*(Note: You can check the full visual validation plots, loss curves, and confusion matrices inside the respective `.pdf` files uploaded in this repository.)*

---

## ## Repository File Structure
```text
├── school-shoe-classifier.py  # Main Python script (Model training & pipeline)
├── _VGG16.pdf                 # Performance metrics and plots for VGG16
├── AlexNet.pdf                # Performance metrics and plots for AlexNet
├── Custom CNN.pdf             # Performance metrics and plots for Custom CNN
├── ResNet50.pdf               # Performance metrics and plots for ResNet50
├── MobileNetV2.pdf            # Performance metrics and plots for MobileNetV2
└── ...                        # Other architecture evaluation PDFs
