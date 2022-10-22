# Note
```
guid: C$`Xw3k2J5
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::11_rnns
```

## Front
Explain the problem of <b>vanishing gradients</b> in the case of
<b>RNNs</b>.

## Back
When computing the gradient of \(h\) the computation involes many
factors of the weight matrix \(W\) and a repeated use of the
\(\operatorname{tanh}\).
<div>
  If the largest Eigenvalue is smaller than 1, gradients vanish.
</div>
<div><img src="paste-91e0d265856f3757aaf9d8d87f19b82bfb26fb42.jpg"></div>
