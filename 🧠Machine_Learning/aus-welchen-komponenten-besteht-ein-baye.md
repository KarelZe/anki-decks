## Note
nid: 1612261686149
model: Basic-d7a3e
tags: 09_bayesian_learning, ultra
markdown: false

### Front
Aus welchen <b>Komponenten </b>besteht ein <b>Bayesian Linear Regression</b>-Modell? Was ist jeweils die Bedeutung?

### Back
\[p(\boldsymbol{w} \mid \boldsymbol{X},
\boldsymbol{y})=\frac{p(\boldsymbol{y} \mid \boldsymbol{X},
\boldsymbol{w}) p(\boldsymbol{w})}{p(\boldsymbol{y} \mid
\boldsymbol{X})}=\frac{p(\boldsymbol{y} \mid \boldsymbol{X},
\boldsymbol{w}) p(\boldsymbol{w})}{\int p(\boldsymbol{y} \mid
\boldsymbol{X}, \boldsymbol{w}) p(\boldsymbol{w}) d
\boldsymbol{w}}\]
<div>
  Posterior of Model Parameters: \(p(w \mid y, X)\)
</div>
<div>
  Likelihood of the Response Features given the Model and
  Predictors Features:
</div>
<div>
  \[p(\boldsymbol{y} \mid \boldsymbol{X}, \boldsymbol{w})=\prod_{i}
  \mathcal{N}\left(y_{i} \mid \boldsymbol{w}^{T}
  \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right),
  \sigma^{2}\right)=\underbrace{\mathcal{N}\left(\boldsymbol{y}
  \mid \boldsymbol{\Phi} \boldsymbol{w}, \sigma^{2}
  \boldsymbol{I}\right)}_{\text {Multivariate distribution }},\]
</div>
<div>
  where \(\boldsymbol{w}^{T}\) is a linear model, \(\sigma^2\) is
  the noise variance and \(\boldsymbol{\Phi}\) the feature matrix.
</div>
<div>
  Prior Probability of Model Parameters: \(p(w)=\mathcal{N}\left(w
  \mid \mathbf{0}, \lambda^{-1} \boldsymbol{I}\right)\)
</div>
<div>
  Evidence / Normalizer: \(p(y, X)\)
</div>
