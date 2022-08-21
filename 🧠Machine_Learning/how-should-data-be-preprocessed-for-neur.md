## Note
nid: 1629200973971
model: Basic-d7a3e
tags: 10_neural_networks
markdown: false

### Front
How should data be preprocessed for Neural Nets?

### Back
Normalize data:
<div>
  <div>
    \(\tilde{\boldsymbol{x}}=(\boldsymbol{x}-\boldsymbol{\mu})
    \oslash \boldsymbol{\sigma}\)
  </div>
  <div>
    Mean \(\mu\), standard deviation \(\sigma\), element-wise
    divison (similar to Hardamard product).
  </div>
  <div>
    \(\tilde{\boldsymbol{x}}\) is standardized with zero mean and
    unit variance.
  </div>
</div>
