# Note
```
guid: bzWh&O2DOG
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
Why is the <b>lower bound</b> easier to optimize than the
<b>marginal log-likelihood</b>?

## Back
<ul>
  <li>✅Integrals move outside the log
  <li>✅ More direct sampling in latent space by sampling from
  approximate posterior \(q_i(z)\) instead of prior \(p(z)\)
  <li>❌No guarantee that we also improve marginal loglikelihood
  (except in the special case of EM)
</ul>
