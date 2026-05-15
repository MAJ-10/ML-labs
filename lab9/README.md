# Lab 9: Decision Trees and Random Forests

**Overview:**
This repository contains the work for Lab 9, focusing on tree-based machine learning algorithms (Decision Trees and Random Forests) for classification tasks.

**Datasets:**
1. `kyphosis.csv`: Medical data used to predict the presence of a spinal condition after surgery.
2. `loan_data.csv`: Financial data used to predict whether a borrower will pay back their loan in full.

**Methodology:**

```mermaid
graph TD;
    A[Load Datasets] --> B[Exploratory Data Analysis];
    B --> C[Data Preprocessing];
    C --> D[Train Decision Tree];
    C --> E[Train Random Forest];
    D --> F[Compare & Evaluate Models];
    E --> F;
