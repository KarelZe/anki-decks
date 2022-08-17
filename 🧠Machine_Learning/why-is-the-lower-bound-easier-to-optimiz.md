## Note
nid: 1656331966429
model: Basic-02d89
tags: 12_var_ml
markdown: false

### Front
Why is the <b>lower bound </b>easier to optimize than the<b> marginal log-likelihood</b>?

### Back
<ul><li>✅Integrals move outside the log</li><li>✅ More direct sampling in latent space by sampling from approximate posterior \(q_i(z)\) instead of prior \(p(z)\)</li><li>❌No guarantee that we also improve marginal loglikelihood (except in the special case of EM)</li></ul>
