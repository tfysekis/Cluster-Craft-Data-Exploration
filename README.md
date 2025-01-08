# Clustering Analysis with DBSCAN - University Project

## Project Overview
This project explores clustering analysis using the DBSCAN algorithm on the **Iris dataset**. The goal is to study the effects of parameter tuning and data normalization on the clustering results. The project was developed as part of a master's degree course.

## What We Did
1. **Loaded and Visualized Data**: Used dimensions (petal length and width) of the Iris dataset to apply clustering.
2. **Clustering with DBSCAN**:
   - Experimented with different `eps` and `min_samples` values.
   - Visualized clusters and noise points using scatter plots.
3. **Normalization**:
   - Applied z-score normalization to standardize feature values.
   - Compared clustering results before and after normalization.

## How to Use
1. Open the Colab file.
2. Follow the steps in the notebook:
   - Run DBSCAN on the original data.
   - Run DBSCAN on normalized data.
   - Visualize and compare results.

## Dependencies
The project uses the following Python libraries:
- `numpy`
- `matplotlib`
- `scikit-learn`
- `scipy`

Install them using:
```
pip install numpy matplotlib scikit-learn scipy
```

## Purpose
This project was created as part of a university course on data analysis. It demonstrates clustering techniques and highlights the importance of data preprocessing.
