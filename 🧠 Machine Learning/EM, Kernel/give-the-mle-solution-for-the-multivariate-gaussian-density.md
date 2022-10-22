# Note
```
guid: mVp%yv+iuZ
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::06_em_for_dim_reduction
```

## Front
Give the MLE solution for the <b>multivariate Gaussian density
function</b>.

## Back
ML estimation for a Gaussian
<div>
  \(\boldsymbol{\mu},
  \boldsymbol{\Sigma}=\operatorname{argmax}_{\boldsymbol{\theta}}
  \log \operatorname{lik}(\boldsymbol{\theta} ; D)=\sum_{i=1}^{N}
  \log \mathcal{N}\left(\boldsymbol{x}_{i} \mid \boldsymbol{\mu},
  \boldsymbol{\Sigma}\right)\)
</div>
<div>
  Take the partial derivatives and set it to 0
</div>
<div>
  \(\frac{\partial \log \operatorname{like}(\boldsymbol{\theta} ;
  \mathcal{D})}{\partial \boldsymbol{\mu}}=\mathbf{0}\)
</div>
<div>
  \(\frac{\partial \log \operatorname{like}(\boldsymbol{\theta} ;
  \mathcal{D})}{\partial \boldsymbol{\Sigma}}=\mathbf{0}\)
</div>
<div>
  Which leads to the closed form solution
</div>
<div>
  \(\mu=\frac{1}{N} \sum_{i=1}^{N} \boldsymbol{x}_{i}\)
</div>
<div>
  \(\boldsymbol{\Sigma}=\frac{1}{N}
  \sum_{i=1}^{N}\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}\right)\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}\right)^{T}\)
</div>
