# NMF-vs-PCA

Both NMF and PCA are used for the dimenssion reduction of a data set. However it is always consider that NMF results are more interpretable
than PCA. Unlike NMF, PCA doesn't learn the parts of things.

In this example I am providing the comparsion of these dimension reduction tool on LED digits images dataset (100 images) which is 
given in the form of 2-D array (lcd-digits.csv is provided in the folder). Initially dataset will be explored with some preliminary plots 
and then NMF and PCA will be used on this dataset. 
Above mentioned hypothesis will be investigated on the basis of results.

# Important modules that are required.
1. pandas
2. matplotlib.pyplot
3. KMN from sklearn.decomposition
4. PCA from sklearn.decomposition
