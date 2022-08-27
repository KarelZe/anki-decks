## Note
nid: 1629464081569
model: Basic-d7a3e-4ce08
tags: ml::02_linear_classification
markdown: false

### Front
Warum optimiert man den <b>Log-Likelihood</b> anstelle des
<b>Likelihood</b>?

### Back
<div>
  <div>
    <div>
      \(\log \operatorname{lik}(\boldsymbol{\theta} ; D)=\sum_{i}
      \log p_{\boldsymbol{\theta}}\left(x_{i}, y_{i}\right)\)
    </div>
    <div>
      Log-Likelihood is easier to optimize:
    </div>
    <ul>
      <li>log is monotonous
      <li>sums are nicer to optimize than products
      <li>logs cancel exponential forms
    </ul>
  </div>
</div>
