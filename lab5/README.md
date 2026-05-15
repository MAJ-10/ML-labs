# Lab 5: Talabat Orders Analysis

**Overview:**
This lab focuses on analyzing a dataset of Talabat orders to understand patterns and build a machine learning model.

**Dataset:**
File: `talabat_enhanced_orders.csv` (Contains order details and customer data).

**Methodology:**

```mermaid
graph TD;
    A[Load Talabat Data] --> B[Data Cleaning];
    C[Exploratory Analysis] --> D[Model Training];
    B --> C;
    D --> E[Evaluation];
