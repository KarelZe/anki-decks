## Note
nid: 1620317751771
model: Basic-b122e
tags: 05_vorlesung
markdown: false

### Front
How does one calculculate <b>MSE</b> for all folds in <b>K-Fold Cross-Validation</b>

### Back
Let the \(K\) parts be \(C_{1}, C_{2}, \ldots, C_{K}\), where
\(C_{K}\) denotes the indices of the observations in part \(k\).
There are \(n_{k}\) observations in part \(k\) : if \(n\) is a
multiple of \(K\), then \(n_{k}=n / K\).
<div>
  If \(\hat{y}_{i}\) is the fit for observation \(i,
  \text{MSE}_{k}=\sum_{i \epsilon
  C_{k}}\left(y_{i}-\hat{y}_{i}\right)^{2} / n_{k}\) then \[C
  V_{\kappa}=\sum_{k=1}^{K} \frac{n_{k}}{n} M S E_{k}\]
</div>
