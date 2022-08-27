## Note
nid: 1644129840078
model: Basic-02d89-e0e22
tags: checklater, ml::02_linear_classification
markdown: false

### Front
Derive the relation between the log-likelihood and the least squares solution for a conditional Gaussian model:
\(p_{\boldsymbol{\theta}}(y \mid \boldsymbol{x})=\mathcal{N}\left(y \mid \boldsymbol{w}^{T} \tilde{\boldsymbol{x}}, \sigma^{2}\right), \quad \boldsymbol{\theta}=\left\{\boldsymbol{w}, \sigma^{2}\right\}\)

### Back
\[
\operatorname{loglik}(\boldsymbol{\theta} ; D)=-\log \sqrt{2 \pi \sigma^{2}}-\sum_{i} \frac{\left(y_{i}-\boldsymbol{w}^{T} \tilde{\boldsymbol{x}}_{i}\right)^{2}}{2 \sigma^{2}}
\]
For obtaining w, only the squared errors matter, i.e.
\[
\operatorname{loglik}(\boldsymbol{\theta} ; D)=\mathrm{const}_{1}-\mathrm{const}_{2} \sum_{i}\left(y_{i}-\boldsymbol{w}^{T} \tilde{\boldsymbol{x}}_{i}\right)^{2}
\]
Hence, the MLE solution is equivalent to the least squares solution. But we can also obtain the variance.
