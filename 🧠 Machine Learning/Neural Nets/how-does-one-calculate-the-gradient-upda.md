## Note
nid: 1629369634852
model: Basic-d7a3e-4ce08
tags: checklater, ml::10_neural_networks
markdown: false

### Front
How does one calculate the gradient update with SGD with momentum term?

### Back
<div>
  \(\boldsymbol{\theta}_{k+1}=\boldsymbol{\theta}_{k}-\eta
  \boldsymbol{m}_{k+1}\)
</div>
<div>
  where \(m\) can be calculated using the geometric average
  (constant \(\gamma\)) or adaptive \(\gamma\) using the
</div>
<div>
  arithmetic average.
</div>
<div>
  Geometric average (constant \(\gamma\)):
</div>
<div>
  \(\boldsymbol{m}_{k}=(1-\gamma) \sum_{i=1}^{k} \gamma^{k-i}
  \boldsymbol{g}_{i}\)
</div>
<div>
  Arithmetic average \(\left(\gamma_{k}=(k-1) / k\right)\):
</div>
<div>
  \(\boldsymbol{m}_{k}=\frac{1}{k} \sum_{i=1}^{k}
  \boldsymbol{g}_{i}\)
</div>
<div><img src="SGD.jpg"></div>
