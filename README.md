# Text_Clustering
20 news group data
The objective for me here was to build text clusters and report whether these clusters make sense.

For this project, I used a dataset named 20newsgroup. This is available in sklearn.datasets.

I ran a TFIDFVectorizer on the sentences to obtain a document-word sparse matrix.

Once I got my array, I applied different clustering techniques such as K-Means clustering and Hierarchical clustering to obtain meaningful clusters. Also checked if these clusters seemed relevant and well separated. (using cluster centroids)

Finally used dimensionality reduction technqiues such as PCA to come up with two dimensional visualization of these clusters. 
