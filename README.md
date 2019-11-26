# PCA-Example

Principal Component Analysis is an unsupervised dimensionality reduction algorithm.

This is used for operations like :
* Noise filtering 
* Visualization
* Feature Extraction
* Stock Market Predictions 
* Gene Data Analysis


Goal of PCA is to identify patterns in data and detect correlation between variables then reduce the dimensions of a d-dimensional dataset by projecting it onto a (k)-dimensional subspace (where k<d) 


Main functions of PCA:
* Standardize the data
* Obtain the Eigenvectors and Eigenvalues from the covariance matrix or correlation matrix, or perform Singular Vector Decomposition
* Sort eigenvalues in descending order and choose the k eigenvectors that correspond to k largest eigenvalues where k is the number of dimensions of the new features supspace (k<=d)
* Construct the projection matrix W from the selected k eigenvectors 
* Transform the orginial dataset X via W to obtain k-dimensional feature subspace Y.


