## Note
nid: 1609155708715
model: Basic-d7a3e
tags: 06_em_for_dim_reduction, ultra
markdown: false

### Front
<p>Why does EM always improve the lower bound?
<p>Why does EM always improve the marginal likelihood?

### Back
<p>EM improves the <b>lower bound</b> \(\mathcal{L}\left(q_{\text {new }}, \boldsymbol{\theta}_{\text {new }}\right) \geq \mathcal{L}\left(q_{\text {old }}, \boldsymbol{\theta}_{\text {old }}\right)\)</p><p>E-Step: KL is set to 0, lower bound has to go up
</p><p>M-Step: Lower bound is maximized
</p><p>
</p><p>EM improves the <b>marginal likelihood</b> \(\log p\left(\boldsymbol{x} \mid \boldsymbol{\theta}_{\mathrm{new}}\right) \geq \log p\left(\boldsymbol{x} \mid \boldsymbol{\theta}_{\mathrm{old}}\right)\)
</p><p>E-Step: Marginal likelihood is unaffected</p><p>M-Step: Lower bound increases and KL increases (can't get smaller than 0)</p>
