## Note
nid: 1656325974136
model: Basic-02d89
tags: 12_var_ml
markdown: false

### Front
What do we optimize for with <b>AutoEncoders</b>?

### Back
Minimize reconstruction loss:
\(L(\boldsymbol{\theta})=\sum_{i}\left\|\operatorname{dec}_{\boldsymbol{\theta}}\left(\operatorname{enc}_{\boldsymbol{\theta}}\left(\boldsymbol{x}_{i}\right)\right)-\boldsymbol{x}_{i}\right\|^{2}\)
