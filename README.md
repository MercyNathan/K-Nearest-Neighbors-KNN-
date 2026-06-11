# Breast Cancer Classification Using K-Nearest Neighbors (KNN)

## Project Overview

This project implements the K-Nearest Neighbors (KNN) algorithm from scratch to classify breast cancer tumors as either **malignant** (cancerous) or **benign** (non-cancerous). The project uses the Breast Cancer Wisconsin Dataset from Kaggle and demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model implementation, prediction, and performance evaluation.

## Objectives

* Load and explore a real-world healthcare dataset.
* Preprocess the dataset for machine learning.
* Implement the KNN algorithm from scratch using Python.
* Classify breast cancer tumors based on their characteristics.
* Evaluate the model using accuracy, confusion matrix, and classification metrics.

## Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

The dataset contains measurements computed from digitized images of breast mass cell nuclei. Features include radius, texture, perimeter, area, smoothness, compactness, symmetry, and other diagnostic measurements.

### Target Variable

* **M (1)** – Malignant Tumor
* **B (0)** – Benign Tumor

## Data Preprocessing

The following preprocessing steps were performed:

1. Removed unnecessary columns (`id` and `Unnamed: 32`).
2. Converted diagnosis labels from categorical values (M/B) to numerical values (1/0).
3. Split the dataset into training and testing sets.
4. Standardized feature values using feature scaling to improve distance-based classification.

## KNN Implementation

The KNN algorithm was implemented without using machine learning libraries for the classifier itself. The implementation includes:

* Euclidean distance calculation
* Identification of K nearest neighbors
* Majority voting for classification
* Prediction for single and multiple instances

## Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

Different K values can also be tested to determine the optimal number of neighbors for classification.

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn (for preprocessing and evaluation only)
