## Note
nid: 1629609228926
model: Basic-d7a3e
tags: 02_linear_classification, checklater
markdown: false

### Front
Given the training data \(D=\left\{\left(x_{i},
y_{i}\right)\right\}_{i=1 \ldots N}\) iid. from the data
distribution \(p_{\text {data }}\) .
<div>
  Let \(p_{\theta}(y \mid x)\) be a family of distributions
  parametrized by \(\boldsymbol{\theta} \in \Theta\).
</div>
<div>
  How could the <b>conditional log-likelihood</b> for this
  distribution be calculated?
</div>

### Back
\(\operatorname{loglik}(\boldsymbol{\theta} ; D)=\sum_{i} \log p_{\boldsymbol{\theta}}\left(y_{i} \mid x_{i}\right)\)
