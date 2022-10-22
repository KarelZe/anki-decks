# Note
```
guid: Bjlo&6P]-V
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
Give the definition of Adaptive Momentum (Adam).

## Back
\(\begin{aligned} \boldsymbol{g}_{k} &=\nabla_{\boldsymbol{\theta}} \mathcal{L}\left(\boldsymbol{\theta}_{k}\right) \\ \boldsymbol{v}_{k+1, i} &=\gamma_{1} \boldsymbol{v}_{k, i}+\left(1-\gamma_{1}\right) \boldsymbol{g}_{k, i}^{2} \quad \ldots \text { gradient norm } \\ \boldsymbol{m}_{k+1} &=\gamma_{2} \boldsymbol{m}_{k}+\left(1-\gamma_{2}\right) \boldsymbol{g}_{k} \quad \ldots \text { momentum } \\ \boldsymbol{\theta}_{k+1, i} &=\boldsymbol{\theta}_{k, i}-\underbrace{\frac{\eta c_{2}(k)}{\sqrt{c_{1}(k) \boldsymbol{v}_{k+1, i}+\epsilon}}}_{\text {norm-based scaling }} \\ & \boldsymbol{m}_{k+1, i} \end{aligned}\)
