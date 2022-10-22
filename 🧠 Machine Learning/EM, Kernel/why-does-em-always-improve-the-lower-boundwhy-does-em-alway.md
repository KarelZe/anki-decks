# Note
```
guid: Gp@0v2,mt*
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::06_em_for_dim_reduction
ultra
```

## Front
<p>Why does EM always improve the lower bound?
<p>Why does EM always improve the marginal likelihood?

## Back
<p>EM improves the <b>lower bound</b> \(\mathcal{L}\left(q_{\text
{new }}, \boldsymbol{\theta}_{\text {new }}\right) \geq
\mathcal{L}\left(q_{\text {old }}, \boldsymbol{\theta}_{\text {old
}}\right)\)
<p>E-Step: KL is set to 0, lower bound has to go up
<p>M-Step: Lower bound is maximized
<p>EM improves the <b>marginal likelihood</b> \(\log
p\left(\boldsymbol{x} \mid
\boldsymbol{\theta}_{\mathrm{new}}\right) \geq \log
p\left(\boldsymbol{x} \mid
\boldsymbol{\theta}_{\mathrm{old}}\right)\)
<p>E-Step: Marginal likelihood is unaffected
<p>M-Step: Lower bound increases and KL increases (can't get
smaller than 0)
