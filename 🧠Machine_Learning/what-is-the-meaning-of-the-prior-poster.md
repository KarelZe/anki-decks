## Note
nid: 1630645105227
model: Basic-d7a3e
tags: 09_bayesian_learning, ultra
markdown: false

### Front
What is the meaning of the prior, posterior, likelihood and evidence in bayesian learning?<div>
</div><div>\(\underbrace{p(\boldsymbol{\theta} \mid \mathcal{D})}_{\text {posterior }}=\frac{\overbrace{p(\mathcal{D} \mid \boldsymbol{\theta})}^{\text {data likelihood}} \overbrace{p(\boldsymbol{\theta})}^{\text {prior}}}{\underbrace{p(\mathcal{D})}_{\text {evidence }}}\)
</div>

### Back
<ul><li><strong>Prior:</strong> Our subjective belief</li><li><strong>Posterior:</strong> Probability of parameter vector given the data</li><li><strong>Likelihood:</strong> Specified by our parametric model \(\mathcal{D}\)</li><li><strong>Evidence:</strong> Normalization, can be used for model comparsion</li></ul>
