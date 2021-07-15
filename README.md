# Predicting composition of Cr-Mo alloy 
<h2> Problem description </h2>
Using the regression models in a real thermodynamic system.

Applied two supervised algorithms, Linear regression and K-Nearest Neighbors to predict the composition values at various eta values.
<hr>
<h3> What does eta values mean? </h3>
These are dimensionless number, that represent normalized energy parameters which corresponds to:

* eta1 - first neighbor cluster
* eta2 - second neighbor cluster
* eta3 - third neighbor cluster
* eta4 - fourth neighbor cluster

<hr>
<h3> What are the other contents in the dataset? </h3>

The dataset contains: u0, u1, u2, u3, u4, eta1, eta2, eta3, eta4.
Here
* u0 - Composition
* u1 - Correlation function for I-neighbor pair
* u2 - Correlation function for II-neighbor pair
* u3 - Correlation function for triangle
* u4 - Correlation function for tetrahedron cluster
<hr>
<h2> Results </h2>

* Accuracy of linear model on training dataset : 49.709004178502795 % 
* Accuracy of linear model on training dataset : 51.05961513782863 % 
* Accuracy of K-Nearest Neighbor model on training dataset : 59.11328125000001 % 
* Accuracy of K-Nearest Neighbor model on training dataset : 51.05961513782863 % 

Using the efficient model, preferbly the KNN model can be used to predict the composition values at different eta values.
