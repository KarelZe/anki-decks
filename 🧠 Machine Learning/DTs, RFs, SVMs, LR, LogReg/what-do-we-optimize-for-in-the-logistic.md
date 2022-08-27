## Note
nid: 1629612401333
model: Basic-d7a3e-4ce08
tags: ml::02_linear_classification
markdown: false

### Front
What do we optimize for in the <b>logistic regression</b> case?

### Back
<div>
  We optimize the cross-entropy loss given by:
</div>\(\operatorname{argmax}_{\tilde{\boldsymbol{w}}} \log
\operatorname{lik}(\tilde{\boldsymbol{w}},
D)=\operatorname{argmax}_{\tilde{\boldsymbol{w}}} \sum_{i} c_{i}
\log \sigma\left(\tilde{\boldsymbol{w}}^{T}
\tilde{\boldsymbol{x}}_{i}\right)+\left(1-c_{i}\right) \log
\left(1-\sigma\left(\tilde{\boldsymbol{w}}^{T}
\tilde{\boldsymbol{x}}_{i}\right)\right)\)
<div>
  Note that \(c_{i}\) hold the class labels. We try to find the
  best estitmates for \(\tilde{\boldsymbol{w}}\).
</div>
