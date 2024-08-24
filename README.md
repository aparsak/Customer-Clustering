# Customer Data Clustering 🗂️

This Jupyter notebook performs a comprehensive analysis of customer data with the following steps:

1. **Data Exploration** 📊
   - Load and clean data
   - Visualize data distributions and relationships using histograms, scatter plots, and box plots

2. **Dimensionality Reduction** 🔍
   - Apply PCA to reduce data dimensions for clustering

3. **Clustering Analysis** 🔢
   - Use K-Means clustering to segment customers
   - Determine the optimal number of clusters with the Elbow Method

4. **Visualization** 📈
   - Plot clusters in PCA-reduced space and original feature space
   - Visualize cluster centers

5. **Evaluation** 🧩
   - Calculate and print the Silhouette Score to assess cluster quality

### Dependencies

- `pandas`
- `seaborn`
- `matplotlib`
- `numpy`
- `scikit-learn`

  
### Future Work 🚀

Explore additional clustering methods and evaluation metrics to enhance analysis:

- **Clustering Methods**:
  - **Hierarchical Clustering**: Analyzes data based on a tree-like structure of nested clusters.
  - **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: Groups together closely packed points and identifies outliers.
  - **Gaussian Mixture Models (GMM)**: Uses probabilistic models to handle clusters with different shapes and sizes.

- **Evaluation Metrics**:
  - **Davies-Bouldin Index**: Measures the average similarity ratio of each cluster with its most similar cluster.
  - **Calinski-Harabasz Index**: Evaluates the ratio of the sum of between-cluster dispersion to within-cluster dispersion.
  - **Adjusted Rand Index (ARI)**: Compares the similarity of the clustering result with a ground truth classification.

## 

Feel free to explore and modify the code for your specific needs!
