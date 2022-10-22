# Note
```
guid: rrWHGK5[$V
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::06_em_for_dim_reduction
ultra
```

## Front
What is the drawback of the <b>EM algorithm</b>? How can it be
fixed?

## Back
EM assumes that E-step can set the KL divergence to 0.
<div>
  However, this is only possible if \(z\) is discrete or if we have
  linear Gaussian models.
</div>
<div>
  <b>Variational Bayes</b> approximate the posterior where a KL
  will be \(> 0\) after E-Step.
</div>
