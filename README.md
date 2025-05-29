# customer-churn

This project applies supervised and unsupervised machine learning techniques to predict customer churn and segment users for an online retail company. The analysis leverages a Kaggle dataset and aims to support data-driven retention and marketing strategies.

## Project Goals

- **Churn Prediction:** Identify customers likely to leave using classification algorithms.
- **Customer Segmentation:** Group customers with similar behaviors to tailor promotions.

## Dataset

The dataset includes features such as tenure, city tier, time spent on app, number of devices, satisfaction score, order history, payment preferences, and more.

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Assessed data structure, variable types, correlations, and class imbalances.
- Visualized key patterns and handled missing values.

### 2. Data Preprocessing
- Addressed missing and anomalous values.
- Encoded categorical variables.
- Balanced the dataset using techniques like SMOTE.

### 3. Classification Models
- **Random Forest:** High accuracy and precision, moderate recall.
- **XGBoost:** Best overall performance across metrics.
- **Logistic Regression:** Used as a baseline.

### 4. Clustering Techniques
- **K-Means with t-SNE:** Produced the most meaningful clusters.
- **DBSCAN:** Less effective due to density variations.
- **Hierarchical Clustering:** Used for dendrogram visualization.

## Results

- **XGBoost** achieved the highest accuracy and AUC-ROC for churn prediction.
- **K-Means + t-SNE** provided the most actionable customer segments.

## Tech Stack

- **Languages:** Python
- **Libraries:** pandas, scikit-learn, xgboost, seaborn, matplotlib, t-SNE
- **Data Source:** [Kaggle E-commerce Dataset](https://www.kaggle.com/)

## Getting Started

1. Clone the repository.
2. Install dependencies:  
