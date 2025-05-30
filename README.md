# Breast-Cancer-Classification

## Project Overview
This project focuses on analyzing the Breast Cancer Wisconsin (Diagnostic) dataset with the objective of accurately classifying tumors as benign or malignant. Emphasis is placed on data preprocessing, exploratory data analysis, and building classification models to maximize predictive performance.

## Key Objectives
- Perform comprehensive preprocessing and exploration of diagnostic data.
- Develop and compare multiple classification models for breast cancer detection.
- Identify the most informative features contributing to tumor classification.
- Evaluate model performance using appropriate classification metrics.

## Dataset
The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, sourced from [Kaggle](https://www.kaggle.com/code/hsniyesakmak/breast-cancer-wisconsin-diagnostic/data?select=data.csv).

## Methodology

### Data Preprocessing
- Handling of missing and zero values (if any).
- Removal of irrelevant or low-variance features.
- Feature scaling using standardization techniques.
- Addressing class imbalance where applicable.

### Exploratory Data Analysis (EDA)
- Statistical summary and distribution analysis of key variables.
- Correlation heatmaps and pairwise feature plots.
- Visualization of feature importance using domain knowledge and automated selection methods.

### Model Development
- Implemented several machine learning models including:
  - Logistic Regression
  - k-Nearest Neighbors (KNN)
  - Random Forests
  - Naive Bayes
- Feature selection using techniques like Recursive Feature Elimination (RFE), Feature Importance and Principal Component Analysis (PCA).

### Evaluation
- Classification models evaluated using:
  - Accuracy
  - Precision, Recall, and F1-score

## Results
- The most effective model achieved over **98% accuracy** on the test set.
- Key features such as **mean radius**, **texture**, and **perimeter** showed strong predictive power in distinguishing malignant tumors.

## Limitations and Future Work
- Limited to the available features in the dataset; future work could incorporate genomic data or patient history.

## Tools and Technologies
- **Language**: R

---

> This project contributes to the early detection of breast cancer using interpretable and efficient machine learning models.
