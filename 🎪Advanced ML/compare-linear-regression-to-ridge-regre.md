## Note
nid: 1621070081109
model: Basic-b122e
tags: 06_lecture
markdown: false

### Front
Compare <b>Linear Regression</b> to <b>Ridge Regression</b>

### Back
Recall that the least squares procedure estimates \(\beta_{0}, \beta_{1}, \ldots, \beta_{p}\) using the values to minimize
<div>
</div><div>\[\operatorname{RSS}=\sum_{i=1}^{n}\left(y_{i}- \hat{y_{i}}\right)^{2} = \sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j} x_{i j}\right)^{2}\]</div><div>
</div><div>
</div><div>In contrast, the ridge regression coefficients estimates \(\hat{\beta^R}\) are the values that minimize</div><div>\[\sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j} x_{i j}\right)^{2}+\lambda \sum_{j=1}^{p} \beta_{j}^{2}=\operatorname{RSS}+\lambda \sum_{j=1}^{p} \beta_{j}^{2},\]

</div><div>where \(\lambda \geq 0\) is a tuning parameter, to be determined separately.
</div>
