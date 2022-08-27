## Note
nid: 1612263887734
model: Basic-d7a3e-4ce08
tags: ml::09_bayesian_learning, ultra
markdown: false

### Front
Wie berechnet sich der <b>Posterior</b> \(p(\boldsymbol{w} \mid
\boldsymbol{X}, \boldsymbol{y})\) unter Annahme von
Normalverteilung bei <b>Bayesian Linear Regression</b>?
<div>
  Gehen Sie dabei auf den <b>Posterior Mean</b>
  \(\boldsymbol{\mu}_{\boldsymbol{w} \mid \boldsymbol{X},
  \boldsymbol{y}}\) und <b>Posterior Covariance</b>
  \(\boldsymbol{\Sigma}_{\boldsymbol{w} \mid \boldsymbol{X},
  \boldsymbol{y}}\) ein.
</div>

### Back
Posterior
<div>
  \[p(\boldsymbol{w} \mid \boldsymbol{X},
  \boldsymbol{y})=\mathcal{N}\left(\boldsymbol{w} \mid
  \boldsymbol{\mu}_{\boldsymbol{w} \mid \boldsymbol{X},
  \boldsymbol{y}}, \boldsymbol{\Sigma}_{\boldsymbol{w} \mid
  \boldsymbol{X}, \boldsymbol{y}}\right)\]
  <div>
    Posterior mean:
  </div>
  <div>
    \[\boldsymbol{\mu}_{\boldsymbol{w} \mid \boldsymbol{X},
    \boldsymbol{y}}=\left(\boldsymbol{\Phi}^{T}
    \boldsymbol{\Phi}+\sigma_{\boldsymbol{y}}^{2} \lambda
    \boldsymbol{I}\right)^{-1} \boldsymbol{\Phi}^{T}
    \boldsymbol{y}\]
  </div>
  <div>
    Posterior covariance:
  </div>
  <div>
    \[\boldsymbol{\Sigma}_{\boldsymbol{w} \mid \boldsymbol{X},
    \boldsymbol{y}}=\sigma_{\boldsymbol{y}}^{2}\left(\boldsymbol{\Phi}^{T}
    \boldsymbol{\Phi}+\sigma_{\boldsymbol{y}}^{2} \lambda
    \boldsymbol{I}\right)^{-1}\]
  </div>
</div>
