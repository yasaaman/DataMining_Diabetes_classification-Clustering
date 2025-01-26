
# Data Mining Project: Diabetes Prediction and Clustering Analysis  

## Overview  

This project demonstrates practical applications of data mining and machine learning techniques, focusing on real-world challenges in data analysis. The goal is to clean and process raw data, build classification models for diabetes prediction, and group data using clustering algorithms to uncover hidden patterns by implementing Decision Tree and K-Nearest Neighbors (KNN) for classification, as well as K-Means and Hierarchical Clustering for grouping. The project emphasizes the importance of data preprocessing, algorithm selection, and result evaluation to ensure accurate and insightful outcomes.


---

## Introduction  
This project applies data mining techniques to solve real-world challenges in data analysis. It includes:  
- Building classification models to predict diabetes using Decision Tree and KNN algorithms.  
- Performing clustering analysis using K-Means and Hierarchical Clustering to identify meaningful groups in the dataset.  
- Evaluating results with metrics such as accuracy, precision,Recall and F1-score to ensure reliability and interpretability.  

---

## Dataset  
The dataset used in this project contains 100,001 entries with the following features:  
- **gender:** Categorical variable indicating the individual's gender (e.g., Male, Female, or Unknown).  
- **age:** Numerical variable representing the individual's age. Some values are missing and need imputation.  
- **hypertension:** Binary variable indicating whether the individual has hypertension (1: Yes, 0: No).  
- **heart_disease:** Binary variable indicating whether the individual has heart disease (1: Yes, 0: No).  
- **smoking_history:** Categorical variable describing the individual's smoking habits (e.g., Never, Current, or No Info).  
- **bmi:** Numerical variable representing the individual's Body Mass Index (BMI).  
- **HbA1c_level:** Numerical variable indicating the individual's average blood sugar level over 2–3 months.  
- **blood_glucose_level:** Numerical variable showing the individual's current blood glucose level.  
- **diabetes:** Binary label (1: Diabetes, 0: No Diabetes) used for classification tasks.  

---

## Methods  
### 1. Data Preprocessing  
The dataset underwent a series of preprocessing steps to ensure high-quality inputs for the models:  
- **Handling Missing Values:** Imputed using statistical methods (mean/median).  
- **Removing Duplicates:** Ensured unique and clean entries.  
- **Outlier Detection:** Identified and treated anomalies for better analysis.  
- **Normalization:** Scaled data for algorithms sensitive to feature magnitudes (e.g., KNN, K-Means).  

### 2. Classification  
Implemented and compared two algorithms for predicting diabetes:  
- **Decision Tree:** A simple, interpretable model that visualizes decisions as a tree structure.  
- **K-Nearest Neighbors (KNN):** A distance-based algorithm that classifies data based on the majority vote of its neighbors.  

### 3. Clustering  
Clustering algorithms were used to group similar data points:  
- **K-Means:** Selected the optimal number of clusters using the Elbow Method and Silhouette Score.  
- **Hierarchical Clustering:** Visualized clusters using dendrograms and identified relationships between clusters.  

---

## Results  
- **Classification:** Compared Decision Tree and KNN based on metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.  
- **Clustering:** Analyzed the key features of each cluster, explained the relationships among data points within clusters, and provided logical interpretations for groupings.  

---

## Conclusion  
This project demonstrates the importance of data preprocessing, algorithm selection, and evaluation in achieving accurate and meaningful results. The findings include:  
- A comparative analysis of Decision Tree and KNN models for diabetes prediction.  
- Insights into clustering results using K-Means and Hierarchical Clustering.  

By combining these techniques, the project provides a comprehensive workflow for both predictive and exploratory data analysis.  

---

## References  
- Relevant documentation and resources for [scikit-learn](https://scikit-learn.org/), [pandas](https://pandas.pydata.org/), and [matplotlib](https://matplotlib.org/).  
- Tutorials and articles on classification and clustering in machine learning.  

---
