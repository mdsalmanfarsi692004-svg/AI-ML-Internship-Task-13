# Task 13: PCA - Dimensionality Reduction

This repository contains a PCA analysis on the Handwritten Digits dataset to reduce dimensionality while preserving accuracy.

## Steps Taken:
1. **Preprocessing**: Standardized the 64-pixel feature vectors.
2. **Analysis**: Plotted Cumulative Variance to find the optimal components.
3. **Reduction**: Compressed data from 64 features -> 30 features (retaining ~95% variance).
4. **Comparison**: Trained Logistic Regression on both datasets.

## Key Results:
* **Efficiency**: Reduced feature space by >50% with negligible loss in accuracy.
* **Visualization**: 2D Scatter plot shows clear separation of digit clusters.

## Files:
* **Task_13_PCA.ipynb**: Code for PCA and visualization.
* **digits_pca_reduced.csv**: The compressed dataset.
* **Task_13_Report.pdf**: Variance and accuracy report.
