## Note
nid: 1653728632411
model: Basic-02d89
tags: 04_regression_bda
markdown: false

### Front
How can \(\hat{\beta}_{0}\) and \(\hat{\beta}_{1}\) in \(\hat{y}=\hat{\beta}_{0}+\hat{\beta}_{1} x\) be solved for analytically?

### Back
Least squares coefficient estimates using sample means:
\[\hat{\beta}_{0}=\bar{y}-\hat{\beta}_{1} \bar{x} \\
\hat{\beta_{1}}=\frac{\sum_{i=1}^{n}\left(x_{i}-\bar{x}\right)\left(y_{i}-\bar{y}\right)}{\sum_{i=1}^{n}\left(x_{i}-\bar{x}\right)^{2}}.\]
