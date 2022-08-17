## Note
nid: 1629782387083
model: Basic-d7a3e
tags: 06_em_for_dim_reduction, ultra
markdown: false

### Front
What is the drawback of the <b>EM algorithm</b>? How can it be
fixed?

### Back
EM assumes that E-step can set the KL divergence to 0.
<div>
  However, this is only possible if \(z\) is discrete or if we have
  linear Gaussian models.
</div>
<div>
  <b>Variational Bayes</b> approximate the posterior where a KL
  will be \(> 0\) after E-Step.
</div>
