## Note
nid: 1629092211311
model: Basic-d7a3e
tags: 06_em_for_dim_reduction
markdown: false

### Front
Explain the <b>two steps</b> of the <b>Expectation Maximization</b>
algorithm on an intuitional level for <b>Gaussian mixture
models</b>.

### Back
<div>
  <div>
    <div>
      In our example of the Gaussian mixture model, we choose
      initial values for \(\mu_{k}, \boldsymbol{\Sigma}_{k},
      \pi_{k}\) and alternate until convergence between
    </div>
    <ul>
      <li><b>E-step:</b> Evaluate the responsibilities \(r_{n k}\)
      (posterior probability of data point \(n\) belonging to
      mixture component \(k\) ).
      <li><b>M-step:</b> Use the updated responsibilities to
      reestimate the parameters \(\mu_{k}, \Sigma_{k}, \pi_{k}\)
    </ul>
  </div>
</div>
