## Note
nid: 1629186922515
model: Basic-d7a3e-4ce08
tags: checklater, ml::10_neural_networks
markdown: false

### Front
How do we optimize the objective function of a neural net on an abstract level?

### Back
\(\mathcal{L}(\boldsymbol{\theta}, \mathcal{D})=\sum_{i=1}^{N}
l\left(\boldsymbol{x}_{i}, \boldsymbol{\theta}\right)+\lambda
\operatorname{penalty}(\boldsymbol{\theta})\),
<div>
  where \(\theta\) is the weight space that hold for all the
  weights or bias of the network of all layers for one coordinate
  <div>
    \(\boldsymbol{\theta}=\left\{\mathbf{W}^{(L)}, \ldots,
    \mathbf{W}^{(1)}, \mathbf{b}^{(L)}, \ldots,
    \mathbf{b}^{(1)}\right\}\)
  </div>
</div>
<div>
  We need to compute the following partial derivatives:
</div>
<div>
  Layer weight matrices: \(\frac{\partial \mathcal{L}}{\partial
  \mathbf{W}^{(l)}}\) Layer bias vectors: \(\quad \frac{\partial
  \mathcal{L}}{\partial \mathbf{b}^{(l)}}\)
</div>
<div>
  This can be done recursively using the chain rule, as each
  weights depend on the previous.
</div>
