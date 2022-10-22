# Note
```
guid: zr~H]K?e-l
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::06_lecture
```

## Front
Compare <b>Linear Regression</b> to <b>Ridge Regression</b>

## Back
Recall that the least squares procedure estimates \(\beta_{0},
\beta_{1}, \ldots, \beta_{p}\) using the values to minimize
<div>
  \[\operatorname{RSS}=\sum_{i=1}^{n}\left(y_{i}-
  \hat{y_{i}}\right)^{2} =
  \sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j} x_{i
  j}\right)^{2}\]
</div>
<div>
  In contrast, the ridge regression coefficients estimates
  \(\hat{\beta^R}\) are the values that minimize
</div>
<div>
  \[\sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j}
  x_{i j}\right)^{2}+\lambda \sum_{j=1}^{p}
  \beta_{j}^{2}=\operatorname{RSS}+\lambda \sum_{j=1}^{p}
  \beta_{j}^{2},\]
</div>
<div>
  where \(\lambda \geq 0\) is a tuning parameter, to be determined
  separately.
</div>
