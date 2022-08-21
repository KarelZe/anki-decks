## Note
nid: 1629608541487
model: Basic-d7a3e
tags: 02_linear_classification
markdown: false

### Front
Give the definition of <b>Standard / Batch Gradient Descent</b>.

### Back
\(\frac{1}{n} \sum_{i} l\left(\boldsymbol{x}_{i} ; \boldsymbol{\theta}\right)\)
<div>
</div><div>\(\boldsymbol{\theta}_{t+1}=\boldsymbol{\theta}_{t}-\frac{\eta}{n} \sum_{i} \nabla_{\boldsymbol{\theta}} l\left(\boldsymbol{x}_{i} ; \boldsymbol{\theta}_{t}\right)\)
</div><div>
</div><div>One uses the <b>entire data</b> set to compute gradients and update its parameters!</div>
