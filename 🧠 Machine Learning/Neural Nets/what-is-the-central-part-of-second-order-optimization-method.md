# Note
```
guid: v5HG5UL%E4
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
What is the central part of <b>second order optimization
methods</b>?

## Back
Usage of taylor approximization:
<div>
  \[ \mathcal{L}(\boldsymbol{\theta}) \approx
  \mathcal{L}\left(\boldsymbol{\theta}_{0}\right)+\left(\boldsymbol{\theta}-\boldsymbol{\theta}_{0}\right)^{T}
  \boldsymbol{g}+\left(\boldsymbol{\theta}-\boldsymbol{\theta}_{0}\right)^{T}
  \boldsymbol{H}\left(\boldsymbol{\theta}-\boldsymbol{\theta}_{0}\right)
  \] With \(\boldsymbol{g}=\nabla_{\boldsymbol{\theta}}
  \mathcal{L}(\boldsymbol{\theta})\) is the gradient and
  \(\boldsymbol{H}=\nabla_{\boldsymbol{\theta}}^{2}
  \mathcal{L}(\boldsymbol{\theta})\) is the Hessian matrix.
</div>
<div>
  Solving for \(\theta\) yields the Newton update.
</div>
<div>
  \(\boldsymbol{\theta}^{*}=\boldsymbol{\theta}_{0}-\boldsymbol{H}^{-1}
  \boldsymbol{g}\)
</div>
