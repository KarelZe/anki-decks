# Note
```
guid: BB>]N!(4lh
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::04_regression
```

## Front
What is <b>ElasticNet</b>?

## Back
Compromise between LASSO and Ridge Regression. Fuses the variable selection property of LASSO with the shrinkage of coefficients of correlated predictors from Ridge regression.

Useful when the number of predictors is much bigger than the number of observations \((p>>n)\)
\[R S S+\lambda \sum_{j=1}^{p}\left(\alpha \beta_{j}^{2}+(1-\alpha)\left|\beta_{j}\right|\right)\]
\(\alpha=1\) : Equivalent to Ridge Regression.
