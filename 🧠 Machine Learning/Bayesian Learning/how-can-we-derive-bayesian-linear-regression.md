# Note
```
guid: P8O/VExj_V
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::09_bayesian_learning
```

## Front
How can we derive <b>Bayesian Linear Regression</b>?

## Back
<div>
  Given:
</div>
<div>
  Likelihood (conditional): \(p(\boldsymbol{y} \mid \boldsymbol{X},
  \boldsymbol{w})=\mathcal{N}\left(\boldsymbol{y} \mid
  \boldsymbol{\Phi} \boldsymbol{w}, \sigma^{2}
  \boldsymbol{I}\right)\) Prior (marginal): \(\quad
  p(\boldsymbol{w})=\mathcal{N}\left(\boldsymbol{w} \mid
  \mathbf{0}, \lambda^{-1} \boldsymbol{I}\right)\) Dimensions:
  \(\quad \boldsymbol{w} \in \mathbb{R}^{d}\) and \(\boldsymbol{Y}
  \in \mathbb{R}^{N \times 1}\), typically \(d \ll N\)
</div>
<div>
  We can obtain the Posterior \(p(\boldsymbol{w} \mid
  \boldsymbol{X}, \boldsymbol{y})=\mathcal{N}\left(\boldsymbol{w}
  \mid \boldsymbol{\mu}_{\boldsymbol{w} \mid \boldsymbol{X},
  \boldsymbol{y}}, \boldsymbol{\Sigma}_{\boldsymbol{w} \mid
  \boldsymbol{X}, \boldsymbol{y}}\right)\):
</div>
<div>
  Posterior mean: \(\quad \boldsymbol{\mu}_{\boldsymbol{w} \mid
  \boldsymbol{X}, \boldsymbol{y}}=\left(\boldsymbol{\Phi}^{T}
  \boldsymbol{\Phi}+\sigma_{\boldsymbol{y}}^{2} \lambda
  \boldsymbol{I}\right)^{-1} \boldsymbol{\Phi}^{T} \boldsymbol{y}\)
  Posterior covariance: \(\boldsymbol{\Sigma}_{\boldsymbol{w} \mid
  \boldsymbol{X},
  \boldsymbol{y}}=\sigma_{\boldsymbol{y}}^{2}\left(\boldsymbol{\Phi}^{T}
  \mathbf{\Phi}+\sigma_{\boldsymbol{y}}^{2} \lambda
  \boldsymbol{I}\right)^{-1}\)
</div>We can sample form the posterior: \(\boldsymbol{w}_{i} \sim
p(\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y})\)
<div>
  Each \(\boldsymbol{w}_{i}\) represents a function \[
  f_{i}(\boldsymbol{x})=\boldsymbol{w}_{i}^{T} \phi(\boldsymbol{x})
  \]
  <div>
    Predictive distribution:
  </div>
  <div>
    \(\begin{aligned} p\left(y^{*} \mid x^{*}, \boldsymbol{X},
    \boldsymbol{y}\right) &=\int p\left(y^{*} \mid
    \boldsymbol{w}, \boldsymbol{x}^{*}\right) p(\boldsymbol{w} \mid
    \boldsymbol{X}, \boldsymbol{y}) d \boldsymbol{w} \\ &=\int
    \mathcal{N}\left(y_{*} \mid \boldsymbol{\phi}_{*}^{T}
    \boldsymbol{w}, \sigma_{y}^{2}\right)
    \mathcal{N}\left(\boldsymbol{w} \mid
    \boldsymbol{\mu}_{\boldsymbol{w} \mid \boldsymbol{X}, y},
    \boldsymbol{\Sigma}_{\boldsymbol{w} \mid \boldsymbol{X},
    y}\right) d \boldsymbol{w} \end{aligned}\)
  </div>
  <div>
    Using Gaussian propagation we obtain:
  </div>
  <div>
    Predictive mean:
  </div>
  <div>
    \(\mu\left(\boldsymbol{x}^{*}\right)=\boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)^{T}\left(\mathbf{\Phi}^{T}
    \mathbf{\Phi}+\lambda \sigma_{\boldsymbol{y}}^{2}
    \boldsymbol{I}\right)^{-1} \mathbf{\Phi}^{T} \boldsymbol{y}\)
  </div>
  <div>
    Predictive variance:
  </div>
  <div>
    \(\sigma^{2}\left(\boldsymbol{x}^{*}\right)=\sigma_{\boldsymbol{y}}^{2}\left(1+\boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)^{T}\left(\mathbf{\Phi}^{T}
    \boldsymbol{\Phi}+\lambda \sigma_{\boldsymbol{y}}^{2}
    \boldsymbol{I}\right)^{-1}
    \boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)\right)\)
  </div>
</div>
