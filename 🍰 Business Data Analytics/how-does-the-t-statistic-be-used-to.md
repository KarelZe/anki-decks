## Note
nid: 1653738055139
model: Basic-02d89
tags: 04_regression_bda
markdown: false

### Front
How does the \(t\)-Statistic be used to test if a coefficient is non-zero?

### Back
SE used for hypothesis tests if a coefficient is non-zero \(\left(H_{0}: \beta_{1}=0 \quad\right)\), meaning there is a (linear) relationship between predictor and response using \(t\)-statistic
\[t=\frac{\hat{\beta_{1}}-0}{S E\left(\hat{\beta}_{1}\right)}\]
Measures the number of standard errors between coefficient and 0.

\(p\)-value: probability of observing values \(>=|t|\) assuming \(\beta_{1}=0\).
Interpretation of \(p\)-value: given a small value of \(p\) we can reject \(H_{0}\).
