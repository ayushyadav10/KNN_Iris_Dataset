# KNN_Iris_Dataset
##K-Nearest Neighbours (KNN) Classifier

This repository demonstrates the implementation of the **K-Nearest Neighbours (KNN)** algorithm for classification using the popular **Iris dataset**. The notebook walks through the process of building a KNN classification model, visualizing the decision boundaries, and comparing the effect of different weight functions (`uniform` and `distance`).

---

## Overview

K-Nearest Neighbours (KNN) is one of the simplest and most widely used machine learning algorithms. It is a non-parametric and instance-based algorithm that is highly effective for both classification and regression tasks.

In this project, the KNN algorithm is applied to classify the **Iris dataset** into three different classes. The classification is performed using the first two features of the dataset, and the results are visualized using decision boundaries.

### Key Features of KNN:
- **Instance-based learning**: No explicit training phase; instead, predictions are made by considering the nearest neighbors of a data point.
- **Flexible**: Can be used for classification and regression.
- **Simple**: Easy to understand and implement.

---

## Advantages and Disadvantages of KNN

### Advantages
1. Easy to understand and implement.
2. Can be used for both classification and regression problems.
3. No assumptions about the data's distribution.

### Disadvantages
1. Computationally expensive due to the need to store and compare all training data.
2. Sensitive to data scaling, requiring normalization for optimal performance.
3. Higher memory requirements compared to other machine learning models.

---

## Applications of KNN

1. Identifying potential loan defaulters in banking.
2. Predicting voter preferences in political campaigns.
3. Calculating credit ratings based on similar customer profiles.

---

## Steps in the Notebook

1. **Import Data**: Import the Iris dataset using `scikit-learn`.
2. **Prepare Variables**: Separate the dataset into independent (`X`) and dependent (`y`) variables.
3. **KNN Classification Model**:
   - Create and train the KNN model.
   - Explore two weight functions:
     - `uniform`: All neighbors contribute equally.
     - `distance`: Closer neighbors have a higher influence.
   - Visualize the decision boundaries using `matplotlib`.

---

## Prerequisites

Ensure you have the following Python packages installed:
- `numpy`
- `matplotlib`
- `scikit-learn`

