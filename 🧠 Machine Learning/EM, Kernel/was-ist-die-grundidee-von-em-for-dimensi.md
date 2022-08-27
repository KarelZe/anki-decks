## Note
nid: 1610226041937
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction, ultra
markdown: false

### Front
<p>Was ist die Grundidee von <b>EM</b> for <b>Dimensionality
Reductio</b>n (sg. <b>probabilistic PCA</b>)?

### Back
<p>Introduce a latent variable model to relate a \(D\)-dimensional
observation vector to a corresponding \(M\)-dimensional gaussian
latent variable (with \(M < D\))
<p>\[ \boldsymbol{x}=\boldsymbol{W}
\boldsymbol{z}+\boldsymbol{\mu}+\boldsymbol{\epsilon} \]
<p>\(\boldsymbol{z}\) is a \(d\)-latent variable (our low
dimensional representation) \(\boldsymbol{W}\) is a \(D \times M\)
matrix relating the latent space \(z\) with the original space
\(x\) \(\boldsymbol{\mu}\) is a constant offset vector
<p>\(\boldsymbol{\epsilon}\) is a d-dimensional Gaussian noise
vector \(\boldsymbol{\epsilon} \sim \mathcal{N}\left(\mathbf{0},
\sigma^{2} \boldsymbol{I}\right)\)
