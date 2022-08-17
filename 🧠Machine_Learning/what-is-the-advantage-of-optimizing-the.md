## Note
nid: 1659637079218
model: Basic-02d89
tags: 12_var_ae_ml
markdown: false

### Front
What is the advantage of optimizing the lower bound instead of the likelihood?
\[\mathcal{L}\left(\left\{q_{i}\right\}, p\right)=\frac{1}{N} \sum_{i} \int q_{i}(\boldsymbol{z}) \log p\left(\boldsymbol{x}_{i} \mid \boldsymbol{z}\right) d \boldsymbol{z}-\mathrm{KL}\left(q_{i}(\boldsymbol{z}) \right| p(\boldsymbol{z})\right)\]with an individual variational distribution \(q_{i}(\boldsymbol{z})\) for each data point.

### Back
More directed sampling:
<ul>
  <li>Instead of sampling from the uninformed prior \(p(z) \ldots\)
  <li>... we can now sample from the variational distributions
  \(q_{i}(\boldsymbol{z}) \approx p\left(\boldsymbol{z} \mid
  \boldsymbol{x}_{i}\right)\)
  <li>Each \(q_{i}(\boldsymbol{z})\) will produce samples with high
  \(p(\boldsymbol{x} \mid \boldsymbol{z})\) once optimized!
</ul>Integral is outside the log:
<ul>
  <li>only one sample from \(q_{i}(\boldsymbol{z})\) needed to
  obtain unbiased estimate of the lower bound
  <li>i.e. suitable for stochastic gradient descent while the
  marginal loglikelihood is not
</ul>
