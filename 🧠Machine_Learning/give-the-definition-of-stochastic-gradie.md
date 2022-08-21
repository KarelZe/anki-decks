## Note
nid: 1629608780475
model: Basic-d7a3e
tags: 02_linear_classification
markdown: false

### Front
Give the definition of <b>Stochastic Gradient Descent</b>.

### Back
\(l\left(\boldsymbol{x}_{i} ; \boldsymbol{\theta}\right)\)
<div>\(\boldsymbol{\theta}_{t+1}=\boldsymbol{\theta}_{t}-\eta \nabla_{\boldsymbol{\theta}} l\left(\boldsymbol{x}_{i} ; \boldsymbol{\theta}_{t}\right)\)
</div><div>
</div><div>Stochastic gradient descent uses a cheaper approximation by just using the \(i\)-th sample at a time, instead of the entire data set.</div>
