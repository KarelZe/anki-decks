# Note
```
guid: n$l_/^$#(H
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::09_bayesian_learning
ultra
```

## Front
How can we estimate the <b>predictive distribution</b> of a
<b>Gaussian</b> using <b>Bayesian Learning</b>?

## Back
The predictive distribution is given by:
<div>
  \(\begin{aligned} \underbrace{p\left(x^{*} \mid
  \boldsymbol{X}\right)}_{\text {marginal likelihood }} &=\int
  \underbrace{p\left(x^{*} \mid \mu\right)}_{\text {likelihood }}
  \underbrace{p(\mu \mid \boldsymbol{X})}_{\text {posterior }} d
  \mu \\ &=\int \mathcal{N}\left(x^{*} \mid \mu, \sigma\right)
  \mathcal{N}\left(\mu \mid \mu_{N}, \sigma_{N}\right) d \mu \\
  &=\mathcal{N}\left(x^{*} \mid \mu_{x^{*}},
  \sigma_{x^{*}}^{2}\right) \end{aligned}\)
</div>
<div>
  The predictive distribution is Gaussian with:
</div>
<div>
  Mean: \(\mu_{x^{*}}=\mu_{N}\)
</div>
<div>
  Variance: \(\sigma_{x^{*}}^{2}=\sigma_{N}^{2}+\sigma^{2}\)
</div>
<div>
  <b>Observations</b>:
</div>
<div>
  <i>predictive mean</i> is the same as the posterior mean.
</div>
<div>
  <i>predictive variance</i> also considers uncertainty from mean.
</div>
