# Features we're using

## Cluster Analysis
We grouped the wells by analyzing their surface X and Y coordinates. We used the KMeans algorithm to cluster the wells into 20 groups. Afterwards we used the cluster number to compute the variation with respect to the mean OilPeakRate.
Under the `/model` directory we store the KMeans model and the cluster labels for each well are stored in `data/cluster_label_features.csv`.
