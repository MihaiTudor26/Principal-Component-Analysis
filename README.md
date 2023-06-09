# Principal Component Analysis (PCA)👨🏼‍🏫

**Principal Component Analysis** is a dimensionality-reduction method that is often used to reduce the dimensionality of large dataset. The idea of PCA is simple — reduce the number of variables of a data set, while preserving as much information as possible. Following the application of this method, we have several benefits
- we can rank the observations based on several variables
- overcome multi-collinearity
- data visualization (biplot)

This method is based on the following steps:
<ol>
<li>Standardize the range of continuous initial variables</li>
<li>Compute the covariance matrix to identify correlations</li>
<li>Compute the eigenvectors and eigenvalues of the covariance matrix to identify the principal components</li>
<li>Create a feature vector to decide which principal components to keep</li>
<li>Recast the data along the principal components axes</li>
</ol>

We will apply Principal Component Analysis for breast cancer Wisconsin (original) [dataset](https://www.kaggle.com/datasets/marshuu/breast-cancer). The dataset contains 699 real observations considering 9 independent variables that allow us to classify the dependent variable as malignant or benign. A brief description of the medical terminology can be consulted in this [notebook](https://github.com/MihaiTudor26/Logistic_Regression_Tutorial).

**📚References.**

- Steven M. Holland, Univ. of Georgia: Principal Components Analysis
- skymind.ai: Eigenvectors, Eigenvalues, PCA, Covariance and Entropy
- Lindsay I. Smith: A tutorial on Principal Component Analysis
