# Note
```
guid: wLEeoBU4No
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::12_adv_topics
```

## Front
How do <b>Bayesian networks</b> relate to <b>dropout</b>?

## Back
<ul>
  <li>Dropout (some neurons are deactivated) is a variational
  approximation of a Bayesian neural networks (have a distribution
  for each weight)
  <li>BNNs can be approximated using Monte Carlo dropout (dropout
  with mean and variance).
  <li>Can be used to quantify model uncertainty.
</ul>
<div>
  <b>Explanation:</b>
</div>
<div>
  \(p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \mathbf{X},
  \mathbf{Y}\right)=\int p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*},
  \omega\right) p(\omega \mid \mathbf{X}, \mathbf{Y}) \mathrm{d}
  \omega\) \(\approx \int p\left(\mathbf{y}^{*} \mid
  \mathbf{x}^{*}, \omega\right) q_{\theta}(\omega) \mathrm{d}
  \omega\) \(\approx \frac{1}{T} \sum_{t=1}^{T}
  p\left(\mathbf{y}^{*} \mid \mathbf{x}^{*}, \omega_{t}\right)\),
  with \(\omega_{t} \sim q_{\theta}(\omega)\)
</div>
<div>
  Model weights are Bernoulli distributed. Approximation is similar
  to averaging all models.
</div>
