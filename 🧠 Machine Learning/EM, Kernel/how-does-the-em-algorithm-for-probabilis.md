## Note
nid: 1610226042598
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction, ultra
markdown: false

### Front
<p>How does the EM algorithm for probabilistic PCA work?

### Back
<p><b>Initialize</b>: Use average of \(\boldsymbol{x}\) for
\(\boldsymbol{\mu}\), random matrix \(\boldsymbol{W}\)
<p>Repeat until convergence:
<p><b>Expectation step:</b>
<p>Compute posterior mean and covariance:
<p>\(\boldsymbol{\mu}_{\boldsymbol{z} \mid
\boldsymbol{x}_{i}}=\left(\boldsymbol{W}^{T}
\boldsymbol{W}+\sigma^{2} \boldsymbol{I}\right)^{-1}
\boldsymbol{W}^{T} \boldsymbol{x}_{i}, \quad
\boldsymbol{\Sigma}_{\boldsymbol{z} \mid
\boldsymbol{x}_{i}}=\sigma^{2}\left(\boldsymbol{W}^{T}
\boldsymbol{W}+\sigma^{2} \boldsymbol{I}\right)^{-1}\)
<p>Generate latent samples:
<p>\(\boldsymbol{z}_{i} \sim
\mathcal{N}\left(\boldsymbol{\mu}_{\boldsymbol{z} \mid
\boldsymbol{x}_{i}}, \mathbf{\Sigma}_{z \mid
\boldsymbol{x}_{i}}\right)\)
<p><b>Maximization step:</b> Update \(\boldsymbol{W},
\boldsymbol{\mu}\) and \(\sigma^{2}\)
<p>\(\left[\begin{array}{c}\boldsymbol{\mu} \\
\boldsymbol{W}\end{array}\right]=\left(\boldsymbol{Z}^{T}
\boldsymbol{Z}\right)^{-1} \boldsymbol{Z}^{T} \boldsymbol{X}, \quad
\sigma^{2}=\frac{1}{n d} \sum_{i=1}^{n} \sum_{k=1}^{d}\left(y_{i
k}-x_{i k}\right)^{2}\)
