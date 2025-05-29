# customer-churn
predicting customer churn in an online retail company
**Machine Learning Customer Retention Analysis**
Initiative Objective
This machine learning initiative aims to forecast customer attrition and analyze buyer segments in e-commerce through predictive modeling and cluster analysis. The workflow incorporated comprehensive data exploration, preprocessing, and multiple algorithmic approaches using a Kaggle-sourced transaction dataset.

Key Components

Exploratory Analysis Phase
Examined dataset structure, variable correlations, and data quality issues

Identified class imbalances (churn vs. retained customers) and missing values

Visualized patterns in customer behavior metrics

Data Preparation
Addressed missing observations and anomalous values

Encoded categorical features and normalized numerical scales

Implemented SMOTE/undersampling to balance class distributions

Predictive Modeling Approaches
Classification Techniques

Random Forest: Demonstrated 92% accuracy with strong precision (0.89) but moderate recall

XGBoost: Surpassed other models with 94% accuracy and optimal AUC-ROC (0.96)

Logistic Regression: Achieved baseline performance (82% accuracy)

Cluster Analysis

K-Means + t-SNE: Yielded more precise customer groupings than PCA alternatives

DBSCAN: Struggled with density variations in purchase patterns

Hierarchical Methods: Dendrogram visualization revealed 5 distinct buyer tiers

Technical Implementation
Tools: Python's scikit-learn, XGBoost, pandas, and visualization libraries

Dataset: Public retail transaction records from Kaggle repository

Strategic Implications
The analysis enables targeted retention campaigns through:

Early identification of at-risk customers via XGBoost predictions

Customized marketing strategies for identified customer clusters

Resource optimization based on churn probability thresholds
