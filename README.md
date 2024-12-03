# CryptoClustering
nineteenth week's assignment

Jupyter Notebook has the process through which data from Resources/.csv becomes scaled,
so that no values in data hold more relative weight than they're worth.

It has the steps for KMeans, which I used to find the ideal amount of clusters with the scaled data (otherwise untouched).
k was found by comparing inertia; then, a scatter plot was generated using 2 of the many features on the axes.

It has the process through which the scaled data's features are reduced to PCs using PCA,
and the steps for KMeans, again, which I used to find the ideal amount of clusters with the PCs.
k was found by comparing inertia; then a scatter plot was generated using 2 of the 3 PCs on the axes.

Note that, while the clusters <em>do</em> look more defined on the PCs,
this is because the PCs represent ~89% of the scaled data which was otherwise untouched.