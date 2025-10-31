# Task 8: K-Means Clustering

## Objective
Perform unsupervised learning using K-Means clustering to group customers based on similar spending patterns and income levels.

---

## Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Google Colab

---

## Steps Performed

### 1. Data Loading
- Uploaded the file `Mall_Customers.csv` to Google Colab.
- Loaded the dataset using Pandas and viewed its structure.

### 2. Data Preprocessing
- Selected the features **Annual Income (k$)** and **Spending Score (1–100)** for clustering.
- Scaled the data using `StandardScaler` to bring all feature values to the same scale.

### 3. Finding Optimal K (Elbow Method)
- Computed the Within Cluster Sum of Squares (WCSS) for values of K ranging from 1 to 10.
- Plotted the Elbow Curve to identify the point where the curve bends, indicating the optimal number of clusters.

### 4. Model Training
- Applied the **KMeans** algorithm with the chosen K value (commonly 5 for this dataset).
- Assigned cluster labels to each data point and added them to the dataset.

### 5. Visualization
- Created a scatter plot to visualize the clusters with color-coded points.
- Marked centroids using black “X” markers to indicate cluster centers.

### 6. Evaluation
- Evaluated the clustering results using the **Silhouette Score**.
- A higher silhouette score indicates better-defined and well-separated clusters.

### 7. PCA Visualization (Optional)
- Used **Principal Component Analysis (PCA)** for dimensionality reduction if multiple features were included.
- Visualized clusters in a 2D plot for better interpretability.

---

## Output
- Identified clear customer segments based on spending and income.
- Produced visual representation of clusters.
- Calculated Silhouette Score to assess clustering quality.

---

## Conclusion
The K-Means algorithm successfully grouped customers into distinct segments, revealing different spending behaviors. These insights can help businesses in customer profiling, targeted marketing, and personalized service strategies.
