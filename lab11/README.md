# Lab 11: Customer Segmentation using K-Means

**Overview:**
This repository contains the work for Lab 11, which focuses on Unsupervised Learning using the K-Means Clustering algorithm to segment customers based on their behavior.

**Datasets:**
1. `mall_customers.csv`: Data from a retail mall used for basic segmentation.
2. `CC_GENERAL.csv`: Credit card usage data for more advanced customer clustering.

**Methodology:**

```mermaid
graph TD;
    A[Load Datasets] --> B[Data Preprocessing & Scaling];
    B --> C[Find Optimal K using Elbow Method];
    C --> D[Apply K-Means Clustering];
    D --> E[Visualize Clusters];
