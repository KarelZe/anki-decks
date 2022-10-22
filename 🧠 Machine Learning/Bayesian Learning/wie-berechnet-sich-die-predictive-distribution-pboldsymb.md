# Note
```
guid: FDh(ftJw8q
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::09_bayesian_learning
ultra
```

## Front
Wie berechnet sich die <b>Predictive Distribution</b>
\(p(\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y})\) unter
Annahme von Normalverteilung bei <b>Bayesian Linear Regression</b>?

## Back
\[\begin{aligned} p\left(y^{*} \mid x^{*}, \boldsymbol{X},
\boldsymbol{y}\right) &=\int p\left(y^{*} \mid \boldsymbol{w},
\boldsymbol{x}^{*}\right) p(\boldsymbol{w} \mid \boldsymbol{X},
\boldsymbol{y}) d \boldsymbol{w} \\ &=\int
\mathcal{N}\left(y_{*} \mid \boldsymbol{\phi}_{*}^{T}
\boldsymbol{w}, \sigma_{\boldsymbol{y}}^{2}\right)
\mathcal{N}\left(\boldsymbol{w} \mid
\boldsymbol{\mu}_{\boldsymbol{w} \mid \boldsymbol{X},
\boldsymbol{y}}, \boldsymbol{\Sigma}_{\boldsymbol{w} \mid
\boldsymbol{X}, y}\right) d \boldsymbol{w} \end{aligned}\]
<div>
  <b>Mittelwert:</b>
  \[\mu\left(\boldsymbol{x}^{*}\right)=\phi\left(\boldsymbol{x}^{*}\right)^{T}\left(\boldsymbol{\Phi}^{T}
  \boldsymbol{\Phi}+\lambda \sigma_{y}^{2}
  \boldsymbol{I}\right)^{-1} \boldsymbol{\Phi}^{T} \boldsymbol{y}\]
</div>
<div>
  <b>Varianz:</b>
</div>
<div>
  \[\quad
  \sigma^{2}\left(x^{*}\right)=\sigma_{y}^{2}\left(1+\phi\left(\boldsymbol{x}^{*}\right)^{T}\left(\boldsymbol{\Phi}^{T}
  \boldsymbol{\Phi}+\lambda \sigma_{y}^{2}
  \boldsymbol{I}\right)^{-1}
  \boldsymbol{\phi}\left(\boldsymbol{x}^{*}\right)\right)\]
</div>
<div>
  <b>Intuition:</b>
</div>
<div>
  Mittelwert ist derselbe wie bei ridge regression. Jedoch hängt
  die Varianz von \(x^{*}\) ab.
</div>
