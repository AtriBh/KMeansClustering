# KMeansClustering

# Customer Segmentation with K-Means Clustering

## Objective
Perform unsupervised clustering using K-Means to identify customer segments based on demographic and behavioral features.

## Tools
- Scikit-learn
- Pandas
- Matplotlib

## Methodology
### 1. Data Preprocessing & Visualization
- Analyzed features: `Age`, `Annual Income`, `Spending Score`
- Applied PCA for 2D visualization

[![Feature Distribution](Screenshot%202025-06-06%20184505.png)]

### 2. Elbow Method for Optimal K
- Computed WCSS for K=2 to K=10
- Identified optimal K at the "elbow" point

[![Elbow Plot](Screenshot%202025-06-06%20184530.png)]

[![Alternative Elbow Plot](Screenshot%202025-06-06%20184545.png)]

### 3. Cluster Visualization
#### 3D Clustering (Age, Income, Spending)
[![3D Clusters](Screenshot%202025-06-06%20184522.png)]

#### 2D Clustering (Income vs Spending Score)
[![2D Clusters](Screenshot%202025-06-06%20184539.png)]

#### Alternative Feature Projection
[![Cluster Projection](Screenshot%202025-06-06%20184552.png)]

### 4. Evaluation
- Calculated Silhouette Score to validate cluster quality
- Compared multiple feature combinations

## Key Insights
- Identified 5 to 6 distinct customer segments
- Highest separation in spending behavior vs income
- Age showed weaker clustering tendency
