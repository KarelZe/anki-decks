## Note
nid: 1629122797868
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction
markdown: false

### Front
Wie bestimmt man die Parameter einer Gauß-Verteilung mittels einem <b>Maximum Likelihood Ansatz</b>?<div>
</div><div>\[\boldsymbol{\mu}, \boldsymbol{\Sigma}=\operatorname{argmax}_{\boldsymbol{\theta}} \log \operatorname{lik}(\boldsymbol{\theta} ; D)=\sum_{i=1}^{N} \log \mathcal{N}\left(\boldsymbol{x}_{i} \mid \boldsymbol{\mu}, \boldsymbol{\Sigma}\right)\]
</div>

### Back
Indem man die partielle Ableitung bildet und mit 0 gleichsetzt:<div>
</div><div>\(\frac{\partial \log \operatorname{like}(\boldsymbol{\theta} ; \mathcal{D})}{\partial \boldsymbol{\mu}}=\mathbf{0}\)
</div><div>
</div><div>\(\frac{\partial \log \operatorname{like}(\boldsymbol{\theta} ; \mathcal{D})}{\partial \boldsymbol{\Sigma}}=\mathbf{0}\)
</div><div>
</div><div>Which yields the closed form solution:</div><div>
</div><div>\(\boldsymbol{\mu}=\frac{1}{N} \sum_{i=1}^{N} \boldsymbol{x}_{i}\)
</div><div>
</div><div>\(\mathbf{\Sigma}=\frac{1}{N} \sum_{i=1}^{N}\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}\right)\left(\boldsymbol{x}_{i}-\boldsymbol{\mu}\right)^{T}\)
</div>
