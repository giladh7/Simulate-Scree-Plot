# Simulate-Scree-Plot
Simulating PCA's Scree Plot under different levels of noise.

A scree plot is a line plot of the eigenvalues in a PCA analysis. It used to determine the number of components to keep in a PCA.
In this notebook we'll see how the PCA's Scree Plot looks like under different levels of noise. For that purpose we're embedding a k-dimensional linear subspace in d dimension space (d>>k). We denote the embedded data matrix as X. Than, we randomly choose rotataion matrix using QR decomposition on an i.i.d Gaussian matrix, and rotate the data. 
We represent the Scree Plot For differnet levels of noise level, and observe the results. We demonstrae that although the "elbow" of the Scree Plot exist for low rate of noise, with a decent rate of noise could show a misleading Scree Plot, in which the elbow 'heuristic' can't help determine the desired amount of componenets in PCA. 
