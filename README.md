# Experiment 5 - Unsupervised Learning

## Overview
This experiment explores **unsupervised learning** using **Python** and **Scikit-learn**.  
We cluster **unlabeled datasets** to find hidden patterns without human intervention.  

**Applications**: image segmentation, NLP, protein clustering, and feature reduction.  
**Techniques used**: K-means, DBSCAN, Gaussian Mixture Model (GMM), PCA.

---

## Clustering Methods

### K-means
- Partitions data into **k clusters** using nearest centroids.  
- Minimizes within-cluster variance.  
- Sensitive to outliers; alternatives: k-medians, k-medoids.

### DBSCAN
- Density-based clustering for **arbitrary shapes** and noisy data.  
- Parameters: `eps` (radius), `MinPts` (minimum points).  
- Identifies **core**, **border**, and **noise points**.

### GMM
- Probabilistic clustering assuming data is a **mixture of Gaussians**.  
- Uses **EM algorithm** for soft assignment.  
- Handles overlapping or non-spherical clusters.

---

## Evaluation Metrics
- Silhouette Score, ARI, NMI  
- Homogeneity, Completeness, V-measure  
- Davies-Bouldin, Dunn, Calinski-Harabasz indices  

---

## Procedure
1. Generate data: `make_blobs` / `make_moons`  
2. Apply clustering algorithms: K-means, DBSCAN, GMM  
3. Visualize clusters vs ground truth  
4. Quantitative comparison using evaluation metrics  
