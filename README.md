# Clustering Analysis on UCI Dataset

## 📊 Project Overview

This project presents a comparative performance study of different clustering algorithms applied to a small dataset from the UCI Machine Learning Repository. The clustering techniques are evaluated using multiple data preprocessing methods and cluster configurations. The primary goal is to understand how preprocessing and the choice of clustering algorithm affect clustering performance on real-world data.

---

## 📁 Dataset Used

- **Dataset**: [UCI Letter Recognition Dataset](https://archive.ics.uci.edu/ml/datasets/Letter+Recognition)
- **Size**: 20,000 samples, 16 features
- **Classes**: 26 (A-Z)
- **Target Variable**: Letter (Categorical)

---

## ⚙️ Clustering Techniques Applied

1. **K-Means Clustering**
2. **Hierarchical Clustering**
3. **Mean Shift Clustering**

---

## 🔧 Preprocessing Techniques Used

- No Data Processing
- Normalization
- Transformation
- PCA (Principal Component Analysis)
- T+N: Transformation + Normalization
- T+N+PCA: Combined preprocessing

---

## 🔎 Evaluation Metrics

1. **Silhouette Score**
2. **Calinski-Harabasz Index**
3. **Davies-Bouldin Index**

These metrics help assess the quality of clustering by considering cohesion and separation.

---

## 📈 Results Summary

Each clustering method was evaluated for 3 cluster configurations (c = 3, 4, 5) under all preprocessing settings. The results were tabulated as follows:

- A **separate table for each clustering algorithm**
- **Rows**: Evaluation metrics
- **Columns**: Preprocessing + cluster number (e.g., "Normalization\nc=3")

📌 The format strictly follows academic presentation standards for clarity and comparison.

---

## 📊 Visualizations

The notebook includes:

- Bar plots of metric scores
- Comparative tables of metrics across algorithms and preprocessing techniques
- Heatmaps for quick performance overview

---

## 📁 File Structure

