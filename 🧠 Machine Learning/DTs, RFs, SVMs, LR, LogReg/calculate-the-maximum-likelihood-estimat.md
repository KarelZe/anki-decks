## Note
nid: 1629475688077
model: Basic-d7a3e-4ce08
tags: ml::02_linear_classification
markdown: false

### Front
Calculate the Maximum Likelihood Estimation (MLE) given a training data \(D=\left\{\left(x_{i}, y_{i}\right)\right\}_{i=1 \ldots N}\) iid. from the data distribution \(p_{\text {data }}\).

### Back
Let \(p_{\boldsymbol{\theta}}(x, y)\) be a family of distributions
parametrized by \(\boldsymbol{\theta} \in \Theta\).
<div>
  \(\operatorname{lik}(\boldsymbol{\theta} ; D)=\prod_{i}
  p_{\boldsymbol{\theta}}\left(x_{i}, y_{i}\right)\)
</div>
