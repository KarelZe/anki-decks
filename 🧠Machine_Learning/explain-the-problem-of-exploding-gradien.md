## Note
nid: 1629283961381
model: Basic-d7a3e
tags: 11_rnns, checklater
markdown: false

### Front
<div>
  Explain the problem of <b>exploding gradients</b> of <b>RNNs.</b>
</div>

### Back
When computing the gradient of \(h\) the computation involes many
factors of the weight matrix \(W\) and a repeated use of the
\(\operatorname{tanh}\).
<div>
  If the largest eigen value is > 1, gradients explode.
</div>
<div><img src=
"paste-91e0d265856f3757aaf9d8d87f19b82bfb26fb42.jpg"></div>
