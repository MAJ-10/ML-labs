# Lab 8: K-Nearest Neighbors (KNN)

**Overview:**
This repository contains the work for Lab 8, focusing on the K-Nearest Neighbors (KNN) machine learning algorithm for classification tasks.

**Datasets:**
1. `Classified Data`: Anonymized dataset used to understand the basics of KNN.
2. `KNN_Project_Data`: Dataset used for the assignment to build and test a KNN model.

**Methodology:**

```mermaid
graph TD;
    A[Load Datasets] --> B[Standardize Features];
    B --> C[Train/Test Split];
    C --> D[Train KNN Model];
    D --> E[Evaluate & Optimize K];
