# Note
```
guid: bxMaI5KqNV
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::06_em_for_dim_reduction
ultra
```

## Front
<p>Wie funktioniert der <b>EM-Algorithmus</b> für <b>Mixture of
Gaussians</b>?

## Back
<p><b>Initialize:</b> Mixture Components + Mixture coefficinents e.
g. with k-means for the component means and some initial covariance
<p><b>Repeat until covariance:</b>
<p><b>Expecation step:</b> Compute responsibilities (degree to
which a component contributes to the model)
<p>\(q_{i k}=\frac{\pi_{k} \mathcal{N}\left(\boldsymbol{x}_{i} \mid
\boldsymbol{\mu}_{k},
\boldsymbol{\Sigma}_{k}\right)}{\sum_{j=1}^{K} \pi_{j}
\mathcal{N}\left(\boldsymbol{x}_{i} \mid \boldsymbol{\mu}_{j},
\boldsymbol{\Sigma}_{j}\right)}=p\left(z=k \mid
\boldsymbol{x}_{i}\right)\)
<p><b>Maximization step:</b> Update coefficients, components means
and component variance
<p>\(\pi_{k}=\frac{\sum_{i} q_{i k}}{N}\)
<p>\(\boldsymbol{\mu}_{k}=\frac{\sum_{i} q_{i k}
\boldsymbol{x}_{i}}{\sum_{i} q_{i k}}\)
<p>\(\boldsymbol{\Sigma}_{k}=\frac{\sum_{i} q_{i
k}\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}_{k}\right)\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}_{k}\right)^{T}}{\sum_{i}
q_{i k}}\)
