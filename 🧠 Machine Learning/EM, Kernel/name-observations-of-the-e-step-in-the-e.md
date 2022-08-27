## Note
nid: 1631078457403
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction, ultra
markdown: false

### Front
Name observations of the E-step in the EM algorithm. What happens to the marginal log-likelihood? What  happens to the KL distance?

### Back
The marignal log-likelihood \(\log p(\boldsymbol{x} \mid
\boldsymbol{\theta})\) is unaffected by the E-step.
<div>
  As KL is minimized the lower bound has to go up.
</div>
<div>
  After the E-step \(\operatorname{KL}(q(z) \| p(z \mid
  \boldsymbol{x}))=0\) and therefore, the lowerbound is tight i.
  e.:
</div>
<div>
  \(\log p(\boldsymbol{x} \mid \boldsymbol{\theta})=\mathcal{L}(q,
  \boldsymbol{\theta})\)
</div>
