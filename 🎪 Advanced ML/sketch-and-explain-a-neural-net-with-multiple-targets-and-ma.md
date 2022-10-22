# Note
```
guid: nWnxyBejG4
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::10_lecture
```

## Front
Sketch and explain a <b>neural net with multiple targets and many
inputs</b>.

## Back
<div>
  \[\begin{array}{c} z=\left(\alpha_{0}+\alpha_{1} x\right) \\
  y=g_{2}\left(\beta_{0}+\beta_{1} z_{1}\right) \\
  O_{k}=g_{1}\left(y_{k}\right), k=1, \ldots, K . \end{array}\]
</div>
<div>
  <div>
    <ul>
      <li>\[\mathrm{M}(\mathrm{p}+1)+\mathrm{K}(\mathrm{M}+1)\]
      parameters (weights)
      <li>We don’t want the global minimizer of the deviance
      (cross-entropy) function.
      <li>Instead we use early stopping or a penalty term
    </ul>
  </div>
</div>
<div><img src="paste-286f949d95015c4f04bbf4ee1a4c7ef733d0b3ff.jpg"></div>
