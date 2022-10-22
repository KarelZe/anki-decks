# Note
```
guid: kA86UaxqOK
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::10_neural_networks
```

## Front
Define <b>gradient normalisation</b> / <b>RMSProp</b>.

## Back
\(\begin{aligned} \boldsymbol{g}_{k}
&=\nabla_{\boldsymbol{\theta}}
\mathcal{L}\left(\boldsymbol{\theta}_{k}\right) \\
\boldsymbol{v}_{k+1, i} &=\gamma \boldsymbol{v}_{k,
i}+(1-\gamma) \boldsymbol{g}_{k, i}^{2} \\
\boldsymbol{\theta}_{k+1, i} &=\boldsymbol{\theta}_{k,
i}-\frac{\eta}{\sqrt{\boldsymbol{v}_{k+1, i}+\epsilon}}
\boldsymbol{g}_{k, i} \end{aligned},\)
<div>
  where \(\boldsymbol{v}_{k+1, i}\) computes running average of the
  squared gardients (root mean square). RMSProp uses small
  \(\epsilon\) to prevent division by zero.
</div>
