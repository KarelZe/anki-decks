# Note
```
guid: r2|}lsyUs>
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::12_adv_topics
```

## Front
How does the approximation of Bayesian neural networks with MC dropout work?

## Back
<ul>
  <li>Probabilistic inference. Dropout also active at test time.
  <li>Computes \(T\) stochastic forward passes with acitive
  dropout.
  <li>Computes output statistics including the mean and variance as
  a measure of epistemic uncertainty.
</ul>
