# Note
```
guid: sNIqo*HnYB
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::06_lecture
```

## Front
Explain the <b>central idea</b> of <b>ridge regression</b>.

## Back
A second term, called a <b>shrinkage penalty</b>, \(\lambda
\sum_{j=1}^{p} \beta_{j}^{2}\) where \(\lambda \geq 0\) is a tuning
parameter.
<div>
  The shrinkage penalty is small when \(\beta_{1}, \ldots,
  \beta_{p}\) are close to zero, and so it has the effecct of
  shrinking the estimates of \(\beta_{j}\) towards zero.
  <div>
    While the tuning parameter \(\lambda\) serves to control the
    relative impact of these two terms on the regression
    coefficient estimates.
  </div>
</div>
