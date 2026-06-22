# 🚀 K-Means Clustering From Scratch

A complete implementation of the K-Means clustering algorithm using **NumPy**, built from scratch without relying on Scikit-Learn's KMeans class.

The project performs customer segmentation on the Mall Customers dataset and includes data preprocessing, optimal cluster selection using the Elbow Method, centroid optimization, and interactive visualizations.

---

## ✨ Key Features

* K-Means implemented completely from scratch
* Random centroid initialization
* Euclidean distance calculation
* Cluster assignment and centroid updates
* Convergence detection
* Elbow Method for optimal cluster selection
* 2D cluster visualization
* Interactive 3D cluster visualization with Plotly

---

## 📊 Dataset

**Mall Customers Dataset**

| Feature                | Description                 |
| ---------------------- | --------------------------- |
| Gender                 | Customer Gender             |
| Age                    | Customer Age                |
| Annual Income (k$)     | Annual Income               |
| Spending Score (1-100) | Customer Spending Behaviour |

---

## 🧠 Algorithm Workflow

```python
1. Choose K clusters
2. Initialize K centroids randomly
3. Compute distance of every point from centroids
4. Assign points to nearest centroid
5. Update centroids using cluster means
6. Repeat until centroids stop moving
```

---

## 📈 Results

### Elbow Method

Used to determine the optimal number of clusters.

<p align="center">
<img src="images/elbow_method.png" width="700">
</p>

### Customer Segmentation

<p align="center">
<img src="images/clusters.png" width="700">
</p>

### Clusters with Centroids

<p align="center">
<img src="images/centroids.png" width="700">
</p>

### Interactive 3D Visualization

<p align="center">
<img src="images/cluster_3d.png" width="700">
</p>

---

## 🛠️ Tech Stack

<p align="left">
<img src="https://skillicons.dev/icons?i=python" />
</p>

**Libraries Used**

* NumPy
* Pandas
* Matplotlib
* Plotly
* Scikit-Learn

---

## 🎯 Learning Outcomes

* Understanding K-Means internals
* Distance-based clustering
* Feature scaling for clustering
* Centroid optimization
* Cluster visualization techniques
* Practical unsupervised learning workflow

---

## 👨‍💻 Author

**Raj Kumar Gupta**
B.Tech CSE (AI & ML)
Amity University Jharkhand

⭐ Star this repository if you found it useful.
