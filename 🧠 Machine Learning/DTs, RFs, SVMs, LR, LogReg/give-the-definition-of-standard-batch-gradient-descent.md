# Note
```
guid: NgC~/bLiUX
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::02_linear_classification
```

## Front
Give the definition of <b>Standard / Batch Gradient Descent</b>.

## Back
\(\frac{1}{n} \sum_{i} l\left(\boldsymbol{x}_{i} ;
\boldsymbol{\theta}\right)\)
<div>
  \(\boldsymbol{\theta}_{t+1}=\boldsymbol{\theta}_{t}-\frac{\eta}{n}
  \sum_{i} \nabla_{\boldsymbol{\theta}} l\left(\boldsymbol{x}_{i} ;
  \boldsymbol{\theta}_{t}\right)\)
</div>
<div>
  One uses the <b>entire data</b> set to compute gradients and
  update its parameters!
</div>
