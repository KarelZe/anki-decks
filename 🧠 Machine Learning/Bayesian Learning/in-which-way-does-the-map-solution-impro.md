## Note
nid: 1630657141214
model: Basic-d7a3e-4ce08
tags: ml::09_bayesian_learning, ultra
markdown: false

### Front
In which way does the MAP solution improve on the standard Linear Regression?

### Back
\(\boldsymbol{w}_{\mathrm{MAP}}=\left(\boldsymbol{\Phi}^{T}
\boldsymbol{\Phi}+\lambda \sigma^{2} \boldsymbol{I}\right)^{-1}
\boldsymbol{\Phi}^{T} \boldsymbol{y}\)
<div>
  The MAP solution includes two additional parameters. \(\lambda\)
  to set the importance of the prior and \(\sigma^2\) to set the
  uncertainty in the training data.
</div>
