## Note
nid: 1659860754996
model: Basic-02d89
tags: 12_adv_topics_dl_cv
markdown: false

### Front
How does the approximation of Bayesian neural networks with MC dropout work?

### Back
<ul>
  <li>Probabilistic inference. Dropout also active at test time.
  <li>Computes \(T\) stochastic forward passes with acitive
  dropout.
  <li>Computes output statistics including the mean and variance as
  a measure of epistemic uncertainty.
</ul>
