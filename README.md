# task8

# K-Means Clustering with Visualization and Evaluation

This project demonstrates how to perform K-Means clustering on a dataset with key steps including visualization, optimal cluster selection using the Elbow Method, and evaluation using the Silhouette Score.

## Steps Included

1. **Load and Visualize Dataset**
   - A synthetic dataset is generated using `make_blobs` (you can replace this with your own dataset).
   - PCA (Principal Component Analysis) is optionally applied to reduce dimensionality for 2D visualization.

2. **Fit K-Means and Assign Cluster Labels**
   - K-Means clustering is applied to the dataset.
   - Cluster labels are assigned to each data point.

3. **Use the Elbow Method to Find Optimal K**
   - The Elbow Method helps determine the optimal number of clusters by plotting inertia (within-cluster sum of squares) against a range of K values.

4. **Visualize Clusters with Color-Coding**
   - The clustered data is visualized in 2D using PCA.
   - Data points are color-coded based on cluster assignment.
   - Cluster centroids are highlighted.

5. **Evaluate Clustering Using Silhouette Score**
   - The Silhouette Score is calculated to evaluate the quality of clustering (range: -1 to 1, higher is better).

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

## How to Run

```bash
python kmeans_clustering.py
```


## Output

* Plots for:

  * Raw data in 2D (via PCA)
  * Elbow method to find optimal clusters
  * Final clustered data with centroids
* Silhouette Score printed to console


