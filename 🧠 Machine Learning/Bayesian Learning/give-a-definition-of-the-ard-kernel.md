## Note
nid: 1631168314052
model: Basic-d7a3e-4ce08
tags: ml::09_bayesian_learning
markdown: false

### Front
Give a definition of the <b>ARD kernel</b>.

### Back
\(k\left(\boldsymbol{x}_{i}, \boldsymbol{x}_{j}\right)=\lambda^{-1}
\exp \left(-\sum_{k=1}^{d} \frac{\left(x_{i, k}-x_{j,
k}\right)^{2}}{2 l_{k}^{2}}\right)+\delta_{i j} \sigma_{y}^{2},\)
<div>
  where \(\lambda\) is the prior precision of the weight vector,
  \(\sigma^2\) is the noise variance if \(i=j\), otherwise 0.
  \(\delta\) acts like a mask, and \(l_k\) the length scale of
  dimension \(k\).
</div>
