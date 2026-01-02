# Customer-segmentation-using-clustering
Project overview
Objective: Segment customers based on behavior (e.g., recency, frequency, monetary value, basket size) using K-Means clustering.
Data: Retail transaction data with features like purchase frequency, spending, income, and recency of last purchase.
​Tech stack: Python, Pandas for data handling, Scikit-learn for clustering, Matplotlib for visualizations.
​
Methodology
Data was cleaned, missing values handled, and numeric features scaled to ensure fair distance calculations.
​The Elbow Method and silhouette score were used to choose the optimal number of clusters, then K-Means was trained on the normalized features.
​PCA reduced dimensions so clusters could be visualized in 2D and 3D plots for interpretation.
​
Key findings
The model typically discovered distinct segments such as low-income/low-spend, high-income/low-spend, and high-value frequent buyers.
Cluster profiling (mean feature values per cluster) revealed which groups contribute most to revenue and which segments are under-served.
​
Business impact
Marketing teams can design targeted campaigns, loyalty programs, and personalized offers for each cluster.
​The same pipeline can be reused on new data, providing a scalable, data-driven segmentation engine for ongoing customer analytics.
