## Note
nid: 1653737250006
model: Basic-02d89-e0e22
tags: bda::04_regression
markdown: false

### Front
How can we test in <b>regression</b> if <b>error terms</b> are
<b>uncorrelated</b>?

### Back
Using the <b>Durbin-Watson-Test</b>. First-order autocorrelation in
residuals time-series \(\quad e_{i}=\rho e_{i-1}+\mu_{t}\) We test
\(H_{0}: \rho=0, H_{1}: \rho \neq 0\) using \[D
W=\frac{\sum_{i=1}^{n-1}\left(e_{i}-e_{i+1}\right)^{2}}{\sum_{i=1}^{n}
e_{i}^{2}}\] DW ranges from 0 to 4 , value of 2 signifies no serial
correlation.
