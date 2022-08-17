## Note
nid: 1653731398608
model: Basic-02d89
tags: 04_regression_bda
markdown: false

### Front
Give the <b>objective</b> of <b>Ridge regression</b> and <b>LASSO
regression</b>.

### Back
<b>Ridge regression:</b>
\[\sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j} x_{i
j}\right)^{2}+\lambda \sum_{j=1}^{p} \beta_{j}^{2}\] <b>Lasso
regression:</b>
\[\sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{j} x_{i
j}\right)^{2}+\lambda \sum_{j=1}^{p}\left|\beta_{j}\right|\] As a
<b>constrained optimization problem</b>: \[\begin{aligned}
&\min _{\beta}
\sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{i} x_{i
j}\right)^{2} \text { subject to }
\sum_{j=1}^{p}\left|\beta_{j}\right| \leq s \\ &\min _{\beta}
\sum_{i=1}^{n}\left(y_{i}-\beta_{0}-\sum_{j=1}^{p} \beta_{i} x_{i
j}\right)^{2} \text { subject to } \sum_{j=1}^{p} \beta_{j}^{2}
\leq s \end{aligned}\]
