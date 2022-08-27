## Note
nid: 1609155707960
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction, ultra
markdown: false

### Front
<p>Wie zerlegt der EM Algorithmus den marginal likelihood?

### Back
<p>\[ \log p(\boldsymbol{x} \mid \boldsymbol{\theta})=\sum_{z} q(z)
\log \frac{p(\boldsymbol{x}, z \mid
\boldsymbol{\theta})}{q(z)}+\sum_{z} q(z) \log \frac{q(z)}{p(z \mid
x)} \]
