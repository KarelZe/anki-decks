## Note
nid: 1621070369551
model: Basic-b122e
tags: 06_lecture
markdown: false

### Front
Explain the <b>central idea</b> of <b>ridge regression</b>.

### Back
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
