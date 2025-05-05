# AI-based-intrusion-detection-system--cicids-2023-dataset


## 📌 Project Overview
This project focuses on detecting malicious network traffic using **CICIDS 2023** dataset. This code trains and evaluates multiple machine learning models on the Backdoor Malware dataset,
including Logistic Regression, Perceptron, Random Forest, and Feedforward Neural Network (MLP).
The models are evaluated based on Accuracy, Recall, Precision, and F1-score.

## 📊 Dataset Used
- **CICIDS 2023** - A benchmark dataset for anomaly detection in network traffic.
- Download from: [https://www.unb.ca/cic/datasets/ids-2023.html](https://www.unb.ca/cic/datasets/ids-2023.html)

## ⚡ Features & Techniques
- **Feature Selection**: PCA for dimensionality reduction.
- **Models Used**: Random Forest, Perceptron, Isolation Forest.
- **Performance**: Achieved **97.67% accuracy** with reduced false positives by **15%**.

## Features
**Accurate Intrusion Detection:**

The system uses machine learning models to accurately detect various types of network intrusions (e.g., DDoS attacks, Brute Force attacks, etc.).

Achieves high accuracy and precision in distinguishing between normal and malicious traffic flows.

**Machine Learning Models:**

The system employs multiple machine learning algorithms, including:

**Random Forest**: A robust ensemble learning model for classification and regression tasks.

**Logistic Regression**: A simple yet effective model for binary classification tasks (normal vs. malicious).

**Perceptron**: A type of neural network used for classifying network traffic.

**False Positive Reduction:**

Isolation Forest: Used to reduce false positives in the system, improving the reliability of the detection system and reducing unnecessary alerts.

Enhances the system’s ability to correctly classify normal traffic while minimizing false alarms.

**Feature Selection with PCA (Principal Component Analysis):**

PCA is used for dimensionality reduction and feature selection to optimize model performance, focusing on the most relevant features of network traffic.

PCA improves the efficiency and speed of the IDS by reducing the number of features without losing critical information.

## Techniques
**Principal Component Analysis (PCA)**:

PCA is used for feature extraction and dimensionality reduction in the project. By transforming the high-dimensional dataset into a lower-dimensional space, PCA retains the most important features and removes redundant ones, improving model training and performance.

**Random Forest Classifier**:

A popular ensemble machine learning algorithm used for classification tasks. The Random Forest model aggregates predictions from multiple decision trees to improve accuracy and reduce overfitting.

**Logistic Regression**:

A statistical method used for binary classification. In this project, it is applied to classify network traffic as either normal or malicious.

**Isolation Forest Algorithm**:

Used for anomaly detection, particularly effective in identifying rare or outlying points in data (i.e., anomalies such as attacks). Isolation Forest helps reduce false positives by identifying and isolating anomalous network traffic patterns.

**Neural Networks (Perceptron)**:

A simple neural network model used for classification, particularly for binary outcomes (e.g., normal vs. malicious traffic).

## Evaluation Metrics:

Accuracy: Measures the percentage of correct predictions made by the system.

Precision and Recall: Used to evaluate the classifier's performance, particularly in terms of correctly identifying malicious traffic and minimizing false alarms.

F1-Score: A balanced measure of precision and recall, providing a more comprehensive evaluation of the model's performance.

## 🛠 Installation
1. Clone the repository:
   ```bash
   
