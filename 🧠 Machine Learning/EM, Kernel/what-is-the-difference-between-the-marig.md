## Note
nid: 1631075636549
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction
markdown: false

### Front
What is the difference between the mariginal distribution of a continous and a discrete latent variable?

### Back
Let \(\boldsymbol{x}\) be an observed variable and
\(\boldsymbol{z}\) be an unobserved variable.
<div>
  \(\underbrace{p(\boldsymbol{x} \mid \boldsymbol{\theta})=\sum_{z}
  p(\boldsymbol{x}, z \mid \boldsymbol{\theta})}_{\text {discrete
  latent variable }}, \quad \underbrace{p(\boldsymbol{x} \mid
  \boldsymbol{\theta})=\int_{\boldsymbol{z}} p(\boldsymbol{x},
  \boldsymbol{z} \mid \boldsymbol{\theta}) d \boldsymbol{z}}_{\text
  {continuous latent variable }}\)
</div>
