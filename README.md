## 2. Principal Component Analysis (PCA)
PCA is a technique for reducing the dimensionality of data while preserving its variance. The PCA implementation in this repository computes the principal components of the data matrix, allowing for dimensionality reduction and visualization of high-dimensional data.


# Example
##usage of Principal Component Analysis (PCA)
from pca import PCA

#Instantiate PCA class
pca = PCA(n_components=2)

#Fit the model to data
pca.fit(X)

#Transform data to reduced dimensionality
X_reduced = pca.transform(X)
