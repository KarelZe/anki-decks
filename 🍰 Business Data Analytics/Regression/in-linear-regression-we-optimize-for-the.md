## Note
nid: 1653737754733
model: Basic-02d89-e0e22
tags: bda::04_regression
markdown: false

### Front
In <b>linear regression</b> we optimize for the \(RSS\). Derive the
<b>equation</b> to obtain the <b>predition vector</b> in <b>matrix
notation</b>.

### Back
Minimize residual sum of squares:
\[R S S=\sum_{i=1}^{n}\left(y_{i}-\hat{y}_{i}\right)^{2}=(Y-X \beta)^{\prime}(Y-X \beta)\]
Computing the derivative results in parameter estimation
\[\hat{\beta}=\left(X^{\prime} X\right)^{-1} X^{\prime} Y\]
Therefore, the prediction vector is given by
\[\hat{Y}=X \hat{\beta}=X\left(X^{\prime} X\right)^{-1} X^{\prime} Y=H Y\]
Hat matrix describes the influence of each observation on the fitted value.

\(X\left(X^{\prime} X\right)^{-1}\) is the pseudo inverse / hat matrix \(H\)
