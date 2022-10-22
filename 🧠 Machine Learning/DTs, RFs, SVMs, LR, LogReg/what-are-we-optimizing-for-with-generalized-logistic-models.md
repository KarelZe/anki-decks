# Note
```
guid: L-xmCH[!Bh
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::02_linear_classification
```

## Front
What are we optimizing for with <b>generalized logistic models</b>?

## Back
\(\operatorname{argmax}_{\boldsymbol{w}} \log \operatorname{lik}(\boldsymbol{w}, D)=\operatorname{argmax}_{\boldsymbol{w}} \sum_{i} c_{i} \log \sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)+\left(1-c_{i}\right) \log \left(1-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right)\)
