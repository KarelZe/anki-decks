## Note
nid: 1630646478513
model: Basic-d7a3e
tags: 09_bayesian_learning, ultra
markdown: false

### Front
What are the 2 steps in Bayesian learning?

### Back
<b>Compute Posterior</b> (Probabilty of being right for \(\theta\))
<div>
  \(p(\boldsymbol{\theta} \mid \mathcal{D})=\frac{p(\mathcal{D}
  \mid \boldsymbol{\theta})
  p(\boldsymbol{\theta})}{p(\mathcal{D})}\)
</div>
<div>
  <b>Predicting of a new data-point</b> \(x^{*}\)
</div>
<div>
  \(\underbrace{p\left(\boldsymbol{x}^{*} \mid
  \mathcal{D}\right)}_{\text {marginal likelihood }}=\int
  \underbrace{p\left(\boldsymbol{x}^{*} \mid
  \boldsymbol{\theta}\right)}_{\text {likelihood }}
  \underbrace{p(\boldsymbol{\theta} \mid \mathcal{D})}_{\text
  {posterior }} d \boldsymbol{\theta}\)
</div>
<div>
  <b>Note:</b> Likelihood \(p\left(\boldsymbol{x}^{*} \mid
  \mathcal{D}\right)\) is now purely determined by the data
  \(\mathcal{D}\).
</div>
