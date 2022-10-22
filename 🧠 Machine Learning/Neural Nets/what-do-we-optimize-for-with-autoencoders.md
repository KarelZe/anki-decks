# Note
```
guid: J}yg?(mqeo
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
What do we optimize for with <b>AutoEncoders</b>?

## Back
Minimize reconstruction loss:
\(L(\boldsymbol{\theta})=\sum_{i}\left\|\operatorname{dec}_{\boldsymbol{\theta}}\left(\operatorname{enc}_{\boldsymbol{\theta}}\left(\boldsymbol{x}_{i}\right)\right)-\boldsymbol{x}_{i}\right\|^{2}\)
