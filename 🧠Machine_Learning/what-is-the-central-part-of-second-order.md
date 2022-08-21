## Note
nid: 1629432660468
model: Basic-d7a3e
tags: 10_neural_networks, checklater
markdown: false

### Front
What is the central part of <b>second order optimization methods</b>?

### Back
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
