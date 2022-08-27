## Note
nid: 1653736940859
model: Basic-02d89-e0e22
tags: bda::04_regression
markdown: false

### Front
How can <b>confidence intervals</b> for <b>estimates</b> be
estimated in a <b>regression setting</b>?

### Back
Standard error: measures the average amount that an observation differs from the fitted value
\[S E(\hat{\mu})^{2}=\frac{\sigma^{2}}{n}\]
Computation for estimated regression coefficients
\[\begin{gathered}
S E\left(\hat{\beta}_{0}\right)^{2}=\sigma^{2}\left[\frac{1}{n}+\frac{\bar{x}^{2}}{\sum_{i=1}^{n}\left(x_{i}-\bar{x}\right)^{2}}\right] \\
S E\left(\hat{\beta}_{1}\right)^{2}=\frac{\sigma^{2}}{\sum_{i=1}^{n}\left(x_{i}-\bar{x}\right)^{2}}
\end{gathered}\]
SE used to compute \(95 \%\) confidence intervals for parameter estimates (given some assumptions)
\[\hat{\beta}_{0} \approx \pm 2 \cdot S E\left(\hat{\beta}_{0}\right) \quad \hat{\beta}_{1} \approx \pm 2 \cdot S E\left(\hat{\beta}_{1}\right)\]
\(\sigma^{2}\) is estimated by residual standard error \(\quad R S E=\sqrt{R S S /(n-p-1)}\)
