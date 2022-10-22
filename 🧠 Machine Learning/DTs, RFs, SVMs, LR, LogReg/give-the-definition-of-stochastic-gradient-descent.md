# Note
```
guid: s|7Q_N_^z)
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::02_linear_classification
```

## Front
Give the definition of <b>Stochastic Gradient Descent</b>.

## Back
\(l\left(\boldsymbol{x}_{i} ; \boldsymbol{\theta}\right)\)
<div>
  \(\boldsymbol{\theta}_{t+1}=\boldsymbol{\theta}_{t}-\eta
  \nabla_{\boldsymbol{\theta}} l\left(\boldsymbol{x}_{i} ;
  \boldsymbol{\theta}_{t}\right)\)
</div>
<div>
  Stochastic gradient descent uses a cheaper approximation by just
  using the \(i\)-th sample at a time, instead of the entire data
  set.
</div>
