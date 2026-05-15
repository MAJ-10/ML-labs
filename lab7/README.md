# Lab 7: Logistic Regression

**Overview:**
This repository contains the work for Lab 7, focusing on classification tasks using the Logistic Regression algorithm. 

**Datasets:**
1. `titanic_train.csv` & `titanic_test.csv`: Passenger data used to predict survival.
2. `advertising.csv`: Customer data used to predict if a user will click on an ad.

**Methodology:**

```mermaid
graph TD;
    A[Load Datasets] --> B[Data Cleaning & Preprocessing];
    B --> C[Exploratory Data Analysis];
    C --> D[Train Logistic Regression Model];
    D --> E[Model Evaluation];
