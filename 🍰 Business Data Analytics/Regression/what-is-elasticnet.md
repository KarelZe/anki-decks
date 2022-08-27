## Note
nid: 1653727807549
model: Basic-02d89-e0e22
tags: bda::04_regression
markdown: false

### Front
What is <b>ElasticNet</b>?

### Back
Compromise between LASSO and Ridge Regression. Fuses the variable selection property of LASSO with the shrinkage of coefficients of correlated predictors from Ridge regression.

Useful when the number of predictors is much bigger than the number of observations \((p>>n)\)
\[R S S+\lambda \sum_{j=1}^{p}\left(\alpha \beta_{j}^{2}+(1-\alpha)\left|\beta_{j}\right|\right)\]
\(\alpha=1\) : Equivalent to Ridge Regression.
