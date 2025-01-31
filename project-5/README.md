Clustering and Dimensionality Reduction Evaluation

This assignment aims to evaluate the performance of K-Means and Agglomerative Clustering algorithms and explore the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering results.

Dataset

The dataset includes annual spending in monetary units (m.u.) on various product categories for clients of a wholesale distributor. Additionally, categorical information about each client’s channel (Hotel/Restaurant/Cafe) and region (Lisbon, Oporto, or Other) is provided.

Applied Methods

K-Means Clustering: 8 clusters were created, and PCA was applied for dimensionality reduction.
Agglomerative Clustering: Applied for comparison with K-Means.

Evaluation
Clustering results were evaluated using Silhouette Scores:

K-Means (with PCA): K-Means with PCA showed better results, enhancing the separation between clusters.
K-Means (without PCA): Clustering without PCA resulted in lower performance.
Agglomerative Clustering: This method showed weaker performance compared to K-Means, indicating poor separation between clusters.

Results
PCA improved clustering performance when combined with K-Means by making the clusters more distinct.
K-Means emerged as the best-performing algorithm for this dataset, thanks to its centroid-based approach.
Agglomerative Clustering, while more flexible, performed worse for this dataset compared to K-Means.

Overall, PCA proved to be an important technique for enhancing clustering performance by reducing noise and making the separation between clusters clearer.













