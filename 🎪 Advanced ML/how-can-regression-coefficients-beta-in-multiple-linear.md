# Note
```
guid: kF3>hRIk+_
notetype: Basic-d7a3e-4ce08
```

### Tags
```
02_vorlesung
```

## Front
How can regression coefficients \(\beta\) in Multiple Linear Regression Models be estimated? Give the formula.

## Back
\[\min _{\boldsymbol{\beta}}
\sum_{i=1}^{N}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} x_{i j}
\beta_{j}\right)^{2}=\min
_{\boldsymbol{\beta}}\|\mathbf{y}-\mathbf{X} \beta\|^{2}\]
<div>
  Matrix form:
</div>
<div>
  \[\begin{array}{c} \beta=\left(X^{T} X\right)^{-1} X^{T} y \\
  e=y-X^{T} \beta=y-\hat{y} \end{array}\]
</div>
